# Local AI Fine-Tuning Starter Kit

A beginner-friendly companion for David Ondrej's local AI fine-tuning video.

This repo gives viewers the practical files behind the lead magnet:

1. **Normal Computer Fine-Tuning Guide** — a plain-English checklist before you train.
2. **Unsloth Studio Quickstart** — the exact links and local launch steps from David's notes.
3. **Starter Training Dataset** — example JSONL rows showing the format of training data.
4. **Fine-Tuning vs RAG Decision Tree** — when to fine-tune, when not to.

## Necessary links from the video / notes

- Unsloth Studio docs: https://unsloth.ai/docs/new/studio
- Hugging Face: https://huggingface.co/
- Open-source model comparison: https://artificialanalysis.ai/models/open-source

## Quick local Unsloth Studio flow

1. Go to https://unsloth.ai/docs/new/studio
2. Click **Quickstart**.
3. Open your terminal.
4. Paste the one-line installer from the Unsloth docs.
5. Wait a few minutes.
6. Launch Unsloth Studio locally:

```bash
unsloth studio -H 0.0.0.0 -p 8888
```

7. Open a new browser tab:

```text
http://127.0.0.1:8888/studio
```

8. Set a **local UI password**. This only locks the local browser UI — it is not a real online account. Use your own password, not a password you reuse elsewhere.
9. Click **Train** on the left.
10. Choose a model to train.
    - Go to https://huggingface.co/ to search models.
    - If you do not know what model to choose, compare open-source models at https://artificialanalysis.ai/models/open-source.
    - For learning on a normal computer, start small before trying large models.

## Rule of thumb

Fine-tuning is for teaching a model a repeatable behavior, answer style, format, or workflow.

If you only need the model to know documents, policies, legal text, medical files, menus, or constantly changing facts, start with RAG / a document assistant first.
