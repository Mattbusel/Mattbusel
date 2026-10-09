# Matt Busel

[English](README.md) | [简体中文](README.zh-CN.md) | 日本語 | [한국어](README.ko.md)

Rust と C++ による LLM インフラ、クオンツ向けツール、数学で動くエンジン、そして Windows PC から開発・リリースしている iOS アプリを作っています。[Tensorust](https://tensorust-site.vercel.app/) 創業者。ニューヨーク在住。

[![GitHub Stars](https://img.shields.io/github/stars/Mattbusel?style=flat&logo=github&label=total%20stars&color=gold)](https://github.com/Mattbusel?tab=repositories&sort=stargazers)

**アプリ開発をご依頼ください。** クライアント向けにネイティブ iOS アプリと AI ソフトウェアを、プロトタイプから App Store でのリリースまで設計・開発・公開します。固定料金：プロトタイプスプリントは $9,500 から、App Store リリースは $28,000 から、アドバイザリーは 1 時間 $225 です。
[**サービスと料金を見る →**](https://mattbusel.github.io/) · [メール](mailto:mattbusel@gmail.com) · [LinkedIn](https://www.linkedin.com/in/matthewbusel/)

## Rust 製の LLM インフラ

| リポジトリ | 内容 |
|---|---|
| [tokio-prompt-orchestrator](https://github.com/Mattbusel/tokio-prompt-orchestrator) | LLM パイプライン向けの、マルチコア対応で Tokio ネイティブなオーケストレーション。[crates.io](https://crates.io/crates/tokio-prompt-orchestrator) で公開中。 |
| [agent-runtime](https://github.com/Mattbusel/agent-runtime) | Tokio 製のエージェントランタイム：オーケストレーション、メモリ、ナレッジグラフ、ReAct ループを 1 つのクレートに。 |
| [Every-Other-Token](https://github.com/Mattbusel/Every-Other-Token) | トークン単位のインタラクション研究のための、リアルタイム LLM ストリームインターセプター。[crates.io](https://crates.io/crates/every-other-token) で公開中。 |
| [llm-cost-dashboard](https://github.com/Mattbusel/llm-cost-dashboard) | LLM のトークン消費、リクエストあたりのコスト、月額請求の見込みを表示するターミナルダッシュボード（ratatui）。[crates.io](https://crates.io/crates/llm-cost-dashboard) で公開中。 |
| [rust-crates](https://github.com/Mattbusel/rust-crates) | AI エージェントと金融システム向けに作った Rust ライブラリの一覧。 |

## llm-cpp：LLM アプリのためのシングルヘッダー C++

[**llm-cpp**](https://github.com/Mattbusel/llm-cpp) は、依存ゼロのシングルヘッダー C++ ライブラリ 26 個をまとめたものです。`.hpp` を 1 つプロジェクトにコピーするだけで使えます。いくつか紹介します。

[llm-stream](https://github.com/Mattbusel/llm-stream)（OpenAI と Anthropic のレスポンスをストリーミング） ·
[llm-chat](https://github.com/Mattbusel/llm-chat) ·
[llm-agent](https://github.com/Mattbusel/llm-agent)（C++ のラムダでツール呼び出し） ·
[llm-retry](https://github.com/Mattbusel/llm-retry) ·
[llm-cache](https://github.com/Mattbusel/llm-cache) ·
[llm-cost](https://github.com/Mattbusel/llm-cost) ·
[llm-format](https://github.com/Mattbusel/llm-format) ·
[llm-json](https://github.com/Mattbusel/llm-json) ·
[llm-guard](https://github.com/Mattbusel/llm-guard) ·
[llm-rag](https://github.com/Mattbusel/llm-rag) ·
[llm-router](https://github.com/Mattbusel/llm-router) ·
[llm-trace](https://github.com/Mattbusel/llm-trace)

## クオンツと金融

| リポジトリ | 内容 |
|---|---|
| [fin-primitives](https://github.com/Mattbusel/fin-primitives) | Rust のマーケット基本部品：価格型、板（オーダーブック）、OHLCV、テクニカル指標、ポジション台帳、リスクモニター。[crates.io](https://crates.io/crates/fin-primitives) で公開中。 |
| [crypto-orderbook](https://github.com/Mattbusel/crypto-orderbook) | Binance の WebSocket からデータを取り込む Rust 製の暗号資産オーダーブックエンジン。Tokio と Axum の REST API を使用。 |
| [Special-Relativity-in-Financial-Modeling](https://github.com/Mattbusel/Special-Relativity-in-Financial-Modeling) | OHLCV データ上に特殊相対論的な幾何を実装した C++20 プロジェクト：ローレンツ因子、時空間隔、測地線シグナル。 |
| [srfm-lab](https://github.com/Mattbusel/srfm-lab) · [srfm-python](https://github.com/Mattbusel/srfm-python) · [srfm-paper-impl](https://github.com/Mattbusel/srfm-paper-impl) | SRFM ファミリー：研究ラボ、Python SDK、再現可能な論文リポジトリ。 |
| [fin-stream](https://github.com/Mattbusel/fin-stream) | Rust によるリアルタイム市場データのストリーミング基本部品。 |

## エンジンとクリエイティブコーディング

| リポジトリ | 内容 |
|---|---|
| [proof-engine](https://github.com/Mattbusel/proof-engine) | Rust 向けの数学レンダリングエンジン：すべての映像が数学関数の出力です。`cargo add proof-engine` |
| [chaos-rpg](https://github.com/Mattbusel/chaos-rpg) | すべての結果が 4 から 10 個の本物の数学アルゴリズムの連鎖を通って決まる、ターミナルのローグライク。 |
| [geodesic-wallpaper](https://github.com/Mattbusel/geodesic-wallpaper) | 曲面上の測地線の流れを描く、Windows 用の動く壁紙。Rust と wgpu 製。 |
| [math-sonify](https://github.com/Mattbusel/math-sonify) | 力学系（Lorenz、Rossler、Kuramoto、三体問題）を音にマッピングするリアルタイムオーディオ。 |

## Windows で作った iOS アプリ

Mac を使わず Windows マシンで書いた SwiftUI アプリです。XcodeGen がプロジェクトを生成し、GitHub Actions の macOS ランナーがビルド、署名、スクリーンショット撮影を行って App Store Connect にアップロードします。

| アプリ | リポジトリ | 内容 |
|---|---|---|
| [Chain](https://apps.apple.com/app/id6814264554) | [chain](https://github.com/Mattbusel/chain) | 1 年をマス目のキルトとして見せる習慣トラッカー。 |
| [Ironbook](https://apps.apple.com/app/id6814264434) | [ironbook](https://github.com/Mattbusel/ironbook) | すべてのセットの横に前回のセッションが表示される筋トレ記録。 |
| [Quiver](https://apps.apple.com/app/id6814263466) | [quiver](https://github.com/Mattbusel/quiver) | アーチャーのためのノート：矢の構成、FOC、印刷できるサイトテープ。 |
| [Baseline Ledger](https://apps.apple.com/app/id6813452278) | [baseline-ledger](https://github.com/Mattbusel/baseline-ledger) | テニスの練習日誌と試合のスタッツ帳。 |
| [Fairway Ledger](https://apps.apple.com/app/id6813452174) | [fairway-ledger](https://github.com/Mattbusel/fairway-ledger) | ゴルフの練習日誌とスタッツ帳。 |
| [Pocket Beings](https://apps.apple.com/app/id6812787188) | [pocket-beings](https://github.com/Mattbusel/pocket-beings) | ポケットの中の町で、7 人の小さな住人が強盗し、賄賂を渡し、選挙に出る様子を眺めるアプリ。 |
| [Clear the Strait](https://apps.apple.com/app/id6810644510) | [clear-the-strait](https://github.com/Mattbusel/clear-the-strait) | 小さなアーケードゲーム：海峡に詰まった彼を押し出そう。 |

アプリのサポートページとプライバシーページは [app-pages](https://github.com/Mattbusel/app-pages) にあります。

## 技術スタック

`Rust` `Tokio` `C++20` `Python` `Swift` `SwiftUI` `wgpu` `WebAssembly` `GitHub Actions`

## その他のリンク

[Tensorust](https://tensorust-site.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/matthewbusel/) · [Medium](https://medium.com/@mattbusel)

## お仕事のご相談

作りたいアプリはありますか？ 同時にお受けするクライアント案件は少数に限っています：[サービスと料金](https://mattbusel.github.io/)、[mattbusel@gmail.com](mailto:mattbusel@gmail.com)、[LinkedIn](https://www.linkedin.com/in/matthewbusel/)。
