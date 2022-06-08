# Missing Slice
![Missing Slice](./images/6-missing-slice.jpeg)
```html
<div w>
  <div p></div>
  <div p r></div>
  <div p b></div>
</div>
<style>
  body {
    background: #e3516e;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  [w] {
    width: 200px;
    height: 200px;
    position: relative;
  }
  [p] {
    position: absolute;
    background: #51b5a9;
    width: 100px;
    height: 100px;
    border-radius: 100px 0 0 0;
  }
  [r] {
    right: 0;
    transform: rotate(90deg);
    background: #fade8b;
  }
  [b] {
    bottom: 0;
    transform: rotate(270deg);
    background: #f7f3d7;
  }
</style>
```
