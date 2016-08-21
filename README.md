# Html_To_Canvas
将整个页面或者页面中的某个元素写到Canvas中

<body>
	<div id="box">
		<h1>HTML保存为Canvas:</h1>
		<div id="content">这里是<strong>主要内容</strong>区域</div>
	</div>
	<h1>下面是画板:</h1>
	
	<script type="text/javascript" src="htmlToCanvas.js"></script>
	<script type="text/javascript">
		htmlToCanvas(document.getElementById("box")).then(function(canvas) {
			document.body.appendChild(canvas);
		});
	</script>
</body>
