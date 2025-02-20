<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بازی تلگرام</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        .container {
            margin-top: 50px;
        }
        button {
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>خوش آمدید به بازی تلگرام!</h1>
        <p>برای شروع بازی، دکمه زیر را فشار دهید:</p>
        <button id="startGameBtn">شروع بازی</button>
        <div id="gameResult" style="margin-top: 20px;"></div>
    </div>

    <script>
        // اینجا می‌توانید کد JavaScript برای بازی رو اضافه کنید
        document.getElementById("startGameBtn").addEventListener("click", function() {
            // شبیه‌سازی یک بازی ساده
            const result = Math.random() < 0.5 ? "شما برنده شدید!" : "شما باختید!";
            document.getElementById("gameResult").innerText = result;
        });
    </script>
</body>
</html>
