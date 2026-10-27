# AI Engineering — study notes

My notes and code examples while reading *AI Engineering* by Chip Huyen.

| Chapter | Notebook | Topics |
|---|---|---|
| 1. Building with Foundation Models | [Notes_one.ipynb](1.Building_With_Foundation_Models/Notes_one.ipynb) | Language models → LLMs → foundation models, masked (BERT) vs autoregressive (GPT-2) models, tokens, self-supervision, AI engineering, use cases |

## Running the notebooks

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install jupyter transformers torch
jupyter notebook
```

The first run downloads small open models from Hugging Face (BERT ~440 MB, GPT-2 ~500 MB).

## Live projects

Apps built while learning, running on Hugging Face and listed at [kigobe.net/projects](https://kigobe.net/projects).
