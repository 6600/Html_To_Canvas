# Html_To_Canvas
将整个页面或者页面中的某个元素写到Canvas中
首先引入js
<script type="text/javascript" src="htmlToCanvas.js"></script>
使用方法:
<script type="text/javascript">
	htmlToCanvas(document.getElementById("box")).then(function(canvas) {
		document.body.appendChild(canvas);
	});
</script>
