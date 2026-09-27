Full-stack developer at Hyosung FMS, building customer-facing applications for payments and settlements.

Spring Boot · Vue.js · Data consistency · External integrations

[Portfolio](https://sanghunkim.com) · [Email](mailto:rlatkdgns042@naver.com)

## Career

### Hyosung FMS Inc. · Application Platform
**Full-stack Developer · Sep 2024–Present**

<details>
<summary>Responsibilities & selected work</summary>

- Develop and maintain customer-facing applications for contracts, payments, and settlements across six services.
- Contributed to electronic contract integration and the Branch Manager B2B platform.
- Handle batch monitoring and customer-reported issues for CMS+ and Ibill alongside development work.
- Serve as the owner of **Ibill**, an education payment platform, since Aug 2026. Review requirements, determine development priorities, and resolve operational issues from investigation through deployment.

**Selected work**

- Extended a shared query API with optional parameters to align payment details with settlement results while preserving existing API behavior.
- Enabled **150,000-row Excel exports within 8 minutes** through paginated API calls and SXSSF streaming, without modifying the upstream system.
- Corrected approximately **20,000 payment requests stuck in an in-progress state** and automated status correction for selected failure cases.
- Centralized external integration error handling with AOP, separating customer-facing messages from operational alerts.

**Technologies:** Java · Spring Boot · Spring Batch · Spring AOP · Vue.js · Oracle

</details>

## Selected Projects

### [UPQuant — Cryptocurrency Quantitative Analysis Dashboard](https://github.com/rlatkd/up-quant)
**Personal project · 2026**

A dashboard for analyzing market conditions, portfolio allocation, and trading strategies across approximately 260 Upbit KRW markets.

<details>
<summary>Implementation details</summary>

- Combined nine quantitative methods, including HMM, GARCH, PCA, and portfolio optimization, with backtesting and strategy validation.
- Incorporated transaction costs, slippage, walk-forward validation, and FDR correction into the relevant analyses.
- Reduced correlation analysis response time from approximately **1.8 seconds to 5 ms** by sharing cached daily candle data across features.
- Implemented stale-while-revalidate, single-flight cache refresh, and a shared WebSocket relay.

**Stack:** Python · FastAPI · React · TypeScript · AWS · GitHub Actions

</details>

### [Automated Billing & Payment System](https://github.com/rlatkd/cms-plus)
**Team project · Architect · 2024**

A system for managing customers, contracts, billing, and payments, built during the Hyosung FMS full-stack training program.

<details>
<summary>Implementation details</summary>

- Designed the system and infrastructure, and implemented payment, product, and batch features.
- Separated application services and deployed them using ECS Fargate, with the analysis service hosted separately.
- Configured a three-broker Kafka cluster with separate topics for payment requests, payment results, and messaging.
- Built centralized logging, metrics monitoring, and CI/CD pipelines.

**Stack:** Java · Spring Boot · Spring Batch · React · Kafka · AWS · ELK · Prometheus · Grafana

</details>

### [MSA-based Web POS Service](https://github.com/rlatkd/sale-sync)
**Team project · 2024**

A web-based POS project developed during the Shinsegae I&C cloud engineer training program.

- Received the program’s top final-project award.

## Education

### Sungkyunkwan University
**Graduate studies in Quantitative Applied Economics · Mar 2026–Present**

### Kyung Hee University
**Bachelor’s degree in Biomedical Engineering · Mar 2018–Feb 2023**

<details>
<summary>Thesis details</summary>

- Undergraduate thesis: comparison of CNN models for liver tumor image classification.
- Compared LeNet5, AlexNet, VGG19, and ResNet50 using 4,325 CT images from LiTS17.
- VGG19 achieved the highest validation accuracy at **99.3%** in the experiment.

</details>

### Hanseo Aviation Institute
**Associate degree in Aircraft Maintenance · Mar 2015–Feb 2017**

## Awards

<details>
<summary>Award details</summary>

- **우수상** — IITP SW전문인재양성 우수성과 컨퍼런스 · Aug 2024
- **파이널 프로젝트 최우수상 · 우수 수료생** — Hyosung FMS Full-Stack Developer Training Program · Aug 2024
- **파이널 프로젝트 최우수상** — Shinsegae I&C Cloud Engineer Training Program · Feb 2024

</details>

## Training & Team Projects

### Hyosung FMS Full-Stack Developer Training Program · 1st Cohort · Feb–Aug 2024

<details>
<summary>Repositories</summary>

- [Automated Billing & Payment System](https://github.com/rlatkd/cms-plus)
- [Futsal Automatic Matching Service](https://github.com/rlatkd/match5)
- [Internet Banking System](https://github.com/rlatkd/hs-bank)

</details>

### Shinsegae I&C Cloud Engineer Training Program · 2nd Cohort · Aug 2023–Feb 2024

<details>
<summary>Repositories</summary>

- [MSA-based Web POS Service](https://github.com/rlatkd/sale-sync)
- [Second-hand Auction Platform v0](https://github.com/rlatkd/ssgbay-v0)
- [Fashion Community](https://github.com/rlatkd/fashion-community)

</details>

## More Projects

### Personal Projects

<details>
<summary>Repositories</summary>

- [Portfolio](https://github.com/rlatkd/portfolio)
- [SKKU QAE Ledger App](https://github.com/rlatkd/quant-ledger)
- [Robust Payment System](https://github.com/rlatkd/rubust-payment-system)
- [Monitoring System](https://github.com/rlatkd/monitoring-system)
- [Real-time Chat Platform](https://github.com/rlatkd/live-chat)
- [Customer Management System v2](https://github.com/rlatkd/management-system-v2)
- [Second-hand Auction Platform v2](https://github.com/rlatkd/ssgbay-v2)
- [Second-hand Auction Platform v1](https://github.com/rlatkd/ssgbay-v1)
- [Customer Management System v1](https://github.com/rlatkd/management-system)

</details>

### Undergraduate Projects

- [CT Image Reconstruction](https://github.com/rlatkd/ct-image-reconstruction)

## Learning Notes

<details>
<summary>Repositories</summary>

- [1day-1commit](https://github.com/rlatkd/1day-1commit)
- [Kafka Streams](https://github.com/rlatkd/kafka-streams)
- [MyBatis & JPA](https://github.com/rlatkd/mybatis-jpa)
- [GitLab Runner](https://github.com/rlatkd/gitlab-runner)
- [JDBC](https://github.com/rlatkd/jdbc)
- [Design Patterns](https://github.com/rlatkd/design-pattern)
- [Qlik Sense Embed](https://github.com/rlatkd/qlik-embed)
- [Qlik Sense Mashup](https://github.com/rlatkd/qlik-mashup)
- [Dockerization](https://github.com/rlatkd/ssgbay-dockerize)
- [CI/CD](https://github.com/rlatkd/cicd-react)
- [Terraform](https://github.com/rlatkd/terraform)

</details>
