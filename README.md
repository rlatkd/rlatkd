## career

- Hyosung FMS Inc. Application Platform
  - Full-stack Developer (2024.09. ~ )
    - Spring Boot v2.5.4
    - Vue.js v2.5.14
    - Oracle v19C

    <details>
      <summary>담당 업무</summary>

    **공유 조회 API 확장을 통한 결제·정산 데이터 정합성 확보**

    - 결제·정산 테이블을 대조해 결제수단별 조회 대상과 기준일의 차이를 확인
    - 선택적 파라미터와 제외 상태 코드를 스펙으로 정리해 공유 API 확장을 협의
    - 휴대전화는 두 테이블에서 의미가 같은 정산일로 조회하도록 수정

    **성과:** VIP 고객사에서 월 3건 발생하던 동일 유형 VoC 해소 · 기존 API 소비자의 조회 동작 유지

    ---

    **응답 크기 제어를 통한 정산대상 결제내역 대량 엑셀 추출**

    - 대량 조회 시 DB는 정상이고 애플리케이션 서버가 종료되는 현상에 주목
    - 1,000건 단위 순차 조회와 SXSSF 스트리밍으로 한 번에 처리할 데이터양 제한
    - 공용 계정계의 동시 조회 부하를 고려해 병렬 호출 대신 순차 처리

    **성과:** 계정계 수정 없이 15만 건을 8분 내 추출 · 기존 5만 건 제한과 매월 반복되던 수기 추출 해소

    ---

    **CMS 결제 요청 실패 청구의 상태 고착 해소 및 실패 보정 자동화**

    - 전송 전에 결제중으로 바꾸는 기존 순서를 유지하고 실패 보정 추가
    - 당일 전송 종료 후 고객 관리 시스템의 현재 서비스 상태를 일괄 조회
    - 이용중지·해지예정·해지 상태인 고객사의 실패 청구를 대기로 보정

    **성과:** 과거 고착 청구 약 2만 건 일괄 보정 · 이후 동일 조건의 실패 청구 자동 보정으로 수기 작업 해소

    ---

    **외부 연동 실패 메시지의 노출 차단 및 실패 알림 자동화**

    - AOP로 단건 외부 연동 호출의 실패 처리를 공통화
    - 원본 예외는 로그에 남기고 고객사 화면에는 안내 문구 표시
    - 발생 시각·대상·호출 API·오류 내용을 운영 담당자에게 문자로 전달

    **성과:** 월 10건 규모의 동일 유형 VoC와 비고 수기 수정 해소 · 고객사 문의 전에 시스템 알림으로 실패 인지

    </details>

## education
- Master of Science (2026.03. - )
  - Sungkyunkwan University, Graduate School, Department of Quantitative Applied Economics
- Bachelor of Engineering (2018.03. - 2023.02.)
  - Kyung Hee University, College of Electronics and Information, Department of Biomedical Engineering
    - *Comparative Study of Convolutional Neural Network (CNN) Models for Liver Tumor Image Classification* (2022.06.)
- Associate Degree (2015.03. - 2017.02.)
  - Hanseo Aviation Institute, Department of Aircraft Maintenance

## trainings

<details>
  <summary>Hyosung FMS Full-Stack Developer Training Program 1st Cohort (2024.02. ~ 2024.08.)</summary>

  - [Automated Billing/Payment Solution](https://github.com/rlatkd/cms-plus)
  - [Futsal Automatic Matching Service](https://github.com/rlatkd/match5)
  - [Internet Banking System](https://github.com/rlatkd/hs-bank)

</details>

<details>
  <summary>Shinsegae I&C Cloud Engineer Training Program 2nd Cohort (2023.08. ~ 2024.02.)</summary>

  - [MSA-based Web POS Service](https://github.com/rlatkd/sale-sync)
  - [Second-hand Auction Platform v0](https://github.com/rlatkd/ssgbay-v0)
  - [Fashion Community](https://github.com/rlatkd/fashion-community)

</details>

## awards

- Institute of Information & Communications Technology Planning & Evaluation (IITP) SW Excellence Conference
  - Outstanding Award (2024.08.)
- Hyosung FMS Full-Stack Developer Training Program 1st Cohort
  - [Final Project](https://github.com/rlatkd/cms-plus) Grand Prize (2024.08.)
  - Outstanding Graduate (2024.08.)
- Shinsegae I&C Cloud Engineer Training Program 2nd Cohort
  - [Final Project](https://github.com/rlatkd/salesync) Grand Prize (2024.02.)

## projects

<details>
  <summary>Long-term Projects</summary>

  - [Cryptocurrency Quant Analysis Dashboard](https://github.com/rlatkd/up-quant)
  - [Automated Billing/Payment Solution](https://github.com/rlatkd/cms-plus)
  - [MSA-based Web POS Service](https://github.com/rlatkd/salesync)
  - [Portfolio](https://github.com/rlatkd/portfolio)

</details>

<details>
  <summary>Team Projects</summary>

  - [Futsal Automatic Matching Service](https://github.com/rlatkd/match5)
  - [Internet Banking System](https://github.com/rlatkd/hs-bank)
  - [Second-hand Auction Platform v0](https://github.com/rlatkd/ssgbay-v0)
  - [Fashion Community](https://github.com/rlatkd/fashion-community)

</details>
 
<details>
  <summary>Personal Projects</summary>

  - [SKKU QAE Ledger App](https://github.com/rlatkd/quant-ledger)
  - [Robust Payment System](https://github.com/rlatkd/rubust-payment-system)
  - [Monitoring System](https://github.com/rlatkd/monitoring-system)
  - [Real-time Chat Platform](https://github.com/rlatkd/live-chat)
  - [Customer Management System v2](https://github.com/rlatkd/management-system-v2)
  - [Second-hand Auction Platform v2](https://github.com/rlatkd/ssgbay-v2)
  - [Second-hand Auction Platform v1](https://github.com/rlatkd/ssgbay-v1)
  - [Customer Management System v1](https://github.com/rlatkd/management-system)

</details>

<details>
  <summary>Undergraduate Projects</summary>
   
  - [CT Image Reconstruction](https://github.com/rlatkd/ct-image-reconstruction)

</details>

## etc

<details>
  <summary>TIL</summary>
  
  - [1day-1commit](https://github.com/rlatkd/1day-1commit)
  - [Kafka Streams](https://github.com/rlatkd/kafka-streams)
  - [Mybatis & JPA](https://github.com/rlatkd/mybatis-jpa)
  - [GitLab Runner](https://github.com/rlatkd/gitlab-runner)
  - [JDBC](https://github.com/rlatkd/jdbc)
  - [Design Pattern](https://github.com/rlatkd/design-pattern)
  - [Qlik Sense Embed](https://github.com/rlatkd/qlik-embed)
  - [Qlik Sense Mashup](https://github.com/rlatkd/qlik-mashup)
  - [Dockerize](https://github.com/rlatkd/ssgbay-dockerize)
  - [CI/CD](https://github.com/rlatkd/cicd-react)
  - [Terraform](https://github.com/rlatkd/terraform)

</details>
