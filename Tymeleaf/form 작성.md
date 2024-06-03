https://middleearth.tistory.com/20

보통 POST 요청을 위해 사용된다.

th:action="@{url}"   -> 어떤 URL로 보낼지 명시
th:object="${객체}" -> 어떤 객체가 값을 받게 될지 명시

Controller에서 GET 요청할때 똑같은 이름으로 객체를 매개변수 처리 해줘야함 -> GET에 미리 보내지 않으면 템플릿 엔진 에러 발생

th:if="${#fields.hasErrors()}" -> Controller에서 BindingResult에 의해 에러가 잡힐 경우 발생


