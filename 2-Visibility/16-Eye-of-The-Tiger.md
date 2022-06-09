# Eye of The Tiger

![Eye of The Tiger](./images/16-eye-of-the-tiger.jpeg)

```html
<div id="oc"></div>
<div id="c"></div>
<style>
  body {
    background: #0b2429;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  #oc {
    transform: rotate(45deg);
    background: #998235;
    width: 200px;
    height: 200px;
    border-radius: 50% 0;
    position: relative;
  }
  #c {
    position: absolute;
    width: 140px;
    height: 140px;
    background: #f3ac3c;
    border: 20px solid #0b2429;
  }
  #c,
  #c:after {
    border-radius: 50%;
  }
  #c:after {
    content: "";
    position: absolute;
    width: 50px;
    height: 50px;
    background: #0b2429;
    top: 45px;
    left: 45px;
  }
</style>
```
