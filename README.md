<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículum Vitae - Rodrigo Ezequiel Noguera Caballero</title>
    <style>
        :root {
            --primary-color: #00796b;
            --secondary-color: #004d40;
            --background-color: #e0f7fa;
            --text-color: #333;
            --heading-color: #00796b;
            --link-color: #004d40;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: var(--background-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 900px;
            margin: 20px auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            display: flex;
            flex-direction: column;
            gap: 20px;
        }

        h1, h2 {
            font-family: 'Roboto', sans-serif;
            color: var(--heading-color);
        }

        p, li {
            font-family: 'Arial', sans-serif;
            color: var(--text-color);
        }

        /* lafotodelperfil */
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin: 0 auto 10px;
            border: 5px solid var(--primary-color);
        }

        /* posicion del encb */
        .header-content {
            text-align: center;
            margin-bottom: 30px;
        }

        .header-content p {
            font-style: italic;
            font-size: 1.2em;
            color: var(--primary-color);
        }

        ul {
            list-style-type: none;
            padding: 0;
        }

        li {
            margin-bottom: 15px;
            padding-left: 20px;
            position: relative;
        }

        li:before {
            content: '•';
            color: var(--primary-color);
            position: absolute;
            left: 0;
            font-size: 1.5em;
            line-height: 1;
        }

        section {
            display: flex;
            flex-direction: column;
        }

        /* Enlaces */
        a {
            color: var(--link-color);
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Estilos para el footer */
        footer {
            text-align: center;
            margin-top: 40px;
            background-color: var(--primary-color);
            padding: 10px;
            border-radius: 5px;
        }

        footer p {
            color: #fff;
        }

        footer a {
            color: #fff;
            text-decoration: underline;
        }

        /* Diseño responsivo */
        @media (max-width: 768px) {
            .container {
                padding: 15px;
            }

            h1 {
                font-size: 2em;
            }

            h2 {
                font-size: 1.5em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="header-content">
                <img src="pimera semana/Imagen de WhatsApp 2024-09-27 a las 18.59.34_af50616f.jpg" alt="Foto de perfil" class="profile-img">
                <h1>Rodrigo Ezequiel Noguera Caballero</h1>
                <p>SOY UNA PERSONA MUY CAPAZ DE AFRONTAR CUALQUIER PROBLEMA, APRENDO MUY RÁPIDO Y SOY BASTANTE COMPETITIVO.</p>
            </div>
        </header>

        <section>
            <h2>Experiencia Laboral</h2>
            <ul>
                <li>
                    <strong>Nómada PY</strong> <br>
                    <em>Posición Actual</em> <br>
                    Trabajando en proyectos de desarrollo web.
                </li>
                <li>
                    <strong>Inoxa SA</strong> <br>
                    <em>AUXILIAR CONTABLE</em> <br>
                    Realización de labores de auxiliar contable, informes, conteo de inventarios, clasificación de facturas y pagarés, etc.
                </li>
            </ul>
        </section>

        <section>
            <h2>Educación</h2>
            <ul>
                <li><strong>Bachiller Técnico en Administración</strong></li>
                <li><strong>Inglés Intermedio</strong></li>
                <li><strong>Primeros Auxilios</strong></li>
            </ul>
        </section>

        <section>
            <h2>Habilidades</h2>
            <ul>
                <li>Respetuoso</li>
                <li>Competitivo</li>
                <li>Comprometido con los resultados</li>
            </ul>
        </section>

        <section>
            <h2>Información de Contacto</h2>
            <p>
                Correo: <a href="mailto:rodrigonoguera1103@gmail.com">rodrigonoguera1103@gmail.com</a><br>
                LinkedIn: <a href="https://www.linkedin.com/in/rodrigo-ezequiel-noguera-caballero-4510b8330/" target="_blank">Perfil de LinkedIn</a>
            </p>
        </section>

        <footer>
            <p>GitHub: <a href="https://github.com/RODRI-goo/RODbox" target="_blank">Mi cuenta en GitHub</a></p>
        </footer>
    </div>
</body>
</html>
