# jquery-qrcode-plus

在[jquery-qrcode](https://github.com/jeromeetienne/jquery-qrcode "jquery-qrcode")的基础上 增加 自定义 

**logo** **bleed** **radius** **shadow** 

![](https://github.com/mayiyahei1992/jquery-qrcode-plus/blob/master/1.png?raw=true)


```javascript
$("#qrcode").qrcode({
  render: "canvas",
  text: "http://www.ganbare.top",
  width : "300", 
  height : "300", 
  background : "#fff",
  foreground : "#000", 
  src: '/logo.png',
  imgRadius:10,
  bleed:0.14,
  imgRadius:10,
  bleed:0.14,
  imgBorder:true,
  imgBorderColor:'#ffc107'
});
```
