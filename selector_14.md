# 结构性伪类选择器：E:only-child

匹配属于父元素中唯一子元素的E

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
p:last-child
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