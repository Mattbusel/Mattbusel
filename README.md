# Matt Busel

I build LLM infrastructure in Rust and C++, quant tooling, math-driven engines, and iOS apps that I ship from a Windows PC. Founder of [Tensorust](https://tensorust-site.vercel.app/). New York.

[![GitHub Stars](https://img.shields.io/github/stars/Mattbusel?style=flat&logo=github&label=total%20stars&color=gold)](https://github.com/Mattbusel?tab=repositories&sort=stargazers)

**Hire me to build your app.** I design, build and ship native iOS apps and AI software for clients, from prototype to App Store launch. Fixed prices: prototype sprints from $9,500, App Store launches from $28,000, $225/hour for advisory.
[**See services and pricing →**](https://mattbusel.github.io/) · [Email](mailto:mattbusel@gmail.com) · [LinkedIn](https://www.linkedin.com/in/matthewbusel/)

## LLM infrastructure in Rust

| Repo | What it is |
|---|---|
| [tokio-prompt-orchestrator](https://github.com/Mattbusel/tokio-prompt-orchestrator) | Multi-core, Tokio-native orchestration for LLM pipelines. On [crates.io](https://crates.io/crates/tokio-prompt-orchestrator). |
| [agent-runtime](https://github.com/Mattbusel/agent-runtime) | Tokio agent runtime: orchestration, memory, knowledge graph and a ReAct loop in one crate. |
| [Every-Other-Token](https://github.com/Mattbusel/Every-Other-Token) | Real-time LLM stream interceptor for token-level interaction research. On [crates.io](https://crates.io/crates/every-other-token). |
| [llm-cost-dashboard](https://github.com/Mattbusel/llm-cost-dashboard) | Terminal dashboard (ratatui) for LLM token spend, cost per request and projected monthly bills. On [crates.io](https://crates.io/crates/llm-cost-dashboard). |
| [rust-crates](https://github.com/Mattbusel/rust-crates) | Index of my Rust libraries for AI agents and financial systems. |

## llm-cpp: single-header C++ for LLM apps

[**llm-cpp**](https://github.com/Mattbusel/llm-cpp) is the umbrella for 26 zero-dependency, single-header C++ libraries. Copy one `.hpp` into your project and use it. A few of them:

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
| [fin-primitives](https://github.com/Mattbusel/fin-primitives) | Rust market primitives: price types, order book, OHLCV, indicators, position ledger, risk monitor. On [crates.io](https://crates.io/crates/fin-primitives). |
| [crypto-orderbook](https://github.com/Mattbusel/crypto-orderbook) | Rust crypto order book engine with Binance WebSocket ingestion, Tokio and an Axum REST API. |
| [Special-Relativity-in-Financial-Modeling](https://github.com/Mattbusel/Special-Relativity-in-Financial-Modeling) | C++20 implementation of special-relativistic geometry on OHLCV data: Lorentz factors, spacetime intervals, geodesic signals. |
| [srfm-lab](https://github.com/Mattbusel/srfm-lab) · [srfm-python](https://github.com/Mattbusel/srfm-python) · [srfm-paper-impl](https://github.com/Mattbusel/srfm-paper-impl) | The SRFM family: research lab, Python SDK, and the reproducible paper repo. |
| [fin-stream](https://github.com/Mattbusel/fin-stream) | Real-time market data streaming primitives in Rust. |

## Engines and creative code

| Repo | What it is |
|---|---|
| [proof-engine](https://github.com/Mattbusel/proof-engine) | A mathematical rendering engine for Rust: every visual is the output of a mathematical function. `cargo add proof-engine` |
| [chaos-rpg](https://github.com/Mattbusel/chaos-rpg) | A terminal roguelike where every outcome runs through a chain of 4 to 10 real mathematical algorithms. |
| [geodesic-wallpaper](https://github.com/Mattbusel/geodesic-wallpaper) | Animated Windows desktop wallpaper that renders geodesic flows on curved surfaces, Rust and wgpu. |
| [math-sonify](https://github.com/Mattbusel/math-sonify) | Real-time audio from dynamical systems (Lorenz, Rossler, Kuramoto, three-body) mapped to sound. |

## iOS apps, built on Windows

SwiftUI apps written on a Windows machine with no Mac. XcodeGen generates the project, and GitHub Actions macOS runners build, sign, screenshot and upload them to App Store Connect.

| App | Repo | What it is |
|---|---|---|
| [Chain](https://apps.apple.com/app/id6814264554) | [chain](https://github.com/Mattbusel/chain) | Habit tracker that shows your year as a quilt of squares. |
| [Ironbook](https://apps.apple.com/app/id6814264434) | [ironbook](https://github.com/Mattbusel/ironbook) | Workout log with your last session beside every set. |
| [Quiver](https://apps.apple.com/app/id6814263466) | [quiver](https://github.com/Mattbusel/quiver) | Archer's notebook: arrow builds, FOC and printable sight tapes. |
| [Baseline Ledger](https://apps.apple.com/app/id6813452278) | [baseline-ledger](https://github.com/Mattbusel/baseline-ledger) | Tennis practice journal and match stat book. |
| [Fairway Ledger](https://apps.apple.com/app/id6813452174) | [fairway-ledger](https://github.com/Mattbusel/fairway-ledger) | Golf practice journal and stat book. |
| [Pocket Beings](https://apps.apple.com/app/id6812787188) | [pocket-beings](https://github.com/Mattbusel/pocket-beings) | Seven tiny people in a pocket town who rob, bribe and run for office while you watch. |
| [Clear the Strait](https://apps.apple.com/app/id6810644510) | [clear-the-strait](https://github.com/Mattbusel/clear-the-strait) | A tiny arcade game: he is stuck in the channel, shove him out. |

Support and privacy pages for the apps live in [app-pages](https://github.com/Mattbusel/app-pages).

## Stack

`Rust` `Tokio` `C++20` `Python` `Swift` `SwiftUI` `wgpu` `WebAssembly` `GitHub Actions`

## Elsewhere

[Tensorust](https://tensorust-site.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/matthewbusel/) · [Medium](https://medium.com/@mattbusel)

## Work with me

Have an app you want built? I take a small number of client projects at a time: [services and pricing](https://mattbusel.github.io/), [mattbusel@gmail.com](mailto:mattbusel@gmail.com), [LinkedIn](https://www.linkedin.com/in/matthewbusel/).
