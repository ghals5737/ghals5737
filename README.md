<h1 align="left">황호민 · Backend Engineer</h1>

> 추상화 뒤가 궁금하면, 직접 만들어 봅니다.

4년차 백엔드 엔지니어. 대용량 트래픽과 시스템 설계를 다루고, 프레임워크가 감춘 동작을 직접 구현해보며 병목의 원인까지 내려갑니다.

---

### Notes

- 추상화를 믿기 전에 한 겹 벗겨 본다 — Kafka 코어를 Kotlin으로 다시 구현
- 단일 API 비대화로 멈춘 시스템을 분리해 핵심 응답 최대 85% 단축
- 동시 요청·배치의 데이터 무결성은 락과 멱등성 설계로
- 파일 전송 배포부터 ECS 무중단 배포까지, 인프라를 직접 바꿔가며 운영

---

### Projects

| Project | Description | Stack | Repo |
| --- | --- | --- | --- |
| **mykafka** | append-only 세그먼트 로그·offset 인덱스, Netty 브로커, `FileRegion` zero-copy 전송까지 직접 구현한 분산 커밋 로그 | Kotlin | [→](https://github.com/ghals5737/mykafka) |
| **Nudg-Api** | JWT·OAuth2 인증을 직접 구현하고, 태그 push → Docker buildx → 셀프호스트 레지스트리 → webhook 배포 파이프라인을 자체 구축 | Kotlin · Spring | [→](https://github.com/ghals5737/Nudg-Api) |
| **Crypto-Trade** | 요청 스로틀링과 함께 외부 콘텐츠를 대량 수집해 타임스탬프 기반 JSON으로 적재하는 데이터 파이프라인 | Python | [→](https://github.com/ghals5737/Crypto-Trade) |

---

### Writing — [blog.hhm.io.kr](https://blog.hhm.io.kr)

- [쓰레드 풀과 커넥션 풀 완벽 정리 — 자원 풀링부터 가상 쓰레드까지](https://blog.hhm.io.kr/blog/threadpool-connection-pool-virtual-threads)
- [API 하나가 병원 전체를 멈췄다 — 단일 API 비대화의 함정](https://blog.hhm.io.kr/blog/fat-api-pagination-no-offset)
- [배치 작업에서 중복 데이터가 생겼다 — Redis Lock으로 멱등성 잡은 과정](https://blog.hhm.io.kr/blog/batch-idempotency-redis-lock)
- [슬로우 쿼리를 EXPLAIN으로 잡은 과정 — 단일 인덱스에서 복합 인덱스로 (3s → 1.4s)](https://blog.hhm.io.kr/blog/slow-query-explain-composite-index)

---

### Tech Stack

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-0769AD?style=flat-square&logo=databricks&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![AWS ECS](https://img.shields.io/badge/AWS_ECS-FF9900?style=flat-square&logo=amazonecs&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)

---

[![Gmail](https://img.shields.io/badge/ghals5737@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ghals5737@gmail.com)
