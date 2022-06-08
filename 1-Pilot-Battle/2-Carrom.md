# Carrom

![Carrom](./images/2-carrom.jpeg)

```html
<div id="w">
  <div id="b1"></div>
  <div id="b2"></div>
  <div id="b3"></div>
  <div id="b4"></div>
</div>
<style>
  body {
    background: #62374e;
    margin: 0;
  }
  #w {
    width: 300px;
    height: 200px;
    margin: 50px;
    position: relative;
  }
  #w > * {
    position: absolute;
    width: 50px;
    height: 50px;
    background: #fdc57b;
  }
  #b2,
  #b4 {
    right: 0;
  }
  #b3,
  #b4 {
    bottom: 0;
  }
</style>
```
