# 多背景属性：multiple background

## 介绍

复合属性，设置对象的多重背景图像（背景色background-color不能设置多重）

## 语法

```
background ： [background-image] | [background-origin] | [background-clip] | [background-repeat] | [background-size] | [background-position]
```

例：

```javascript
<!DOCTYPE html>
<html >
<head>
<style>
.test{
height:300px;
background:url(http://s1.jikexueyuan.com/current/static/images/logo.png) no-repeat scroll 10px 20px,url(http://s1.jikexueyuan.com/current/static/images/logo.png) no-repeat scroll 50px 60px,url(http://s1.jikexueyuan.com/current/static/images/logo.png) no-repeat scroll 90px 100px;
background-origin:content-box;
background-clip:padding-box;
background-size:100px 120px;
}
</style>
</head>
<body>
<div class="test">定义多重背景图像</div>
</body>
</html>
```