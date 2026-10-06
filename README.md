# Pratyush Mathur

Systems / ML infrastructure. I build the plumbing under LLM serving — schedulers, memory, and CUDA — and measure it.

## Featured

**[Inferno](https://github.com/pratyushmathur1/inferno)** — from-scratch Llama serving in C++/CUDA (continuous batching, paged KV, GPU kernels). Real SmolLM2 weights; greedy answers stay stable under preemption. On A100, beats naive PyTorch `generate` on TTFT/ITL and trails production vLLM — with public ablations.

- [Architecture](https://github.com/pratyushmathur1/inferno/blob/main/ARCHITECTURE.md) · [Results](https://github.com/pratyushmathur1/inferno/blob/main/RESULTS.md)
