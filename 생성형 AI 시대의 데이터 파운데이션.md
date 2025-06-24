# 생성형 AI 시대의 데이터 파운데이션: 데이터에서 지능으로, 혁신을 만드는 게임 체인저

## 어한나 (Solutions Architect, AWS)

삼성중공업 담당

### 데이터 파운데이션

Gen-AI를 위해서 필요함

what is data foundation?

- What: 조직 차원의 데이터 전략
- Who: 조직의 데이터와 데이터 실무자 중심
- Why: 빠르고 신뢰할 수 있는 데이터 기반의 의사결정
- How: 포괄적, 통합적, 체계적으로 관리되는 도구와 솔루션

Data foundation of AWS

포괄적인, 통합된, 거버넌스

“The data flywheel”

사람 + 프로세스 + 기술 ⇒ 세 가지 요소를 통해 개발 진행

이런 선순환 구조를 통해 비즈니스 및 기술 측면에서 이점 존재

- 비즈니스: 데이터 신뢰성 확보, 수익화 구현, 유연한 비즈니스 전환
- 기술: 검색/발견 용이, 접근성 강화, 명확한 가이드라인 제시로 인해 데이터 재사용 증가 → 효율성 증가

데이터 라는 것이, 각 기업이 가지는 차별점이다 → 이걸 어떻게 사용하느냐가 중요

비정형 데이터의 추가가 가장 중요한 부분 → 80% 이상의 데이터가 비정형, 갈수록 비율 증가

메타데이터를 활용해야 하나, 이걸 만드는 것이 쉽지 않음

비정형 데이터의 데이터 프로세싱

- AI 서비스를 활용하여 비정형 데이터에서부터 메타데이터 추출
- 이렇게 추출된 메타데이터를 활용하여, 카탈로그화 하여 검색 시 용이하도록 보조

벡터 데이터 관리

- tokenization → vectorization → vector DB → vector similarity
- 벡터 검색은 Amazon OpenSearch Service로 진행됨

다양한 DB Source(SQL & No-SQL)으로부터 데이터를 통합해야 함 → 한 곳에서 수집/관리를 위해 Amazon Redshift 사용

- 문제: pipeline이 복잡해짐 → Zero-ETL: directly copy the targeted data

Data Governance - data security & quality

범용 데이터 프로세싱

최적화된 데이터 저장소

향상된 데이터 통합

포괄적 데이터 거버넌스

⇒ 위 네 가지 요소를 만족해야, 효율적인 개발 가능

### Amazon.com

팀이 수십개다 보니, 데이터가 silo화 되어 있는 등 데이터 관리에 문제

- 데이터 사일로 해소
    - 모든 사일로를 연결 및 데이터 카탈로그 구축
- 데이터 품질 향상
- 데이터 보안 및 거버넌스

효과: 재무 사이클 개선, 직원 생산성 향상, 분석가 업무 환경 혁신

Amazon SageMaker: Amazon’s Data foundation platform

- Unified Studio → 서로 다른 AI 기능이 필요한 경우, 별도 시스템에 각각 접속할 필요 없이, 하나에만 접속
    - Amazon Q(programming chatbot)
    - SQL을 잘 몰라도, 원하는 데이터 추출 및 분석 가능
- Unified Studio를 통해 서로 직무가 다른 사람들끼리도 원활한 소통 및 협업 가능
- Why? → data analysis is inevitable in using AI