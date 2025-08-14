# Mini Transformer

A simple, educational implementation of the Transformer architecture in PyTorch based on the original research paper "Attention Is All You Need".

## Overview

This project implements a basic Transformer model from scratch to understand the core concepts:
- Multi-head self-attention mechanism
- Position encodings
- Feed-forward networks
- Layer normalization
- Encoder-decoder architecture

## Requirements

- Python 3.8+
- PyTorch
- NumPy
- (Additional dependencies will be added as needed)

## Usage

```python
# Example usage (to be implemented)
from src.model.transformer import Transformer

model = Transformer(
    vocab_size=10000,
    d_model=512,
    nhead=8,
    num_layers=6
)
```

## Implementation Status

- [x] Basic project structure
- [ ] Attention mechanism
- [ ] Position encodings
- [ ] Encoder layers
- [ ] Decoder layers
- [ ] Full Transformer model
- [ ] Training loop
- [ ] Example usage

## References

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - Vaswani et al.
