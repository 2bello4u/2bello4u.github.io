<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lilpo Tour 2026</title>
    <style>
        /* Bloqueamos y ocultamos CUALQUIER elemento que intente inyectar el tema automático de GitHub */
        header, footer, pre, code, hr, #header, #footer, .header, .footer {
            display: none !important;
            opacity: 0 !important;
            visibility: hidden !important;
            height: 0 !important;
            margin: 0 !important;
            padding: 0 !important;
        }

        /* Animación para el fondo que cubre todo (de blanco puro a rosa) */
        @keyframes fondoFade {
            0% { background-color: #ffffff; }
            100% { background-color: #ffc0cb; }
        }

        /* Animación para que los textos aparezcan suavemente */
        @keyframes textoFade {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }

        /* Configuración total de la pantalla limpia */
        html, body {
            margin: 0 !important;
            padding: 0 !important;
            width: 100% !important;
            height: 100vh !important;
            overflow: hidden !important;
            background-color: #ffffff;
            /* El fade ahora dura 2.5 segundos (1 segundo más lento) */
            animation: fondoFade 2.5s ease-out forwards !important;
        }

        /* Contenedor central absoluto que tapa cualquier interferencia */
        .pantalla-limpia {
            position: fixed !important;
            top: 0 !important;
            left: 0 !important;
            width: 100% !important;
            height: 100% !important;
            display: block !important;
            z-index: 999999 !important; /* Se superpone a todo */
            font-family: "Helvetica Neue", Helvetica, Arial, sans-serif !important;
            text-align: center !important;
        }

        /* Centrado vertical de los textos */
        .centrado-vertical {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 100%;
            animation: textoFade 2.8s ease-out forwards;
        }

        /* Título Principal (Sin negrita) */
        h1 {
            color: #000000 !important;
            font-size: 4rem !important;
            font-weight: normal !important; /* QUITADA LA NEGRITA */
            margin: 0 0 20px 0 !important;
            text-transform: uppercase !important;
            letter-spacing: 2px !important;
            cursor: default !important;
            transition: opacity 0.3s ease, transform 0.3s ease !important;
        }

        /* Hover sutil en el título */
        h1:hover {
            opacity: 0.6 !important;
            transform: scale(1.02);
        }

        /* Enlace de la fecha (Sin negrita) */
        .tour-link {
            display: inline-block !important;
            font-size: 1.5rem !important;
            color: #000000 !important;
            font-weight: normal !important; /* QUITADA LA NEGRITA */
            text-decoration: none !important;
            transition: opacity 0.3s ease, letter-spacing 0.3s ease !important;
        }

        /* Evita que cambie de color al hacer clic o visitarlo */
        .tour-link:visited, 
        .tour-link:active,
        .tour-link:hover {
            color: #000000 !important;
        }

        /* Hover interactivo para el link de tickets */
        .tour-link:hover {
            opacity: 0.5 !important;
            letter-spacing: 1.5px !important; /* Separa un poquito las letras al pasar el cursor */
        }
    </style>
</head>
<body>

    <div class="pantalla-limpia">
        <div class="centrado-vertical">
            <h1>lilpo tour 2026</h1>
            
            <a class="tour-link" href="https://directoriotickets.com/client/event/underfest-4ta-edicion" target="_blank">
                buenos aires ....... 25 de julio
            </a>
        </div>
    </div>

</body>
</html>
