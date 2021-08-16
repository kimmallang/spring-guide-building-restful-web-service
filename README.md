## Spring boot를 사용해서 RESTful 웹 서비스 만들기

<br />

상세 설명
- https://kimmallang.blogspot.com/2021/08/restful.html

<br />

목표
- HTTP GET 요청을 수락하는 서비스를 빌드합니다

- HTTP 요청 시 다음과 같이 응답합니다.

        http://localhost:8080/greeting
         ㄴ {"id":1,"content":"Hello, World!"}
        
        http://localhost:8080/greeting?name=Kim
         ㄴ {"id":1,"content":"Hello, Kim!"}

<br />

준비물
- 좋아하는 텍스트 편집기 또는 IDE
- JDK 1.8 이상
- Gradle 4 이상 또는 Maven 3.2 이상
