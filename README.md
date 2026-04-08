<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Perfil - Abraham</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Fuente tipo tech -->
    <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap" rel="stylesheet">

    <style>
        body {
            margin: 0;
            font-family: 'Share Tech Mono', monospace;
            background-color: #0a0f1c;
            color: white;
        }

        .container {
            width: 90%;
            margin: auto;
            text-align: center;
            padding-top: 40px;
        }

        .perfil img {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            border: 3px solid #00aaff;
            object-fit: cover;
        }

        h1 {
            margin-top: 15px;
            color: #00aaff;
        }

        hr.white {
            border: 1px solid white;
            margin: 40px 0;
        }

        hr.green {
            border: 1px solid #00ff88;
            margin: 40px 0;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            color: #00ff88;
        }

        .tech-list {
            list-style: none;
            padding: 0;
        }

        .tech-list li {
            background: rgba(255,255,255,0.05);
            margin: 10px auto;
            padding: 10px;
            width: 300px;
            border-left: 4px solid #00aaff;
        }

        .stats img {
            width: 400px;
            margin: 10px;
        }

        @media (max-width: 600px) {
            .stats img {
                width: 90%;
            }
        }
    </style>
</head>

<body>

<div class="container">

    <!-- Perfil -->
    <div class="perfil">
        <img src="tu_imagen.jpg" alt="Foto de Abraham">
        <h1>Hola, soy Abraham</h1>
    </div>

    <hr class="white">

    <!-- Sobre mí -->
    <div class="section">
        <h2><strong>Sobre mí</strong></h2>
        <p>
            Durante mi trayectoria universitaria y profesional, he desarrollado diversas aplicaciones orientadas
            a facilitar la comprensión de distintos procesos. He aplicado los conocimientos adquiridos de forma
            teórica, llevándolos a la práctica mediante el desarrollo de soluciones funcionales y eficientes.
        </p>
    </div>

    <!-- Tecnologías -->
    <div class="section">
        <h2>🚀 Tecnologías</h2>
        <ul class="tech-list">
            <li>Flutter + Dart</li>
            <li>Python + Django</li>
            <li>C# + .NET + SQL Server</li>
            <li>PHP + CodeIgniter</li>
        </ul>
    </div>

    <hr class="green">

    <!-- GitHub Stats -->
    <div class="section stats">
        <h2>📊 GitHub Analytics</h2>

        <img src="https://github-readme-stats.vercel.app/api?username=TU_USUARIO&show_icons=true&theme=tokyonight" alt="stats">

        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TU_USUARIO&layout=compact&theme=tokyonight" alt="langs">

        <img src="https://streak-stats.demolab.com?user=TU_USUARIO&theme=tokyonight" alt="streak">
    </div>

</div>

</body>
</html>
