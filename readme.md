# Scroller

## Getting start

```js
var scrollerImage = new window.scroller(window, document, document.getElementById("scroller_image"), 2600, false);

setInterval(function(){
    scrollerImage.flush_all();
}, 100);
```
