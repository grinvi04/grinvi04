<div align="center">

# 김봉민 · BongMin Kim

백엔드 개발자

[![Gmail](https://img.shields.io/badge/grinvi04@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:grinvi04@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-grinvi04-181717?style=flat-square&logo=github)](https://github.com/grinvi04)

</div>

---

## 👋 About Me

13년째 백엔드 개발하고 있습니다. 주로 Java/Spring을 다뤘습니다.

요즘은 Claude Code·MCP 같은 AI 도구를 개발에 어떻게 써먹을지 이것저것 실험 중입니다. AI한테 일관된 방식으로 일을 시키려고 가드레일·커맨드 같은 장치를 직접 만들어 보면서, 사이드 프로젝트 몇 개를 굴리고 있습니다. 깊게 파기보단 틈날 때 기술 블로그·문서 찾아보며 필요한 만큼 익히는 편입니다.

등산, 건강 관리, 주식 좋아합니다. ⛰️📈

---

## 🛠 Tech Stack

**Backend**  
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

**Database & Cache**  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Infra / DevOps**  
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS EKS](https://img.shields.io/badge/AWS_EKS-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)

**Frontend**  
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**AI-Augmented Dev**  
![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white)

---

## 📂 Projects

### [🌲 DriveTree](https://github.com/grinvi04/drivertree) · [Live →](https://drivertree.vercel.app)
> NestJS · Next.js 16 · PostgreSQL (pgvector) · Prisma · Tailwind v4 · Railway · Vercel

**"면허 학원도, 유튜브도 알려주지 않는 — 초보운전자를 위한 실전 가이드 서비스"**

| 기능 | 설명 |
|---|---|
| 📚 실전 가이드 | 비보호좌회전·접촉사고·주차 등 실생활 시나리오 중심 콘텐츠 |
| 🤖 AI 챗봇 | TF-IDF + pgvector 기반 RAG 챗봇으로 자연어 도로 질문 답변 |
| ⚖️ 범칙금 계산기 | 위반 유형별 과태료·범칙금·벌점 즉시 조회 |
| 🚗 유지비 계산기 | 차종·연료·주행거리 입력 → 월별 유지비 자동 산출 |
| 🔒 관리자 백오피스 | 가이드 CRUD + 챗봇 모니터링 로그 대시보드 |

---

### [🐀 쥐꼬리맵 (jwikoori-map)](https://github.com/grinvi04/jwikoori-map) · [Live →](https://jwikoori-map.vercel.app)
> Spring Boot 3.3 · Java 17 · Clean Architecture + DDD · Vue 3 · PostgreSQL (Neon) · JPA · Flyway · Railway · Vercel

**"대한민국 중소·중견기업 임금 정보 공개 플랫폼"**

| 기능 | 설명 |
|---|---|
| 💰 임금 정보 공개 | 중소·중견기업 임금 데이터 검색·열람 |
| 📝 임금 제보 | 사용자 임금 제보 등록 (블라인드 처리 지원) |
| 🛡️ 신고·모더레이션 | 부적절 제보 신고 → 관리자 blind/dismiss (`@PreAuthorize` 인가) |
| 🔐 인증 | Spring Security + JWT |
| 🏛️ 아키텍처 | Clean Architecture + DDD (domain·application·infrastructure·interfaces 분리) |

---

### [⚙️ webhook-service](https://github.com/grinvi04/webhook-service)
> Python · FastAPI · Celery · Redis · PostgreSQL · Prometheus · Keycloak · Docker

**"서명 검증부터 자동 재시도까지 — 프로덕션 수준의 멀티테넌트 웹훅 수신·처리 플랫폼"**

| 기능 | 설명 |
|---|---|
| 🏢 멀티테넌트 | `tenant_id` 기반 완전 격리 — 고객별 독립 시크릿·이벤트·메트릭 관리 |
| 🔐 서명 검증 | GitHub HMAC-SHA256 · Stripe 공식 SDK — 위변조 페이로드 즉시 거부 |
| ⚡ 비동기 큐 | Celery + Redis — API 202 응답과 처리 로직 완전 분리 |
| 🔄 신뢰성 | 최대 3회 지수 백오프 재시도 + Dead Letter Queue + 이벤트 Replay API |
| 🧱 레이어드 설계 | Repository 패턴으로 DB 접근 캡슐화 · 트랜잭션 경계 분리 |
| 📊 관측성 | Prometheus Counter·Histogram + Grafana 대시보드 |

---

## 📊 GitHub Stats

<div align="center">

![grinvi04's GitHub stats](https://github-readme-stats.vercel.app/api?username=grinvi04&show_icons=true&hide_border=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=grinvi04&layout=compact&hide_border=true&theme=tokyonight)

</div>

---

<div align="center">

📫 **grinvi04@gmail.com**

</div>
