# CodeAlpha
<html lang="en">
<head>
    <title>Temperature Conversion</title>
    <!--Google font-->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Mono:wght@500&display=swap" rel="stylesheet">
    <!--Stylesheet-->
    <link rel="stylesheet" href="temp.css">
</head>
<body>
    <div class="wrapper">
        <div class="container">
            <label for="celsius">Celsius</label>
            <input type="number" id="celsius" oninput= "celToFar()" oninput = "kelToCel()">
            
        </div>
        <div class="container">
            <label for="fahrenheit">Fahrenheit    </label>
            <input type="number" id="fahrenheit" oninput = "farToCel()">
            
        </div>
        <div class="container">
            <label for="kelvin">   kelvin</label>
            <input type="number" id="kelvin" oninput = "kelToCel()">
        </div>
    </div>
    <script src="temp1.js"></script>
</body>
</html>
