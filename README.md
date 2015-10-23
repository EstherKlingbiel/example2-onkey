# example2-onkey
<!DOCTYPE HTML>
<html>
<head>
<title>Javascript: onkeydown, onkeyup</title>

<style type="text/css">
	
	body 
	{
		background-color: rgb(102, 255, 255);
	}

</style>
</head>

<body>

		<input type="text" id="demo">

		<script type="text/javascript">
			console.log('javascript is working')

		function down() 
		{
			document.getElementById("demo").style.border= "thick solid red"
		}

		document.getElementById("demo").onkeydown = function()
		{
			down();
		}

		function up()
		{
			document.getElementById("demo").style.border= "thick solid orange"
		}

		document.getElementById("demo").onkeyup = function()
		{
			up();
		}



		</script>


</body>
