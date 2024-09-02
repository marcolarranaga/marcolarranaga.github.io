<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Imagen de cabecera */
        .header-image {
            width: 100%;
            height: 300px;
            background-image: url('ocean_pic.jpg');
            background-size: cover;
            background-position: center;
        }

        /* Contenedor para los íconos */
        .icon-container {
            display: flex;
            justify-content: space-around;
            margin: 20px 0;
            padding: 10px 0;
            background-color: #f4f4f4;
        }

        /* Estilo para los íconos */
        .icon {
            text-align: center;
            flex-grow: 1;
        }

        .icon img {
            width: 50px;
            height: 50px;
            cursor: pointer;
        }

        .icon p {
            margin-top: 10px;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <!-- Imagen horizontal -->
    <div class="header-image"></div>

    <!-- Contenedor de íconos -->
    <div class="icon-container">
        <div class="icon">
            <a href="#about-me">
                <img src="ruta/a/icono1.png" alt="About Me">
                <p>About Me</p>
            </a>
        </div>
        <div class="icon">
            <a href="#research-interest">
                <img src="ruta/a/icono2.png" alt="Research Interest">
                <p>Research Interest</p>
            </a>
        </div>
        <div class="icon">
            <a href="#publications">
                <img src="ruta/a/icono3.png" alt="Publications">
                <p>Publications</p>
            </a>
        </div>
    </div>

    <!-- Secciones de contenido -->
    <section id="about-me">
        <h2>About Me</h2>
        <p>Aquí va tu contenido sobre ti.</p>
    </section>

    <section id="research-interest">
        <h2>Research Interest</h2>
        <p>Aquí va tu contenido sobre tus intereses de investigación.</p>
    </section>

    <section id="publications">
        <h2>Publications</h2>
        <p>Aquí va tu contenido sobre tus publicaciones.</p>
    </section>

</body>
</html>
