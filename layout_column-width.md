# 列宽属性：column-width

## 介绍

设置对象每列的宽度

## 语法

```
column-width: auto|length;
```

例：

```javascript
<!DOCTYPE html>
<html lang="zh-cn">
<head>
<meta charset="utf-8" />
<title>CSS column-width_CSS参考手册_web前端开发参考手册系列</title>
<style>
body{font:14px/1.5 georgia,serif,sans-serif;}
p{margin:0;padding:5px 10px;background:#eee;}
h1{margin:10px 0;font-size:16px;}
.test{
width:628px;
border:10px solid #000;
-moz-column-width:200px;
-moz-column-count:3;
-webkit-column-width:200px;
-webkit-column-count:3;
column-width:200px;
column-count:3;
}
.test2{
border:10px solid #000;
-moz-column-width:200px;
-webkit-column-width:200px;
column-width:200px;
}
.test3{
border:10px solid #000;
-moz-column-count:5;
-webkit-column-count:5;
column-count:5;
}
</style>
</head>
<body>
<h1>列数及列宽固定:</h1>
<div class="test">
<p>This module describes multi-column layout in CSS. By using functionality described in this document, style sheets can declare that the content of an element is to be laid out in multiple columns. </p>
<p>On the Web, tables have also been used to describe multi-column layouts. The main benefit of using CSS-based columns is flexibility; content can flow from one column to another, and the number of columns can vary depending on the size of the viewport. Removing presentation table markup from documents allows them to more easily be presented on various output devices including speech synthesizers and small mobile devices.</p>
</div>
<h1>列宽固定，根据容器宽度液态分布列数:</h1>
<div class="test2">
<p>This module describes multi-column layout in CSS. By using functionality described in this document, style sheets can declare that the content of an element is to be laid out in multiple columns. </p>
<p>On the Web, tables have also been used to describe multi-column layouts. The main benefit of using CSS-based columns is flexibility; content can flow from one column to another, and the number of columns can vary depending on the size of the viewport. Removing presentation table markup from documents allows them to more easily be presented on various output devices including speech synthesizers and small mobile devices.</p>
</div>
<h1>列数固定，根据容器宽度液态分布列宽:</h1>
<div class="test3">
<p>This module describes multi-column layout in CSS. By using functionality described in this document, style sheets can declare that the content of an element is to be laid out in multiple columns. </p>
<p>On the Web, tables have also been used to describe multi-column layouts. The main benefit of using CSS-based columns is flexibility; content can flow from one column to another, and the number of columns can vary depending on the size of the viewport. Removing presentation table markup from documents allows them to more easily be presented on various output devices including speech synthesizers and small mobile devices.</p>
</div>
</body>
</html>
</style>
``