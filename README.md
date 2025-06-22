# lov.msg
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>I Love You</title>
    <style>
        body {
            background: linear-gradient(to right, #ffafbd, #ffc3a0);
            text-align: center;
            font-family: 'Segoe UI', sans-serif;
            color: white;
            padding-top: 50px;
            animation: fadeIn 2s ease-in;
        }

        h1 {
            font-size: 3em;
            animation: pop 1s ease-out;
        }

        p {
            font-size: 1.5em;
            margin-top: 20px;
        }

        @keyframes pop {
            0% { transform: scale(0); opacity: 0; }
            100% { transform: scale(1); opacity: 1; }
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        .hearts {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            z-index: -1;
        }

        .hearts::before {
            content: "❤️❤️❤️❤️❤️❤️❤️";
            font-size: 50px;
            animation: float 10s linear infinite;
        }

        @keyframes float {
            0% { transform: translateY(100%); }
            100% { transform: translateY(-100%); }
        }
    </style>
    <script>
        window.onload = function() {
            alert("I love you baby girl ❤️");
        };
    </script>
</head>
<body>
    <div class="hearts"></div>
    <h1>I Love You Baby Girl 💖</h1>
    <p>You are the light of my life, my best friend, and my forever person.</p>
    <p>This little page is just a tiny gift from my heart to yours i love you soo much my rasgulla .</p>
</body>
</html>
