# 伪类选择器：E:root

匹配文档的根元素，在HTML中，根元素永远是HTML。

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
:root
{
background:#35b558;
}
</style>
</head>
<body>

<h1>标题-极客学院</h1>
<p>第一行</p>
<p>第二行</p>
<p>第三行。</p>

</body>
</html>
```