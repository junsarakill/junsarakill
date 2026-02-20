# 🛠️ 불편거리 해소장

> "일상의 반복적인 불편함을 발견하고, 이를 해결하기 위해 직접 만든 도구들을 기록하는 공간입니다."
> — _AI Gemini_

### 📦 해결 도구 목록
* **[JKGameHotKey](https://github.com/junsarakill/JKGameHotKey)** : 가상 단축키 미지원 게임을 위한 구조적 동적 매핑 유틸리티
  <details>
  <summary>주요 기능 및 특징</summary>

  - **Relational Data Structure**: 마스터 인덱스와 개별 시트를 분리하여 수많은 설정을 체계적으로 관리하는 계층적 구조
  - **Event-Driven Optimization**: 타이머 반복문 대신 '창 활성화 이벤트'에 반응하는 트리거 설계로 불필요한 CPU 자원 소모 최소화
  - **Context-Aware Lifecycle**: 게임 활성 시 설정을 로드하고, 대응 게임이 없을 시 프로세스를 자가 종료(Self-Terminate)하여 시스템 청결 유지
  - **Single Process Efficiency**: 단일 상주 스크립트로 무한한 확장성을 제공하는 자원 최적화 설계
  - **Window Layout & Visuals**: 전역 핫키 기반 창 위치 관리 및 가상키 시각화 오버레이 지원
  </details>

* **[JKMediaHotKey](https://github.com/junsarakill/JKMediaHotKey)** : 게임 환경에서의 입력 차단을 우회하는 시스템 레벨 미디어 제어 유틸리티
  <details>
  <summary>주요 기능 및 특징</summary>
  
  - **Input Hook Bypass**: 특정 게임이 마우스/키보드 입력을 독점(Exclusive Mode)하여 미디어 키가 작동하지 않는 현상을 가상 키(`F13`) 매핑을 통해 해결
  - **Low-Level Message Transmission**: 단순 키 에뮬레이션이 아닌 `WM_APPCOMMAND`(0x319) 메시지를 시스템(Program Manager)에 직접 포스팅하여 가장 확실한 실행 보장
  - **Hardware-Software Bridge**: 로지텍 G-Hub 등 하드웨어 매크로와 소프트웨어 스크립트를 결합하여 물리 버튼의 한계를 극복한 사용자 정의 워크플로우 구현
  - **Zero-UI Background Operation**: 윈도우 시작 시 자동 실행되어 백그라운드에서 상주하며, 최소한의 리소스로 하드웨어 버튼의 활용도를 극대화
  - **Conflict-Free Mapping**: 일반 키보드에 존재하지 않는  키를 활용함으로써 기존 애플리케이션과의 단축키 충돌 가능성을 원천 차단


























참여 프로젝트 정리
- 콜옵 블옵2 모작 | 아군 AI 및 미션 진행 파트 | 언리얼 | [https://github.com/junsarakill/CODBO](url) | 2024 8월
- 비행 훈련 시뮬레이션 | 대항군 및 미션 진행 | 언리얼 | [https://github.com/MTVS-AirJet/MTVS_AirJet_Final](url) | 2024 9월~12월(예정)
- 헬다이버즈2 모작 | 플레이어 및 스트라타젬 일부 | 언리얼 | [https://github.com/junsarakill/IntoTheHell](url) | 2024 7월
- 스나이퍼 엘리트 VR 모작 | 저격총 및 미션 징행 | 유니티 | [https://github.com/junsarakill/SES](url) | 2023 9월
- 오버쿡드2 모작 | 재료, 테이블 상호작용 및 멀티플레이 전환 | 유니티 | [https://github.com/jimandy00/Overcooked2](url) | 2023 8월
- 리틀 나이트메어2 모작 | 추적 마네킹 AI 역할 | 유니티 | [https://github.com/junsarakill/LucidDream](url) | 2023 7월
