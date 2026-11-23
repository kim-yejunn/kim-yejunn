<h2>김예준 · Backend Developer</h2>

**외부 데이터를 정확하게 수집하고, 일부가 실패해도 멈추지 않는 시스템을 만듭니다.**

- 고객사 Linux 서버와 이중화(HA) 클러스터를 1년 2개월간 구축·운영하다 서버 개발로 전향했습니다.
- 계기는 서버 전환(페일오버)은 정상이었지만 애플리케이션이 DB에 다시 연결하지 못해 서비스가 20분간 멈춘 장애였습니다.
- 기능을 만들 때 "일부가 실패하면 어떻게 되는가"를 먼저 묻고, 결과는 로그와 측정값으로 확인합니다.

<br>

### Tech Stack

**Backend**&nbsp;
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-0769AD?style=flat-square)
![Spring Batch](https://img.shields.io/badge/Spring%20Batch-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Modulith](https://img.shields.io/badge/Spring%20Modulith-6DB33F?style=flat-square&logo=spring&logoColor=white)

**Database**&nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Infra · Test**&nbsp;
![AWS](https://img.shields.io/badge/AWS%20ECS%C2%B7ECR%C2%B7RDS%C2%B7S3-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Testcontainers](https://img.shields.io/badge/Testcontainers-251A41?style=flat-square&logo=testcontainers&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

<br>

### Projects

| 프로젝트 | 기간 · 역할 | 핵심 |
|---|---|---|
| [**MoNew**](https://github.com/SB14-GoS/sb14-monew-team01)<br>관심사 맞춤 뉴스 통합 서비스 | 2026.10 ~ 2026.11 · 5인<br>**팀장**, 활동 내역·이벤트 파이프라인·S3 백업/복구·배포 (PR 38/107) | MongoDB 조회 모델로 활동 내역 조회 평균 3.90 → 1.66ms. Transactional Outbox로 장애 중 유실 50% → 0%, multikey·복합 인덱스로 댓글 삭제 API 388.9 → 11.1ms · 기사 50만 건 35.2 → 0.036ms. Testcontainers·PR CI·MDC 로깅 등 팀 개발 기반 구축 |
| [**Findex**](https://github.com/SB14-Avengers/sb14-findex-team01)<br>공공 Open API 주가지수 연동 | 2026.09 · 6인<br>연동 도메인 전체·이력 조회·배포 (PR 13/67) | 지수 167개 27,625건 연동 실패 0건. 50건 청크+폴백 트랜잭션으로 커밋 27,625 → 약 553회, 실패 건만 FAILED 이력 격리. N+1 제거 및 복합 커서로 약 18만 건 누락·중복 없이 조회 |
| [**OneRoof**](https://github.com/kim-yejunn/oneroof) ([배포](https://oneroof-17dq.axhub.app))<br>관련 거래처·판매장려금 지급 통제 | 2026.11 · 개인<br>AX 인재전쟁(삼일PwC) 과제 W07<br>**2,916명 중 상위 5% 인증** | 대표자·주소·계좌 중 2개 이상 일치를 Union-Find로 전이 판정해 한도 쪼개기 탐지. Spring Modulith 10개 모듈 Outbox·권한·연체 상계 통제. AI는 회신 정리만 맡기고 원문에 없는 금액·증빙 제거. 단위·통합 테스트 46개 |
| [**Discodeit**](https://github.com/kim-yejunn/14-sprint-mission/tree/%EA%B9%80%EC%98%88%EC%A4%80)<br>Discord형 채팅 백엔드 | 2026.07 ~ 2026.10 · 개인 | GitHub Actions로 ECR 푸시 → ECS 배포 자동화. 저장소 인터페이스로 로컬/S3 전환, Presigned URL 다운로드, N+1 제거 및 테스트 커버리지 Codecov |

<br>

### Experience · Education

- **시스템엔지니어(주임)** · (주)에스엠인포메이션 기술본부 · 2025.01 ~ 2026.03<br>
  금융·공공기관 서버 접근제어 구축, Linux HA 클러스터 구축·운영과 장애 대응
- **코드잇 스프린트** Spring 백엔드 과정 · 2026.07 ~
- **컴퓨터공학 학사** · 학점은행제 / 서일대학교 소프트웨어공학과 전문학사
- 정보처리산업기사 · SQL 개발자(SQLD)

<br>

### Contact

[![Email](https://img.shields.io/badge/kimyj0830@naver.com-03C75A?style=flat-square&logo=naver&logoColor=white)](mailto:kimyj0830@naver.com)
