# Acid Rain
![Acid Rain](./images/5-acid-rain.jpeg)
```html
<div w>
  <div b c></div>
  <div c m></div>
  <div t c></div>
</div>
<style>
  body {
    background: #0b2429;
    justify-content: center;
    align-items: center;
    display: flex;
  }
  [w] {
    height: 240px;
    width: 240px;
    position: relative;
  }
  [c] {
    position: absolute;
    background: #f3ac3c;
    width: 120px;
    height: 120px;
    border-radius: 50% 0 50% 50%;
  }
  [m] {
    z-index: 2;
    background: #998235;
    top: 60px;
    left: 60px;
  }
  [b] {
    z-index: 3;
    bottom: 0;
  }
  [t] {
    z-index: 1;
    right: 0;
    transform: rotate(180deg);
  }
</style>
```
