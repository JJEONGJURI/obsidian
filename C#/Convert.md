#### String -> Int
Convert.ToInt32(변수명); 
	-> char형 가능.  ASCII 코드로 반환
	-> string 형 가능
	-> null 값을 0으로 반환 
int.Parse(변수명); 
	-> string 형만 가능. char형 불가
	-> 변환하려는 변수가 정수임이 확실할 때 사용
	->null값 -> System.ArgumentNullException 예외 발생

차이 : null 값 처리 방식이 다르고 / char형 변수의 사용 여부가 다르다.

#### Int -> String
Convert.ToString(변수명); -> int를 string 타입으로 변경