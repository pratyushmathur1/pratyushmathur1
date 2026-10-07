# Pratyush Mathur


## Featured

**[Inferno](https://github.com/pratyushmathur1/inferno)** -- from-scratch Llama serving in C++/CUDA: continuous batching, paged KV, and **prefix caching** for shared system prompts.

- Real SmolLM2 weights; greedy answers stay stable under preemption
- On A100: up to **24.9x** warm TTFT with `--prefix-cache`; beats naive PyTorch `generate` on TTFT/ITL; trails production vLLM (honest)

Links: [Architecture](https://github.com/pratyushmathur1/inferno/blob/main/ARCHITECTURE.md) · [Results](https://github.com/pratyushmathur1/inferno/blob/main/RESULTS.md)
