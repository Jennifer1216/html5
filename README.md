# touch事件实现手机轮播
- 主要运用了touchstart,touchmove,touchend并采用事件监听实现效果
- 此效果只能在手机端才能正常显示，因此电脑观看时，请开启手机模拟器
- 手机端显示时，需在head标签中加上
```html
  <meta name="viewport" content="width=device-width,initial-scale=1,minimum-scale=1,maximum-scale=1,user-scalable=no" />
```
- 另外，为实现不同手机，不同屏幕自适应，你可以加上下面这段脚本代码
```javascript
 document.getElementsByTagName("html")[0].style.fontSize = document.documentElement.clientWidth/3 + "px";

```
