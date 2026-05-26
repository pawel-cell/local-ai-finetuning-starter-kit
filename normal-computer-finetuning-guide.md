# Normal Computer Fine-Tuning Guide

Use this before you train. The goal is not to build a perfect model on day one. The goal is to run a small, safe experiment and learn what works.

## 1. Choose the right job

Fine-tuning is useful when you want the model to copy a repeatable behavior:

- answer format
- writing style
- internal workflow
- classification habit
- code review style
- customer support tone
- data-to-summary transformation

Do **not** fine-tune just to upload knowledge. For facts, documents, policies, laws, patient/client files, menus, or changing knowledge, start with RAG or a document assistant.

## 2. Pick a small model first

- Normal computer: start with small models for learning the flow.
- Strong laptop/desktop: try larger models only after the small test works.
- Do not start with huge models. A successful small run teaches more than a failed giant run.

Rule: first prove your data is useful, then increase model size.

## 3. Prepare 30–100 high-quality examples

Each row should show:

- a realistic user request
- the ideal answer
- the exact tone and format you want repeated

Good data beats a bigger model.

## 4. Protect private data

Before training, remove private client, patient, legal, financial, medical, account, or password data unless you have explicit permission and a safe local workflow.

## 5. Run the smallest useful experiment

Train one narrow behavior first. Example:

- turn a messy sales-call note into a clean CRM summary
- classify support tickets into 5 categories
- answer clinic FAQ questions in a specific style
- generate code comments in your team's format

## 6. Test with examples the model never saw

After training, test the model on fresh inputs. If it only works on examples that look exactly like your training rows, your dataset is too narrow.

## 7. Keep a simple experiment log

Track:

- model name
- dataset version
- number of examples
- training settings
- what improved
- what got worse

If you cannot explain what changed, do not trust the new model yet.
