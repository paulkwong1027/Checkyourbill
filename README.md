<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Energy Impact Awareness Calculator</title>
<script>
function showFixedCost() {
    // Set the cost to a fixed value to illustrate the impact
    var fixedCost = 4199.2e9; // This represents HK$4199.2 billion
    document.getElementById('totalCost').value = `HK$ ${fixedCost.toLocaleString()}`;
    
    // Display the alert message to the user
    alert("No matter how little or how much energy you think you use, the collective environmental impact is immense. The energy cost we are facing together is a staggering HK$4199.2 billion, which reflects the scale of the challenge ahead of us.");
}
</script>
</head>
<body>

<h2>Energy Impact Awareness</h2>

<p>Enter your estimated energy consumption below to see the collective environmental impact.</p>

<label for="consumption">Your estimated energy consumption (in degrees):</label><br>
<input type="number" id="consumption" placeholder="Energy in degrees"><br><br>

<button onclick="showFixedCost()">Calculate Impact</button><br><br>

<label for="totalCost">Collective Environmental Impact Cost (HK$):</label><br>
<input type="text" id="totalCost" readonly><br>

</body>
</html>
