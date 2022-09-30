### React Component

![image](https://user-images.githubusercontent.com/88424067/193166017-7589c4d3-ce2c-460b-a980-cb9972564115.png)

* 속성을 넣으면 해당 속성에 맞는 Element를 만들어준다. [붕어빵을 생각해보면 편하다]

![image](https://user-images.githubusercontent.com/88424067/193166108-81fc3aa6-7748-4915-b0ce-dfbdb9eab44a.png)

* 클래스와 인스턴스의 관계와 동일하다 볼 수 있다.

### Props (Property)

* Component에 전달할 다양한 정보를 담고 있는 javascript 객체이다. [붕어빵에 넣는 재료라고 생각해보면 편하겠다]

![image](https://user-images.githubusercontent.com/88424067/193166253-9b743570-beca-48b7-b61a-bda8e0d891b5.png)

* Airbnb의 홈페이지에 Component 예시를 보자

![image](https://user-images.githubusercontent.com/88424067/193166416-831d4e4b-0349-4960-bd31-6afb47a11620.png)

### Props의 특징

### READ-ONLY

값을 변경할 수 없다. [붕어빵이 다 구어진 이후에 속재료를 바꿀 수 없다]

그렇다면 다른 Props 값으로 Element를 생성하려면 어떻게 해야할까?
  새로운 값을 컴포넌트에 전달하여 새로운 Element를 생성해준다.

모든 리액트 컴포넌트는 Props를 직접 바꿀 수 없고 같은 Props에 대해서는 항상 같은 결과를 보여줄 것! 이라고 React Docs에 적혀있다. **

