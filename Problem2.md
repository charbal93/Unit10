<!DOCTYPE html>
<html>
	<head>
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>

		<script>
			$(document).ready(function()
			{
 				$("#btn1").click(function()
 				{
        			$("p").append(" <b>Appended text</b>.");
    			});
    			$("#btn2").click(function()
    			{
        			$("ol").append("<li>Appended item</li>");
    			});
			});
		</script>
	</head

	<body>
		<p>This is a paragraph.</p>
		<p>This is another paragraph.</p>

		<ol>
			<li>List Item 1</li>
			<li>List Item 2</li>
			<li>List Item 3</li>
		</ol>

		<button id="btn1">Append Text</button>
		<button id="btn2">Append list items</button>
	</body>
</html>
