## React Component

![image](https://user-images.githubusercontent.com/88424067/193166017-7589c4d3-ce2c-460b-a980-cb9972564115.png)

속성을 넣으면 해당 속성에 맞는 Element를 만들어준다. [붕어빵을 생각해보면 편하다]

![image](https://user-images.githubusercontent.com/88424067/193166108-81fc3aa6-7748-4915-b0ce-dfbdb9eab44a.png)

클래스와 인스턴스의 관계와 동일하다 볼 수 있다.

## Props (Property)

Component에 전달할 다양한 정보를 담고 있는 javascript 객체이다. [붕어빵에 넣는 재료라고 생각해보면 편하겠다]

![image](https://user-images.githubusercontent.com/88424067/193166253-9b743570-beca-48b7-b61a-bda8e0d891b5.png)

Airbnb의 홈페이지에 Component 예시를 보자

![image](https://user-images.githubusercontent.com/88424067/193166416-831d4e4b-0349-4960-bd31-6afb47a11620.png)

### Props의 특징

**READ-ONLY**

값을 변경할 수 없다. [붕어빵이 다 구어진 이후에 속재료를 바꿀 수 없다]

### 그렇다면 다른 Props 값으로 Element를 생성하려면 어떻게 해야할까?

새로운 값을 컴포넌트에 전달하여 새로운 Element를 생성해준다.

모든 리액트 컴포넌트는 Props를 직접 바꿀 수 없고 같은 Props에 대해서는 항상 같은 결과를 보여줄 것! 이라고 React Docs에 적혀있다.

## Component 만들기

![image](https://user-images.githubusercontent.com/88424067/193179482-3ce0cc7e-6894-4d0c-a8f1-e03442213f2d.png)

function component를 주로 사용한다. (hook)

### Function Component

![image](https://user-images.githubusercontent.com/88424067/193179657-c5312cb8-a01b-419e-ae34-ec9145a18917.png)

### Class Component

![image](https://user-images.githubusercontent.com/88424067/193179726-96e03770-d890-4431-a5ba-7cea28a5707c.png)

React.Component를 상속받아서 만들게 된다.

### Component의 이름

**항상 첫 글자는 대문자**

![image](https://user-images.githubusercontent.com/88424067/193187969-c4a8bc5d-4bf2-42e7-98eb-843098064577.png)

Welcome이 아니라 welcome이었다면, react는 component가 아니라 DOM tag로 인식하게 된다.

### Component 렌더링

Component로 부터 생성된 Element가 화면에 보여지는 것이지 Component가 직접 렌더링 되는게 아니다.

![image](https://user-images.githubusercontent.com/88424067/193188333-07a33959-8d60-4ecc-b473-89156aaf2404.png)
