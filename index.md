<html> 
<head> 
<script type="text/javascript">
var i=0;
function t1(){
var arr=
["https://s2.ax1x.com/2020/01/10/lfX7tO.jpg","https://s2.ax1x.com/2020/01/10/lhZysP.jpg","https://s2.ax1x.com/2020/01/09/lWQDTf.jpg"];
var bottom = document.getElementById('zhengti');
if(i==arr.length){
i=0;
}
bottom.src=(arr[i++]);
}
</script>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8"> 
<title>hello world</title> 
</head> 
<body> 
<p>I WILL UPDATE SOME LABEL IN HERE </p>
<ul>
  <li> <a href="https://www.baidu.com/">百度</a> </li>
  <li> <a href="https://www.163.com/">网易</a> </li>
</ul>
<form action="test2.html">
<table>
<tr>
  <td>USERNAME:</td>
  <td><input type="text" name="username"><br></td>
</tr>
<tr>
<td>PASSWORD:</td>
<td><input type="password" name="password"></td>
</tr>
</table>
<p><input type="submit" value="CONFIRM"></p>
</form>
<div id="buttom">
<input type="button" value="切换背景" onclick="t1();"/>
</div>
<div style="position:absolute; width:100%; height:100%; z-index:-1; left:0; top:0;"> 
<img id="zhengti" src="https://s2.ax1x.com/2020/01/09/lWJnSO.jpg" height="100%" width="100%" style="left:0; top:0;"> 
</div> 
</body> 
</html>
