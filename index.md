<html>
<head>
<meta charset="utf-8">
<title>Testing Webpage</title>
<h1> WELCOME </h1>
<p>HELLO !!! THIS IS A TEST WEBPAGE</p>
<script type="text/javascript">
var i=0;
function t1(){
var arr=
['url(https://s2.ax1x.com/2020/01/09/lWJnSO.jpg)','url(https://s2.ax1x.com/2020/01/10/lfX7tO.jpg)','url(https://s2.ax1x.com/2020/01/10/lfXfXR.jpg','url(https://s2.ax1x.com/2020/01/09/lWQDTf.jpg)'];
var bottom = document.getElementById('zhengti');
if(i==arr.length){
i=0;
}
bottom.style.backgroundImage = (arr[i++]);
}
</script>
</head>
<body id="zhengti" background="https://s2.ax1x.com/2020/01/09/lWQDTf.jpg" >
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
</body>
</html>
