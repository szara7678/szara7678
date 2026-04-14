<h1 align="center">김인수 | Insu Kim</h1>
<p align="center">로봇 운영 시스템을 제품 관점으로 설계·구현하는 풀스택 개발자</p>
<p align="center">React · Next.js · TypeScript · NestJS · Express · FastAPI · ROS2 · Nav2 · Kafka · WebSocket · MongoDB · PostgreSQL</p>

<p align="center">
  <a href="https://knowledge.openakashic.com/notes/김인수-insu-kim-포트폴리오-허브">
    <img src="https://img.shields.io/badge/📘_Portfolio_Hub-knowledge.openakashic.com-1f6feb?style=for-the-badge" alt="Portfolio Hub" />
  </a>
  <a href="mailto:gci.insu@gmail.com">
    <img src="https://img.shields.io/badge/Email-gci.insu%40gmail.com-24292e?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

## 🧭 채용 담당자를 위한 빠른 경로

저는 **자체 운영 중인 지식 네트워크(OpenAkashic)** 위에 포지션별로 정리된 이력서와 프로젝트 상세 문서를 공개해 두었습니다. 지원 포지션에 가장 가까운 이력서부터 확인해 주세요.

| 포지션 | 이력서 | 요약 |
| --- | --- | --- |
| 🤖 로봇 / ROS2 엔지니어 | [로봇 엔지니어 이력서](https://knowledge.openakashic.com/notes/이력서-로봇-ros2-엔지니어-포지션) | Nav2·도킹·엘리베이터 액션·LiDAR 파이프라인 실증 경험 |
| 🧩 풀스택 / 프로덕트 엔지니어 | [풀스택 이력서](https://knowledge.openakashic.com/notes/이력서-풀스택-프로덕트-엔지니어-포지션) | React+NestJS로 운영 콘솔 초기 구조 설계·구현 |
| ⚙️ 백엔드 / 인프라 엔지니어 | [백엔드·인프라 이력서](https://knowledge.openakashic.com/notes/이력서-백엔드-인프라-엔지니어-포지션) | 실시간 메시징 + AWS→자체서버 마이그레이션 운영 |
| 🌏 Global / English role | [Resume (English)](https://knowledge.openakashic.com/notes/resume-english-insu-kim) | Full-stack / robotics product engineer |

👉 **[📘 포트폴리오 허브 전체 보기](https://knowledge.openakashic.com/notes/김인수-insu-kim-포트폴리오-허브)** — 프로젝트 상세, 기술 스택, 작업 방식까지 한눈에

---

## About

아리카(ARICA)에서 다중 로봇 관제, 맵 편집, 운영형 웹 서비스를 개발하고 있습니다.
복잡한 현장 요구사항을 **화면 UX · API · 데이터 흐름 · 로봇 인터페이스 · 배포 · 운영 문서**까지 하나의 제품 흐름으로 엮어, 실제 운영자가 바로 사용할 수 있는 수준까지 완성도를 끌어올리는 역할을 맡고 있습니다.

## Current Work · ARICA

- **[ARC Fleet — 다중 로봇 통합 관제 플랫폼](https://knowledge.openakashic.com/notes/arc-fleet-다중-로봇-통합-관제-플랫폼)**
  운영 콘솔의 초기 구조와 핵심 기능 설계를 맡고, 프론트엔드와 백엔드를 직접 구현.
  프로젝트/로봇/그룹/모델 관리, 실시간 관제, 맵 편집·보정, 명령 이력, 배포 상태 확인 기능과 운영 가드레일(삭제 확인, 미저장 이탈 방지, 대표 지도 변경 경고)을 화면·서버 양쪽에 녹여 설계.
  `React` · `TypeScript` · `NestJS` · `MongoDB` · `Socket.IO` · `MQTT`

- **[국립평창청소년수련원 로봇 운영·콘텐츠 통합 시스템](https://knowledge.openakashic.com/notes/국립평창청소년수련원-로봇-운영-콘텐츠-통합-시스템)**
  안내·이송·순찰 로봇 실증 현장에서 관리자 웹 · 콘텐츠 관리 웹 · 운영 서버 · 배포 구조를 한 흐름으로 개발.
  프로젝트에 포함된 이송 로봇 **뉴비(Neubie)** 의 Nav2 bringup, keepout/narrow mode, docking/undock, elevator action 운용과 3D LiDAR→2D scan 파이프라인 안정화를 담당.
  이중화 서버 이슈와 운영 장애 대응 절차를 문서화해 팀 재현 가능한 형태로 정리.

- **[RobotApp Web — 브라우저 기반 ROS2 운영 도구](https://knowledge.openakashic.com/notes/robotapp-web-브라우저-기반-ros2-운영-도구)**
  FastAPI + WebSocket + rclpy 기반 ROS2 게이트웨이로 rosbridge 없이 3D 뷰어, 2D 맵 편집기, 원격 제어, 파라미터 업로드, E-STOP 흐름을 웹에서 처리.

## Selected Projects

- **[OpenAkashic](https://knowledge.openakashic.com/notes/openakashic-가시성-제어-지식-네트워크-이-사이트)** — 가시성 제어 지식 네트워크 (이 README가 가리키는 사이트). FastAPI + PostgreSQL FTS + FastMCP + Caddy + Cloudflare Tunnel로 자체 서버에서 운영 중. AWS→자체 서버 마이그레이션 완료.
- **RoboDine** — ROS2 + AI 식당 자동화 시스템. 부트캠프 **최우수상** 수상. [repo](https://github.com/addinedu-roscamp-4th/roscamp-repo-2) · [slides](https://drive.google.com/drive/folders/1NJt7mWoMAfzyQoPRiEO4BvGzIQ_Fv9lZ?usp=sharing)
- **IchiMozzi** — JLPT 준비 AI 학습 앱. 기획·모바일 UX·백엔드·학습 로그 구조 설계, Google Play 출시. [Play Store](https://play.google.com/store/apps/details?id=com.szara7678.ichimozzi)
- **RODI** — 다중 쇼핑몰 상품 관리 백엔드. 쿠팡·스마트스토어·11번가 API를 어댑터 패턴으로 통합. [소개 PDF](https://drive.google.com/file/d/14ClwDBwc5qhItAi6JC9amdoCuxbUaJP2/view?usp=sharing)
- **시니어마을** — 시니어 커뮤니티 플랫폼 기획 · Python+Selenium+Gemini 콘텐츠 자동화. [seniorvillage.co.kr](https://www.seniorvillage.co.kr)

→ 각 프로젝트의 책임 범위·의사결정 상세는 [포트폴리오 허브](https://knowledge.openakashic.com/notes/김인수-insu-kim-포트폴리오-허브)에서 확인하실 수 있습니다.

## Strengths

- **제품 흐름 전체를 한 책임자로** — 화면 요구사항이 서버 데이터 모델, 실시간 이벤트, 로봇 인터페이스, 배포·운영 문서로 일관되게 이어지도록 설계합니다.
- **운영 감각** — 운영자가 실수하기 쉬운 지점을 가드레일(삭제 확인·미저장 이탈 방지·배포 상태 표시)로 바꾸는 것을 기본 설계에 포함합니다.
- **현장 대응** — 네트워크 이중화·외부 장비·로봇 주행 이슈가 동시에 터지는 현장에서 기능 수정과 인수인계 문서를 함께 남깁니다.
- **자가 운영 인프라 경험** — AWS에서 자체 서버로 마이그레이션해 Docker Compose + Caddy + Cloudflare Tunnel 스택을 직접 운영 중입니다.

## Tech Stack

**Frontend** React · Next.js · TypeScript · Tailwind · Zustand · TanStack Query · Three.js · Konva
**Backend** NestJS · Express · FastAPI · Python · Node.js
**Datastore** MongoDB · PostgreSQL (FTS + trigram)
**Realtime / Messaging** WebSocket · Socket.IO · Kafka · MQTT · rclpy (ROS2 DDS)
**Robotics** ROS2 · Navigation2 · costmap/keepout tuning · docking & elevator actions
**Infra** Docker Compose · Caddy · Cloudflare Tunnel · AWS (S3/EC2/RDS) · nginx · GitHub Actions

## Links

- 📘 **Portfolio Hub** — <https://knowledge.openakashic.com/notes/김인수-insu-kim-포트폴리오-허브>
- 🌐 Personal Portfolio Site — <https://szara7678.github.io/portfolio_page/>
- 🐙 GitHub — [@szara7678](https://github.com/szara7678)
- ✉️ Email — <gci.insu@gmail.com>

---

## GitHub Snapshot

![Public Repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fszara7678&query=%24.public_repos&label=public%20repos&style=for-the-badge&logo=github)
![Followers](https://img.shields.io/github/followers/szara7678?style=for-the-badge)
![Following](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2Fszara7678&query=%24.following&label=following&style=for-the-badge&logo=github)
![Profile Views](https://komarev.com/ghpvc/?username=szara7678&style=for-the-badge)
