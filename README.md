#   [다나눠]

###  팀명: Five Men(FM)

###  🤯팀장: 윤영현(FE, Server, AI)

###  👨‍👨‍👦‍👦팀원:  전병규(BE, AI), 길훈성(DB, AI), 이석기(, AI)

### 1. 프로젝트 개요👉🏻  


	🚩주제 : 다나와 가격 비교 서비스에서 최저가 상품 분류 시스템의 자동화
	🚩개요 : 
		1.  사람이 검색을 통해 비슷한 상품을 찾고 직접 그룹에 넣어주는 현재의 방식보다는 자동화 방안이 필요하다.    
		2.  상품명, 이미지, 가격, 제조사, 브랜드 등의 상품정보를 통해 비슷한 상품을 80%이상의 정확도로 자동링크하는 시스템을 개발한다.
    

### 2. 프로젝트 주요 기능💡

    
    상품 분류 기능🔍
	    - 상품 데이터를 전처리하여 분류하는 모델을 생성한다.
	    - 모델을 통해 유사도가 높은 상품들끼리 그룹화한다.
	    
	최저가 리스트🧾
	    - 제휴마켓별 상품의 최저가를 오름차순으로 나타낸다.
	    - 최저가 리스트에서 각 Row는 해당 마켓의 상품으로 연결되는 링크이다.
    
    
### 3. 기대효과🙊

    - 상품 분류 시스템 성능 향상
    - 분류작업의 인력 감소
    

### 4. 구현 기능📦

     - 상품 최저가 리스트 페이지
     - 최저가 링크
     - AI 모델학습

### 5. 기술 스택📚 

####    

    <Backend>  
     - Spring boot
     - maria-db
     
####

	<A.I>
	- Python
	- TensorFlow
    - Numpy
    - Pandas
    - Word2Vec
    - Word Mover's Distance
    - Correlation

####    

    <Server>  
     - AWS
     - Docker