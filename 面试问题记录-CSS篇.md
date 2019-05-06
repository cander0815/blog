# 子元素在父元素中水平垂直居中

> 这个问题可以从几个方面来考虑, 子元素是行内元素还是块状元素, 子元素是否确定宽高等

以下代码是以以下HTML代码为基础书写:

```html
<style>
* {
	margin: 0;
	padding: 0;
}

.wrap {
  width: 100px;
  height: 100px;
  margin: 30px auto;
  background: red;
}

.child {
  background: green;
}

</style>
<div class="wrap">
	<div class="child"></div>
</div>

```


1. 子元素是行内元素时, 父元素使用文字居中(text-algin)
