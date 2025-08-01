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
<summary>에덴포지 - 무한텍스트 탑 등반 RPG (개인 프로젝트)</summary>

- **텍스트 기반 RPG 게임**: 간단한 텍스트 기반 RPG 게임으로 진입장벽 및 리소스 최소화  
- **끝없는 탑 등반 시스템**: 제한 없는 레벨링으로 끝없는 컨텐츠 설계  
- **현재 층과 몬스터 레벨에 따른 아이템 드랍**: 게임의 컨셉에 맞는 드랍 시스템 구축
- **아이템 레벨에 따른 제작 아이템 레벨 변동**: 게임의 컨셉에 맞게 재료 아이템 레벨에 의한 장비 레벨 변동
- **재료를 얻기 위해 끊임없이 어려워지는 미니게임**: 지뢰찾기, 같은 그림 맞추기, 리듬게임 등의 미니게임 구현 및 스킬 레벨에 따른 높은 아이템 레벨 설계  
- <a href="https://github.com/szara7678/edenforge" target="_blank">게임 플레이 (깃허브 페이지)</a>

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
<summary>타로 카드 게임 (개인 프로젝트)</summary>

- **덱 셔플 알고리즘**: Fisher–Yates 방식으로 완전 무작위 카드 셔플 구현  
- **CSS 애니메이션**: keyframe(슬라이드인, 페이드아웃)으로 카드 전개 연출  
- **DOM 동적 업데이트**: 카드 클릭 시 순수 JS로 상태·UI 동기화  
- **반응형 디자인**: 뷰포트 단위(vw/vh) 활용해 모바일·데스크톱 모두 최적화  
- <a href="https://szara7678.github.io/TarotGame/" target="_blank">데모 & 코드 보기</a>

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
| **언어**               | Python ★★★★★, JavaScript (ES6+) ★★★★☆, C# ★★★☆☆, C++ ★★★☆☆        |
| **프레임워크/라이브러리** | ROS2, OpenCV, React, FastAPI, Flask                                |
| **DevOps / Infra**     | AWS (EC2, S3, RDS), Docker, GitHub Actions                         |
| **협업 도구**          | Slack, Jira, Confluence                                            |

---

## 📚 학력
- **한국외국어대학교 (2016.03 – 2025.09)**  
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
