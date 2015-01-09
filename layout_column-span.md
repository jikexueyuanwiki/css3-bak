# 跨列属性：column-span

## 介绍

设置元素是否横跨所有列

##  语法

```
column-span: 1|all;
```

例：设置div中文本横跨所有列

```javscript
div
{
-moz-column-span:all; /* Firefox */
-webkit-column-span:all; /* Safari 和 Chrome */
column-column-span:all;
}
```

## 浏览器支持

Internet Explorer 10 和 Opera 支持 column-span 属性。

Safari 和 Chrome 支持替代的 -webkit-column-span 属性。

> 注：Internet Explorer 9 以及更早版本的浏览器不支持 column-span 属性。