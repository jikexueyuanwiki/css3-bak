# 盒模型：overflow-style

## 介绍

规定溢出元素的首选滚动方法。

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
div
{
width:150px;
height:50px;
border:thin solid black;
overflow:hidden;
overflow-style:marquee,panner;
}
</style>
</head>
<body>

<div>
在线教育平台。在线教育平台。
在线教育平台。在线教育平台。
在线教育平台。在线教育平台。
在线教育平台。在线教育平台。
在线教育平台。在线教育平台。
</div>

<p>overflow-style 属性规定溢出元素的首选滚动方法。</p>

</body>
</html>
```

> 注：目前没有浏览器支持 overflow-style 属性。