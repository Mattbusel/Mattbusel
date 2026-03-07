# Matthew Charles Busel

Building the primitive layer for production AI systems.

319,000+ lines of code across Rust, C++, and Python.

[![Star History Chart](https://api.star-history.com/svg?repos=Mattbusel/tokio-prompt-orchestrator,Mattbusel/Every-Other-Token,Mattbusel/LLM-Hallucination-Detection-Script,Mattbusel/llm-cpp&type=Date)](https://star-history.com/#Mattbusel/tokio-prompt-orchestrator&Mattbusel/Every-Other-Token&Mattbusel/LLM-Hallucination-Detection-Script&Mattbusel/llm-cpp)

---

## Projects

| Stars | Repo | What it does |
|---|---|---|
| 45 | [tokio-prompt-orchestrator](https://github.com/Mattbusel/tokio-prompt-orchestrator) | Multi-agent LLM orchestration. Ran 24 simultaneous Claude Code agents. Circuit breaker, dedup, retry, backpressure. Self-improving loop live. |
| 23 | [Every-Other-Token](https://github.com/Mattbusel/Every-Other-Token) | Intercepts every other token mid-generation, scores confidence, visualizes perplexity in real time. Research tool for LLM interpretability. |
| 14 | [LLM-Hallucination-Detection-Script](https://github.com/Mattbusel/LLM-Hallucination-Detection-Script) | Framework-agnostic Python + Rust toolkit for detecting hallucinations in LLM outputs. |
| 6 | [llm-cpp](https://github.com/Mattbusel/llm-cpp) | 26 single-header C++20 libraries for LLM infrastructure. Zero dependencies. Drop in what you need. |
| 5 | [Reddit-Options-Trader-ROT](https://github.com/Mattbusel/Reddit-Options-Trader-ROT-) | Financial intelligence platform. 200+ users across 46 countries. Validated signals: MASI +34%, ZIM +25%, OLB +137%. |

---

## Rust Primitive Layer

[rust-crates](https://github.com/Mattbusel/rust-crates) - 10 production libraries, all used inside tokio-prompt-orchestrator:

| Crate | What it does |
|---|---|
| [tokio-agent-memory](https://github.com/Mattbusel/tokio-agent-memory) | Episodic, semantic, working memory with decay and multi-agent bus |
| [tokio-memory](https://github.com/Mattbusel/tokio-memory) | Ebbinghaus forgetting curve + async persistence |
| [llm-budget](https://github.com/Mattbusel/llm-budget) | Hard budget enforcement across agent fleets |
| [llm-wasm](https://github.com/Mattbusel/llm-wasm) | LLM inference primitives for WebAssembly and edge |
| [llm-diff](https://github.com/Mattbusel/llm-diff) | Semantic diff and versioning for LLM outputs |
| [llm-sync](https://github.com/Mattbusel/llm-sync) | CRDTs and vector clocks for distributed agent state |
| [wasm-agent](https://github.com/Mattbusel/wasm-agent) | ReAct agent loop for WASM with resumable state |
| [mem-graph](https://github.com/Mattbusel/mem-graph) | Knowledge graph: typed nodes, edges, BFS/DFS |
| [fin-primitives](https://github.com/Mattbusel/fin-primitives) | Price types, order book, OHLCV, indicators, PnL |
| [fin-stream](https://github.com/Mattbusel/fin-stream) | Lock-free SPSC ring buffer, 100K+ ticks/second |

---

## Finance + Research

**[Special-Relativity-in-Financial-Modeling](https://github.com/Mattbusel/Special-Relativity-in-Financial-Modeling)** - What if price velocity has a speed limit? Lorentz transforms on OHLCV data. DOI: 10.5281/zenodo.18639919

**[LLMTokenStreamQuantEngine](https://github.com/Mattbusel/LLMTokenStreamQuantEngine)** - C++ engine that maps LLM token semantics to real-time trade signals at sub-second resolution.

12 DOI-indexed papers on Zenodo. Active DARPA ERIS submission.

---

## Stack

Rust / C++ / Python / Tokio / WebAssembly / CRDT / MCP

New York / [linkedin.com/in/matthewbusel](https://linkedin.com/in/matthewbusel) / mattbusel@gmail.com / [medium.com/@mattbusel](https://medium.com/@mattbusel)

![Total Stars](https://img.shields.io/github/stars/Mattbusel?style=flat&label=Total%20Stars&color=gold)