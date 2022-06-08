# Ups n Down

![Ups n Down](./images/4-ups-n-down.jpeg)

```html
<div id="w">
  <div></div>
  <div></div>
  <div></div>
</div>
<style>
  body {
    margin: 0;
    background: #62306d;
    padding: 50px;
  }
  #w {
    width: 300px;
    height: 200px;
    display: flex;
  }
  #w > * {
    background: #f7ec7d;
    width: 100px;
    height: 100px;
    border-radius: 50% 50% 0 0;
  }
  #w > div:nth-child(2n + 1) {
    align-self: flex-end;
    transform: rotate(180deg);
  }
</style>
```
