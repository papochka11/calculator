# calculator
<!DOCTYPE html>
<html>
<head>
	<title>calculator</title>
	<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet">
<link rel="stylesheet" type="text/css" href="calculator.css">
</head>
<body>
	<table class="calculator">
		<tbody>
			<tr class="Calculator__output">
				<td colspan="4">0</td>
			</tr>
			<tr>
				<td class="Calculator_numb">7</td>
				<td class="Calculator_numb">8</td>
				<td class="Calculator_numb">9</td>
				<td class="Calculator_fun">/</td>
			</tr>
			<tr>
				<td class="Calculator_numb">4</td>
				<td class="Calculator_numb">5</td>
				<td class="Calculator_numb">6</td>
				<td class="Calculator_fun">*</td>
			</tr>
			<tr>
				<td class="Calculator_numb">1</td>
				<td class="Calculator_numb">2</td>
				<td class="Calculator_numb">3</td>
				<td class="Calculator_fun">-</td>
			</tr>
			<tr>
				<td class="Calculator_numb" colspan="3">0</td>
				<td class="Calculator_fun">+</td>
			</tr>
			<tr>
				<td class="Calculator_enter" colspan="4">=</td>
			</tr>
		</tbody>
	</table>
</body>
</html>
////////////////////////
html, body, table {
	width: 100%;
	height: 100%;
	margin: 0;
	padding: 0;
}

td {
	text-align: center;
}

.Calculator {
	font-family: Roboto;
	font-size: 32px;
	font-weight: 700;
}

.Calculator__oupput {
	background-color: black;
	color: white;
}

.Calculator_enter {
	background-color: #f1f1f1;
}

.Calculator_fun {
	background-color: #ff9800;
	color: white;
}

.Calculator_numb {
	background-color: #555555;
	color: white;
}
