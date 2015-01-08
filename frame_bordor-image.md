# 图片边框：border-image

## 介绍

使用图片来创建边框

## 语法

```
border-image：<border-image-source> || <border-image-slice> [ / <border-image-width>? [ / <border-image-outset> ]? ]? || <border-image-repeat>
``

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
div
{
border:15px solid transparent;
width:300px;
padding:10px 20px;
}

#round
{
-moz-border-image:url(http://a1.jikexueyuan.com/home/201412/22/a4de/5498065379467.png) 30 30 round; /* Old Firefox */
-webkit-border-image:url(http://a1.jikexueyuan.com/home/201412/22/a4de/5498065379467.png) 30 30 round; /* Safari and Chrome */
-o-border-image:url(/i/border.png) 30 30 round; /* Opera */
border-image:url(/i/border.png) 30 30 round;
}

#stretch
{
-moz-border-image:url(/i/border.png) 30 30 stretch; /* Old Firefox */
-webkit-border-image:url(/i/border.png) 30 30 stretch; /* Safari and Chrome */
-o-border-image:url(/i/border.png) 30 30 stretch; /* Opera */
border-image:url(/i/border.png) 30 30 stretch;
}
</style>
</head>
<body>

<div id="round">在这里，图片铺满整个边框。</div>
<br>
<div id="stretch">在这里，图片被拉伸以填充该区域。</div>

<p>这是我们使用的图片：</p>
<img src="/i/border.png">

<p><b>注释：</b> Internet Explorer 不支持 border-image 属性。</p>
<p>border-image 属性规定了用作边框的图片。</p>

</body>
</html>
```