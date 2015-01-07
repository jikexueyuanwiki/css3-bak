# 结构性伪类选择器：E:empty

匹配没有任何子元素（包括text节点）的元素E

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
p:empty
{
width:100px;
height:20px;
background:#35b558;
}
</style>
</head>
<body>

<h1>标题-极客学院</h1>
<p>第一行</p>
<p></p>
<p>第二行</p>
<p>第三行</p>
<p>第四行</p>

</body>
</html>
```