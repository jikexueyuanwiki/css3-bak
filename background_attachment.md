# 内联元素背景图像平铺循环方式：background-attachment

## 介绍

设置对象的背景图像是随对象内容滚动还是固定的

## 语法

```
background-attachment：<attachment> [ , <attachment> ]*
<attachment> = fixed | local | scroll
```


例：

```javascript
<html>
<head>
<style type="text/css">
body
{
background-image:url(http://s1.jikexueyuan.com/current/static/images/logo.png);
background-repeat:no-repeat;
background-attachment:fixed
}
</style>
</head>

<body>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
<p>图像不会随页面的其余部分滚动。</p>
</body>

</html>
```