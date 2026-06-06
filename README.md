# 황호민 — Backend Engineer

대용량 트래픽과 시스템 설계를 다루는 4년차 백엔드 엔지니어입니다.
프레임워크가 감춰둔 동작을 직접 구현해보며 병목의 원인까지 내려가는 방식으로 일합니다.

- 단일 API 비대화로 멈춘 시스템을 분리해 핵심 응답을 최대 85% 단축
- 동시 요청·배치 환경의 데이터 무결성을 락과 멱등성 설계로 해결
- 파일 전송 배포부터 ECS 무중단 배포까지, 인프라를 직접 바꿔가며 운영

---

## Tech Stack

**Language**
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

**Framework & Persistence**
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-0769AD?style=flat-square&logo=databricks&logoColor=white)

**Data & Cache**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)

**Infra**
![AWS ECS](https://img.shields.io/badge/AWS_ECS-FF9900?style=flat-square&logo=amazonecs&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

**Observability**
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)

---

## Selected Work

**[Pulley-Test](https://github.com/ghals5737/Pulley-Test)** — 동시 채점·할당 요청에서 같은 학습지가 중복 할당되는 문제를 비관적 락으로 막고, JPA `Specification` 동적 쿼리와 복합 인덱스로 대량 조회를 설계한 학습지 관리 API.

**[Nudg-Api](https://github.com/ghals5737/Nudg-Api)** — JWT·Google OAuth2 인증과 리프레시 토큰 흐름을 직접 구현하고, 태그 push 시 Docker buildx 빌드 → 셀프호스트 레지스트리 → 배포 webhook으로 이어지는 배포 파이프라인을 자체 구축한 Kotlin/Spring 백엔드.

**[Crypto-Trade](https://github.com/ghals5737/Crypto-Trade)** — 외부 블로그 콘텐츠를 요청 스로틀링과 함께 대량 수집하고 타임스탬프 기반으로 JSON에 적재하는 데이터 수집 파이프라인.

---

## Writing — [blog.hhm.io.kr](https://blog.hhm.io.kr)

내부 동작과 트러블슈팅 과정을 기록합니다.

- [쓰레드 풀과 커넥션 풀 완벽 정리 — 자원 풀링부터 가상 쓰레드까지](https://blog.hhm.io.kr/blog/threadpool-connection-pool-virtual-threads)
- [API 하나가 병원 전체를 멈췄다 — 단일 API 비대화의 함정](https://blog.hhm.io.kr/blog/fat-api-pagination-no-offset)
- [배치 작업에서 중복 데이터가 생겼다 — Redis Lock으로 멱등성 잡은 과정](https://blog.hhm.io.kr/blog/batch-idempotency-redis-lock)
- [슬로우 쿼리를 EXPLAIN으로 잡은 과정 — 단일 인덱스에서 복합 인덱스로 (3s → 1.4s)](https://blog.hhm.io.kr/blog/slow-query-explain-composite-index)

---

## Contact

[![Gmail](https://img.shields.io/badge/ghals5737@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ghals5737@gmail.com)
