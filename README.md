<h1 align="left">👨‍💻 박성환</h1>
<h3 align="left">Backend Developer</h3>

<p align="left">
서비스 운영에서 반복되는 문제를 찾아<br/>
<strong>시스템과 업무 흐름을 개선하는 백엔드 개발자</strong>입니다.
</p>

<p align="left">
  <a href="https://mrpark219.github.io/about/">
    <img src="https://img.shields.io/badge/About-111111?style=for-the-badge&logo=githubpages&logoColor=white" alt="About"/>
  </a>
  <a href="https://mrpark219.github.io">
    <img src="https://img.shields.io/badge/Blog-111111?style=for-the-badge&logo=githubpages&logoColor=white" alt="Blog"/>
  </a>
  <a href="https://www.linkedin.com/in/mrpark219">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:mrpark219@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## 🔍 About Me

예약, 결제, 정산과 숙소 관리 시스템(PMS) 연동을 개발하며
운영 중 발생하는 데이터 불일치 문제를 해결했습니다.
반복적인 확인과 검토가 필요한 업무에 AI를 활용해 운영 효율도 개선했습니다.

- 결제 후 숙소 예약에 실패한 건의 취소를 자동화하고, 대사 배치에서 발견된 취소 누락 건까지 처리했습니다.
- 성수기 중심으로 진행하던 숙소 정책 검수를 AI가 매일 변경 후보를 탐지하고 운영자가 검토 후 승인하는 방식으로 전환했습니다.
- 요구사항 정리부터 설계와 구현까지 AI를 활용하고, 실제 적용 여부는 직접 측정하고 검증하며 판단합니다.

자세한 경력은 [About 페이지](https://mrpark219.github.io/about/)에서 확인할 수 있습니다.

---

## 💼 주요 경험

| 분야               | 경험                                                                                                                                             |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------ |
| **결제와 예약**    | 예약 실패 유형을 구분하고, 취소 키 기반 멱등 처리와 SQS를 적용해 결제 취소를 자동화했습니다.                                                     |
| **재고 동시성**    | JPA 1차 캐시와 트랜잭션 경계를 분석해 초과 판매를 해결했습니다. 베타 서버 부하 테스트에서 주문 완료 처리량을 **15.5 → 218 TPS**로 개선했습니다.  |
| **배치 성능**      | 숙소 연동 배치를 Spring Batch 기반으로 재설계해 약 7만 2천 개 숙소의 전체 연동 시간을 **평균 10시간 → 11분대**로 단축했습니다.                   |
| **AI 운영 자동화** | 숙소 정책의 변경 판별과 요약을 분리해 실제 변경이 없는 검수 후보 비율을 **69.9% → 2.7%**로 낮추고, 건당 외부 AI API 비용을 **70% 절감**했습니다. |

---

## 🛠 Tech Stack

| Category             | Stack                                                         |
| -------------------- | ------------------------------------------------------------- |
| **Language**         | Java, Kotlin                                                  |
| **Backend**          | Spring Boot, Spring Batch, Spring AI, JPA/Hibernate, QueryDSL |
| **Database / Cache** | MySQL, Redis, Caffeine, OpenSearch                            |
| **Infrastructure**   | AWS ECS, SQS, S3, Docker, Jenkins                             |
| **Observability**    | Datadog, Pinpoint                                             |
| **Testing**          | JUnit, k6                                                     |

---

## 🚀 Selected Projects

| Project                                                                      | Description                                                                                                     | Tech          |
| ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- | ------------- |
| 🔒 [no-more-oversell](https://github.com/mrpark219/no-more-oversell)          | 제한 수량 상품에 동시 예약과 결제 요청이 들어올 때 재고 초과 주문을 막는 구조를 구현하고 검증했습니다.          | Redis, k6     |
| 📦 [bookiverse](https://github.com/mrpark219/bookiverse)                      | 주문, 결제, 재고를 서비스 단위로 분리하고 서비스 간 이벤트 전달과 데이터 정합성을 유지하는 구조를 검증했습니다. | Kafka, Outbox |
| 🏊 [deep-dive](https://github.com/mrpark219/deep-dive)                        | JPA, Spring Batch, 동시성, MSA 등 학습 내용을 정리합니다.                                                       | Java, Spring  |
| 🏆 [goldroad-backend](https://github.com/9oormthon-goldroad/goldroad-backend) | 제주 이주 은퇴자를 위한 커뮤니티 서비스 MVP입니다. 구름톤 12기에서 우수상을 수상했습니다.                       | Backend, DKOS |

---

## ✍️ Featured Articles

| Topic                          | Article                                                                                              |
| ------------------------------ | ---------------------------------------------------------------------------------------------------- |
| **Spring Batch / Performance** | [10시간 걸리던 숙소 연동 배치를 20분으로 줄인 이야기](https://medium.com/post/f8d3ea5a12a5)          |
| **JPA / Concurrency**          | [락을 걸었는데 왜 오버부킹이 날까? JPA 1차 캐시의 함정 탈출기](https://medium.com/post/33570ca77b56) |
| **Spring Batch / Concurrency** | [병렬 배치 마이그레이션기 — Spring Batch 6의 동시성 변화](https://medium.com/post/0de21a8838f7)      |
