# UI元素状态伪类选择器：E:enabled

匹配所有用户界面（form表单）中处于可用状态的E元素

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
input[type="text"]:enabled
{
background:#ffff00;
}
input[type="text"]:disabled
{
background:#dddddd;
}
</style>
</head>
<body>

<form action="">
First name: <input type="text" value="jike" /><br>
Last name: <input type="text" value="xueyuan" /><br>
Country: <input type="text" disabled="disabled" value="Disneyland" /><br>
</form>

</body>
</html>
```