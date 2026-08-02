---
layout: single
title: "📊 AI 일간보고서 — 2026년 08월 02일"
date: 2026-08-02 09:05:00 +0900
categories:
  - 일간보고서
tags:
  - "InstellaMoE"
  - "MiniMaxH3"
  - "SupabaseEvals"
  - "미네소타누디파이금지법"
  - "2026"
author_profile: false
read_time: true
toc: true
toc_label: "목차"
toc_sticky: true
header:
  overlay_image: "https://picsum.photos/seed/daily-ai-report/1600/500"
  overlay_filter: "0.6"
---

> **2026년 08월 02일 AI 트렌드 종합 요약** — 오늘 하루 AI 업계의 핵심 소식을 정리했습니다.

## 2026년 08월 02일 AI 일간보고서

## 오늘의 핵심 요약

주말 사이 나온 소식들은 하나의 축으로 읽힌다. **공급 쪽 단가는 계속 내려가고, 수요 쪽 신뢰 비용은 올라간다.** AMD는 엔비디아 GPU 없이 학습한 완전 개방형 MoE 모델을 학습 단계 체크포인트까지 통째로 풀었고, MiniMax는 2K 영상 생성에 초당 0.13달러라는 명시적 가격표를 붙였다. 반대편에서는 미네소타의 누디파이 앱 금지법이 법원의 집행정지 기각으로 그대로 발효됐고, 구독자 320만 명의 크리에이터가 자신의 AI 사용을 공개 반성했다. 만드는 비용은 싸지는데, 쓰는 비용은 법적·평판적으로 비싸지는 국면이다.

## 주요 이슈 1: 오픈 모델의 경쟁축이 '가중치'에서 '학습 인프라 증명'으로

AMD가 8월 1일 공개한 Instella-MoE-16B-A3B는 성능 순위표만 보면 그리 극적이지 않다. 베이스 평균 76.7로 Moonlight-16B-A3B(76.2)를 근소하게 앞서지만 Qwen3.5-4B-Base(79.5)에는 뒤진다. 진짜 메시지는 다른 데 있다. 이 모델은 인스팅트 MI300X·MI325X만으로 공개 코퍼스 7.1조 토큰을 처음부터 학습했고, Gated MLA와 FarSkip-Collective로 사전학습 12.7% 가속과 TTFT 최대 39.2% 단축을 확보했다.

