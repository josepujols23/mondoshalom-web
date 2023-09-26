<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mondoshalom</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #1a1a1a;
            color: #eee;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        .navbar {
            position: absolute;
            top: 0;
            width: 100%;
            background-color: #333;
            padding: 15px 0;
            text-align: center;
            font-size: 1.5em;
            font-weight: bold;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
        }

        .main-content {
            max-width: 800px;
            text-align: center;
            background: rgba(0, 0, 0, 0.7);
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 25px rgba(0, 0, 0, 0.5);
        }

        .main-content h2 {
            border-bottom: 2px solid #777;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        .main-content img {
            max-width: 300px;
            border-radius: 15px;
            box-shadow: 0px 0px 15px rgba(255, 255, 255, 0.6);
            margin: 20px 0;
        }

        .symbols {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }

        .symbol {
            font-size: 2em;
            cursor: pointer;
            transition: color 0.3s ease;
        }

        .symbol:hover {
            color: #ff4500;
        }

    </style>
</head>
<body>
    <div class="navbar">
        Mondoshalom
    </div>
    <div class="main-content">
        <h2>Datos en Tiempo Real</h2>
        <p>Aquí se mostrarán los datos en tiempo real para jugadores.</p>
        <img src="https://example.com/babe-ruth.jpg" alt="Babe Ruth">
        <p>Imagen de Babe Ruth, una leyenda del béisbol.</p>
        <div class="symbols">
            <span class="symbol">&#9733;</span>
            <span class="symbol">&#9881;</span>
            <span class="symbol">&#9813;</span>
        </div>
    </div>
</body>
</html>
