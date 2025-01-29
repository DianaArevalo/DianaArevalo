<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio</title>    
    <!-- Importar fuentes de Google -->
    <link href="https://fonts.googleapis.com/css2?family=Spline+Sans+Mono:wght@300;700&family=Victor+Mono:ital,wght@1,100;700&display=swap" rel="stylesheet">
    <style>
        /* Aplicar la fuente a todo el documento */
        body {
            font-family: 'Spline Sans Mono', monospace; /* Usa Spline Sans Mono */
            background-color: #101B23;
            color: white;
            text-align: center;
            margin: 0;
            padding: 20px;
        }
        /* Contenedor principal */
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }
        /* Imagen de presentación */
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
        }
        /* Sección de enlaces */
        .links {
            display: flex;
            gap: 10px;
            margin-top: 10px;
        }
        .links a img {
            width: 40px; /* Tamaño de los iconos */
        }
        /* Encabezados */
        h1 {
            font-family: 'Victor Mono', monospace; /* Usa Victor Mono */
            font-size: 24px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://github.com/user-attachments/assets/9a53052c-6c54-4a25-a578-07f8d5b4d259" 
            alt="Imagen Presentación" class="profile-img">        
        <h1>Desarrolladora de Software con gran pasión por la tecnología y todo lo que mi mente puede imaginar y crear</h1>
        <p>Presentación</p>        
        <h1>Proyectos</h1>
        <div>RoadMap</div>
        <!-- Enlaces con iconos -->
        <div class="links">
            <a href="https://github.com/tuusuario">
                <img src="github.svg" alt="GitHub">
            </a>
            <a href="https://linkedin.com/in/tuusuario">
                <img src="linkedin.svg" alt="LinkedIn">
            </a>
        </div>
    </div>

</body>
</html>
