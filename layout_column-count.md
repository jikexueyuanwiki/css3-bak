# 列数属性：column-count

## 介绍

设置对象的列数

## 语法

```
column-count: number|auto;
```

例：设置div中的文本为4列

```javascript
div
{
-moz-column-count:4; /* Firefox */
-webkit-column-count:4; /* Safari 和 Chrome */
column-count:4;
}
```

## 浏览器支持

Internet Explorer 10 和 Opera 支持 column-count 属性。

Firefox 支持替代的 -moz-column-count 属性。

Safari 和 Chrome 支持替代的 -webkit-column-count 属性。

> 注：Internet Explorer 9 以及更早版本的浏览器不支持 column-count 属性。