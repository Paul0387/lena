<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Je t'aime Léna</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
        }
        .container {
            text-align: center;
        }
        h1 {
            font-size: 3em;
            color: #ff6b6b;
            margin-bottom: 20px;
        }
        .heart {
            font-size: 10em;
            color: #ff0000;
            animation: beat 1.5s infinite;
        }
        @keyframes beat {
            0% { transform: scale(1); }
            25% { transform: scale(1.2); }
            50% { transform: scale(1); }
            75% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Je t'aime Léna</h1>
        <div class="heart">❤️</div>
    </div>
</body>
</html>
