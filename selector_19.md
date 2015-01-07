# UI元素状态伪类选择器：E::selection

匹配E元素中被用户选中或处于高亮状态的部分

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
::selection
{
color:#ff0000;
}
::-moz-selection
{
color:#ff0000;
}
</style>
</head>
<body>

<h1>请试着选取页面上的文本</h1>

<p>一行文字一行文字</p>

<div>这是 div 元素中的文本。</div>

<br>

<a href="http://www.jikexueyuan.com" target="_blank">访问 极客学院</a>

</body>
</html>
```