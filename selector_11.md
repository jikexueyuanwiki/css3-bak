# 伪类选择器：E:nth-last-of-type(n)

匹配同类型中的倒数第n个同级兄弟元素E

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
p:nth-last-of-type(2)
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