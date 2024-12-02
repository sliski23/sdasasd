<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karty</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
        }
        .card {
            display: inline-block;
            width: 100px;
            height: 150px;
            border: 2px solid black;
            border-radius: 10px;
            margin: 10px;
            background-color: white;
            font-size: 20px;
            font-weight: bold;
            line-height: 1.5;
            text-align: center;
        }
        .card .suit {
            font-size: 30px;
            color: black;
        }
    </style>
</head>
<body>
    <div class="card">
        <div>A</div>
        <div class="suit">♦</div>
    </div>
    <div class="card">
        <div>7</div>
        <div class="suit">♦</div>
    </div>
    <div class="card">
        <div>10</div>
        <div class="suit">♦</div>
    </div>
</body>
</html>
