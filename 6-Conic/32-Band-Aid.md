# Band Aid

![Band Aid]()

```html
<div id="b1"></div>
<div id="b2"></div>
<style>
  body {
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    background: #ffffff;
  }
  div {
    width: 200px;
    height: 50px;
    position: absolute;
  }
  #b1 {
    background: linear-gradient(
      90deg,
      #f3ac3c 75px,
      #fbe18c 75px 125px,
      #f3ac3c 125px 200px
    );
    transform: rotate(45deg);
  }
  #b2 {
    background: linear-gradient(
      90deg,
      #a3a368 75px,
      #fbe18c 75px 125px,
      #a3a368 125px 200px
    );
    transform: rotate(-45deg);
  }
</style>
```
