---
layout: default_es
title: "Blog en español"
lang: "es"
permalink: /es/
---

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }}</title>
    <link href="https://fonts.googleapis.com/css2?family=Titillium+Web:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Estilos para centrar el contenido */
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: 'Titillium Web', sans-serif;
            background-color: #f0f0f0;
        }

        /* Estilos del contenedor principal */
        .container {
            text-align: center;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h1 {
            font-size: 2rem;
            color: #333;
            margin: 0;
        }

        p {
            color: #666;
            margin-top: 10px;
        }

        /* Estilo para la imagen */
        .image {
            max-width: 100%;
            height: auto;
            margin-top: 20px;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>{{ page.title }}</h1>
        <p>Texto descriptivo con la fuente Titillium Web en el centro de la interfaz.</p>
        <img src="/images/Emanuel-1.png" alt="Descripción de la imagen" class="image">
    </div>
</body>
</html>
