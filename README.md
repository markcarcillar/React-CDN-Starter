# React CDN Starter
```html
<!DOCTYPE html>
<html>
<head>
  <title>Hello React</title>
</head>
<body>
  <div id="root"></div>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/babel-standalone/6.24.0/babel.js"></script>
  <script crossorigin src="https://unpkg.com/react@17/umd/react.development.js"></script>
  <script crossorigin src="https://unpkg.com/react-dom@17/umd/react-dom.development.js"></script>
  <!-- Your script here -->
  <script type="text/babel">
    const element = <h1>Hello world!</h1>;
    ReactDOM.render(
      element,
      document.querySelector('#root')
    )
  </script>
</body>
</html>
```
