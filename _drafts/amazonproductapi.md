---
---



[https://www.sitepoint.com/amazon-product-api-exploration-lets-build-a-product-search/]


##아마존 지역 정보 포함한 사이트
amazon production api  contain locale, about url and what is avabable
[https://docs.aws.amazon.com/ko_kr/AWSECommerceService/latest/DG/AnatomyOfaRESTRequest.html]


##opreation api
아마존 api 기능

1. item-search : 제목, 범주, 제조업체 가격과같은 특정 매개 변수로 항목을 검색하며 하나 이상의 항목을 반환.
2. item-lookup : ASIN or ISBN (for book) 으로 검색하여 한의 항목에 대해 반환  
3. similarity-lookup ㅣ 요청한 항목과 비슷한 항목들을 반환
4. cart-create : 원격쇼핑 할수 있도록 아마존서버에 장바구니 생성
5. cart-add : 원격으로 장바구니에 담음


##response group
항목에대한 반환 옵션

1. small :  return basic information (about item, asin, title ,group)
2. review : review iframe
3. offer-summary: 조건에대한 가장 낮은 가격 반환
3. item-attributes (속성) :  all the attributes


##broewnode
상품에대한 구체적인 카테고리
[http://www.findbrowsenodes.com/]
example) book -> history -> african

##locale-information
[https://docs.aws.amazon.com/ko_kr/AWSECommerceService/latest/DG/localevalues.html]

지역마다 모든 데이터와 항목이 다르다