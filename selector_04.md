# 属性选择器：E[attr^="value"]

指选择attr属性值以“value”开头的所有元素，换句话说，选择的属性其以对应的属性值是以“value”开始的.

例：

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
<style type="text/css">
p[title^="val"] {color:#FF0000;}
</style>
</head>
<body>
<div style="width:733px; border: 1px solid #666; padding:5px;">
<p title="value">匹配具有att属性、且值以val开头的E元素</p>
</div>
</body>
</html>
```