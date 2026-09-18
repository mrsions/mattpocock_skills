# Skills Guide

이 폴더에는 개발, 생산성, 문서 작성, 실험적 작업을 돕는 스킬이 모여 있습니다.  
아래 스킬명을 클릭하면 각 스킬의 자세한 사용법이 담긴 `SKILL.md`로 이동하며, 총 35개를 카테고리별로 정리했습니다.

## Engineering

코드 설계, 구현, 테스트, 디버깅, 리뷰와 프로젝트 운영을 위한 스킬입니다.

### [ask-matt](./skills/engineering/ask-matt/SKILL.md)

현재 상황에 맞는 스킬이나 작업 흐름을 찾아주는 라우터입니다.  
아이디어부터 구현과 리뷰까지 필요한 경로를 빠르게 선택하도록 안내합니다.

### [code-review](./skills/engineering/code-review/SKILL.md)

지정한 커밋, 브랜치, 태그 등 기준점 이후의 변경사항을 두 축으로 검토합니다.  
코딩 표준 준수 여부와 원래 사양을 충실히 구현했는지를 병렬로 점검합니다.

### [codebase-design](./skills/engineering/codebase-design/SKILL.md)

작은 인터페이스 뒤에 많은 동작을 숨기는 깊은 모듈 설계를 위한 공통 언어를 제공합니다.  
모듈, 인터페이스, 깊이, seam, adapter, locality 같은 개념으로 테스트 가능성과 변경 용이성을 높입니다.

### [diagnosing-bugs](./skills/engineering/diagnosing-bugs/SKILL.md)

어려운 버그와 성능 회귀를 단계적으로 진단하는 루프입니다.  
재현 가능한 피드백 루프를 만들고 최소화, 가설, 계측, 수정, 회귀 테스트까지 진행합니다.

### [domain-modeling](./skills/engineering/domain-modeling/SKILL.md)

프로젝트의 용어와 개념을 다듬고 공유된 도메인 모델로 정리합니다.  
`CONTEXT.md`와 ADR을 함께 갱신해 설계 과정에서 결정된 언어와 경계를 기록합니다.

### [grill-with-docs](./skills/engineering/grill-with-docs/SKILL.md)

계획이나 설계를 집요하게 인터뷰하면서 프로젝트 문서도 함께 만드는 흐름입니다.  
질문을 통해 용어를 선명하게 하고 글로서리와 ADR을 작업 중에 남깁니다.

### [implement](./skills/engineering/implement/SKILL.md)

사양서나 티켓을 바탕으로 실제 구현을 진행하는 실행 스킬입니다.  
가능하면 TDD를 적용하고 타입 검사, 테스트, 코드 리뷰까지 마친 뒤 커밋합니다.

### [improve-codebase-architecture](./skills/engineering/improve-codebase-architecture/SKILL.md)

코드베이스의 얕은 모듈과 구조적 마찰을 찾아 개선 후보를 제시합니다.  
시각적 HTML 보고서로 선택지를 보여준 뒤 선택한 개선안을 인터뷰로 구체화합니다.

### [prototype](./skills/engineering/prototype/SKILL.md)

상태 모델, 비즈니스 로직, UI 설계 질문에 답하기 위한 버리는 프로토타입을 만듭니다.  
실행 가능한 작은 결과물로 여러 경우를 직접 확인하고 검증된 결정을 본 코드에 반영하도록 돕습니다.

### [research](./skills/engineering/research/SKILL.md)

공식 문서, 소스 코드, 사양서 같은 신뢰도 높은 1차 자료로 질문을 조사합니다.  
근거와 함께 결과를 하나의 Markdown 문서로 남기고 필요하면 백그라운드 에이전트가 조사합니다.

### [resolving-merge-conflicts](./skills/engineering/resolving-merge-conflicts/SKILL.md)

진행 중인 merge 또는 rebase 충돌을 각 변경의 원래 의도를 추적하며 해결합니다.  
충돌 덩어리마다 양쪽 의도를 검토하고 작업을 완료한 뒤 자동 검사를 실행합니다.

### [setup-matt-pocock-skills](./skills/engineering/setup-matt-pocock-skills/SKILL.md)

