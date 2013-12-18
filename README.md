<html>
<head>
<script>
function myFunction()

{     if (document.getElementById("mehr").style.display == "none"){
document.getElementById("mehr").style.display = "block";
}else { document.getElementById("mehr").style.display = "none";}}
</script>
</head>
<body>
<a href="javascript:myFunction()">Text einblenden</a>
	<div id="mehr"style="display:none;">
	<p>This is some text.</p>
</div>
</body>
</html>

