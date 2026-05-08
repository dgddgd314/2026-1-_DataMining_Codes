# 2026-1-_DataMining_Codes

산업공학과 전공 선택 <데이터마이닝> 알고리즘 학습 및 발표 자료 저장소입니다. 

### 01. Logistic Regression
로지스틱 회귀의 수식 도출과 손실 함수 최적화 과정을 다룬 1차 발표 분량입니다.
- PPTImageMaker.ipynb: 슬라이드 사이사이에 들어간 이미지들을 생성한 파일
- PenguinClassification.ipynb: Palmer Penguins 데이터셋 분류 실습

### 02. Neural Network
퍼셉트론의 수학적 증명 및 다층신경망 MLP, 그리고 initialization, optimizer, normalization 등을 다룬 2차 발표 분량입니다.
- DM_HW2.ipynb: 슬라이드 사이사이에 들어간 이미지들(보통 수학적 함수 설명)을 생성한 파일
- Moon_dataset_(DM_HW2).ipynb: Moon Dataset을 바탕으로 진행한 신경망 학습 실습

---

## 🛠 Tech Stack
- **Language**: Python 3.11.3
- **Libraries**: 
  - `Scikit-learn`: 머신러닝 모델 구축
  - `Statsmodels`: 통계적 추론 및 p-value 확인
  - `Matplotlib`, `Seaborn`: 데이터 시각화 및 지형도 모델링
  - `Pandas`, `Numpy`: 데이터 전처리 및 수치 계산
 
---

## 📝 Usage
각 폴더의 `.py` 혹은 `.ipynb` 파일을 실행하여 분석 결과와 그래프를 확인할 수 있습니다. 
01. LR에서 데이터셋은 `Seaborn` 라이브러리의 내장 데이터(`penguins`)를 사용합니다.
02. NN에서 데이터셋은 `sklearn` 라이브러리의 내장 데이터(`make_moons`)를 사용합니다.
