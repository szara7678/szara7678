<h2 align="center">👋 안녕하세요, 전략적 제품 기획·설계 기반 풀스택 개발자 김인수입니다.</h2>
<p align="center">서비스 기획부터 구현·운영까지, 고객 문제 해결에 집중합니다.</p>

---

## 🚀 주요 활동
- **심화 ROS2와 AI를 활용한 자율주행&로봇팔 개발자 부트캠프 (2025.03 – 06)**  
  ‘핑키’ 모바일 로봇 3대와 6축 로봇팔 'Jetcobot' 2대를 통합 운용해 식당 자동화 서비스를 개발하며 **최우수상** 수상  
  - **Web GUI 개발**: React 기반 대시보드에 실시간 로봇 상태 모니터링·원격 제어 인터페이스 구현 및 손님을 위한 키오스크 인터페이스 구현  
  - **DB 구축·관리**: PostgreSQL에서 주문·재고·로깅 데이터 스키마 설계  
  - **메인 서버 구축**: FastAPI로 인증·인가 포함 RESTful API 설계·구현  
  - **통신체계 관리**: ROS2, UDP, TCP, REST API 등 통신 인터페이스 관리  
  - **실시간 영상 스트리밍**: UDP+WebRTC 조합으로 720p 영상 지연 150ms 이하 달성  
  - **객체 감지**: YOLOv8+OpenCV 연동해 블록 객체의 6DoF 추론 정확도 92% 이상  
  - **아키텍처 설계**: SW Architecture, Data Structure, Sequence Diagram 등 설계 문서화  
  - **협업 도구**: Slack으로 일일 스크럼·알림, Jira로 스프린트·이슈 관리, Confluence에 아키텍처·API 문서 작성  
  - <a href="https://github.com/addinedu-roscamp-4th/roscamp-repo-2" target="_blank">GitHub 리포지토리</a> · <a href="https://drive.google.com/drive/folders/1NJt7mWoMAfzyQoPRiEO4BvGzIQ_Fv9lZ?usp=sharing" target="_blank">발표자료</a> · <a href="https://drive.google.com/file/d/1iCLAiBXBZht4rgVXUg4SX2QK6Bx14ux3/view?usp=sharing" target="_blank">시연 영상</a>

---

## 🧩 주요 프로젝트

<details>
<summary>국립평창청소년수련원 로봇 운영·콘텐츠 통합 시스템 (실무, 프론트엔드·백엔드)</summary>

- **관제 프론트엔드 개발**: Next.js 14 기반 로봇 관리 시스템에서 실시간 알림 카드, 로봇 위치 보간 애니메이션, 순찰 이미지 모달, 지도 편집 UI, 코드 관리 업로드/초기화 기능 구현  
- **콘텐츠 서비스 개발**: 안내로봇용 웹 서비스에서 통계 API, 본관/생활관 이원화 대기화면, 콘텐츠 업로드, TTS·이메일 연동 기능 개발  
- **운영형 백엔드 연동**: Express+TypeScript 웹서버의 ZIP 코드 업로드 API, 버전 관리, S3 저장 구조를 연계해 현장 배포 워크플로우 개선  
- **실시간 운영 구조 이해**: Kafka 기반 작업 상태 수집, WebSocket 모니터링 전송, 로봇·IoT·서버가 혼재한 현장 네트워크 구조를 바탕으로 기능 개선 및 운영 대응  

</details>

<details>
<summary>ARC Fleet 다중 로봇 통합 관제 플랫폼 (실무, 프론트엔드·백엔드·프로토콜)</summary>

- **관제 플랫폼 개발**: React+TypeScript 기반 UI에서 프로젝트/로봇/그룹/모델 관리, 실시간 관제, 수동 제어, 지도 편집 흐름 고도화  
- **백엔드 설계·개선**: NestJS+MongoDB+Socket.IO+MQTT 기반 구조에서 프로젝트·맵·명령·관리 데이터 흐름 정리 및 운영 기능 개선  
- **프로토콜 문서화**: REQUEST / AGREE / INFORM / FAILURE / QUERY / SUBSCRIBE 구조의 에이전트 메시지 명세와 인터페이스 스키마를 정리해 협업 기준 수립  
- **운영 안정화**: 관리 화면 삭제 가드, stale cache 정합성, 목록 재조회, 관리 UI 정책 정리를 통해 실서비스 UX와 유지보수성 개선  

