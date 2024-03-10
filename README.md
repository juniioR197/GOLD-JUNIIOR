# Gold-Junior Web Project

Este proyecto web utiliza HTML y CSS para mostrar una página principal con imágenes y un carrusel de fotos.

## Contenido del Proyecto

### 1. Archivo HTML (index.html)

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GOLD-JUNIIOR</title>
    <link rel="stylesheet" href="BODY.css">
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
