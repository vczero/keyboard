模拟数字键盘
----
```
<script type="text/javascript">
(function(){
	var input1 = document.getElementById('text1');
	var input2 = document.getElementById('text2');

	input1.onclick = function(){
		new KeyBoard(input1);
	};

	input2.onclick = function(){
		new KeyBoard(input2);
	};

})();
</script>
```
