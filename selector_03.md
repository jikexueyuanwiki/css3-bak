#属性选择器：E[attr~="value"]

可根据属性值中的词列表的某个词来进行选择元素，选择器是属性值是一个或多个词列表，如果是列表时，他们需要用空格隔开，只要属性值中有一个value相匹配就可以选中该元素，而我们前面所讲的`E[attr="value"]`是属性值需要完全匹配才会被选中，两者区别就是一个有“〜”号，一个没有“〜”号。

例：title 属性中包含单词 "jike" 的图片会获得红色边框。

```javascript
<!DOCTYPE html>
<html>
<head>
<style>
[title~=jike]
{
border:5px solid red;
}
</style>
</head>
<body>

<p>title 属性中包含单词 "jike" 的图片会获得红色边框。</p>

<img src="http://a1.jikexueyuan.com/home/201412/21/21df/5496e376f33c7.jpg" title="jike xueyuan" />
<br />
<img src="http://a1.jikexueyuan.com/home/201412/21/21df/5496e376f33c7.jpg" title="egret" />

</body>
</html>
```

> 注：对于 IE8 及更早版本的浏览器中的 [attribute~=value]，必须声明 <!DOCTYPE>。
