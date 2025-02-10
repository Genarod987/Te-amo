<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Te Amo</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #ffcccb;
            font-family: 'Arial', sans-serif;
        }
        h1 {
            font-size: 3rem;
            color: #d32f2f;
            animation: palpitar 1s infinite;
        }
        @keyframes palpitar {
            0% { transform: scale(1); }
            50% { transform: scale(1.1); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <h1>¡Te amo!</h1>
</body>
</html>