현재 저장소의 이슈 트래커, triage 라벨, 도메인 문서 구조를 설정합니다.  
다른 Engineering 스킬을 사용하기 전에 한 번 실행해 프로젝트별 기반을 맞춥니다.

### [tdd](./skills/engineering/tdd/SKILL.md)

실패하는 테스트부터 시작하는 red-green-refactor 방식으로 기능과 버그 수정을 진행합니다.  
한 번에 작은 수직 슬라이스를 완성하며 빠른 피드백으로 설계와 구현을 함께 검증합니다.

### [to-spec](./skills/engineering/to-spec/SKILL.md)

현재 대화를 별도 인터뷰 없이 사양서로 정리하고 프로젝트 이슈 트래커에 게시합니다.  
이미 논의된 요구사항과 결정을 빠짐없이 합성해 구현에 사용할 기준을 만듭니다.

### [to-tickets](./skills/engineering/to-tickets/SKILL.md)

계획, 사양서, 대화를 tracer-bullet 티켓 묶음으로 나누고 티켓 간 blocking edge를 기록합니다.  
로컬 파일이나 실제 이슈 트래커에 구현 가능한 단위로 게시해 작업 순서를 분명히 합니다.

### [triage](./skills/engineering/triage/SKILL.md)

이슈와 외부 PR을 triage 역할의 상태 머신에 따라 분류하고 검증합니다.  
필요하면 grilling을 거친 뒤 다른 에이전트가 바로 작업할 수 있는 brief로 정리합니다.

### [wayfinder](./skills/engineering/wayfinder/SKILL.md)

한 번의 에이전트 세션으로 끝나지 않는 큰 작업을 결정 티켓의 지도처럼 계획합니다.  
결정이 필요한 항목을 하나씩 해결해 목적지까지의 실행 경로를 선명하게 만듭니다.

### [wizard](./skills/engineering/wizard/SKILL.md)

사람만 수행할 수 있는 인프라 설정, 자격 증명, CI 비밀값, 외부 대시보드 작업을 위한 대화형 bash wizard를 생성합니다.  
사용자가 직접 해야 하는 단계를 안전하고 따라 하기 쉬운 흐름으로 안내합니다.

## Productivity

계획 정리, 협업 인계, 학습, 질문 설계와 대화 개선을 위한 일반 workflow 스킬입니다.

### [grill-me](./skills/productivity/grill-me/SKILL.md)

계획이나 설계를 집요하게 인터뷰해 생각을 구체화하는 사용자 호출형 스킬입니다.  
결정 트리의 모든 가지를 확인해 구현 가능한 방향과 공유된 이해에 도달하도록 돕습니다.

### [grilling](./skills/productivity/grilling/SKILL.md)

계획, 결정, 아이디어를 설계 트리로 나누고 질문을 통해 끝까지 검증합니다.  
각 라운드에서 지금 답할 수 있는 질문을 모아 제시하고 모든 분기가 정리될 때까지 반복합니다.

### [handoff](./skills/productivity/handoff/SKILL.md)

현재 대화를 다른 에이전트가 이어갈 수 있도록 짧고 구조화된 인계 문서로 압축합니다.  
이미 만들어진 사양서, 계획, ADR, 이슈, diff는 중복하지 않고 경로로 참조하며 민감한 정보는 가립니다.

### [teach](./skills/productivity/teach/SKILL.md)

현재 작업 폴더를 상태가 유지되는 학습 공간으로 삼아 새로운 기술이나 개념을 여러 세션에 걸쳐 가르칩니다.  
미션, 참고 자료, 학습 기록, 대화형 수업을 연결해 지식과 실습을 함께 쌓습니다.

### [to-questionnaire](./skills/productivity/to-questionnaire/SKILL.md)

혼자 결정하기 어려운 문제를 다른 사람이 작성할 수 있는 Markdown questionnaire로 바꿉니다.  
주제 자체보다 수신자와 필요한 답을 먼저 정리한 뒤 정보의 빈틈을 채우는 질문을 설계합니다.

### [wait-what](./skills/productivity/wait-what/SKILL.md)

앞선 설명이 제대로 전달되지 않았을 때 핵심 맥락을 쉬운 말로 다시 설명합니다.  
`CONTEXT.md`의 프로젝트 용어를 사용해 혼란을 줄이고 다음 대화를 이어갈 수 있게 합니다.

