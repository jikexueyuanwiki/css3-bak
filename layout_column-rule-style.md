# 边框样式属性:column-rule-style

## 介绍

设置对象的边框样式为实线、虚线、隐藏等样式

## 语法

```
column-rule-style: none|hidden|dotted|dashed|solid|double|groove|ridge|inset|outset;
```

例：设置对象的边框样式为实线

```javascript
div
{
-moz-column-rule-style:solid; /* Firefox */
-webkit-column-rule-style:solid; /* Safari 和 Chrome */
column-rule-style:solid;
}
```

## 浏览器支持

Internet Explorer 10 和 Opera 支持 column-rule-style 属性。

Firefox 支持替代的 -moz-column-rule-style 属性。

Safari 和 Chrome 支持替代的 -webkit-column-rule-style 属性。

> 注：Internet Explorer 9 以及更早版本的浏览器不支持 column-rule-style 属性。