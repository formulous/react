## Context
기존에 props로 전달하던 데이터를 다른 방식으로 전달함 [중복 감소]

### 기존의 데이터 전달 방식
![image](https://user-images.githubusercontent.com/88424067/193982139-227d4beb-cb40-4c95-9b99-19f5892a2f37.png)

### Context 데이터 전달 방식
![image](https://user-images.githubusercontent.com/88424067/193982175-220d6acb-ca70-40eb-8820-70b24d8d93e5.png)

### 언제 Context를 사용해야 할까?
- 여러개의 Component들이 접근해야 하는 데이터 (로그인 여부, 로그인 정보, UI테마, 현재 선택된 언어 등등...)
- 하나의 props를 전달해야할 때 들어가는 deepth가 깊어지는 경우
![image](https://user-images.githubusercontent.com/88424067/193982846-5aab8be7-40ad-4ca4-a94a-b212c704f64a.png)

### Context API

