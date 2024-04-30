# English to Swedish Neural Machine Translation with PyTorch

This project implements a neural machine translation (NMT) system using PyTorch to translate text from English to Swedish. The architecture includes a sequence-to-sequence (seq2seq) model with attention mechanism.

## Project Overview

The NMT model consists of the following components:

- **Encoder**: The encoder processes input sequences using stacked GRU layers and creates hidden representations.
  
- **Decoder with Attention**: The decoder utilizes an attention mechanism (Bahdanau) to focus on relevant parts of the input sequence while generating the output sequence.

## Setup

To run this project, make sure you have Python 3.x installed along with the following dependencies:

- PyTorch
- NumPy
- torchtext
- GloVe pre-trained word embeddings

You can install the required packages using pip:

```bash
pip install torch numpy torchtext
