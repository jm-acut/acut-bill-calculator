# acut-bill-calculator

<!DOCTYPE html>
<html>
<head>
  <title>Electricity Bill Calculator</title>
<style>

table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
  }
  table {
  width: 100%;
  } th, td {
  padding: 15px; 
  text-align: center; }


</style>
</head>
<body> 
  <h1>Electricity Bill Calculator</h1>

 
<form>
   
    <label for="day"> Month:</label>
    <input type="number" id="cost" name="cost"><br><br>
  
    
    <label for="consumption">Power Consumption (kWh):</label>
    <input type="number" id="consumption" name="consumption"><br><br>

    
    <label for="cost">Cost per kilowatt-hour:</label>
    <input type="number" id="cost" name="cost"><br><br>
    
    
    <input type="submit" value="Calculate">
</form>

 
  <h2>Result:</p>

<table style="width:100%">
    
<tr>
    <th>Month</th>
    <th>Power Consumption</th>
    <th>Cost Per kwh</th>
    <th>Result</th>
</tr>
<tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
</tr>
<tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
</tr>
<tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
</tr>
<tr>
    <td></td>
    <td></td>
    <td></td>
    <td></td>
</tr>
</table>

</body>
</html>
