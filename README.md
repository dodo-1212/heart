<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pink Heart</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f8ff; /* لون خلفية خفيف */
            font-family: Arial, sans-serif;
        }

        .container {
            text-align: center;
        }

        .heart {
            width: 150px;
            height: 150px;
            position: relative;
            background-color: pink;
            transform: rotate(-45deg);
            margin: 20px auto;
        }

        .heart::before,
        .heart::after {
            content: "";
            width: 150px;
            height: 150px;
            border-radius: 50%;
            background-color: pink;
            position: absolute;
        }

        .heart::before {
            top: -75px;
            left: 0;
        }

        .heart::after {
            left: 75px;
            top: 0;
        }

        h1 {
            color: #333;
        }

        p {
            color: #555;
            font-size: 18px;
        }

        footer {
            margin-top: 40px;
            font-size: 14px;
            color: #777;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to the Heart Page!</h1>
        <div class="heart"></div>
        <p>Here's a pink heart just for you! ❤️</p>
    </div>
    <footer>
        Made with ❤️ by dodi
    </footer>
</body>
</html>
