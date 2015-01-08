# 结构性伪类选择器：E:only-of-type

匹配属于同类型中唯一兄弟元素的E

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
p:only-of-type
{
background:#35b558;
}
</style>
</head>

<body>

<div>
<p>第一行</p>
</div>

<div>
<p>第二行</p>
<p>第三行</p>
</div>

</body>
</html>
```