### [writing-for-agents](./skills/productivity/writing-for-agents/SKILL.md)

스킬, `AGENTS.md`, `CLAUDE.md`처럼 에이전트가 읽는 문서를 예측 가능하게 작성하는 원칙을 제공합니다.  
context pointer, 정보 계층, context load와 cognitive load를 활용해 필요한 지침이 적절한 때 도달하도록 설계합니다.

## In Progress

아직 실험 중인 공개 스킬입니다. 동작과 구조가 바뀔 수 있으므로 사용 전 원문을 확인하는 것이 좋습니다.

### [claude-handoff](./skills/in-progress/claude-handoff/SKILL.md)

현재 대화를 새 백그라운드 에이전트에게 넘겨 작업을 즉시 이어가게 합니다.  
인계 요약을 함께 전달해 새 세션이 기존 맥락과 목표를 잃지 않도록 합니다.

### [loop-me](./skills/in-progress/loop-me/SKILL.md)

여러 세션에 걸쳐 만들 workflow의 사양을 집요한 질문으로 구체화합니다.  
현재 작업 폴더를 상태 저장 공간으로 사용해 다음 세션에서도 설계와 결정을 이어갑니다.

### [setup-ts-deep-modules](./skills/in-progress/setup-ts-deep-modules/SKILL.md)

TypeScript 저장소에 dependency-cruiser를 연결해 각 패키지를 깊은 모듈로 구성합니다.  
구현은 하위 폴더에 숨기고 entry point로만 접근하게 하며 테스트도 같은 경로를 사용하게 합니다.

### [writing-beats](./skills/in-progress/writing-beats/SKILL.md)

글을 독자가 따라가는 beat의 여정으로 구성하는 탐색형 글쓰기 스킬입니다.  
시작할 beat를 고르고 그 부분만 쓴 뒤 다음 beat로 이동해 글이 자연스럽게 끝날 때까지 발전시킵니다.

### [writing-fragments](./skills/in-progress/writing-fragments/SKILL.md)

아직 구조를 정하지 않은 원재료에서 문장, 주장, 장면 같은 다양한 writing fragment를 채집합니다.  
대화의 처음부터 쓸 만한 조각을 모아 하나의 문서에 축적하고 나중에 글의 재료로 활용합니다.

### [writing-shape](./skills/in-progress/writing-shape/SKILL.md)

정리되지 않은 Markdown 원재료를 읽고 글의 구조와 문단을 하나씩 확정합니다.  
각 단계에서 독자가 알아야 할 개념을 먼저 grounding하고 형식 선택의 이유를 검토하며 완성된 글로 다듬습니다.

## Misc

자주 쓰지는 않지만 특정 개발 환경이나 작업에서 유용한 보조 스킬입니다.

### [git-guardrails-claude-code](./skills/misc/git-guardrails-claude-code/SKILL.md)

위험한 Git 명령을 실행하기 전에 차단하는 Claude Code hook을 설정합니다.  
push, 강제 reset, clean, 브랜치 삭제, 전체 checkout과 restore 같은 실수하기 쉬운 작업을 보호합니다.

### [migrate-to-shoehorn](./skills/misc/migrate-to-shoehorn/SKILL.md)

테스트 코드의 `as` 타입 단언을 `@total-typescript/shoehorn` 방식으로 옮깁니다.  
부분적인 테스트 데이터를 타입 안전하게 만들면서 production code에는 shoehorn을 사용하지 않도록 안내합니다.

### [scaffold-exercises](./skills/misc/scaffold-exercises/SKILL.md)

섹션, 문제, 해답, 설명 자료로 구성된 exercise 디렉터리 구조를 생성합니다.  
이름 규칙과 필수 README를 지키고 저장소의 lint를 통과할 수 있는 학습 자료 뼈대를 만듭니다.

### [setup-pre-commit](./skills/misc/setup-pre-commit/SKILL.md)

Husky와 lint-staged를 설정해 커밋 시 Prettier, 타입 검사, 테스트를 실행하게 합니다.  
저장소의 패키지 매니저를 감지하고 필요한 설정과 검사 명령을 현재 프로젝트에 맞춰 연결합니다.
