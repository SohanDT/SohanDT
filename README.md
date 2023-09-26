<!DOCTYPE html>
<html>
<head>
    <title>Temperature Converter</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <h1>Temperature Converter</h1>
    <div class="converter">
        <input type="number" id="inputTemp" placeholder="Enter temperature">
        <select id="unitFrom">
            <option value="celsius">Celsius</option>
            <option value="fahrenheit">Fahrenheit</option>
        </select>
        <span>to</span>
        <select id="unitTo">
            <option value="celsius">Celsius</option>
            <option value="fahrenheit">Fahrenheit</option>
        </select>
        <button id="convertBtn">Convert</button>
        <p id="result"></p>
    </div>
    <script src="script.js"></script>
</body>
</html>
