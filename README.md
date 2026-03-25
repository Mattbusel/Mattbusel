# Matthew Charles Busel

Building the primitive layer for production AI systems, and the engine that renders mathematics.

**2m+ lines of code** across Rust, C++, and Python.

---

## Projects

| Stars | Repo | What it does |
|-------|------|-------------|
| — | **proof-engine** | Mathematical rendering engine. 460k+ lines of Rust. PBR lighting, force field physics, amorphous entities, shader graph, GPU compute, procedural music, fluid simulation, ECS, scripting VM, behavior trees, rollback netcode. Published on crates.io. https://github.com/Mattbusel/proof-engine| 
| — | **chaos-rpg** | Commercial roguelike where every outcome runs through real mathematical functions. 108K+ lines. 12 classes, 12 bosses, 820-node passive tree, 4 frontends. Runs on Proof Engine. https://github.com/Mattbusel/chaos-rpg |
| 47 | **tokio-prompt-orchestrator** | Multi-agent LLM orchestration. Ran 24 simultaneous Claude Code agents. Circuit breaker, dedup, retry, backpressure. Self-improving loop live. |
| 23 | **Every-Other-Token** | Intercepts every other token mid-generation, scores confidence, visualizes perplexity in real time. Research tool for LLM interpretability. |
| 14 | **LLM-Hallucination-Detection-Script** | Framework-agnostic Python + Rust toolkit for detecting hallucinations in LLM outputs. |
| 7 | **llm-cpp** | 26 single-header C++20 libraries for LLM infrastructure. Zero dependencies. Drop in what you need. |
| 5 | **Reddit-Options-Trader-ROT** | Financial intelligence platform. 200+ users across 46 countries. Validated signals: MASI +34%, ZIM +25%, OLB +137%. |

---

## Proof Engine

A mathematical rendering engine for Rust. **262,000+ lines. 283 source files. Solo-built. MIT licensed.**

The engine does not render graphics. It renders mathematics. Particles follow real differential equations. Damage hits spawn gravitational force fields. Entities are glyph clusters held together by physics that disintegrate as they take damage.

`cargo add proof-engine`

**Core systems:** Instanced glyph rendering · 30+ MathFunction variants with RK4 attractors · 18+ force field types · Amorphous entities with HP-linked cohesion · Navier-Stokes fluid simulation · SPH particles · Soft body with tearing · Rigid body with 8 constraint types · Node-based shader graph (40+ nodes) compiling to GLSL at runtime · Deferred rendering with G-buffer · Cook-Torrance PBR with cascaded shadow maps and IBL · GPU compute pipeline · 32-voice polyphonic synthesizer · Procedural music engine (15 scales, chord progressions, melody generation) · FFT from scratch · Behavior trees + GOAP planner · A* + NavMesh + steering behaviors · Terrain with hydraulic erosion and climate simulation · Weather system · Economy system · Full scripting language (lexer → parser → AST → compiler → stack VM) · Multiplayer with rollback netcode and lag compensation · ECS · Editor tools · Save system with compression · Replay recording · Localization (10 languages)

---

## CHAOS RPG

A roguelike where every outcome runs through a chain of real mathematical functions. **108,000+ lines of Rust. 4 frontends. Runs on Proof Engine.**

`Available on itch.io` → [mattbusel.itch.io/chaos-rpg](https://mattbusel.itch.io/chaos-rpg)

12 classes · 12 unique bosses · 820+ node passive tree · 181 achievements · 8 crafting operations · Nemesis system · Misery Index · Daily seed leaderboard · Procedural audio · Run narratives · Full lore system

**Combined: 370,000+ lines of Rust. A game and the engine it runs on. Both solo.**

---

## Rust Primitive Layer

**rust-crates** — 10 production libraries, all used inside tokio-prompt-orchestrator:

| Crate | What it does |
|-------|-------------|
| **tokio-agent-memory** | Episodic, semantic, working memory with decay and multi-agent bus |
| **tokio-memory** | Ebbinghaus forgetting curve + async persistence |
| **llm-budget** | Hard budget enforcement across agent fleets |
| **llm-wasm** | LLM inference primitives for WebAssembly and edge |
| **llm-diff** | Semantic diff and versioning for LLM outputs |
| **llm-sync** | CRDTs and vector clocks for distributed agent state |
| **wasm-agent** | ReAct agent loop for WASM with resumable state |
| **mem-graph** | Knowledge graph: typed nodes, edges, BFS/DFS |
| **fin-primitives** | Price types, order book, OHLCV, indicators, PnL |
| **fin-stream** | Lock-free SPSC ring buffer, 100K+ ticks/second |

---

## Finance + Research

**Special-Relativity-in-Financial-Modeling** — Lorentz transforms on OHLCV data. VR=1.27×, Bartlett p=6×10⁻¹⁶. DOI: 10.5281/zenodo.18639919

**LLMTokenStreamQuantEngine** — C++ engine mapping LLM token semantics to real-time trade signals at sub-second resolution.

15 DOI-indexed papers on Zenodo under Oxidized Archive. Active DARPA ERIS submission. Google Scholar indexed. Academia.edu top 8.1% in Symbolic Computation.


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Mattbusel&layout=compact&theme=tokyonight)](https://github.com/Mattbusel)

[![GitHub Stars](https://img.shields.io/github/stars/Mattbusel?style=for-the-badge&logo=github&label=Total%20Stars&color=gold)](https://github.com/Mattbusel)
---

## Stack

Rust / C++ / Python / Tokio / OpenGL / WebAssembly / CRDT / MCP

New York · [linkedin.com/in/matthewbusel](https://linkedin.com/in/matthewbusel) · mattbusel@gmail.com · [medium.com/@mattbusel](https://medium.com/@mattbusel)
