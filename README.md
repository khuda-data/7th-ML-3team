# 7th-ML-3team

🍽 Kyung Hee Univ. Restaurant Recommendation System

이 프로젝트는 사용자의 취향을 반영하여 최적의 맛집을 추천하는 시스템입니다.

경희대학교 국제캠퍼스 279곳의 음식점을 크롤링하여 사용자에게 적합한 음식점을 추천합니다.

## 📌 주요 기능
-  **음식점 데이터 크롤링 (Naver Maps)**
-  **컨텐츠 기반 추천 시스템 (Word2Vec)**
-  **XGBoost 모델을 활용한 평점 예측**
-  **Streamlit을 활용한 음식점 추천**

## 폴더 구조
┣ 📂 1_crawling_data # 크롤링한 데이터 저장 폴더

┣ 📂 2_pre_EDA # 전처리 된 데이터 파일과 EDA 파일

┣ 📂 3_model # XGBoost 기반 모델 소스 코드와 성능 검증 시각화

┣ 📜 4_recommendation # Word2Vec 기반 추천 시스템 소스 코드와 데이터 파일

┗ 📜 README.md # 프로젝트 설명 파일
