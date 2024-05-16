배열을 직접 'Console.WriteLine()'에 전달하면 배열의 형식이 출력되며, 배열의 내용이 출력되지 않는다. 배열의 내용을 출력하려면 문자열로 변환해야 한다.

string a = "00010010-01010011";
char[] a.bit = data.ToCharArray();
Console.WriteLine(a_bit);

![[Pasted image 20240516114641.png]]

배열에 포함된 실제 문자를 출력하려면 문자 배열을 문자열로 변환해야 한다. 이를 위해 `string` 생성자를 사용할 수 있다.

string a = "00010010-01010011";
char[] a.bit = data.ToCharArray();
Console.WriteLine(new string(a_bit));
