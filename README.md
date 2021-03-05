Crawling Project
===========

프로젝트 주제
---------- 
- Top 3 호텔 플랫폼 내 상품 크롤링

프로젝트 목적
---------- 
- 주요 호텔 플랫폼들의 호텔 정보를 한 곳에 취합하여, 원하는 조건의 호텔룸의 최저가 상품을 빠르게 확인 및 결제까지 하도록 도움

사이트 소개
--------

1. 야놀자

![야놀자](https://user-images.githubusercontent.com/78460759/110055723-d82d0300-7da0-11eb-877d-a83ba73f8dc1.png)

2. 데일리호텔 

![데일리호텔](https://user-images.githubusercontent.com/78460759/110056001-54bfe180-7da1-11eb-8bce-b215f0b46096.png)


3. 여기어때

![여기어때](https://user-images.githubusercontent.com/78460759/110055902-2c37e780-7da1-11eb-84ec-e4fa4a6f6a80.png)


물리적 시나리오 
---------
1. spider.py를 통해 만든 각 호텔 module 생성


2. 크론탭 설정하여 설정한 주기 (ex. 20분)마다 모듈 실행


3. 3사의 호텔정보를 mongodb database에 저장(overwrite)


4. flask를 통한 웹페이지 서비스 구현

Member / Role
---------
- 임현수 :
- 최민권 :
