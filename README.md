# Language Modelling

A collection of language modeling experiments and implementations using PyTorch and Transformers.

## Projects

### Text Generation
- [shakespeare-transformer.ipynb](shakespeare-transformer.ipynb) - Causal transformer decoder trained from scratch on Shakespeare text
- [shakespeare-lstm.ipynb](shakespeare-lstm.ipynb) - LSTM-based character-level language model for Shakespeare text generation

### Fine-tuning & Transfer Learning
- [t5-cnn-fine-tuning.ipynb](t5-cnn-fine-tuning.ipynb) - Fine-tuning T5 model on CNN/DailyMail summarization dataset
- [triplet-loss-fine-tuning.ipynb](triplet-loss-fine-tuning.ipynb) - Sentence embedding fine-tuning using triplet loss

### Classification
- [disaster-tweets.ipynb](disaster-tweets.ipynb) - Tweet classification for disaster detection

## Setup

```bash
# Install dependencies with uv
uv sync

# Or with pip
pip install -e .
```

## Requirements

- Python 3.11+
- PyTorch 2.9+
- Transformers 4.57+
- See [pyproject.toml](pyproject.toml) for full dependencies

## Usage

Launch Jupyter and open any notebook:

```bash
jupyter notebook
```

Results and trained models are saved to the `results/` directory.
