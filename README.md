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

```javascript
<script type="text/babel">
  ReactDOM.render(<LikeButton/>, document.querySelector('#root')); // React 17 version code
  ReactDOM.createRoot(document.querySelector('#root')).render(<LikeButton/>); // React 18 version code
</script>
```
