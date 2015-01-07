# 伪类选择器：E:nth-child(n)

匹配父元素中的第n个子元素E

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
p:nth-child(2)
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

> 注：</b>Internet Explorer 不支持 :nth-child() 选择器。
```