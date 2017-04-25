
<!DOCTYPE html>
<html lang="en">
<head>
<title>Fun With Tables</title>
<meta charset="utf-8">

<style>
table	{margin: auto;
	width: 200px;}

thead	{background-color: #eaeaea;}

tbody	{font-family: Arial, sans-serif;
	 font-size: .90em;}

tbody td {border-bottom: 1px #000033 dashed;
	  padding-left: 25px;}


caption {font-size: 2em;
         font-weight: bold;}

tfoot	{background-color: #eaeaea;
	 font-weight: bold;
	 text-align: center;}

#day	{font-weight: bold;}

#hours	{font-weight: bold;}

</style>

</head>
<body>




<h6>Page 343 - Figure 8.12</h6>

<table>
<caption>Time Sheet</caption>
<thead>
<tr>
	<th id="day">Day</th>
	<th id="hours">Hours</th>
</tr>
</thead>
<tbody>

<tr>
	<td headers="day">Monday</td>
	<td headers="hours">4</td>
</tr>
<tr>
	<td headers="day">Tuesday</td>
	<td headers="hours">3</td>
</tr>

<tr>
	<td headers="day">Wednesday</td>
	<td headers="hours">5</td>
</td>
</tr>
<tr>
	<td headers="day">Thursday</td>
	<td headers="hours">3</td>
</tr>
<tr>
	<td headers="day">Friday</td>
	<td headers="hours">3</td>
</tr>

</tbody>
<tfoot>
<tr>
	<td headers="day">Total</td>
	<td headers="hours">18</td>
</tr>
</tfoot>
</table>

</body>
</html>
