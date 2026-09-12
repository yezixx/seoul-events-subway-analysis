# 서울시 행사와 지하철 이용 패턴 분석

2025년 서울시 체육시설 공연·행사 정보와 서울교통공사 지하철 승하차 데이터를 활용하여, 행사에 따른 지하철 이용 패턴의 변화와 역별 특성을 분석한 데이터 분석 프로젝트입니다.

## 🔗 Project Link

* [Google Colab 분석 노트북](https://colab.research.google.com/drive/1Xb089oIyJ-WIa_TrNYqV0uBzKMdTbcuJ?usp=sharing)

## 📌 Analysis

* 행사일과 비행사일의 시간대별 지하철 이용 패턴 비교
* K-Means를 활용한 지하철역 이용 패턴 군집화
* Z-score, LOF, DBSCAN을 활용한 이상치 탐지
* 행사장 인접 역별 행사 영향 비교

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## 📊 Key Findings

* 지하철역은 이용 패턴에 따라 주거형, 업무지구형, 상업형, 관광·환승형 등으로 구분할 수 있었습니다.
* 행사 영향은 역마다 다르게 나타났으며, 특히 종합운동장역에서 대규모 행사 전후의 이용량 변화가 두드러졌습니다.
* 행사 여부뿐 아니라 행사 규모, 집객력, 요일 등 다양한 요인이 지하철 이용 패턴에 영향을 미치는 것으로 분석했습니다.
