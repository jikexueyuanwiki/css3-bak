# CSS3过渡

## 介绍

以在不使用 Flash 动画或 JavaScript 的情况下，当元素从一种样式变换为另一种样式时为元素添加效果

## 浏览器支持

Internet Explorer 10、Firefox、Chrome 以及 Opera 支持 transition 属性。

Safari 需要前缀 -webkit-。

> 注：Internet Explorer 9 以及更早的版本，不支持 transition 属性。
> 注：Chrome 25 以及更早的版本，需要前缀 -webkit-。

例：

```javascript
<!DOCTYPE html>
<html lang="zh-cn">
<head>
<meta charset="utf-8" />
<title></title>
<style>
h1{font-size:16px;}
.test{overflow:hidden;width:100%;margin:0;padding:0;list-style:none;}
.test li{float:left;width:100px;height:100px;margin:0 5px;border:1px solid #ddd;background-color:#eee;text-align:center;-moz-transition:background-color .5s ease-in;-webkit-transition:background-color .5s ease-in;-o-transition:background-color .5s ease-in;-ms-transition:background-color .5s ease-in;transition:background-color .5s ease-in;}
.test li:nth-child(1):hover{background-color:#bbb;}
.test li:nth-child(2):hover{background-color:#999;}
.test li:nth-child(3):hover{background-color:#630;}
.test li:nth-child(4):hover{background-color:#090;}
.test li:nth-child(5):hover{background-color:#f00;}
</style>
</head>
<body>
<h1>请用鼠标在矩形上移动：</h1>
<ul class="test">
	<li>背景色过渡</li>
	<li>背景色过渡</li>
	<li>背景色过渡</li>
	<li>背景色过渡</li>
	<li>背景色过渡</li>
</ul>
</body>
</html>
```