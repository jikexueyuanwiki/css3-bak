# 否定伪类： E:not(s)

匹配所有不匹配简单选择符s的元素E

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
p
{
color:#000000;
}
:not(p)
{
color:#ff0000;
}
</style>
</head>
<body>

<h1>这是标题</h1>

<p>第一行</p>

<p>第二行</p>

<div>这是 div 元素中的文本。</div>

<br>

<a href="http://www.jikexueyuan.com" target="_blank">访问 极客学院</a>

</body>
</html>
```