즉 AMD가 파는 건 모델이 아니라 "우리 GPU로 프런티어급 학습 파이프라인이 끝까지 돈다"는 증거다. 사전학습부터 RL까지 전 단계 체크포인트와 데이터 믹스, 학습 설정을 함께 공개한 것도 같은 맥락이다. 다만 가중치는 학술·연구용 ResearchRAIL 라이선스로 묶여 상업 배포는 막혀 있고, 실제로 재사용 가치가 큰 건 MIT로 풀린 학습 코드베이스다. 개방의 무게중심이 결과물에서 재현 가능한 공정으로 옮겨가고 있다. [MarkTechPost](https://www.marktechpost.com/2026/08/01/amd-instella-moe-16b-a3b-fully-open-mixture-of-experts-llm/)

## 주요 이슈 2: 영상 생성에 붙은 초당 단가, 15초에 2달러

MiniMax H3는 텍스트·이미지·비디오·오디오를 하나의 생성 프레임워크로 묶은 옴니모달 모델로, 2K 해상도 4~15초 클립을 네이티브 스테레오 사운드와 함께 출력한다. H3-VAE 토크나이저가 유효 시퀀스 길이에서 4배 이득을 만들었고, 이해용·생성용 트랜스포머 분리로 학습 처리량을 약 30% 올렸다는 설명이다.

주목할 숫자는 벤치마크가 아니라 가격이다. **초당 약 0.13달러, 15초 클립 한 편에 약 1.95달러.** 2K 스테레오 영상 한 편이 커피 한 잔 값 아래로 내려왔다는 뜻이다. 다만 현재는 API 전용이고 오픈 가중치는 예고 상태이며, Artificial Analysis 집계상 영상 편집은 선두지만 텍스트→비디오·이미지→비디오는 구글 Gemini Omni Flash에 밀린다. 품질 1위가 아니어도 단가표를 먼저 확정해 시장을 가져가려는 전형적인 중국 모델사 전략이다. [MarkTechPost](https://www.marktechpost.com/2026/08/01/minimax-releases-minimax-h3-an-omni-modal-video-model-that-generates-15-second-2k-clips-with-native-stereo-audio/)

## 주요 이슈 3: 에이전트 평가 기준이 '정확도'에서 '얼마나 헤매는가'로

Supabase가 8월 1일 Apache-2.0으로 공개한 Evals는 실제 컨테이너 환경에 코딩 에이전트를 붙여 제품·주제·단계 세 축으로 채점한다. 결정론적 검증과 LLM-as-a-judge를 결합하고 재시도는 1회만 허용한다.

결과에서 눈에 띈 건 만점자가 여럿이라는 사실이 아니라 **만점에 도달하는 경로가 완전히 달랐다**는 점이다. Claude Code는 빌드 단계에서 지원 없이 100%를 냈고 시나리오당 문서 참조가 약 2페이지였던 반면, Codex는 약 8페이지를 읽었고 스킬을 로드해주자 89%에서 100%로 올라갔다. Sonnet 5도 78%에서 100%로 뛰었다. Opus 5와 Kimi K3는 지원 없이 100%였다.

같은 100%라도 문서 참조가 4배 차이 나면 토큰 비용과 지연시간도 그만큼 벌어진다. 정확도 단일 지표로 에이전트를 고르던 관행이 실무에서 왜 자주 깨지는지를 설명하는 데이터이자, 플랫폼 사업자가 자기 환경의 채점표를 직접 쥐기 시작했다는 신호이기도 하다. [MarkTechPost](https://www.marktechpost.com/2026/08/01/supabase-releases-evals-an-open-source-benchmark-that-scores-claude-code-codex-and-opencode-on-real-supabase-tasks/)

## 주요 이슈 4: 규제는 발효되고, 사용자는 스스로 멈췄다

미네소타 연방법원 도노반 프랭크 판사는 xAI의 임시제한명령 신청을 기각했다. 법이 서명된 지 3개월이 지나 시행 사흘 전인 7월 29일에야 신청이 들어왔다는 점을 들어 "피해가 임박하지 않았다"고 판단했다. 결과적으로 비동의 성적 이미지 생성 서비스를 겨냥한 미국 첫 주 단위 금지법이 8월 1일 그대로 발효됐다. 운영자에게 생성 **건당 최대 50만 달러**를 물릴 수 있는 구조이고, 본안 성격 심리는 8월 19일이다.

같은 날 다른 종류의 브레이크도 걸렸다. 구독자 320만 명의 유튜버 행크 그린이 영상에 챗봇 응답으로 보이는 문구가 섞여 들어간 일을 계기로 "LLM과 상호작용하며 얻는 도파민이 건강하지 않다"며 제작 일시 중단을 선언했다. 한편 샘 올트먼이 제안한 ChatGPT Work 기반 육아 팟캐스트 활용법은 반박 게시물이 좋아요 12만 2,000개로 원글(9,600개)의 12배 이상 확산되며 역풍을 맞았다. [TechCrunch](https://techcrunch.com/2026/08/01/judge-denies-xais-request-to-block-minnesota-ban-on-nudify-apps/) / [TechCrunch](https://techcrunch.com/2026/08/01/youtuber-hank-green-says-his-ai-usage-is-not-healthy/)

## 오늘의 시사점

네 가지 소식은 서로 다른 층위에서 같은 이야기를 한다. **기술 공급은 계속 상품화되고, 채택의 병목은 신뢰로 이동한다.**

AMD와 MiniMax가 보여준 건 학습 인프라와 생성 단가의 상품화다. 엔비디아 밖에서도 7.1조 토큰 학습이 완주되고, 2K 영상 15초가 2달러 아래로 내려온다. 여기까지는 예측 가능한 하강 곡선이다.

문제는 그다음이다. Supabase Evals가 드러낸 문서 참조량 4배 격차는, 모델을 고를 때 정확도만 보면 실제 운영비를 못 잡는다는 뜻이다. 미네소타 판결은 생성 기능 하나에 건당 50만 달러의 잠재 부채가 붙을 수 있음을 확인했다. 행크 그린 사례와 올트먼의 역풍은 소비자와 창작자 쪽에서 AI 사용 자체가 평판 비용을 발생시키기 시작했음을 보여준다.

결국 2026년 하반기 AI 도입의 실질 비용은 API 단가표가 아니라 **운영 토큰 + 법적 노출 + 평판 리스크**의 합으로 계산해야 한다. 오늘 가장 싸 보이는 선택지가 반드시 가장 저렴한 선택지는 아니다.

---

## 📎 참고 자료

1. [AMD Releases Instella-MoE-16B-A3B — MarkTechPost](https://www.marktechpost.com/2026/08/01/amd-instella-moe-16b-a3b-fully-open-mixture-of-experts-llm/)
2. [Introducing Instella-MoE — ROCm Blogs](https://rocm.blogs.amd.com/artificial-intelligence/instella-moe/README.html)
3. [MiniMax Releases MiniMax H3 — MarkTechPost](https://www.marktechpost.com/2026/08/01/minimax-releases-minimax-h3-an-omni-modal-video-model-that-generates-15-second-2k-clips-with-native-stereo-audio/)
4. [Supabase Releases Evals — MarkTechPost](https://www.marktechpost.com/2026/08/01/supabase-releases-evals-an-open-source-benchmark-that-scores-claude-code-codex-and-opencode-on-real-supabase-tasks/)
5. [Judge denies xAI's request to block Minnesota ban on 'nudify' apps — TechCrunch](https://techcrunch.com/2026/08/01/judge-denies-xais-request-to-block-minnesota-ban-on-nudify-apps/)
6. [Judge denies request by Elon Musk's xAI to pause Minnesota nudification ban — NBC News](https://www.nbcnews.com/tech/elon-musk/judge-denies-request-elon-musks-xai-block-mn-nudification-ban-rcna589993)
7. [YouTuber Hank Green says his AI usage is 'not healthy' — TechCrunch](https://techcrunch.com/2026/08/01/youtuber-hank-green-says-his-ai-usage-is-not-healthy/)
8. [Sam Altman is still making the case for parenting via ChatGPT — TechCrunch](https://techcrunch.com/2026/08/01/sam-altman-is-still-making-the-case-for-parenting-via-chatgpt/)
