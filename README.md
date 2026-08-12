<h1 align="left">👨‍💻 박성환</h1>
<h3 align="left">Server Engineer</h3>

<p align="left">
복잡한 도메인 흐름을 <strong>신뢰할 수 있는 구조</strong>로 정리하는 백엔드 개발자입니다.<br/>
예약 · 결제 · 정산 · 배치 · 외부 연동처럼 기준이 흔들리기 쉬운 영역에서
<strong>정합성, 동시성, 운영 안정성</strong>을 높이는 구조 개선에 집중합니다.
</p>

<p align="left">
  <a href="https://mrpark219.github.io">
    <img src="https://img.shields.io/badge/Blog-111111?style=for-the-badge&logo=githubpages&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/mrpark219">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:mrpark219@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

## 🔍 About Me

```text
✔ Java / Spring 기반 백엔드 시스템을 개발합니다.
✔ 예약 · 결제 · 정산 · 배치 · 외부 연동 도메인의 정합성과 운영 안정성을 개선해왔습니다.
✔ 필요한 곳에는 LLM을 적용해 운영 자동화까지 함께 풀어가되, 최종 판단과 검증은 항상 직접 합니다.
✔ 성능 개선, 동시성 제어, 레거시 전환, MSA 설계 학습 내용을 글과 코드로 정리합니다.
```

---

## 🛠 Tech Stack

| Category             | Stack                                                           |
| -------------------- | --------------------------------------------------------------- |
| **Language**         | Java, Kotlin, Python, JavaScript                                |
| **Backend**          | Spring Boot, Spring Data JPA, Querydsl, Spring Batch, Spring AI |
| **Database / Cache** | MySQL, Redis, OpenSearch                                        |
| **Infra / DevOps**   | AWS ECS, SQS, S3, Docker, Jenkins, GitHub Actions, Datadog      |
| **Testing**          | JUnit, Spring Boot Test, JMeter, k6                             |
| **Study**            | MSA, DDD, Clean Architecture, Kubernetes                        |

---

## ✍️ Featured Articles

| Topic                          | Article                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Spring Batch / Performance** | [10시간 걸리던 숙소 연동 배치를 20분으로 줄인 이야기](https://blog.ban-life.com/%EC%83%88%EB%B2%BD%EC%97%90-%EC%8B%9C%EC%9E%91%ED%95%9C-%EB%B0%B0%EC%B9%98%EA%B0%80-%ED%87%B4%EA%B7%BC%ED%95%A0-%EB%95%8C-%EB%81%9D%EB%82%9C%EB%8B%A4%EB%A9%B4-10%EC%8B%9C%EA%B0%84%EC%A7%9C%EB%A6%AC-%EC%88%99%EC%86%8C-%EC%97%B0%EB%8F%99-%EB%B0%B0%EC%B9%98-20%EB%B6%84-%EB%A7%8C%EC%97%90-%EB%81%9D%EB%82%B8-%EC%9D%B4%EC%95%BC%EA%B8%B0-spring-batch-f8d3ea5a12a5) |
| **JPA / Concurrency**          | [락을 걸었는데 왜 오버부킹이 날까? JPA 1차 캐시의 함정 탈출기](https://blog.ban-life.com/%EB%9D%BD-lock-%EC%9D%84-%EA%B1%B8%EC%97%88%EB%8A%94%EB%8D%B0-%EC%99%9C-%EC%98%A4%EB%B2%84%EB%B6%80%ED%82%B9%EC%9D%B4-%EB%82%A0%EA%B9%8C-jpa-1%EC%B0%A8-%EC%BA%90%EC%8B%9C%EC%9D%98-%ED%95%A8%EC%A0%95-%ED%83%88%EC%B6%9C%EA%B8%B0-33570ca77b56)                                                                                                               |
| **Spring Batch / Concurrency** | [병렬 배치 마이그레이션기 — Spring Batch 6, 동시성의 단위가 청크에서 아이템으로 바뀌었다](https://blog.ban-life.com/%EB%B3%91%EB%A0%AC-%EB%B0%B0%EC%B9%98-%EB%A7%88%EC%9D%B4%EA%B7%B8%EB%A0%88%EC%9D%B4%EC%85%98%EA%B8%B0-spring-batch-6-%EB%8F%99%EC%8B%9C%EC%84%B1%EC%9D%98-%EB%8B%A8%EC%9C%84%EA%B0%80-%EC%B2%AD%ED%81%AC%EC%97%90%EC%84%9C-%EC%95%84%EC%9D%B4%ED%85%9C%EC%9C%BC%EB%A1%9C-%EB%B0%94%EB%80%8C%EC%97%88%EB%8B%A4-0de21a8838f7)         |

---

## 🚀 Selected Projects

### 🏊‍♂️🌊 [deep-dive](https://github.com/mrpark219/deep-dive)

MSA, DDD, Clean Architecture, JPA, Spring Batch, 동시성, AWS 학습 내용을 정리하는 저장소입니다.

### 🔒 [no-more-oversell](https://github.com/mrpark219/no-more-oversell)

제한 수량 상품에 동시 예약·결제 요청이 들어올 때 재고 초과 주문을 막는 구조를 직접 구현·검증한 프로젝트입니다. (Redis, k6)

### 📦 [bookiverse](https://github.com/mrpark219/bookiverse)

주문·결제·재고 책임을 서비스 단위로 분리했을 때, 서비스 간 이벤트 전달과 데이터 정합성을 유지하는 구조를 검증한 프로젝트입니다. (Kafka, Outbox)

### 🧩 [msa-study](https://github.com/mrpark219/msa-study)

Spring Boot와 Spring Cloud 기반 e-commerce 학습용 예제입니다.
Config Server, Eureka, Gateway, OpenFeign, Resilience4j, Kafka, Zipkin, Prometheus/Grafana, Docker 배포 구성을 구현했습니다.

### 🏆 [goldroad-backend](https://github.com/9oormthon-goldroad/goldroad-backend)

구름톤 12기 우수상 수상작 ‘황금향’ 백엔드 시스템입니다.

### 🚇 [melona](https://github.com/mrpark219/melona)

지하철 실시간 위치 및 혼잡도 정보 제공 서비스입니다.

### 📱 [ipTIME-WOL](https://github.com/mrpark219/ipTIME-WOL)

iOS 단축어 연동 Wake-on-LAN 실행 유틸리티입니다.
