# 属性选择器：E[attr="value"]

指定属性的值，可以更精确的获得自己需要的元素。

例：为带有target=“blank"的链接添加红色背景

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
a[target=_blank]
{
background-color:red;
}
</style>
</head>
<body>

<p>target="_blank" 的链接会得到红色背景：</p>

<a href="http://www.w3school.com.cn">www.jikexueyuan.com</a>
<a href="http://www.disney.com" target="_blank">http://www.jikexueyuan.com/resources/</a>
<a href="http://www.wikipedia.org" target="_top">http://www.jikexueyuan.com/vip/</a>

</body>
</html>
```

> 注：对于 IE8 及更早版本的浏览器中的 [<i>attribute</i>]，必须声明 <!DOCTYPE>。