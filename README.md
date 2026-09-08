# Nodu

> 심플하지만, 확실하게 동작하는 개발을 지향합니다.

백엔드와 프론트엔드를 함께 다룹니다. 기획 협의 · DB 설계 · 백엔드 · 프론트 · 배포를
한 사람이나 두 사람이 맡는 환경에서 일해 왔습니다.

| 항목 | 내용 |
| --- | --- |
| 기간 | 2025.02 ~ 현재 |
| 프로젝트 | 21건 — SI 19건 · 자사 서비스 2건 |
| 도메인 | 챗봇 10 · AI 생성 6 · 자사 서비스 2 · 웹/모바일 2 · ERP 1 |
| 역할 | 전 건 풀스택 (단독 또는 2인) |

<br>

### 일하는 방식

- **필요가 확인된 뒤에 인프라를 늘립니다.** Redis도 인메모리 세션이 다중 워커에서 유실되는 걸 겪은 뒤에 넣었습니다.
- **외부 API와 결제는 실패한다고 전제합니다.** 환불을 먼저 확정하고, 이중 차감을 막고, 실주문은 드라이런을 기본값으로 둡니다.
- **숫자는 코드가 계산하고 AI는 서술만 맡깁니다.** AI가 만든 SQL은 화이트리스트 검증을 거친 뒤에만 실행합니다.

<br>

### 기술

| 영역 | |
| --- | --- |
| **Backend** | Python · FastAPI · Django · SQLAlchemy · Alembic · Celery · Pydantic |
| **Frontend** | TypeScript · React · Vite · Tailwind CSS · TanStack Query |
| **Mobile** | Flutter · Capacitor |
| **Database** | MySQL · Redis |
| **Infra** | AWS · Nginx · Gunicorn · GitHub Actions |
| **AI · API** | OpenAI · Google Gemini · Claude · ElevenLabs · Firebase |

<br>

### 링크

- **포트폴리오** · [noduu.duckdns.org](https://noduu.duckdns.org) — 프로젝트 21건, 기술 스택, 개발 방식
- **블로그** · [eehnodu.tistory.com](https://eehnodu.tistory.com)

작업물은 대부분 회사 프로젝트라 저장소를 공개하지 않았습니다.
프로젝트마다 무엇을 만들고 어떻게 풀었는지는 포트폴리오에 정리해 두었습니다.
