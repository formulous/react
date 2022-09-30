# react

### react도 결국 HTML, CSS, JavaScript 다.

JSX - 개발자 친화적인 conponent 구성을 위해 react에서 만든 문법

ex)
```javascript
return (
  <button onClick={() => this.setState({liked: true})}>
    Like
  </button>
)
// JSX가 아래와 같이 변경해주어 웹에서 해석할 수 있게됨
// => return React.createElement('button', {onClick: () => this.setState({liked: true})}, 'Like');
```

* 위와 같은 JSX 문법을 해석하기 위해 script의 type에 text/babel을 추가해준다.

```html
<script type="text/babel">
  ReactDOM.render(<LikeButton/>, document.querySelector('#root')); // React 17 version code
  ReactDOM.createRoot(document.querySelector('#root')).render(<LikeButton/>); // React 18 version code
</script>
```

----------------------------------------------------------------------------------------------------------
### JSX

javascript의 확장 문법 -> javaScript + XML + HTML
간결한 코드, 가독성 향상, 보안 향상

```javascript
const element = <h1>hello, world!</h1>;
```

CreateAlement => JSX를 javascript로 변환해 줌

![image](https://user-images.githubusercontent.com/88424067/193163059-233b95a0-32a9-46d1-9e0f-f1fbe8bd5bb2.png)

### element

웹 사이트를 구성하는 요소의 가장 작은 단위

![image](https://user-images.githubusercontent.com/88424067/193162731-25fa483a-8ed2-42cf-94a2-74eee74aa6c3.png)

`React Elements는 DOM Elemet를 가상 표현한다` 라고 생각하면 된다. (자바스크립트 객체 형태로 존재한다) 

예시) ![image](https://user-images.githubusercontent.com/88424067/193163042-c098b014-318c-4914-9365-ef80e29d1487.png)


실제로 React Element는 DOM Element보다 훨씬 가벼우며 실제 웹 페이지에 표현 될 때에만 DOM Element로 표현되게 된다.

