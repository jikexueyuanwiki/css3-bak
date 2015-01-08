# UI元素状态伪类选择器：E:checked

匹配所有用户界面（form表单）中处于选中状态的元素E

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
input:checked
{
background:#ff0000;
}
</style>
</head>
<body>

<form action="">
<input type="radio" checked="checked" value="male" name="gender" /> Male<br>
<input type="radio" value="female" name="gender" /> Female<br>
<input type="checkbox" checked="checked" value="Bike" /> I have a bike<br>
<input type="checkbox" value="Car" /> I have a car
</form>

</body>
</html>
```

> 注：由于只有Opera支持，本例只在 Opera 中正确工作。

