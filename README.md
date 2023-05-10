
## 요구사항 정리
    Customer는 주소와 상품명 정보를 가지고 있고 Deliver 클래스에 배달을 요청
    Deliver 클래스는 Customer 클래스의 주소와 주문한 상품의 상품명을 판별한 후
    일치하면 배달 후 배달완료 메세지 발생

## -클래스
### * Application
    메인 메소드
### * Deliver :
    isRightProduct() :
    전달받은 상품명이 일치하는지 판별
    isRightAddres() :
    전달받은 주소가 정확한지  판별
    completeDeliver() :
    주소와 상품명이 모두 일치할 경우 배달완료 메시
    지(주소와 상품명도 같이 출력)를 출력
    
    
### * Customer :
    -Order() : 
    Deliver클래스에 배달을 요청 
    -Product() : 
    문자열 상품명을 저장
    -Addres() : 
    문자열 주소를 저장



