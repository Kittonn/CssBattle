# Cloaked Spirits

![Cloaked Spirits](./images/10-cloaked-spirits.jpeg)

```html
<div id="w">
  <div id="b"><div id="c"></div></div>
  <div id="b"><div id="c"></div></div>
  <div id="b"><div id="c"></div></div>
</div>
<style>
  body {
    margin: 0;
    background: #62306d;
  }
  #w {
    width: 300px;
    height: 250px;
    margin: 50px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
  }
  #b {
    width: 100px;
    height: 100px;
    background: #f7ec7d;
    position: relative;
  }
  #b:nth-child(2n) {
    height: 200px;
  }
  #b:nth-child(2n) > * {
    background: #aa445f;
    border: 20px solid #e38f66;
  }
  #c {
    top: -50px;
    position: absolute;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background: #e38f66;
    border: 20px solid #aa445f;
  }
</style>
```
