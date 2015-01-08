# CSS3 3D转换

## 介绍

使元素改变形状、尺寸和位置的一种效果。

## 浏览器支持

Internet Explorer 10 和 Firefox 支持 3D 转换。

Chrome 和 Safari 需要前缀 -webkit-。

Opera 仍然不支持 3D 转换（它只支持 2D 转换）。

## 3D转换的几种方法：

### rotateX()

使元素围绕其 X 轴以给定的度数进行旋转。

例：

```javascript
div
{
transform: rotateX(120deg);
-webkit-transform: rotateX(120deg); /* Safari 和 Chrome */
-moz-transform: rotateX(120deg); /* Firefox */
}
```

### rotateY()

使元素围绕其 Y 轴以给定的度数进行旋转。

例：

```javascript
div
{
transform: rotateY(130deg);
-webkit-transform: rotateY(130deg); /* Safari 和 Chrome */
-moz-transform: rotateY(130deg); /* Firefox */
}
```