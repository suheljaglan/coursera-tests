<!DOCTYPE html>
<html>
<head>
	<title>Floating element</title>
	<style type="text/css">
		div{
			background-color:lightgreen;
		}
		p{
			width: 50px;
			height: 50px;
			border:1px solid black;
			margin-right: 5px;
		}
		#p1{
			background-color: maroon;
            float:left<!-- -->;
		}
		#p2{
			background-color: pink;
            float:left;
		}
		#p3{
			background-color: grey;
            float:left;
		}
		#p4{
			background-color: orange;
            float:left;
		}
	</style>
</head>
<body>

	<h1>Floating Element</h1>
	<div>
	<p id="p1"></p>
	<p id="p2"></p>
	<p id="p3"></p>
	<p id="p4"></p>
    <section>This is regular content containing after the paragraph boxes</section>
</div>
</body>
</html>
