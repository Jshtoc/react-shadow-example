# 리액트 새도우

```javascript
npm i react-shadow 설치


import root from "react-shadow";

function App() {
  return (
    <root.div> // 이렇게 감싸준다.
      <div className="App">
        <header className="App-header">
          <img src={logo} className="App-logo" alt="logo" />
          <p>
            Edit <code>src/App.js</code> and save to reload.
          </p>
          <a
            className="App-link"
            href="https://reactjs.org"
            target="_blank"
            rel="noopener noreferrer"
          >
            Learn React
          </a>
        </header>
      </div>
      // 스타일을 따로 위에서 설정하여 이곳에만 해당하는 새도우 스타일을 지정할 수 있다.
      <style type="text/css">{styles}</style>
    </root.div>
  );
}

```
