<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <title>Chiroyli Website</title>
    <style>
        body {
            margin: 0;
            font-family: Arial;
            background: linear-gradient(to right, #4facfe, #00f2fe);
            color: white;
            text-align: center;
        }

        .box {
            margin-top: 100px;
            background: rgba(0,0,0,0.3);
            padding: 30px;
            border-radius: 15px;
            display: inline-block;
        }

        h1 {
            font-size: 40px;
        }

        button {
            padding: 12px 25px;
            border: none;
            border-radius: 25px;
            background: yellow;
            color: black;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background: orange;
        }
    </style>
</head>
<body>

    <div class="box">
        <h1>Salom Azamat 😎</h1>
        <p>Bu zamonaviy web sahifa</p>
        <button onclick="changeText()">Bos meni</button>
        <p id="demo"></p>
    </div>

    <script>
        function changeText() {
            document.getElementById("demo").innerHTML = "Zo'r! Siz tugmani bosdingiz 🔥";
        }
    </script>

</body>


# Praktika
