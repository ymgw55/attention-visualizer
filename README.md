# Attention Visualizer

An interactive visualization tool for understanding attention mechanisms in transformer models, including Multi-Head Attention (MHA), Grouped Query Attention (GQA), and Multi-Query Attention (MQA). Also supports KV caching and sliding window attention visualization.

## Features

- **Multiple Attention Types**: Supports MHA, GQA, and MQA visualization
- **KV Cache Visualization**: Shows cached values with hatched patterns to understand inference optimization
- **Sliding Window Attention**: Configurable attention window sizes for local attention patterns
- **Interactive Visualization**: Color-coded highlighting with play/pause animation and step-by-step exploration

## References

### Papers
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - Vaswani et al., 2017 (Multi-Head Attention)
- [GQA: Training Generalized Multi-Query Transformer Models from Multi-Head Checkpoints](https://arxiv.org/abs/2305.13245) - Ainslie et al., 2023 (Grouped Query Attention)
- [Fast Transformer Decoding: One Write-Head is All You Need](https://arxiv.org/abs/1911.02150) - Shazeer, 2019 (Multi-Query Attention)
- [Transformer-XL: Attentive Language Models Beyond a Fixed-Length Context](https://arxiv.org/abs/1901.02860) - Dai et al., 2019 (KV Cache)
- [Longformer: The Long-Document Transformer](https://arxiv.org/abs/2004.05150) - Beltagy et al., 2020 (Sliding Window Attention)

### Resources
The attention calculation animation was inspired by this resource. Thank you!

- [Transformers KV Caching Explained](https://medium.com/@joaolages/kv-caching-explained-276520203249) - João Lages, 2023


## Contributing

We welcome contributions to improve the Attention Visualizer!

## Development Notes

This repository was created through vibe coding with ChatGPT o3 and GitHub Copilot (Claude Sonnet 4).
