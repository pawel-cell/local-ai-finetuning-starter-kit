# Unsloth Studio Quickstart Notes

These are the practical links and steps from David's notes.

## Install Unsloth

1. Go to https://unsloth.ai/docs/new/studio
2. Click **Quickstart**.
3. Open your terminal.
4. Paste the one-line installer from the Unsloth docs.
5. Wait a few minutes.

## Launch Unsloth Studio locally

```bash
unsloth studio -H 0.0.0.0 -p 8888
```

Open this in your browser:

```text
http://127.0.0.1:8888/studio
```

## Local password

Set a local UI password. This only locks the local Unsloth Studio UI in your browser. It is not a real account/email login. Use a fresh local password, not a password you reuse anywhere else.

## Start training

1. Click **Train** on the left.
2. Choose a model to train.
3. Go to https://huggingface.co/ to browse models.
4. If you do not know what model to choose, use https://artificialanalysis.ai/models/open-source to compare open-source models.
5. Start small. The point is to learn the workflow before spending time on a bigger model.

## Model note

David's notes mention Qwen 3 / `unsloth/Qwen3.6`. If that exact model name changes, use Hugging Face search and the Unsloth docs to choose the currently supported small Qwen model.
