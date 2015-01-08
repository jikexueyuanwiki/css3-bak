# 伪类选择器：nth-last-child()

规定属于其父元素的第二个子元素的每个 p 元素，从最后一个子元素开始计数

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
p:nth-last-child(2)
{
background:#35b558;
}
</style>
</head>
<body>

<h1>标题-极客学院</h1>
<p>第一行</p>
<p>第二行</p>
<p>第三行</p>

</body>
</html>
```