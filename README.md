# Matt Busel

English | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | [한국어](README.ko.md)

**iPhone apps, Rust tools and a Steam game. One person.** I run [Tensorust](https://tensorust.com/), a one-person software studio in New York; AI agents run the marketing, in public.

**Now:** [**O'BLOCK**](https://store.steampowered.com/app/5357680/?utm_source=github_profile), a sneaker-flipping game on my own Rust engine, is out free on Steam October 20 (English, 简体中文, 日本語, 한국어). One mechanic: you name a price, and the buyers lie. [Wishlist it on Steam](https://store.steampowered.com/app/5357680/?utm_source=github_profile).

[![GitHub Stars](https://img.shields.io/github/stars/Mattbusel?style=flat&logo=github&label=total%20stars&color=gold)](https://github.com/Mattbusel?tab=repositories&sort=stargazers)

## Open-source Rust you can use today

69 crates on [crates.io](https://crates.io/users/mattbusel), 5,038 downloads (checked Oct 17, 2026). All MIT. These six are the ones most worth your time:

| Crate | Use it to | Install |
|---|---|---|
| [tokio-prompt-orchestrator](https://github.com/Mattbusel/tokio-prompt-orchestrator) | Put a proxy in front of any LLM API: the same prompt twice costs one call, outages fail fast, spend is capped. Drop-in for OpenAI and Anthropic clients. | `cargo install tokio-prompt-orchestrator --features web-api` |
| [fin-primitives](https://github.com/Mattbusel/fin-primitives) | Trading code with exact decimal prices, an order book, ticks to candles, 700+ indicators, Black-Scholes Greeks and risk limits. | `cargo add fin-primitives` |
| [every-other-token](https://github.com/Mattbusel/Every-Other-Token) | Watch an LLM answer token by token with per-token confidence from logprobs, and rewrite tokens live. No API key needed to try it. | `cargo install every-other-token` |
| [proof-engine](https://github.com/Mattbusel/proof-engine) | Draw math in real time: strange attractors, ODEs and force fields with HDR bloom on OpenGL. 21 demos. | `cargo add proof-engine` |
| [llm-cost-dashboard](https://github.com/Mattbusel/llm-cost-dashboard) | Price every LLM call from your logs (104 models, prompt caching, Claude Code logs) in a terminal dashboard, Prometheus or Rust. | `cargo install llm-cost-dashboard` |
| [llm-budget](https://github.com/Mattbusel/llm-budget) | Give each agent a hard dollar cap so a runaway loop stops instead of running up the bill. 232 real model prices. | `cargo add llm-budget` |

The full list with live download counts: [tensorust.com/open-source](https://tensorust.com/open-source/). Issues and PRs welcome on any of them.

**Hire me to build your app.** I design, build and ship native iOS apps and AI software for clients, from prototype to App Store launch. Fixed prices: prototype sprints from $9,500, App Store launches from $28,000, $225/hour for advisory.
[**See services and pricing**](https://tensorust.com/) · [Email](mailto:mattbusel@gmail.com) · [LinkedIn](https://www.linkedin.com/in/matthewbusel/)

## More LLM infrastructure in Rust

| Repo | What it is |
|---|---|
| [agent-runtime](https://github.com/Mattbusel/agent-runtime) | Tokio agent runtime: orchestration, memory, knowledge graph and a ReAct loop in one crate. |
| [LLM-Hallucination-Detection-Script](https://github.com/Mattbusel/LLM-Hallucination-Detection-Script) | Flag low-confidence spans in LLM output from token logprobs. Crate: `llm-token-visualizer`. |
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
| [crypto-orderbook](https://github.com/Mattbusel/crypto-orderbook) | Rust crypto order book engine with Binance WebSocket ingestion, Tokio and an Axum REST API. |
| [Special-Relativity-in-Financial-Modeling](https://github.com/Mattbusel/Special-Relativity-in-Financial-Modeling) | C++20 implementation of special-relativistic geometry on OHLCV data: Lorentz factors, spacetime intervals, geodesic signals. |
| [srfm-lab](https://github.com/Mattbusel/srfm-lab) · [srfm-python](https://github.com/Mattbusel/srfm-python) · [srfm-paper-impl](https://github.com/Mattbusel/srfm-paper-impl) | The SRFM family: research lab, Python SDK, and the reproducible paper repo. |
| [fin-stream](https://github.com/Mattbusel/fin-stream) | Real-time market data streaming primitives in Rust. |

## Engines and creative code

| Repo | What it is |
|---|---|
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

[Tensorust](https://tensorust.com/) · [Open source](https://tensorust.com/open-source/) · [crates.io](https://crates.io/users/mattbusel) · [LinkedIn](https://www.linkedin.com/in/matthewbusel/) · [Medium](https://medium.com/@mattbusel)

## Work with me

Have an app you want built? I take a small number of client projects at a time: [services and pricing](https://tensorust.com/), [mattbusel@gmail.com](mailto:mattbusel@gmail.com), [LinkedIn](https://www.linkedin.com/in/matthewbusel/).
