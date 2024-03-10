<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GOLD-JUNIIOR</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background-color: #f8f8f8;
        }

        .main-photo-container {
            display: flex;
            justify-content: space-around;
            align-items: center;
            padding: 20px;
        }

        .main-photo-content {
            text-align: center;
        }

        img {
            width: 100%;
            max-width: 400px;
            display: block;
            margin: 0 auto;
            border: 10px solid gold;
            border-radius: 10px;
        }

        h1 {
            margin-top: 10px;
            font-size: 3em;
            color: gold;
        }

        .qr-frame {
            margin-top: 20px;
        }

        .separator {
            margin: 20px 0;
            border: none;
            height: 2px;
            background-color: #ccc;
        }

        .photo-catalog-container {
            padding: 20px;
        }

        .slick-carousel {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .slick-carousel img {
            width: 100%;
            max-width: 150px;
            margin: 10px;
            border: 5px solid gold;
            border-radius: 5px;
        }

        .gif-frame {
            margin: 20px auto;
            max-width: 400px;
        }

        .button-container {
            margin-top: 20px;
            text-align: center;
        }

        .whatsapp-button {
            display: inline-block;
            padding: 12px 24px;
            font-size: 16px;
            font-weight: bold;
            text-align: center;
            text-decoration: none;
            color: #fff;
            background-color: #25D366;
            border: 2px solid #128C7E;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .whatsapp-button:hover {
            background-color: #128C7E;
        }
    </style>
</head>
<body>

    <!-- Sección para la foto principal -->
    <div class="main-photo-container">
        <div class="main-photo-content">
            <img src="JPG.PNG" alt="Imagen Principal con Marco">
            <h1>GOLD JUNIIOR</h1>
            
            <!-- Frame para el código QR -->
            <div class="qr-frame">
                <!-- Aquí puedes insertar tu código QR o enlaces necesarios -->
                <!-- Por ejemplo, puedes usar la etiqueta <img> para el código QR -->
                <!-- <img src="tu-qr-code.png" alt="Código QR"> -->
                <!-- Asegúrate de cambiar la ruta del código QR según tus necesidades -->
            </div>
        </div>
    </div>

    <!-- Separador entre la imagen principal y el catálogo -->
    <hr class="separator">

    <!-- Sección para el catálogo de fotos -->
    <div class="photo-catalog-container">
        <!-- Carrusel de imágenes (galería de fotos) -->
        <div class="slick-carousel">
            <!-- Imagen "madre.gif" en la parte superior izquierda -->
            <div class="top-left-image">
                <img src="madre.gif" alt="GIF"> 
                <!-- Asegúrate de cambiar la ruta del GIF según tus necesidades -->
            </div>
            <div><img src="CATALOGO/1A.jpeg" alt="Imagen 1"></div>
            <div>
                <img src="CATALOGO/2A.jpeg" alt="Imagen 2">
                <!-- Nuevo Frame para el GIF "promo.gif" al lado de la imagen "3A.jpeg" -->
                <div class="gif-frame">
                    <img src="promo.gif" alt="GIF"> 
                    <!-- Asegúrate de cambiar la ruta del GIF según tus necesidades -->
                </div>
            </div>
            <div><img src="CATALOGO/3A.jpeg" alt="Imagen 3"></div>
            <div><img src="CATALOGO/4A.jpeg" alt="Imagen 4"></div>
            <div><img src="CATALOGO/5A.jpeg" alt="Imagen 5"></div>
            <div><img src="CATALOGO/6A.jpeg" alt="Imagen 6"></div>
            <!-- Añade más imágenes según sea necesario -->
        </div>
    </div>

    <!-- Botón de contacto por WhatsApp -->
    <div class="button-container">
        <a href="https://wa.me/3507549786" target="_blank" class="whatsapp-button">Contactar por WhatsApp</a>
    </div>

    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="https://cdn.jsdelivr.net/jquery.slick/1.8.1/slick.min.js"></script>
    <script src="script.js"></script>

</body>
</html>
