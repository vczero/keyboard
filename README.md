模拟数字键盘
----

###一、起由
	（1）目前虚拟键盘需要输入小数点，需要切换键盘；
	（2）不同设备上存在兼容性。
	
	
###二、用法
	（1）new KeyBoard(inputElement);
	（2）禁用软键盘，添加readonly="readonly"属性；
	（3）Demo如下
		<!DOCTYPE html>
		<html>
		<head>
			<meta charset="utf-8" />
			<title>模拟数字键盘</title>
			<meta name="viewport" content="width=device-width, initial-scale=1.0, 
			maximum-scale=1.0, minimum-scale=1.0, minimal-ui" />
		</head>
		<body>
			<div>
				<input id="text1" readonly="readonly" style="height:28px;width:98%;outline:none;
				border:1px solid #1AB6FF;padding-left:3px;"/>
				<br />
				<br />
				<input id="text2" readonly="readonly"  style="height:28px;width:98%;
				outline:none;border:1px solid #1AB6FF;padding-left:3px;"/>
			</div>
			<script type="text/javascript" src="keyboard.js"></script>
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
		</body>
		</html>
		
###三、二维码
![222](erweima.png)
