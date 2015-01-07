# 圆角边框：border-radius

## 介绍

绘制圆角的矩形

##补充

border-top-left-radius 绘制对象左上角圆角边框

border-top-right-radius 绘制对象右上角圆角边框

border-bottom-left-radius 绘制对象左下角圆角边框

border-bottom-right-radius 绘制对象右下角圆角边框

例：为div元素添加圆角

```javascript
div
{
text-align:center;
border:4px solid #a1a1a1;
padding:20px 40px;
background:#dddddd;
width:260px;
border-radius:20px;
-moz-border-radius:20px; /* 老的 Firefox */
}
```