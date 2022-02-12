# [Project] 신용카드 고객 이탈 분석 (Predict Churning Customers)

## **신용카드 고객 이탈 분석 모델 개발**

### 과제 목표

신용카드 이용 고객 데이터를 활용한 고객 이탈 예측 모델 개발

### 분석결과 활용 프로세스

고객 이탈에 있어 어떠한 요소가 크게 작용하는지 분석 후 고객 이탈 방지

### 현황

신규 고객 유입보다는 기존 고객의 이탈을 방지함으로써 고객 수 유지 필요

### 문제점

이탈 고객 분류가 제대로 이루어지지 않아 이탈 가능성이 있는 고객을 제대로 구분해내지 못하는 중

### 분석 내용

1. 이탈 / 비이탈 고객 분류
   - Logistic Regression, RandomForest, XGBoost을 이용한 모델 구축
   - 데이터 불균형 처리를 위해 SMOTE 기법 적용
2. 사용카드 선택에 있어 가장 많은 영향을 끼치는 고객 특성 선정
3. 결과 도출

### 기대효과

- 기존에 분류하지 못했던 숨은 이탈 고객을 분류하여 분류 원인 발견 가능
- 이탈 가능성이 있는 고객의 상황과 이탈 이유를 분석하여 향상된 고객서비스 제공
- 다양한 카드 서비스 제공을 위한 고객 특성 분석 및 희망 서비스 예측 가능

### 필요 데이터

신용카드 고객 데이터 (https://www.kaggle.com/sakshigoyal7/credit-card-customers)