# StringTokenizer_JAVA
Explanation about how to use StringTokenizer with JAVA coding

String msg = input.nextLine();
		StringTokenizer st = new StringTokenizer(msg, "/");	// 토큰: 하나의 문장으로부터 분할한 한 덩어리(문자를 분할한 단위) (단어별로 나누고 싶으면 이용)
		while(st.hasMoreTokens())		//토큰이 되어 여기 들어옴 => 그 다음 문장이 또 있느냐(지정할 토큰이 있냐)
		{
			String temp = st.nextToken();	//
			System.out.println(temp);
		}
