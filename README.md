### 2024 1학기 7조 프로젝트

#### 내 역할
- 백엔드/ ML 파이프라인/ AWS 서버 구성

---

### 주요 기능

1. **기록 데이터 수집 및 처리**
   - 진행된 경기 결과 및 선수 통계 데이터를 수집하고 이를 분석 가능한 형태로 처리

2. **팀 전력 분석**
   - 팀의 과거 성적, 현재 선수단의 통계, 팀의 경기 전략 등을 기반으로 팀의 전력을 분석

3. **선수 통계 분석**
   - 주요 선수들의 기록과 성적을 분석하여 그들의 기량을 평가하고 예측에 활용

4. **투수 대 타자 매칭 분석**
   - 투수와 타자 간의 매칭 기록을 분석하여 각 투수 대 타자 조합에 대한 성능을 예측

5. **경기 예측**
   - 수집된 데이터와 분석 결과를 기반으로 다가오는 경기의 결과를 예측

6. **승부 확률 제시**
   - 예측된 경기 결과에 대한 승부 확률을 제시하여 사용자에게 정보를 제공

7. **기록 업데이트**
   - 경기가 끝난 후 데이터를 업데이트하고 분석하여 사용자에게 최신 정보를 제공

---

### 부가 기능

1. **사용자 커뮤니티**
   - 사용자들 간의 토론과 의견 교환을 할 수 있는 커뮤니티 플랫폼 제공

2. **팀별 전력 시각화**
   - 팀의 시즌 전력을 시각적으로 표현하여 사용자가 팀 간의 성능을 쉽게 비교

3. **승부 및 기록 예측 성공률 제공**
   - 예측에 대한 성공률을 제공하여 사용자에게 투명성과 신뢰성 제공

---

### 시스템 아키텍처

<img src="https://github.com/shimyounseob/baseball-prediction-webservice/assets/97441805/06b8f09c-94bf-4b25-a486-73e710a41474" width="500">

### ERD

<img src="https://github.com/shimyounseob/baseball-prediction-webservice/assets/97441805/6cb5cd80-880e-455a-8d40-e6a6b2d7a0ef" width="500">

---

#### 기술 스택
- **프레임워크**: Django v4.2.13
- **웹서버**: NGINX + Gunicorn v22
- **시스템 자동화**: Airflow v2.9.1
- **ML 모델 관리**: Mlflow v2.13.1
- **운영체제**: AWS Linux 2023
- **개발언어**: Python v3.9.16
- **데이터베이스**: MySQL
- **저장소**: Amazon S3
- **CI/CD**: GitHub (CI), Github Actions (CD)
- **개발환경**: Jupyter Notebook
