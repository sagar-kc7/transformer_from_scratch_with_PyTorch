# Transformer from Scratch with PyTorch

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sagar-kc7/transformer_from_scratch_with_PyTorch/blob/main/transformer_from_scratch_with_PyTorch.ipynb)

This repository contains a notebook-first, from-scratch implementation of the
Transformer architecture in PyTorch, based on the *Attention Is All You Need*
paper.

Paper: https://proceedings.neurips.cc/paper_files/paper/2017/file/3f5ee243547dee91fbd053c1c4a845aa-Paper.pdf

## Notebook coverage

The notebook (`transformer_from_scratch_with_PyTorch.ipynb`) walks through:

- Input embedding and positional embedding
- Layer normalization and feed-forward blocks
- Multi-head attention
- Residual connections
- Encoder and decoder blocks
- Projection layer and full Transformer assembly
- Dataset preparation
- Training loop setup
- Inference
- Attention visualization

## Dependencies used in the notebook

- PyTorch
- Hugging Face `datasets`
- `tokenizers`
- NumPy
- Pandas
- Altair
- TensorBoard (`torch.utils.tensorboard`)
- `tqdm`

## How to run

1. Open the notebook in Google Colab using the badge above, or run it locally in
   Jupyter.
2. Execute cells in order, from model components through training and inference.

## Project status

🚧 Work in progress / educational implementation.
