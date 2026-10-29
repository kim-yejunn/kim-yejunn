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

**Database**&nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**Infra**&nbsp;
![AWS](https://img.shields.io/badge/AWS%20ECS%C2%B7ECR%C2%B7S3-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Etc**&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

<br>

### Projects

| 프로젝트 | 기간 · 역할 | 핵심 |
|---|---|---|
| [**Findex**](https://github.com/SB14-Avengers/sb14-findex-team01)<br>공공 Open API 주가지수 연동 | 2026.09 · 6인<br>지수 데이터 연동·연동 이력·배포 | 27,625건 연동 실패 0건. 청크 트랜잭션으로 커밋 27,625회 → 약 553회, 실패 건만 이력으로 격리. 복합 커서로 약 18만 건 누락·중복 없이 조회 |
| [**MoNew**](https://github.com/SB14-GoS/sb14-monew-team01)<br>관심사 맞춤 뉴스 통합 서비스 | 2026.10 ~ · 6인<br>**팀장**, 세팅·알림·활동 내역 | 커밋 이후 이벤트로 MongoDB 활동 내역 문서를 미리 갱신해 대량 데이터 조회 평균 3.90ms → 1.66ms. Testcontainers·CI 커버리지·MDC 로깅 등 팀 개발 환경 구축 |
| [**Discodeit**](https://github.com/kim-yejunn/14-sprint-mission/tree/%EA%B9%80%EC%98%88%EC%A4%80)<br>Discord형 채팅 백엔드 | 2026.07 ~ 2026.10 · 개인 | GitHub Actions로 ECR 푸시 → ECS 배포 자동화. 저장소 인터페이스로 로컬/S3 전환, Presigned URL 다운로드. 테스트 커버리지 Codecov |
| [**너랑 연습**](https://github.com/kim-yejunn/practiceyou.github.io)<br>카카오톡 대화 기반 말투 모방 챗봇 | 2024.09 ~ 2024.10 · 3인<br>백엔드 | 기기별로 다른 카카오톡 내보내기 4종을 형식 판별 후 정규화. OpenAI API 연동, tiktoken으로 최근 19,000토큰 유지, 배포 |

<br>

### Experience · Education

- **시스템엔지니어(주임)** · (주)에스엠인포메이션 기술본부 · 2025.01 ~ 2026.03
  금융·공공기관 서버 접근제어 구축, Linux HA 클러스터 구축·운영과 장애 대응
- **코드잇 스프린트** Spring 백엔드 과정 · 2026.07 ~
- **컴퓨터공학 학사** · 학점은행제 / 서일대학교 소프트웨어공학과 전문학사
- 정보처리산업기사 · SQL 개발자(SQLD)

<br>

### Contact

[![Email](https://img.shields.io/badge/kimyj0830@naver.com-03C75A?style=flat-square&logo=naver&logoColor=white)](mailto:kimyj0830@naver.com)
[![Solved.ac Profile](https://mazassumnida.wtf/api/v2/generate_badge?boj=kimyj0830)](https://solved.ac/kimyj0830/)
