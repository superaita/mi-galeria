<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Galería de Fotos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        h1 {
            background-color: #333;
            color: white;
            padding: 15px 0;
            margin: 0;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }
        .gallery img {
            width: 250px;
            height: auto;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.2);
            transition: transform 0.2s;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>

    <h1>Mi Galería de Fotos</h1>
    <p>Sube tus fotos a la carpeta <strong>fotos</strong> en GitHub para que aparezcan aquí.</p>

    <div class="gallery">
        <img src="fotos/foto1.jpg" alt="Foto 1">
        <img src="fotos/foto2.jpg" alt="Foto 2">
        <img src="fotos/foto3.jpg" alt="Foto 3">
    </div>

</body>
</html>
