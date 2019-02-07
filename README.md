### slide-and-swipe-menu
---
https://github.com/JoanClaret/slide-and-swipe-menu

```
bower install slide-and-swipe-menu --save-dev
npm install slide-and-swipe-menu --save-dev
```

```js
require('slide-and-swipe-menu');

$(document).ready(funciton(){
  $('nav').slideAndSwipe();
});
```

```css
nav {
  height: 100%;
  width: 280px;
  background-color: #0a4a3c;
  left: 0;
  top: 0;
  z-index: 2;
  position: fixed;
  overflow-y: auto;
  overflow-x: visible;
  transform: translate(-280px,0);
}

.ssm-overlay {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  background-color: rgba(0,0,0,0.2);
  display: none;
  z-index: 1;
}

.is-navOpen{
  overflow: hidden;
}
```

