# mycalp1
<!DOCTYPE html>
<html>
<head>
	<title>calculator</title>
	<style>
		.c1{
			padding: 15px 15px;
			margin: 15px 15px;
			border: 1px solid green;
			background-color: yellow;
			width: 75PX;
			height: 75PX;
			font-size: 30PX;
			border-radius: 15PX;
		}

		.t
		{
			padding:20px  75px;
			border-radius:95px;
			background-color: lightgreen;
			align-items: flex-start;
			align-items: flex-start;
			font-size: 25px; 
	</style>
	<script >
		function ac() {
			document.getElementById("res").value="";
		}
		function show(input) 
		{
			document.getElementById("res").value+=input;
			
		}
		function cal() {
			let answer=eval(document.getElementById("res").value);
			document.getElementById("res").value=answer;
		}

	</script>
</head>
<body>

<table border="10" cellspacing="5PX" cellpadding="5PX" bgcolor="grey" align="center">
	<caption><h1 class="h" >MATHS ON HAND NOW<h1 cellspacing="0px"></caption>
	<tr>
		<td colspan="3" class="t1" ><input id="res" type="text" class="t" name=""></td>
		<td><button class="c1" style="background-color: red"  onmouseover="ac()">AC</button></td>
	</tr>
	<tr>
		<td align="center"><button class="c1" onclick="show('1')">1</button> </td>
		<td align="center"><button class="c1" onclick="show('2')">2</button> </td>
		<td align="center"><button class="c1" onclick="show('3')">3</button> </td>		
		<td align="center"><button class="c1" onclick="show('+')">+</button> </td>
	</tr>

	<tr>
		<td align="center"><button class="c1" onclick="show('4')">4</button> </td>
		<td align="center"><button class="c1" onclick="show('5')">5</button> </td>
		<td align="center"><button class="c1" onclick="show('6')">6</button> </td>		
		<td align="center"><button class="c1" onclick="show('-')">-</button> </td>
	</tr>

	<tr>
		<td align="center"><button class="c1" onclick="show('7')">7</button> </td>
		<td align="center"><button class="c1" onclick="show('8')">8</button> </td>
		<td align="center"><button class="c1" onclick="show('9')">9</button> </td>		
		<td align="center"><button class="c1" onclick="show('*')">*</button> </td>
	</tr>

	<tr>
		<td align="center"><button class="c1" onclick="show('0')">0</button> </td>
		<td align="center"><button class="c1" onclick="show('%')">%</button> </td>
		<td align="center"><button class="c1" onclick="show('/')">/</button> </td>		
		<td align="center"><button class="c1" onclick="cal('=')">=</button> </td>
	</tr>

		<tr>
		<td align="center"><button class="c1" onclick="show('(')">(</button> </td>
		<td align="center"><button class="c1" onclick="show(')')">)</button> </td>
		<td align="center"><button class="c1" onclick="show('.')">.</button> </td>		
		<td align="center"><button class="c1" onclick="show('**')">^</button> </td>
	</tr>
	    <td colspan="4"><center><h1 style="font-weight: 1000px;"><button class="p" type="button" onclick="f1()">PRINT</button><h1></center></td>


</table>


<script >		
	function f1(){
		print()
	}
	
</script>

</body>
</html>
