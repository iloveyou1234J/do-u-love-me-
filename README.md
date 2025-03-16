# do-u-love-me?
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DO U LOVE MEE?</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: pink;
            padding-top: 50px;
        }
        h1 {
            font-size: 36px;
        }
        button {
            font-size: 20px;
            padding: 10px 20px;
            margin: 10px;
            cursor: pointer;
        }
        #noBtn {
            position: absolute;
        }
    </style>
    <script>
        function moveNo() {
            var x = Math.random() * window.innerWidth - 100;
            var y = Math.random() * window.innerHeight - 50;
            document.getElementById("noBtn").style.left = `${x}px`;
            document.getElementById("noBtn").style.top = `${y}px`;
        }
    </script>
</head>
<body>
    <h1>DO U LOVE MEE? 💕</h1>
    <button onclick="alert('YAY! I love you too! 💖')">YES</button>
    <button id="noBtn" onmouseover="moveNo()">NO</button>
</body>
</html>
