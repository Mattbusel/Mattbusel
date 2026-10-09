# Matt Busel

[English](README.md) | 简体中文 | [日本語](README.ja.md) | [한국어](README.ko.md)

我用 Rust 和 C++ 构建大模型（LLM）基础设施，也做量化工具、数学驱动的引擎，以及在一台 Windows 电脑上开发并上架的 iOS 应用。[Tensorust](https://tensorust-site.vercel.app/) 创始人。坐标纽约。

[![GitHub Stars](https://img.shields.io/github/stars/Mattbusel?style=flat&logo=github&label=total%20stars&color=gold)](https://github.com/Mattbusel?tab=repositories&sort=stargazers)

**找我开发你的应用。** 我为客户设计、开发并上线原生 iOS 应用和 AI 软件，从原型一直到 App Store 上架。固定报价：原型冲刺 $9,500 起，App Store 上架项目 $28,000 起，咨询 $225/小时。
[**查看服务和报价 →**](https://mattbusel.github.io/) · [邮箱](mailto:mattbusel@gmail.com) · [LinkedIn](https://www.linkedin.com/in/matthewbusel/)

## 用 Rust 构建的 LLM 基础设施

| 仓库 | 简介 |
|---|---|
| [tokio-prompt-orchestrator](https://github.com/Mattbusel/tokio-prompt-orchestrator) | 面向 LLM 流水线的多核、Tokio 原生编排框架。已发布到 [crates.io](https://crates.io/crates/tokio-prompt-orchestrator)。 |
| [agent-runtime](https://github.com/Mattbusel/agent-runtime) | 基于 Tokio 的 Agent 运行时：编排、记忆、知识图谱和 ReAct 循环集于一个 crate。 |
| [Every-Other-Token](https://github.com/Mattbusel/Every-Other-Token) | 实时 LLM 流拦截器，用于 token 级交互研究。已发布到 [crates.io](https://crates.io/crates/every-other-token)。 |
| [llm-cost-dashboard](https://github.com/Mattbusel/llm-cost-dashboard) | 终端仪表盘（ratatui），显示 LLM token 花费、每次请求的成本和预计月度账单。已发布到 [crates.io](https://crates.io/crates/llm-cost-dashboard)。 |
| [rust-crates](https://github.com/Mattbusel/rust-crates) | 我为 AI Agent 和金融系统编写的 Rust 库索引。 |

## llm-cpp：面向 LLM 应用的单头文件 C++ 库

[**llm-cpp**](https://github.com/Mattbusel/llm-cpp) 是 26 个零依赖、单头文件 C++ 库的总入口。把一个 `.hpp` 复制进你的项目就能用。其中几个：

[llm-stream](https://github.com/Mattbusel/llm-stream)（流式接收 OpenAI 和 Anthropic 的响应） ·
[llm-chat](https://github.com/Mattbusel/llm-chat) ·
[llm-agent](https://github.com/Mattbusel/llm-agent)（用 C++ lambda 实现工具调用） ·
[llm-retry](https://github.com/Mattbusel/llm-retry) ·
[llm-cache](https://github.com/Mattbusel/llm-cache) ·
[llm-cost](https://github.com/Mattbusel/llm-cost) ·
[llm-format](https://github.com/Mattbusel/llm-format) ·
[llm-json](https://github.com/Mattbusel/llm-json) ·
[llm-guard](https://github.com/Mattbusel/llm-guard) ·
[llm-rag](https://github.com/Mattbusel/llm-rag) ·
[llm-router](https://github.com/Mattbusel/llm-router) ·
[llm-trace](https://github.com/Mattbusel/llm-trace)

## 量化与金融

| 仓库 | 简介 |
|---|---|
| [fin-primitives](https://github.com/Mattbusel/fin-primitives) | Rust 行情基础组件：价格类型、订单簿、OHLCV、技术指标、持仓台账、风险监控。已发布到 [crates.io](https://crates.io/crates/fin-primitives)。 |
| [crypto-orderbook](https://github.com/Mattbusel/crypto-orderbook) | Rust 加密货币订单簿引擎，支持 Binance WebSocket 数据接入，基于 Tokio，并提供 Axum REST API。 |
| [Special-Relativity-in-Financial-Modeling](https://github.com/Mattbusel/Special-Relativity-in-Financial-Modeling) | 在 OHLCV 数据上实现狭义相对论几何的 C++20 项目：洛伦兹因子、时空间隔、测地线信号。 |
| [srfm-lab](https://github.com/Mattbusel/srfm-lab) · [srfm-python](https://github.com/Mattbusel/srfm-python) · [srfm-paper-impl](https://github.com/Mattbusel/srfm-paper-impl) | SRFM 系列：研究实验室、Python SDK，以及可复现的论文仓库。 |
| [fin-stream](https://github.com/Mattbusel/fin-stream) | 用 Rust 编写的实时行情数据流基础组件。 |

## 引擎与创意编程

| 仓库 | 简介 |
|---|---|
| [proof-engine](https://github.com/Mattbusel/proof-engine) | 一个 Rust 数学渲染引擎：每一个画面都是某个数学函数的输出。`cargo add proof-engine` |
| [chaos-rpg](https://github.com/Mattbusel/chaos-rpg) | 一款终端 Roguelike 游戏，每个结果都要经过一串 4 到 10 个真实数学算法的计算。 |
| [geodesic-wallpaper](https://github.com/Mattbusel/geodesic-wallpaper) | Windows 动态桌面壁纸，渲染曲面上的测地线流，使用 Rust 和 wgpu。 |
| [math-sonify](https://github.com/Mattbusel/math-sonify) | 把动力系统（Lorenz、Rossler、Kuramoto、三体）映射成实时音频。 |

## 在 Windows 上开发的 iOS 应用

在一台没有 Mac 的 Windows 电脑上编写的 SwiftUI 应用。XcodeGen 生成工程，GitHub Actions 的 macOS 运行器负责构建、签名、截图，并上传到 App Store Connect。

| 应用 | 仓库 | 简介 |
|---|---|---|
| [Chain](https://apps.apple.com/app/id6814264554) | [chain](https://github.com/Mattbusel/chain) | 习惯打卡应用，把你的一整年显示成一床由方格拼成的被子。 |
| [Ironbook](https://apps.apple.com/app/id6814264434) | [ironbook](https://github.com/Mattbusel/ironbook) | 健身训练记录，每一组旁边都显示你上一次训练的数据。 |
| [Quiver](https://apps.apple.com/app/id6814263466) | [quiver](https://github.com/Mattbusel/quiver) | 射箭手的笔记本：箭支配置、FOC 和可打印的瞄具刻度贴。 |
| [Baseline Ledger](https://apps.apple.com/app/id6813452278) | [baseline-ledger](https://github.com/Mattbusel/baseline-ledger) | 网球练习日志和比赛数据记录本。 |
| [Fairway Ledger](https://apps.apple.com/app/id6813452174) | [fairway-ledger](https://github.com/Mattbusel/fairway-ledger) | 高尔夫练习日志和数据记录本。 |
| [Pocket Beings](https://apps.apple.com/app/id6812787188) | [pocket-beings](https://github.com/Mattbusel/pocket-beings) | 口袋小镇里的七个小人，在你眼前抢劫、行贿、竞选公职。 |
| [Clear the Strait](https://apps.apple.com/app/id6810644510) | [clear-the-strait](https://github.com/Mattbusel/clear-the-strait) | 一款迷你街机游戏：他卡在海峡里了，把他推出去。 |

这些应用的支持页面和隐私政策页面放在 [app-pages](https://github.com/Mattbusel/app-pages)。

## 技术栈

`Rust` `Tokio` `C++20` `Python` `Swift` `SwiftUI` `wgpu` `WebAssembly` `GitHub Actions`

## 其他地方

[Tensorust](https://tensorust-site.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/matthewbusel/) · [Medium](https://medium.com/@mattbusel)

## 与我合作

有想做的应用吗？我同一时间只接少量客户项目：[服务和报价](https://mattbusel.github.io/)、[mattbusel@gmail.com](mailto:mattbusel@gmail.com)、[LinkedIn](https://www.linkedin.com/in/matthewbusel/)。
