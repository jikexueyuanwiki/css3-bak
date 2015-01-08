# 尺寸属性：background-size

## 介绍

设置对象的背景图像的尺寸大小

## 语法

```
background-size: length|percentage|cover|contain;
```

例：

```javascript
<style>
h1{font-size:20px;}
h2{font-size:16px;}
p{border:10px dashed #666;width:300px;height:300px;padding:20px;background:url(http://a1.jikexueyuan.com/home/201412/03/3785/547ea8f5505a5.jpg) no-repeat;}
.cover p{background-size:cover;}
.contain p{background-size:contain;}
.length p{background-size:100px 140px;}
</style>
```