</details>

<details>
<summary>RobotApp Web RViz/SLAM Fleet MVP (실무, 프론트엔드·백엔드)</summary>

- **ROS2 직접 연동 백엔드**: FastAPI+WebSocket+rclpy 기반으로 rosbridge 없이 DDS 토픽을 직접 구독·발행하는 게이트웨이 개발  
- **웹 관제 UI 개발**: React+TypeScript+Three.js+Konva 기반으로 3D 뷰어, 2D 맵 편집기, 조이스틱 원격 제어, 파일 관리 UI 구현  
- **SLAM/Nav2 운영 기능**: tmux 기반 서비스 실행·헬스체크, 파라미터 업로드, 맵 저장/편집, E-STOP 워크플로우 등 운영 도구 개발  
- **데이터 파이프라인 정리**: 맵·코스트맵·배터리·TF 데이터를 WebSocket으로 브로드캐스트하고, 상태 관리와 렌더링 흐름을 문서화  

</details>

<details>
<summary>무한 텍스트 탑 등반 RPG (개인 프로젝트)</summary>

- **텍스트 기반 RPG 게임**: 간단한 텍스트 기반 RPG 게임으로 진입장벽 및 리소스 최소화  
- **끝없는 탑 등반 시스템**: 제한 없는 레벨링으로 끝없는 컨텐츠 설계  
- **현재 층과 몬스터 레벨에 따른 아이템 드랍**: 게임의 컨셉에 맞는 드랍 시스템 구축
- **아이템 레벨에 따른 제작 아이템 레벨 변동**: 게임의 컨셉에 맞게 재료 아이템 레벨에 의한 장비 레벨 변동
- **재료를 얻기 위해 끊임없이 어려워지는 미니게임**: 지뢰찾기, 같은 그림 맞추기, 리듬게임 등의 미니게임 구현 및 스킬 레벨에 따른 높은 아이템 레벨 설계  
- <a href="https://szara7678.github.io/endless_text_rpg/" target="_blank">게임 플레이 (깃허브 페이지)</a>
</details>

<details>
<summary>이치모찌 학습 앱 (개인 프로젝트)</summary>

- **문제 자동 생성**: Gemini API 활용, 유형별 템플릿 설계 및 생성 로직 구현  
- **오답노트·학습 통계**: PostgreSQL에 사용자별 데이터 저장, Chart.js 대시보드로 사용자 정보 시각화  
- **맞춤형 학습 경로**: 난이도 적응형 알고리즘 설계·구현  
- **인프라 설계·운영**:  
  - EC2(t3.medium) 애플리케이션 호스팅  
  - S3에 문제 데이터·로그 보관  
- **CI/CD**: GitHub Actions로 푸시 시 자동 빌드·테스트·배포 파이프라인 구성  
- <a href="https://play.google.com/store/apps/details?id=com.szara7678.ichimozzi" target="_blank">구글 플레이에서 다운로드</a>

</details>

<details>
<summary>시니어마을 플랫폼 (개인 프로젝트, 서비스 기획·자동화 개발)</summary>

- **서비스 기획**: 사용자 플로우·와이어프레임 작성  
- **자동화 워크플로우**: Python+Selenium+Gemini 기반 반복 업무 스크립트 개발  
- <a href="https://www.seniorvillage.co.kr" target="_blank">웹사이트 방문</a>

</details>

<details>
<summary>RODI 주문관리 시스템 (팀 프로젝트, 백엔드 개발)</summary>

- **데이터 ETL 파이프라인**: 해외 쇼핑몰 크롤링(JSON) → Python ETL 모듈로 가공  
- **API 자동 업로드**: Coupang·Gmarket·11st REST API 연동, 각 스토어에 자동 업로드  
- <a href="https://drive.google.com/file/d/14ClwDBwc5qhItAi6JC9amdoCuxbUaJP2/view?usp=sharing" target="_blank">소개 자료 보기</a>

</details>

<details>
<summary>스도쿠 게임 (개인 프로젝트)</summary>

