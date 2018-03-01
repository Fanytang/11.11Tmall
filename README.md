# 11.11Tmall
采用rem实现移动端双十一页面
Js设置HTML的font size
```
<script type="text/javascript">
	(function() {
		if(window.screen.width > 750) {
			document.querySelector('html').style.fontSize = 100 + 'px';
		} else {
			document.querySelector('html').style.fontSize = window.screen.width / 7.5 + 'px';
		}
	})();
	window.onresize=function(){
		if (window.screen.width>750) {
			document.querySelector('html').style.fontSize=100+'px';
		}
		else{document.querySelector('html').style.fontSize =window.screen.width/7.5+'px';}
	}
</script>
```
