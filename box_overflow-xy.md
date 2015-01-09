# 盒模型：overflow-x/overflow-y

## 介绍

如果内容溢出元素内容区域，是否对内容的左/右边缘进行裁剪。

## 语法

```
overflow-x ： visible | auto | hidden | scroll

overflow-y ： visible | auto | hidden | scroll
```

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
div
{
width:110px;
height:110px;
border:thin solid black;
overflow-x:hidden;
overflow-y:hidden;
}
</style>
</head>
<body>

<div><p style="width:140px">
在线教育平台。在线教育平台。
在线教育平台。在线教育平台。
在线教育平台。在线教育平台。
在线教育平台。在线教育平台。
在线教育平台。在线教育平台。
</p></div>

</body>
</html>
```

> 注：Overflow-x 是否对内容的左/右边缘进行裁剪。
> 
　　  Overflow-y 是否对内容的上/下边缘进行裁剪。
