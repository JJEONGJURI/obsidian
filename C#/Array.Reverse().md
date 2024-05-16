string.ToArray()
	-> string을 배열로 변환
Array.Reverse()
	-> 문자열 배열의 순서 뒤집기
new string()
	-> 문자열로 변환

string str = "Hello world";
char[] charArr = str.ToArray();
Array.Reverse(charArr);
string newStr = new string(charArr);
Console.WriteLine(newStr);

>> dlrow olleH