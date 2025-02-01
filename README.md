<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Water Usage Monitoring system</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <h1>Water Usage Monitoring system</h1>
    <p> This webpage allows you in calculating and suggests you measures in how you can reduce your water usage</p>

    <hr>
    <div class="container">
        <form>
        
        </form>
            <label for="shower">Shower Usage (in liters):</label>
            <input type="number" id="shower" name="shower" placeholder="Shower" required>
            <br>
            <label for="washing">Washing (in liters):</label>
            <input type="number" id="washing" name="washing" placeholder="Washing" required>
<br>
            <label for="cooking">Cooking (in liters):</label>
            <input type="number" id="cooking" name="cooking" placeholder="Cooking " required>
<Br>
            <label for="gardening">Gardening (in liters):</label>
            <input type="number" id="gardening" name="gardening" placeholder="Gardening " required>
            <hr>
<br>
            <button type="button" onclick="calculateUsage()">Calculate Water Usage</button>
        </form>

        <div class="result">
            <h3 id="total-usage">Total Water Used: 0 liters</h3>
            <div id="usage-suggestions"></div>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
