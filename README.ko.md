# Matt Busel

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.ja.md) | 한국어

Rust와 C++로 LLM 인프라를 만들고, 퀀트 도구와 수학으로 움직이는 엔진, 그리고 Windows PC에서 개발해 출시하는 iOS 앱을 만듭니다. [Tensorust](https://tensorust-site.vercel.app/) 창업자. 뉴욕 거주.

[![GitHub Stars](https://img.shields.io/github/stars/Mattbusel?style=flat&logo=github&label=total%20stars&color=gold)](https://github.com/Mattbusel?tab=repositories&sort=stargazers)

**앱 개발을 맡겨 주세요.** 클라이언트를 위해 네이티브 iOS 앱과 AI 소프트웨어를 프로토타입부터 App Store 출시까지 설계하고, 만들고, 내보냅니다. 고정 가격: 프로토타입 스프린트 $9,500부터, App Store 출시 $28,000부터, 자문은 시간당 $225.
[**서비스와 가격 보기 →**](https://mattbusel.github.io/) · [이메일](mailto:mattbusel@gmail.com) · [LinkedIn](https://www.linkedin.com/in/matthewbusel/)

## Rust로 만든 LLM 인프라

| 저장소 | 설명 |
|---|---|
| [tokio-prompt-orchestrator](https://github.com/Mattbusel/tokio-prompt-orchestrator) | LLM 파이프라인을 위한 멀티코어, Tokio 네이티브 오케스트레이션. [crates.io](https://crates.io/crates/tokio-prompt-orchestrator)에 공개. |
| [agent-runtime](https://github.com/Mattbusel/agent-runtime) | Tokio 에이전트 런타임: 오케스트레이션, 메모리, 지식 그래프, ReAct 루프를 크레이트 하나에. |
| [Every-Other-Token](https://github.com/Mattbusel/Every-Other-Token) | 토큰 단위 상호작용 연구를 위한 실시간 LLM 스트림 가로채기 도구. [crates.io](https://crates.io/crates/every-other-token)에 공개. |
| [llm-cost-dashboard](https://github.com/Mattbusel/llm-cost-dashboard) | LLM 토큰 지출, 요청당 비용, 예상 월 청구액을 보여 주는 터미널 대시보드(ratatui). [crates.io](https://crates.io/crates/llm-cost-dashboard)에 공개. |
| [rust-crates](https://github.com/Mattbusel/rust-crates) | AI 에이전트와 금융 시스템을 위해 만든 Rust 라이브러리 목록. |

## llm-cpp: LLM 앱을 위한 싱글 헤더 C++

[**llm-cpp**](https://github.com/Mattbusel/llm-cpp)는 의존성 없는 싱글 헤더 C++ 라이브러리 26개를 묶은 프로젝트입니다. `.hpp` 하나를 프로젝트에 복사해서 바로 쓰면 됩니다. 그중 몇 가지:

[llm-stream](https://github.com/Mattbusel/llm-stream)(OpenAI와 Anthropic 응답 스트리밍) ·
[llm-chat](https://github.com/Mattbusel/llm-chat) ·
[llm-agent](https://github.com/Mattbusel/llm-agent)(C++ 람다로 도구 호출) ·
[llm-retry](https://github.com/Mattbusel/llm-retry) ·
[llm-cache](https://github.com/Mattbusel/llm-cache) ·
[llm-cost](https://github.com/Mattbusel/llm-cost) ·
[llm-format](https://github.com/Mattbusel/llm-format) ·
[llm-json](https://github.com/Mattbusel/llm-json) ·
[llm-guard](https://github.com/Mattbusel/llm-guard) ·
[llm-rag](https://github.com/Mattbusel/llm-rag) ·
[llm-router](https://github.com/Mattbusel/llm-router) ·
[llm-trace](https://github.com/Mattbusel/llm-trace)

## 퀀트와 금융

| 저장소 | 설명 |
|---|---|
| [fin-primitives](https://github.com/Mattbusel/fin-primitives) | Rust 시장 기본 요소: 가격 타입, 호가창(오더북), OHLCV, 지표, 포지션 원장, 리스크 모니터. [crates.io](https://crates.io/crates/fin-primitives)에 공개. |
| [crypto-orderbook](https://github.com/Mattbusel/crypto-orderbook) | Binance WebSocket 수집, Tokio, Axum REST API를 갖춘 Rust 암호화폐 오더북 엔진. |
| [Special-Relativity-in-Financial-Modeling](https://github.com/Mattbusel/Special-Relativity-in-Financial-Modeling) | OHLCV 데이터에 특수상대론적 기하를 구현한 C++20 프로젝트: 로런츠 인자, 시공간 간격, 측지선 신호. |
| [srfm-lab](https://github.com/Mattbusel/srfm-lab) · [srfm-python](https://github.com/Mattbusel/srfm-python) · [srfm-paper-impl](https://github.com/Mattbusel/srfm-paper-impl) | SRFM 프로젝트 군: 연구 랩, Python SDK, 재현 가능한 논문 저장소. |
| [fin-stream](https://github.com/Mattbusel/fin-stream) | Rust로 만든 실시간 시장 데이터 스트리밍 기본 요소. |

## 엔진과 크리에이티브 코딩

| 저장소 | 설명 |
|---|---|
| [proof-engine](https://github.com/Mattbusel/proof-engine) | Rust용 수학 렌더링 엔진: 모든 화면이 수학 함수의 출력입니다. `cargo add proof-engine` |
| [chaos-rpg](https://github.com/Mattbusel/chaos-rpg) | 모든 결과가 4개에서 10개의 실제 수학 알고리즘을 연달아 거쳐 결정되는 터미널 로그라이크. |
| [geodesic-wallpaper](https://github.com/Mattbusel/geodesic-wallpaper) | 곡면 위의 측지선 흐름을 그리는 Windows 움직이는 배경화면, Rust와 wgpu로 제작. |
| [math-sonify](https://github.com/Mattbusel/math-sonify) | 동역학계(Lorenz, Rossler, Kuramoto, 삼체 문제)를 소리에 매핑하는 실시간 오디오. |

## Windows에서 만든 iOS 앱

Mac 없이 Windows 컴퓨터에서 작성한 SwiftUI 앱들입니다. XcodeGen이 프로젝트를 생성하고, GitHub Actions macOS 러너가 빌드, 서명, 스크린샷 촬영을 거쳐 App Store Connect에 업로드합니다.

| 앱 | 저장소 | 설명 |
|---|---|---|
| [Chain](https://apps.apple.com/app/id6814264554) | [chain](https://github.com/Mattbusel/chain) | 1년을 네모 칸 퀼트로 보여 주는 습관 트래커. |
| [Ironbook](https://apps.apple.com/app/id6814264434) | [ironbook](https://github.com/Mattbusel/ironbook) | 모든 세트 옆에 지난번 운동 기록을 보여 주는 운동 일지. |
| [Quiver](https://apps.apple.com/app/id6814263466) | [quiver](https://github.com/Mattbusel/quiver) | 양궁인을 위한 노트: 화살 구성, FOC, 인쇄 가능한 조준기 눈금 테이프. |
| [Baseline Ledger](https://apps.apple.com/app/id6813452278) | [baseline-ledger](https://github.com/Mattbusel/baseline-ledger) | 테니스 연습 일지와 경기 기록장. |
| [Fairway Ledger](https://apps.apple.com/app/id6813452174) | [fairway-ledger](https://github.com/Mattbusel/fairway-ledger) | 골프 연습 일지와 기록장. |
| [Pocket Beings](https://apps.apple.com/app/id6812787188) | [pocket-beings](https://github.com/Mattbusel/pocket-beings) | 주머니 속 마을의 작은 주민 일곱 명이 강도질하고, 뇌물을 주고, 선거에 나가는 모습을 지켜보는 앱. |
| [Clear the Strait](https://apps.apple.com/app/id6810644510) | [clear-the-strait](https://github.com/Mattbusel/clear-the-strait) | 작은 아케이드 게임: 해협에 끼어 버린 그를 밀어내세요. |

앱의 지원 페이지와 개인정보 처리방침 페이지는 [app-pages](https://github.com/Mattbusel/app-pages)에 있습니다.

## 기술 스택

`Rust` `Tokio` `C++20` `Python` `Swift` `SwiftUI` `wgpu` `WebAssembly` `GitHub Actions`

## 다른 곳에서

[Tensorust](https://tensorust-site.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/matthewbusel/) · [Medium](https://medium.com/@mattbusel)

## 함께 일하기

만들고 싶은 앱이 있나요? 한 번에 소수의 클라이언트 프로젝트만 맡습니다: [서비스와 가격](https://mattbusel.github.io/), [mattbusel@gmail.com](mailto:mattbusel@gmail.com), [LinkedIn](https://www.linkedin.com/in/matthewbusel/).
