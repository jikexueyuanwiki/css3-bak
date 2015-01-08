# 阴影属性：box-shadow

## 介绍

为对象添加阴影

## 语法

```
box-shadow: h-shadow v-shadow blur spread color inset;
```


例：为div元素添加阴影

```javascript
div
{
width:200px;
height:200px;
background-color:#35b558;
-moz-box-shadow: 20px 10px 5px #888888; /* 老的 Firefox */
box-shadow: 10px 20px 5px #888888;
}
```