<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portfolio de Samuel</title>
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #4f0202;
            color: #ff036c;
            text-align: center;
        }

        header {
    background-image: url(melendi.2.jpg); 
    background-position: center;
    color: white; 
    padding: 50px 20px;
    text-shadow: 2px 2px 4px rgba(0,0,0,0.7); 
}


        header h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2em;
        }

        main {
            padding: 20px;
        }

        .portfolio-item {
            background-color: #ffffff;
            margin: 20px auto;
            padding: 30px;
            width: 90%;
            max-width: 800px;
            border-radius: 15px;
            text-align: left;
            color: #000;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
        }

        .portfolio-item h2 {
            color: #6a00ff;
        }

        ol {
            padding-left: 20px;
        }

        .portfolio-item img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-top: 15px;
        }

        .button {
            background-color: #6200ea;
            color: white;
            padding: 10px 20px;
            font-size: 1.1em;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .button:hover {
            background-color: #ff0000;
        }

        .shitpost {
            color: #ff5722;
            font-size: 1.3em;
            background-color: #e0f7fa;
            padding: 20px;
            margin: 40px auto;
            border-radius: 10px;
            width: 90%;
            max-width: 700px;
        }

        footer {
           background-image: url(tralalerotralala.jpg);
           background-position: 10%;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Portfolio de Samuel</h1>
        <p>Aquí intentaré hacer un programa lo suficientemente bueno como para que <strong>mi profesor me apruebe.</strong></p>
    </header>

    <main>
        <section class="portfolio-item">
            <h2>Cosas que sé hacer (más o menos)</h2>
            <ol>
                <li>Socorrista de lagartijas en el Sahara</li>
                <li>Paracaidista de taburetes</li>
                <li>Cantante de ópera bajo el agua</li>
                <li>Jugador semiprofesional de waterpolo</li>
            </ol>
        </section>

        <section class="portfolio-item">
            <h2>Uno de mis cantantes favoritos</h2>
            <img src="melendi.jpg.jpg" alt="Melendi, cuando hacía buena música (según Samuel)">
        </section>

        <section class="portfolio-item">
            <h2>Botón para escuchar un temazo 🎸</h2>
            <a class="button" href=https://www.youtube.com/watch?v=8ka_6EATkhY target="_blank" rel="noopener noreferrer">
                Escuchar a Melendi 🎵
            </a>
        </section>

        <section class="shitpost">
            <p>Aquí me apetecía cambiar el color de la letra. No sé qué más poner 😄</p>
        </section>
    </main>

    <footer>
        <p>&copy; Portfolio de Samuel - Hecho con ❤️ (aunque se me hizo tarde terminando esto).</p>
    </footer>

</body>
</html>


   
