<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Richard | Personal Website</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #1f4037, #99f2c8);
            display: flex;
            flex-direction: column;
            min-height: 100vh;
            color: #333;
        }

        header {
            background: #111;
            color: white;
            padding: 25px;
            text-align: center;
        }

        .container {
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 40px 20px;
        }

        .card {
            background: white;
            padding: 35px;
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            text-align: center;
            max-width: 500px;
            width: 100%;
        }

        .card h2 {
            margin-bottom: 15px;
        }

        .card p {
            margin-bottom: 10px;
            font-size: 16px;
        }

        .email {
            font-weight: bold;
            color: #1f4037;
        }

        button {
            margin-top: 20px;
            padding: 10px 20px;
            border: none;
            border-radius: 6px;
            background: #1f4037;
            color: white;
            cursor: pointer;
            font-size: 16px;
            transition: 0.3s;
        }

        button:hover {
            background: #145c4a;
        }

        footer {
            background: #111;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Richard's Website</h1>
</header>

<div class="container">
    <div class="card">
        <h2>Hello, I'm Richard 👋</h2>
        <p>Welcome to my personal webpage.</p>
        <p>You can contact me at:</p>
        <p class="email">optimalyoungforever@gmail.com</p>
        <button onclick="contactAlert()">Send Greeting</button>
    </div>
</div>

<footer>
    &copy; 2026 Richard | All Rights Reserved
</footer>

<script>
    function contactAlert() {
        alert("Thanks for visiting my website!");
    }
</script>

</body>
</html>
