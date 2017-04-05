# wjy-js
js school

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>IFE JavaScript Task 01</title>
  </head>
<body>

  <label>请输入您的姓名：<input id="aqi-input" type="text"></label>
  <button id="button" onclick="show()">确认填写</button>

  <div>您的姓名是：<span id="aqi-display">尚无录入</span></div>

<script type="text/javascript">

 function show () {
  	var x=document.getElementById('aqi-input').value;
  	document.getElementById('aqi-display').innerText=x;
  	//document.getElementById('aqi-display').innerHTML=x; innerHTML能达到同样的效果
  }//function
</script>

</body>
</html>