- **백트래킹 솔버 최적화**: ES5로 작성된 고성능 재귀 알고리즘  
- **퍼즐 검증**: 백트래킹+Elimination 혼합 방식으로 입력값 실시간 검증  
- **모드 지원**: 수동 입력 및 자동 풀이 모드 전환 기능  
- **힌트 기능**: 현재 보드 상태 기반 추천 숫자 제공  
- <a href="https://szara7678.github.io/Sudoku-master/" target="_blank">데모 & 코드 보기</a>

</details>

<details>
<summary>덧셈 카드 게임 (개인 프로젝트)</summary>

- **카드 생성·점수 집계**: 무작위 숫자 카드 생성 함수, 레벨별 점수 계산 로직  
- **난이도 조절**: 레벨별 시간 제한·문제 난이도 알고리즘 설계  
- **실시간 점수판**: DOM 업데이트로 즉각적인 점수·타임어택 피드백 제공  
- <a href="https://szara7678.github.io/PlusCardGame/" target="_blank">데모 & 코드 보기</a>

</details>

---

## 💼 경력
- **Arica 로봇 엔지니어 (2025.08 – 재직중)**  
  - 국립평창수련원 PNYC 실증 프로젝트에서 안내·이송·순찰 로봇 운영 시스템의 프론트엔드/백엔드 기능 개발 및 고도화  
  - Arc-Fleet 다중 로봇 통합 관제 플랫폼의 React/NestJS 기반 프론트엔드·백엔드 개발, 지도 편집·프로젝트 관리·운영 UX 개선  
  - 에이전트 메시지 프로토콜, 로봇 상태 인터페이스, 실시간 데이터 흐름(Socket.IO, MQTT, WebSocket) 문서화 및 구조 정리  
  - RobotApp(Web RViz/SLAM Fleet MVP)에서 FastAPI+React 기반 관제, 맵 편집, SLAM/Nav2 운영 도구 개발

- **RODI 백엔드 엔지니어 (2023.07 – 2024.04)**  
  - 크롤링된 JSON 데이터 ETL 파이프라인 설계·구현 (Python, Selenium)  
  - 국내 주요 마켓 API 연동 모듈 개발 및 자동 업로드 스케줄러 구축  
  - Notion으로 진행 작업 공유, Figma로 프론트엔드 기획 공유

- **(주)GCI 시니어마을 플랫폼 기획·자동화 스크립트 개발 (2023.03 – 운영중)**  
  - 플랫폼 서비스 흐름 설계, 와이어프레임 제작  
  - Python+Selenium+Gemini 기반 반복 업무 자동화 스크립트 개발  
  - 플랫폼 유지 및 게시글 수정

---

## 🔧 기술 스택

| 구분                   | 사용 기술                                                          |
| ---------------------- | ------------------------------------------------------------------ |
| **언어**               | Python ★★★★★, TypeScript ★★★★☆, JavaScript (ES6+) ★★★★☆, Java ★★★☆☆, C++ ★★★☆☆ |
| **프레임워크/라이브러리** | ROS2, React, Next.js, NestJS, FastAPI, Express, Three.js, Konva, Zustand, OpenCV |
| **DevOps / Infra**     | Docker, Docker Compose, MongoDB, PostgreSQL, AWS (EC2, S3, RDS), MQTT, Socket.IO, Kafka, GitHub Actions |
| **협업 도구**          | Slack, Jira, Confluence, Notion, Figma                             |

---

## 📚 학력
- **한국외국어대학교 (2016.03 – 수료(졸업유예))**  
  일본언어문화 & 세계문화예술경영

---

## 🌍 언어 능력
- 한국어 (Native) • 일본어 (Intermediate) • 영어 (Advanced)

---

## 📬 연락처
- ✉️ gci.insu@gmail.com  
- 🐙 <a href="https://github.com/szara7678" target="_blank">GitHub: szara7678</a>

---

## 🌐 프로필 페이지
👉 <a href="https://szara7678.github.io/portfolio_page/" target="_blank">Portfolio</a>

---

## 💻 GitHub 활동
![GitHub stats](https://github-readme-stats.vercel.app/api?username=szara7678&show_icons=true&theme=tokyonight)  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=szara7678&layout=compact&theme=tokyonight)  

![GitHub followers](https://img.shields.io/github/followers/szara7678?style=social)  
![Profile views](https://komarev.com/ghpvc/?username=szara7678)  
