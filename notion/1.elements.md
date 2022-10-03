### Elements의 특징

* immutable (불변성)

한번 생성된 Element는 변하지 않는다. 즉, Element 생성 후에는 children이나 attributes를 바꿀 수 없다.

![image](https://user-images.githubusercontent.com/88424067/193163403-7f68f528-15cc-47a9-b78c-cb2f06150e62.png)

화면 변화를 필요로 할 때는 새로운 Element를 만들어 보여주면 된다.

![image](https://user-images.githubusercontent.com/88424067/193163475-24eb9fb0-9b7b-4398-a707-6013acd23da4.png)

VirtualDOM은 어떤 부분이 달라졌는지 검사하고 달라진 부분에 대해서만 새로운 Element를 생성해 변경해준다.

### Elemets 렌더링 하기

![image](https://user-images.githubusercontent.com/88424067/193163655-ae7816ed-de98-49ad-b8d7-ca59ff5e4712.png)

실제 Browser DOM에 존재하는 Root DOM Node에 모든 Element가 표현되게 된다.

![image](https://user-images.githubusercontent.com/88424067/193163766-067e6824-dfc6-47d8-8e40-fc5dd8af46c6.png)

![image](https://user-images.githubusercontent.com/88424067/193163881-ea250c8f-3296-4851-99a1-eb206d72e485.png)

위의 예시에서 tick 함수를 매초 호출하게 된다. 매초 새로운 Element를 생성되고 기존 Element와 교체된다.
