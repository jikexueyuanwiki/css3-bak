# 2D变形

## 介绍

通过 CSS3 2D变形，可以对元素进行移动、缩放、转动、拉长或拉伸。

## 2D变形的几种方法：

### translate()：

使元素从其当前位置移动，指定的 left（x 坐标） 和 top（y 坐标） 

例：

```javscript
div
{
transform: translate(50px,100px);
-ms-transform: translate(50px,100px); /* IE 9 */
-webkit-transform: translate(50px,100px); /* Safari and Chrome */
-o-transform: translate(50px,100px); /* Opera */
-moz-transform: translate(50px,100px); /* Firefox */
}
```

### rotate()：

使元素顺时针旋转给定的角度。允许负值，元素将逆时针旋转。

例：

```javascript
div
{
transform: rotate(60deg);
-ms-transform: rotate(60deg); /* IE 9 */
-webkit-transform: rotate(60deg); /* Safari and Chrome */
-o-transform: rotate(60deg); /* Opera */
-moz-transform: rotate(60deg); /* Firefox */
}
```

### scale()

根据给定的宽度（X 轴）和高度（Y 轴），使元素的尺寸增加或减少。

例：

```javascript
div
{
transform: scale(1,2);
-ms-transform: scale(1,2); /* IE 9 */
-webkit-transform: scale(1,2); /* Safari 和 Chrome */
-o-transform: scale(1,2); /* Opera */
-moz-transform: scale(1,2); /* Firefox */
}
```

### skew()：

根据给定的水平线（X 轴）和垂直线（Y 轴）参数，使元素翻转给定的角度
例：

```javascript
div
{
transform: skew(30deg,20deg);
-ms-transform: skew(30deg,20deg); /* IE 9 */
-webkit-transform: skew(30deg,20deg); /* Safari and Chrome */
-o-transform: skew(30deg,20deg); /* Opera */
-moz-transform: skew(30deg,20deg); /* Firefox */
}
```

### matrix()：

把所有 2D 转换方法组合在一起，它需要六个参数，包含数学函数，允许您：旋转、缩放、移动以及倾斜元素。

例：

```javascript
div
{
transform:matrix(0.866,0.5,-0.5,0.866,0,0);
-ms-transform:matrix(0.866,0.5,-0.5,0.866,0,0); /* IE 9 */
-moz-transform:matrix(0.866,0.5,-0.5,0.866,0,0); /* Firefox */
-webkit-transform:matrix(0.866,0.5,-0.5,0.866,0,0); /* Safari and Chrome */
-o-transform:matrix(0.866,0.5,-0.5,0.866,0,0); /* Opera */
}
```