# 기업 평가 제공 서비스 호갱끼데스까 API서버

### 툴: Ruby on Rails 5 API
### API:  네이버 뉴스검색 API
#### 설명: 스마트폰으로 특정 제품의 바코드를 찍으면 해당 제품의 회사의 이름과 함께, 부정적 단어(세금/사건/논란/체불/기소)와 긍정적 단어(봉사/기부/공헌/감동/혁신)가 같이 검색되어 그 중 가장 많은 양의 뉴스가 검색된 키워드 기반 뉴스들을 사용자에게 보여준다.

ex) 

‘오뚜기 세금’ => 216건 검색

‘오뚜기 봉사’ => 957건 검색

‘오뚜기 기부’ => 987건 검색

가장 많이 검색된 ‘오뚜기 기부’ 키워드 관련 뉴스들을 사용자에게 보여준다.

* 네이버 뉴스 검색 API을 활용해 ‘좋은 기업’ / ‘나쁜 기업’ 구별 기능
* 뉴스 사진 크롤링 기능 (네이버 뉴스 API에서 이미지 미제공)
* 리액트 / iOS 프론트엔드와 연동 완료
