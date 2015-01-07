# 属性选择器：E[attr]

为CSS3属性选择器中最简单的一种，只使用属性名，不确定任何属性值。

例：为带有target属性的链接添加红色背景

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
a[target]
{
background-color:red;
}
</style>
</head>
<body>

<p>带有 target 属性的链接会得到红色背景：</p>

<a href="http://www.w3school.com.cn">www.jikexueyuan.com</a>
<a href="http://www.disney.com" target="_blank">http://www.jikexueyuan.com/resources/</a>
<a href="http://www.wikipedia.org" target="_top">http://www.jikexueyuan.com/vip/</a>

</body>
</html>
```

> 注：对于 IE8 及更早版本的浏览器中的 [<i>attribute</i>]，必须声明 <!DOCTYPE>。