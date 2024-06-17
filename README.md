<h1 align="center"> 🍅 오뚜기 데이터를 활용한 <br> 심리검사 기반 오뚜기 식품 추천 서비스 </h1>
<h4 align="center"> 2023 숙명여대 BIGDATA/AI 해커톤 인기상 수상 🏅 </h4>

## Introduction
**대회 소개**
- 대회명: 2023 숙명여대 BIGDATA/AI 해커톤
- 대회 기간: 2023.09.22 ~ 2023.09.23
- 주최: 숙명여대 캠퍼스타운 사업단, AWS
- 참가자: 숙명여대, 서울대, 고려대, 연세대, 상명대에서 총 18개팀 76명 참여

**프로젝트 소개**
- 주제: 오뚜기 데이터를 활용한 심리검사 기반 음식 추천 서비스 개발 
- 목적: 오뚜기의 신제품을 효과적으로 홍보하기 위해, 소비자의 흥미를 유발하는 심리검사를 통한 상품 추천 서비스를 제공하고자 함 
- 데이터 출처 및 제공
    - 오뚜기 제공 리뷰 데이터 기반 상품 데이터
    - 오뚜기 공식 사이트 크롤링을 통한 오뚜기 상품 데이터
- 참여자
    - [송지빈](https://github.com/jibin86)
    - [정다운](https://github.com/daunJJ)
    - [정재원](https://github.com/havehill) 

## Content 
**데이터 수집** 
- 오뚜기 공식 사이트 Crawling

**데이터 전처리**
- [오뚜기 제공 리뷰 데이터 상품 추출](https://github.com/daunJJ/Streamlit_Hackathon/blob/main/Code_Analysis/ottogi_sales_EDA.ipynb)
- [오뚜기 공식 사이트 크롤링 데이터와 매핑](https://github.com/daunJJ/Streamlit_Hackathon/blob/main/Code_Analysis/ottogi_crawling_EDA.ipynb)

**추천 모델링**
- 심리검사용 질문과 답변 카테고리 생성
- [심리검사 답변과 오뚜기 상품 매핑 (GPT Prompt Engineering)](https://github.com/daunJJ/Streamlit_Hackathon/blob/main/Code_Analysis/Categorize_PromptEngineering.ipynb)
- [코사인 유사도 기반 추천 알고리즘 구현 ](https://github.com/daunJJ/Streamlit_Hackathon/blob/main/Code_Analysis/similarity_recommend.ipynb)

**웹 개발**
- Figma를 이용한 UX 디자인
- [Streamlit을 이용한 웹 프론트 개발](https://github.com/daunJJ/Streamlit_Hackathon/blob/main/Code_Web/streamlit_web.py)

## Presentation
[<img src="https://github.com/daunJJ/Streamlit_Hackathon/assets/109944763/a77acb84-040d-42c3-81c7-9e929b8833b4" width="450"/>](https://github.com/daunJJ/Streamlit_Hackathon/blob/main/Presentation/Streamlit%ED%95%B4%EC%BB%A4%ED%86%A4_%EC%98%81%EC%83%81%EC%A0%9C%EC%99%B8.pdf)
