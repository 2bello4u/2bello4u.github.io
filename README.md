HTML
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lilpo Tour 2026</title>
    <style>
        /* Animación para el fondo (de blanco a rosa) */
        @keyframes fondoFade {
            0% { background-color: #ffffff; }
            100% { background-color: #ffc0cb; }
        }

        /* Animación para los textos (aparecen suavemente) */
        @keyframes textoFade {
            0% { opacity: 0; transform: translateY(10px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        /* Configuración de la página */
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
            text-align: center;
            /* Aplicamos la animación de fondo */
            animation: fondoFade 1.5s ease-out forwards;
            overflow: hidden;
        }

        /* Contenedor principal para animar los textos juntos */
        .contenedor {
            animation: textFade 1.8s ease-out forwards;
        }

        /* Estilo del título principal */
        h1 {
            color: #000000;
            font-size: 4rem;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 2px;
            transition: transform 0.3s ease, opacity 0.3s ease;
            cursor: default;
        }

        /* Efecto hover en el título principal */
        h1:hover {
            transform: scale(1.03);
            opacity: 0.8;
        }

        /* Estilo para el enlace de la fecha */
        .tour-link {
            display: inline-block;
            font-size: 1.5rem;
            color: #000000;
            text-decoration: none;
            font-weight: bold;
            transition: transform 0.3s ease, letter-spacing 0.3s ease, opacity 0.3s ease;
        }

        /* Forzamos a que NO cambie de color si ya fue visitado o clickeado */
        .tour-link:visited, 
        .tour-link:active {
            color: #000000 !important;
        }

        /* Efecto hover específico para el enlace */
        .tour-link:hover {
            color: #000000 !important;
            transform: scale(1.05);
            letter-spacing: 1px; /* Hace una leve separación de las letras al pasar el cursor */
            opacity: 0.7;
        }
    </style>
</head>
<body>

    <div class="contenedor">
        <h1>lilpo tour 2026</h1>
        
        <a class="tour-link" href="https://directoriotickets.com/client/event/underfest-4ta-edicion" target="_blank">
            buenos aires ....... 25 de julio
        </a>
    </div>

</body>
</html>
