# 结构性伪类选择器：E:first-of-type

匹配同级兄弟元素中的第一个E元素

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
p:first-of-type
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