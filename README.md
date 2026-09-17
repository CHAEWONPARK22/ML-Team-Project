# 🫀 Heart Failure Risk Prediction

> Machine Learning Team Project

심장질환 관련 데이터를 활용하여 환자의 심장질환 위험을 분석하고,
Regression, Classification, Clustering의 세 가지 머신러닝 접근법을 적용한 프로젝트입니다.

---

## 📌 Project Overview

### Objective

환자의 기본 건강 및 생활 관련 정보를 활용하여 심장질환 위험을 분석하고,
다양한 머신러닝 기법을 통해 환자의 위험도와 질환 여부를 예측하는 것을 목표로 했습니다.

### Dataset

**Heart Failure Prediction Dataset**

- 918 samples
- 11 input features
- HeartDisease target

주요 변수:

`Age` · `Sex` · `ChestPainType` · `RestingBP` · `Cholesterol` ·  
`FastingBS` · `RestingECG` · `MaxHR` · `ExerciseAngina` · `Oldpeak` · `ST_Slope`

---

## 🛠️ Machine Learning Approaches

### 1. Regression

환자의 심장질환 위험도를 **0~1 사이의 연속적인 Risk Score**로 예측했습니다.

#### Models

- Simple Linear Regression
- Multiple Linear Regression
- Random Forest Regression

#### Analysis

- Regression Model Performance Comparison
- Actual vs. Predicted Visualization
- Feature Importance
- Permutation Importance
- Feature-Risk Score Relationship Analysis

Random Forest Regression을 활용하여 여러 변수의 관계를 반영한
위험도 예측을 수행하고, Feature Importance와 Permutation Importance를
통해 주요 변수의 영향도를 분석했습니다.

---

### 2. Classification

환자의 심장질환 여부(`HeartDisease`)를 **0/1로 분류**했습니다.

#### Models

- Perceptron
- Logistic Regression
- SVM
- Decision Tree
- Random Forest
- KNN
- LDA

Accuracy, Precision, Recall, F1-score를 활용하여 모델 성능을 비교하고,
Random Forest와 Logistic Regression의 하이퍼파라미터 튜닝 및
Feature Importance 분석을 수행했습니다.

---

### 3. Clustering

레이블 없이 환자 데이터를 특성 패턴에 따라 군집화하여
고위험군과 저위험군의 특성을 분석했습니다.

#### Models

- K-Means Clustering
- Agglomerative Clustering
- DBSCAN

Elbow Method와 Silhouette Score를 활용하여 K-Means의 군집 수를
비교하고, PCA와 t-SNE를 이용하여 군집 결과를 시각화했습니다.

또한 각 군집의 특징을 분석하여 환자 집단별 심장질환 비율과
주요 건강 지표의 차이를 확인했습니다.

---

## 👩‍💻 My Contribution

### Regression Analysis

Regression 파트를 담당하여 다음과 같은 분석을 수행했습니다.

- Regression 문제 정의
- Regression 데이터 전처리
- Standardization
- Simple Linear Regression 구현
- Multiple Linear Regression 구현
- Random Forest Regression 구현
- Regression 모델 성능 비교
- Actual vs. Predicted 시각화
- Feature Importance 분석
- Permutation Importance 분석
- Feature-Risk Score 관계 분석

---

## 📊 Key Analysis

Regression 분석에서는 단일 변수와 여러 변수를 활용한 회귀 모델을
비교하고, Random Forest Regression을 이용하여 변수의 중요도를 분석했습니다.

또한 Permutation Importance를 활용하여 테스트셋 성능을 기준으로
변수의 영향도를 추가적으로 확인했습니다.

---

## 📄 Full Project Report

자세한 데이터 전처리 과정과 Regression, Classification, Clustering
분석 결과는 전체 프로젝트 보고서에서 확인할 수 있습니다.

[📎 View Full Project Report](./docs/Machine%20Learning%20Project%20Report.pdf)

---

## 📓 Colab Notebooks

각 분석 파트별 Google Colab Notebook입니다.

| Part | Notebook |
|------|----------|
| 📈 Regression | [Open in Google Colab](https://colab.research.google.com/drive/1l7pcfuRkkYVV_h69Pmym-MEz-vOWr1jZ?usp=sharing) |
| 🎯 Classification | [Open in Google Colab](https://colab.research.google.com/drive/17rcYFTnZxEwxOPwXjxvcrc4N-XTvNe3U?usp=sharing) |
| 🔍 Clustering | [Open in Google Colab](https://colab.research.google.com/drive/1bgOtNG74EBB_z-fdCGGwxC91iDA11dma?usp=sharing) |
