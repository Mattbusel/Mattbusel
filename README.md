# Matt Busel

English | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

**AI engineer. Rust, Python, Swift.** I run [Tensorust](https://tensorust.com/), a one-person software studio in New York.

- Built large data scraping infrastructure in Rust, SQL and Python.
- Run teams of AI agents that do the marketing, in public.
- Ship iOS apps, Rust crates and a Steam game.

**Now:** [**O'BLOCK**](https://store.steampowered.com/app/5357680/?utm_source=github_profile), a sneaker-flipping game on my own Rust engine. Free on Steam (English, 简体中文, 日本語, 한국어). You name a price. The buyers lie.

[![GitHub Stars](https://img.shields.io/github/stars/Mattbusel?style=flat&logo=github&label=total%20stars&color=gold)](https://github.com/Mattbusel?tab=repositories&sort=stargazers)

## Open-source Rust

69 crates on [crates.io](https://crates.io/users/mattbusel), 5,038 downloads (checked Oct 17, 2026). All MIT. Start with these six:

| Crate | What it does | Install |
|---|---|---|
| [tokio-prompt-orchestrator](https://github.com/Mattbusel/tokio-prompt-orchestrator) | Proxy in front of any LLM API. The same prompt twice costs one call. Outages fail fast. Spend is capped. Drop-in for OpenAI and Anthropic clients. | `cargo install tokio-prompt-orchestrator --features web-api` |
| [fin-primitives](https://github.com/Mattbusel/fin-primitives) | Trading basics: exact decimal prices, an order book, ticks to candles, 700+ indicators, Black-Scholes Greeks, risk limits. | `cargo add fin-primitives` |
| [every-other-token](https://github.com/Mattbusel/Every-Other-Token) | Watch an LLM answer token by token with confidence from logprobs. Rewrite tokens live. No API key needed to try it. | `cargo install every-other-token` |
| [proof-engine](https://github.com/Mattbusel/proof-engine) | Draws math in real time: strange attractors, ODEs and force fields with HDR bloom on OpenGL. 21 demos. | `cargo add proof-engine` |
| [llm-cost-dashboard](https://github.com/Mattbusel/llm-cost-dashboard) | Prices every LLM call from your logs (104 models, prompt caching, Claude Code logs). Terminal dashboard, Prometheus or Rust. | `cargo install llm-cost-dashboard` |
| [llm-budget](https://github.com/Mattbusel/llm-budget) | Hard dollar cap per agent. A runaway loop stops instead of running up the bill. 232 real model prices. | `cargo add llm-budget` |

Full list with live download counts: [tensorust.com/open-source](https://tensorust.com/open-source/). Issues and PRs welcome.

**Hire me.** I build native iOS apps and AI software for clients, from prototype to App Store. Prototype sprints from $9,500. App Store launches from $28,000. Advisory $225/hour.
[**Services and pricing**](https://tensorust.com/) · [Email](mailto:mattbusel@gmail.com) · [LinkedIn](https://www.linkedin.com/in/matthewbusel/)

## More LLM infrastructure in Rust

| Repo | What it is |
|---|---|
| [agent-runtime](https://github.com/Mattbusel/agent-runtime) | Tokio agent runtime: orchestration, memory, knowledge graph and a ReAct loop in one crate. |
| [LLM-Hallucination-Detection-Script](https://github.com/Mattbusel/LLM-Hallucination-Detection-Script) | Flags low-confidence spans in LLM output from token logprobs. Crate: `llm-token-visualizer`. |
| [rust-crates](https://github.com/Mattbusel/rust-crates) | Index of my Rust libraries for AI agents and finance. |

## llm-cpp: single-header C++ for LLM apps

[**llm-cpp**](https://github.com/Mattbusel/llm-cpp) holds 26 zero-dependency, single-header C++ libraries. Copy one `.hpp` in and use it. A few:

[llm-stream](https://github.com/Mattbusel/llm-stream) (streaming OpenAI and Anthropic responses) ·
[llm-chat](https://github.com/Mattbusel/llm-chat) ·
[llm-agent](https://github.com/Mattbusel/llm-agent) (tool calling with C++ lambdas) ·
[llm-retry](https://github.com/Mattbusel/llm-retry) ·
[llm-cache](https://github.com/Mattbusel/llm-cache) ·
[llm-cost](https://github.com/Mattbusel/llm-cost) ·
[llm-format](https://github.com/Mattbusel/llm-format) ·
[llm-json](https://github.com/Mattbusel/llm-json) ·
[llm-guard](https://github.com/Mattbusel/llm-guard) ·
[llm-rag](https://github.com/Mattbusel/llm-rag) ·
[llm-router](https://github.com/Mattbusel/llm-router) ·
[llm-trace](https://github.com/Mattbusel/llm-trace)

## Quant and finance

| Repo | What it is |
|---|---|
| [crypto-orderbook](https://github.com/Mattbusel/crypto-orderbook) | Rust crypto order book with Binance WebSocket ingestion, Tokio and an Axum REST API. |
| [Special-Relativity-in-Financial-Modeling](https://github.com/Mattbusel/Special-Relativity-in-Financial-Modeling) | C++20 special-relativity geometry on OHLCV data: Lorentz factors, spacetime intervals, geodesic signals. |
| [srfm-lab](https://github.com/Mattbusel/srfm-lab) · [srfm-python](https://github.com/Mattbusel/srfm-python) · [srfm-paper-impl](https://github.com/Mattbusel/srfm-paper-impl) | The SRFM family: research lab, Python SDK, reproducible paper repo. |
| [fin-stream](https://github.com/Mattbusel/fin-stream) | Real-time market data streaming in Rust. |

## Engines and creative code

| Repo | What it is |
|---|---|
| [chaos-rpg](https://github.com/Mattbusel/chaos-rpg) | Terminal roguelike. Every outcome runs through a chain of 4 to 10 real math algorithms. |
| [geodesic-wallpaper](https://github.com/Mattbusel/geodesic-wallpaper) | Animated Windows wallpaper of geodesic flows on curved surfaces. Rust and wgpu. |
| [math-sonify](https://github.com/Mattbusel/math-sonify) | Live audio from dynamical systems (Lorenz, Rossler, Kuramoto, three-body). |

## iOS apps, built on Windows

SwiftUI apps written on Windows with no Mac. XcodeGen makes the project. GitHub Actions macOS runners build, sign, screenshot and upload to App Store Connect.

| App | Repo | What it is |
|---|---|---|
| [Chain](https://apps.apple.com/app/id6814264554) | [chain](https://github.com/Mattbusel/chain) | Habit tracker that shows your year as a quilt of squares. |
| [Ironbook](https://apps.apple.com/app/id6814264434) | [ironbook](https://github.com/Mattbusel/ironbook) | Workout log with your last session beside every set. |
| [Quiver](https://apps.apple.com/app/id6814263466) | [quiver](https://github.com/Mattbusel/quiver) | Archer's notebook: arrow builds, FOC and printable sight tapes. |
| [Baseline Ledger](https://apps.apple.com/app/id6813452278) | [baseline-ledger](https://github.com/Mattbusel/baseline-ledger) | Tennis practice journal and match stats. |
| [Fairway Ledger](https://apps.apple.com/app/id6813452174) | [fairway-ledger](https://github.com/Mattbusel/fairway-ledger) | Golf practice journal and stats. |
| [Pocket Beings](https://apps.apple.com/app/id6812787188) | [pocket-beings](https://github.com/Mattbusel/pocket-beings) | Seven tiny people in a pocket town who rob, bribe and run for office. |
| [Clear the Strait](https://apps.apple.com/app/id6810644510) | [clear-the-strait](https://github.com/Mattbusel/clear-the-strait) | Tiny arcade game: he's stuck in the channel, shove him out. |

Support and privacy pages: [app-pages](https://github.com/Mattbusel/app-pages).

## Stack

`Rust` `Tokio` `C++20` `Python` `Swift` `SwiftUI` `wgpu` `WebAssembly` `GitHub Actions`

## Elsewhere

[Tensorust](https://tensorust.com/) · [Open source](https://tensorust.com/open-source/) · [crates.io](https://crates.io/users/mattbusel) · [LinkedIn](https://www.linkedin.com/in/matthewbusel/) · [Medium](https://medium.com/@mattbusel)

## Work with me

I take a few client projects at a time: [services and pricing](https://tensorust.com/), [mattbusel@gmail.com](mailto:mattbusel@gmail.com), [LinkedIn](https://www.linkedin.com/in/matthewbusel/).
