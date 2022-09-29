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
// => return React.createElement('button', {onClick: () => this.setState({liked: true})}, 'Like');
```
