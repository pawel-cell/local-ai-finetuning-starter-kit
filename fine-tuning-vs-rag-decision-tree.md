# Fine-Tuning vs RAG Decision Tree

## Use prompting first when...

- the task is simple
- you can explain the desired output in one prompt
- you do not need the model to remember private documents
- you only need a better instruction, not a new model

## Use RAG / document search when...

- the model needs access to documents, policies, case files, product docs, menus, or laws
- the facts change often
- accuracy depends on retrieving the right source text
- you need citations or source links

Examples: clinic policies, lawyer documents, internal company wiki, SOPs, manuals.

## Use fine-tuning when...

- the model needs to learn a repeatable behavior
- you want consistent output format
- you want a specific tone or style
- you want the model to follow a workflow from examples
- you have 30–100+ good examples of input → ideal output

Examples: intake reply style, CRM summaries, code review comments, support categorization, structured report writing.

## Use both RAG + fine-tuning when...

- you need private/current knowledge **and** a consistent workflow/style
- RAG supplies the facts
- fine-tuning teaches how to answer with those facts

## Red flag

If the user says, "I want the model to know my documents," that is usually RAG first, not fine-tuning first.
