<p align="center">
  <img src="./assets/profile-banner.svg" alt="asbazq — Build. Observe. Improve." width="100%" />
</p>

<p align="center">
  <strong>만들고, 관찰하고, 더 나은 구조로 개선합니다.</strong><br />
  Java · Spring 기반의 백엔드와 Python 기반의 AI를 다루며, 서비스 구현부터 검색·예측까지 연결합니다.
</p>

<p align="center">
  <a href="https://velog.io/@asbazq"><img src="https://img.shields.io/badge/ENGINEERING_LOG-20C997?style=flat-square&amp;logo=velog&amp;logoColor=white" alt="Velog 기술 블로그" /></a>
  <a href="https://www.notion.so/206f4991cf2380d1aed4e7fae12cd031"><img src="https://img.shields.io/badge/NOTES-172B3A?style=flat-square&amp;logo=notion&amp;logoColor=white" alt="Notion 노트" /></a>
  <a href="https://github.com/asbazq?tab=repositories"><img src="https://img.shields.io/badge/EXPLORE_REPOS-172B3A?style=flat-square&amp;logo=github&amp;logoColor=white" alt="전체 저장소" /></a>
</p>

<br />

## 01 / Backend

### [YuGiOhDeck ↗](https://github.com/asbazq/YuGiOhDeck)
**카드 검색부터 덱 구성·공유, AI 카드 판별까지.**

유희왕 덱 구성 및 공유 플랫폼입니다. MySQL Full-Text 검색, URL 기반 덱 공유, Redis 대기열을 적용하고 API와 크롤러의 실행 역할을 분리했습니다.

`Spring Boot` `React` `MySQL` `Redis` `FastAPI`

---

### [QueueSystem ↗](https://github.com/asbazq/queueSystem)
**몰리는 요청은 순서 있게, 입장은 안전하게.**

Redis Sorted Set과 Lua Script로 입장·승급을 원자적으로 처리합니다. WebSocket으로 대기 상태를 전달하고, Heartbeat와 TTL로 이용 상태를 관리합니다.

`Java` `Spring Boot` `Redis` `Lua` `WebSocket`

---

<br />

## 02 / AI

### [youtube-semantic-search ↗](https://github.com/asbazq/youtube-semantic-search)
**질문에서 관련 자막으로, 자막에서 정확한 영상 시점으로.**

YouTube 자막을 의미 단위로 나누고 다국어 임베딩과 ChromaDB로 검색합니다. 로컬 Ollama 기반 RAG 챗봇은 검색된 자막 원문과 영상 시점 링크를 제공하며, 인용 구절을 서버에서 검증합니다.

`Python` `SentenceTransformers` `ChromaDB` `Ollama` `FastAPI` `Vue`

---

### [skala-min_project ↗](https://github.com/asbazq/skala-min_project)
**배터리 초기 데이터에서 수명 예측까지, 선택의 근거와 한계를 함께.**

초기 100사이클 데이터로 ESS 배터리의 전체 사이클 수명을 예측합니다. EDA와 특징 비교를 거쳐 RBF SVR을 선택하고, 프로토콜 그룹 기반 검증과 배치 간 평가로 일반화 성능을 분석했습니다.

`Python` `pandas` `NumPy` `scikit-learn` `SVR`

<br />

## 03 / Engineering focus

| 관심사 | 프로젝트에서 다룬 내용 |
| :--- | :--- |
| **트래픽과 동시성** | Redis 대기열 · Lua 원자 연산 · 입장 인원 제어 |
| **서비스와 데이터** | Spring API · MySQL 검색 · 수집 프로세스 분리 |
| **실시간 사용자 경험** | WebSocket 상태 전달 · 재연결과 세션 수명 관리 |
| **AI 검색과 근거 검증** | 자막 청킹 · 다국어 임베딩 · 벡터 검색 · RAG 인용 검증 |
| **ML 실험과 평가** | EDA · 특징 비교 · 그룹 기반 검증 · 배치 간 오류 분석 |
| **관찰과 개선** | 부하 테스트 · 응답 흐름 분석 · 기술 선택과 트러블슈팅 기록 |

<br />

## 04 / Toolbox

**Backend** &nbsp; Java · Spring Boot · Spring Data JPA  
**Data & Messaging** &nbsp; MySQL · Redis · WebSocket  
**AI & ML** &nbsp; Python · SentenceTransformers · ChromaDB · Ollama · scikit-learn · pandas · NumPy  
**Frontend** &nbsp; React · Vue · JavaScript  
**Infra & Collection** &nbsp; Docker Compose · AWS EC2 / RDS · Selenium · Jsoup

<br />

---

<p align="center">
  <sub>작동하는 기능에서, 설명할 수 있는 설계로.</sub>
</p>
