# Unit10: Problem1

<!DOCTYPE html>
<html>

<head>
	<meta charset="UTF-8">
	<title> Unit 10 Assignment </title>
	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
	<script>
		$(document).ready(function()
		{
			 $(".btn1").click(function()
			 {
			  		$("div").animate({height: "100px"});
			 });
		});
	</script>
</head>

<body>
	<button class="btn1">Change Height</button>

	<div style="background:#98bf21; height:200px; width:600px;">Hello World</div>
</body>
</html>
