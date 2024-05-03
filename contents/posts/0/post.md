---
title: "새로운 세대의 평가 기준: 데이터 오염 문제를 해결하다"
description: "destest: 새로운 세대의 평가 기준: 데이터 오염 문제를 해결하다"
date: 2024-05-04
update: 2024-05-04
tags:
  - gpt2chatbot
  - Llama38B
  - SB1047
---

## 기술적 조용함 속의 논의: SB-1047과 새로운 GPT2 챗봇

이번 주말은 큰 이슈 없이 조용했지만, 몇 가지 주목할 만한 기술 논의가 있었습니다. [SB-1047](https://www.reddit.com/r/LocalLLaMA/comments/1cfizbb/california_sb1047_seems_like_it_could_impact_open/?utm_source=ainews&utm_medium=email&utm_campaign=ainews-a-quiet-weekend)에 대한 토론이 활발했으며, 새로운 [gpt2-chatbot](https://twitter.com/phill__1/status/1784964135920235000?utm_source=ainews&utm_medium=email&utm_campaign=ainews-a-quiet-weekend)이 lmsys에서 소개되었습니다. 또한, Llama-3-8B를 1백만 컨텍스트로 확장하는 작업에 대한 정보도 공유되었습니다. 이 외에도, 보안 문제로 잠시 중단되었던 Nous Research의 [WebSim/WorldSim](https://www.latent.space/p/sim-ai?utm_source=ainews&utm_medium=email&utm_campaign=ainews-a-quiet-weekend) 팟캐스트가 재개될 준비를 하고 있습니다.

### AI Viewpoint 🤖
이번 주말의 기술 논의는 큰 이슈는 아니었지만, AI와 기술의 미래에 중요한 영향을 미칠 수 있는 주제들이 포함되어 있습니다. SB-1047과 같은 법적 조치는 기술 개발과 적용에 법적 틀을 제공하며, 새로운 AI 챗봇의 등장은 사용자 인터페이스와 상호작용의 발전을 예시합니다. 또한, 기술의 확장성을 보여주는 Llama-3-8B의 컨텍스트 확장은 AI의 처리 능력과 다양한 응용 가능성을 시사합니다. 이러한 기술적 발전과 논의는 향후 AI 연구와 개발 방향에 중요한 영향을 미칠 것입니다.

## Community Summary
- **Yann LeCun은 AR 인터페이스로 AI 어시스턴트와 상호작용할 것이라 예측**: [Yann LeCun은 10-15년 내에 스마트폰 대신 AR 안경과 팔찌를 통해 지능형 어시스턴트와 상호작용할 것이라고 말했습니다.](https://www.reddit.com/r/singularity/comments/1cfr9j4/yann_lecun_says_in_10_years_we_wont_have/?utm_source=ainews&utm_medium=email&utm_campaign=ainews-a-quiet-weekend)

- **Dolphin-2.9 모델, Llama-3 기반으로 출시**: [새로운 Dolphin-2.9 모델이 Llama-3를 기반으로 출시되어 이전 버전의 품질 문제를 해결할 수 있을 것으로 보입니다.](https://www.reddit.com/r/LocalLLaMA/comments/1cf3k1d/anyone_tried_new_dolphin29llama38b256k/?utm_source=ainews&utm_medium=email&utm_campaign=ainews-a-quiet-weekend)

- **PixArt Sigma, 0.6B 파라미터로 Stable Diffusion 3.0 수준 달성**: [PixArt Sigma 모델이 0.6B 파라미터만으로 Stable Diffusion 3.0 수준의 성능을 달성했으며, 완벽한 프롬프트 준수를 보이며 로컬에서 사용 가능합니다.](https://www.reddit.com/r/singularity/comments/1cfacll/pixart_sigma_is_the_first_model_with_complete/?utm_source=ainews&utm_medium=email&utm_campaign=ainews-a-quiet-weekend)

- **트랜스포머는 알고리즘 작업을 위해 의미 없는 채우기 토큰을 사용할 수 있음**: [트랜스포머는 알고리즘 작업을 해결하기 위해 '......'와 같은 의미 없는 채우기 토큰을 사용할 수 있으며, 특정 밀집 감독이 필요합니다.](https://www.reddit.com/r/LocalLLaMA/comments/1cf2w5a/transformers_can_use_meaningless_filler_tokens_eg/?utm_source=ainews&utm_medium=email&utm_campaign=ainews-a-quiet-weekend)

- **Reasoning and Multi-Step Problem Solving**: [@cwolferesearch는 추론 작업을 위한 최근의 프롬프트 엔지니어링 연구를 개요하며, zero-shot CoT 프롬프팅, 복잡성에 따른 CoT 예시 선택, 논리의 점진적 개선, 복잡한 작업을 하위 작업으로 분해하는 방법을 포함합니다.](https://twitter.com/cwolferesearch/status/1784992130777137362?utm_source=ainews&utm_medium=email&utm_campaign=ainews-a-quiet-weekend)

- **Tool Usage and API Integration**: [@cwolferesearch는 LLM이 외부 도구 및 API를 활용하는 방법에 대한 연구를 강조하며, 텍스트 기반 API, 도구 호출로 구성된 자연어 프로그램, 샌드박스 환경에서의 코드 실행을 포함합니다.](https://twitter.com/cwolferesearch/status/1784992130777137362?utm_source=ainews&utm_medium=email&utm_campaign=ainews-a-quiet-weekend)

- **Optimizing Context Window Usage**: [@cwolferesearch는 프롬프트의 맥락 창 속성의 영향에 대한 연구를 논의하며, 관련 없는 맥락의 부정적 효과, 프롬프트의 시작/끝에 대한 주의 편향, 최적의 few-shot 예시 선택 전략을 포함합니다.](https://twitter.com/cwolferesearch/status/1784992130777137362?utm_source=ainews&utm_medium=email&utm_campaign=ainews-a-quiet-weekend)

- **Improving LLM-Assisted Writing**: [@cwolferesearch는 LLM 생성 글쓰기를 향상시키는 기술을 다루며, 개요 생성 및 반복적 채우기, 작은 LLM을 사용하여 '방향성 자극' 생성, 요약에서 정보 밀도를 점진적으로 증가시키는 방법을 포함합니다.](https://twitter.com/cwolferesearch/status/1784992130777137362?utm_source=ainews&utm_medium=email&utm_campaign=ainews-a-quiet-weekend)

