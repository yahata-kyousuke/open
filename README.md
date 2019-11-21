<html>
<head>
<meta charset="UTF-8">
<script>
function clickBtn(){
  alert("テストですこんにちは\(語彙力\)");
  var str = document.getElementById("spell");
  document.getElementById("spell") = str;
}
</script>
</head>
<body>
<h1 style="color:green;font-size:60px;">テストだけど？</h1>
<br/>
<input type="button" value="ぶっとん" onclick="clickBtn()">
<p id="spell"></p>
</body>
</html>
