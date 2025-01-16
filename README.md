# 🕹️ Multivariate Statistical Analysis for Optimal Pokémon Team Formation

## 📖 Overview
최적의 포켓몬 조합을 찾아라! 

이 프로젝트는 다변량통계분석 수업의 일환으로, 포켓몬 월드챔피언십과 같은 e스포츠 대회에서 약점을 분석하여 최적의 포켓몬 팀 조합을 탐색하는 프로젝트입니다. 군집분석과 통계적 방법론을 활용하여 상성과 능력치를 고려한 이상적인 팀 구성을 제안했습니다.

---

## 🗓️ Period
2023년 9월 ~ 2023년 12월 (3개월)

---

## 👥 Team
장예진, 주고은

---

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![K-Means Clustering](https://img.shields.io/badge/K%2DMeans%20Clustering-blue?style=for-the-badge) ![Dendrogram](https://img.shields.io/badge/Dendrogram-orange?style=for-the-badge)

---

## 🧑‍💻 Key Task
1. **데이터 수집**
   - Kaggle에서 포켓몬 데이터셋(32개 컬럼, 801개 데이터) 활용

2. **데이터 전처리**
   - `Type2`의 결측치를 '없음'으로 대체
   - 상성 변수(`against_*`)와 능력치(`Base_total`, `Attack`, `Defense` 등)를 중심으로 분석

3. **군집 분석**
   - 팔꿈치 그래프와 실루엣 계수를 사용하여 K값을 5로 설정
   - K-means 클러스터링을 통해 5개의 군집으로 분류
   - 각 군집의 특성을 분석하여 상성과 타입을 파악

4. **최적의 팀 조합 도출**
   - 각 군집에서 약점 점수가 적은 포켓몬을 선정하여 최적의 조합 구성:
     - 거북왕(물), 핫삼(벌레/강철), 리자몽(불/비행), 메타그로스(강철/에스퍼), 루카리오(격투/강철)
   - 역할 기반 조합도 추가 생성:
     - Physical Sweeper, Special Sweeper, Mixed Sweeper, Tanker

5. **시각화**
   - 덴드로그램과 워드 클라우드를 통해 분석 결과를 시각화

---

## 🌟 Retrospective
이번 프로젝트를 통해 군집분석과 데이터 시각화의 효용성을 체감할 수 있었습니다. 상성과 능력치를 고려한 데이터 분석이 단순히 높은 능력치를 가진 포켓몬을 선택하는 것보다 훨씬 효율적인 조합을 도출할 수 있음을 확인했습니다.  
또한, 포켓몬의 성격, 특성, 소지품 등의 추가 변수를 반영한다면 분석의 정밀도를 더욱 높일 수 있음을 깨달았습니다. 머신러닝 모델을 통한 가상의 배틀 시뮬레이션은 향후 연구 과제로 남았습니다.
