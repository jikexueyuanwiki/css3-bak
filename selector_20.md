# 目标伪类：E:target

匹配相关URL指向的E元素

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
:target
{
border: 2px solid #D4D4D4;
background-color: #e5eecc;
}
</style>
</head>
<body>

<h1>这是标题</h1>

<p><a href="#news1">显示第一行</a></p>
<p><a href="#news2">显示第二行</a></p>

<p>请点击上面的链接，:target 选择器会突出显示当前活动的 HTML 锚点。</p>

<p id="news1"><b>第一行...</b></p>
<p id="news2"><b>第二行...</b></p>

</body>
</html>
```

> 注：</b> Internet Explorer 8 以及更早的版本不支持 :target 选择器。
