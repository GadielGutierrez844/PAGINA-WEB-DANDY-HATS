<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cronología de Dandy Hats</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(to right, #1c1c1c, #2e2e2e);
            color: #ffffff;
            margin: 0;
            padding: 0;
        }

        header {
            background: linear-gradient(to right, #00d9ff, #ff4081);
            padding: 30px 0;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0,0,0,0.5);
        }

        header h1 {
            font-size: 3.5em;
            color: #fff;
            margin: 0;
            text-transform: uppercase;
            letter-spacing: 3px;
            text-shadow: 2px 2px 10px #000;
        }

        .timeline {
            max-width: 1100px;
            margin: 40px auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 40px;
            padding: 0 20px;
        }

        .event {
            background-color: #1f1f1f;
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 0 15px rgba(0, 217, 255, 0.3);
            display: flex;
            flex-direction: column;
            align-items: center;
            transition: transform 0.3s;
        }

        .event:hover {
            transform: scale(1.03);
        }

        .event img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 15px;
            box-shadow: 0 0 10px #000;
        }

        .year {
            font-size: 1.5em;
            color: #ff4081;
            margin-bottom: 10px;
            font-weight: bold;
        }

        .game {
            font-size: 1.3em;
            color: #00d9ff;
            margin-bottom: 15px;
            font-weight: bold;
        }

        .event p {
            text-align: justify;
            line-height: 1.6;
        }

        .links {
            text-align: center;
            margin: 50px 0;
        }

        .links a {
            color: #00ffcc;
            font-weight: bold;
            font-size: 1.1em;
            text-decoration: none;
            display: block;
            margin: 10px 0;
        }

        .links a:hover {
            color: #ffffff;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Historia de Dandy Hats</h1>
    </header>

    <div class="timeline">

        <div class="event">
            <img src="DANDY HATS 2021.webp" alt="Dandy Hats Inicio">
            <div class="year">2021</div>
            <div class="game">Nacimiento de la idea</div>
            <p>En un pequeño cuarto de estudio, un grupo de jóvenes apasionados por el estilo urbano y el diseño decidió crear una marca diferente: gorras con actitud, personalidad y frescura. Así nació la idea de Dandy Hats.</p>
        </div>

        <div class="event">
            <img src="DANDY HATS 2022.webp" alt="Lanzamiento Dandy">
            <div class="year">2022</div>
            <div class="game">Lanzamiento oficial</div>
            <p>Dandy Hats lanzó su primera colección con cinco modelos únicos. Usando redes sociales como Instagram y TikTok, lograron posicionarse rápidamente entre jóvenes de 15 a 25 años. Su estilo urbano y elegante los hizo destacar.</p>
        </div>

        <div class="event">
            <img src="DANDY HATS 2023.webp" alt="Colaboraciones Dandy">
            <div class="year">2023</div>
            <div class="game">Crecimiento y colaboraciones</div>
            <p>La marca colaboró con artistas locales y diseñadores gráficos para lanzar ediciones limitadas. Dandy Hats comenzó a vender en línea y en eventos urbanos, ganando reconocimiento en todo el país.</p>
        </div>

        <div class="event">
            <img src="DANDY HATS 2024.png" alt="Expansión Dandy">
            <div class="year">2024</div>
            <div class="game">Internacionalización</div>
            <p>Gracias a su éxito, Dandy Hats comenzó a distribuir en otros países de América Latina. Abrieron su primer punto de venta físico en CDMX y lanzaron una línea premium con diseños exclusivos y materiales de alta calidad.</p>
        </div>

        <div class="event">
            <img src="DANDY HATS 2025.webp" alt="Presente y Futuro">
            <div class="year">2025</div>
            <div class="game">Presente y futuro</div>
            <p>Hoy, Dandy Hats es sinónimo de estilo y autenticidad. Planean introducir productos como sudaderas, mochilas y accesorios, manteniendo siempre su esencia original: calidad, originalidad y orgullo por lo urbano.</p>
        </div>
    </div>

    <div class="links">
        <a target="_blank" href="https://youtu.be/7cQZWKOKpcI?si=uL-gpv2Y7kiKnGgt">Conoce la historia completa en este video especial</a>
    </div>
</body>
</html>
