<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Link - The Legend of Zelda</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            color: white;
            text-align: center;
            background-image: url('https://wallpapers.com/images/hd/zelda-breath-of-the-wild-4k-cbzp67luzqcjtv08.jpg'); /* Imagen de fondo */
            background-size: cover;
            background-attachment: fixed;
        }
        header {
            background: rgba(0, 0, 0, 0.7);
            padding: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        header img {
            width: 50px;
            height: auto;
        }
        .nav-buttons {
            display: flex;
            gap: 15px;
        }
        .nav-buttons button {
            background-color: #45ca4c;
            border: none;
            padding: 10px 20px;
            color: white;
            font-weight: bold;
            cursor: pointer;
            border-radius: 5px;
        }
        .nav-buttons button:hover {
            background-color: #ff4500;
        }
        section {
            padding: 20px;
            background: rgba(0, 0, 0, 0.5);
            margin: 20px;
            border-radius: 10px;
        }
        .gif-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .gif-container img {
            border: 2px solid white;
            border-radius: 10px;
            max-width: 200px;
        }
        .links-section {
            color: #45ca4c; /* Color verde claro */
            margin-top: 20px;
            text-align: center; /* Centrar el texto */
        }
        .links-section a {
            color: #45ca4c;
            text-decoration: none;
            font-weight: bold;
        }
        .links-section a:hover {
            color: #ff4500;
        }
        .game-images {
            display: flex;
            gap: 20px;
            justify-content: center;
            margin-top: 10px;
        }
        .game-images img {
            border: 2px solid white;
            border-radius: 10px;
            max-width: 150px;
        }
        .about-link {
            color: #45ca4c; /* Color verde claro */
            text-align: center; /* Centrar el texto */
            font-size: 1.2em;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="nav-buttons">
            <button onclick="window.location.href='https://www.zelda.com/'" target="_blank">Sitio Oficial</button>
            <button onclick="window.location.href='https://es.wikipedia.org/wiki/The_Legend_of_Zelda'" target="_blank">Wikipedia</button>
            <button onclick="window.location.href='https://www.youtube.com/results?search_query=zelda+gameplay'" target="_blank">Ver Gameplay</button>
        </div>
    </header>

    <section class="about-link">
        <h2>Acerca de Link</h2>
        <p>Link es el valiente héroe que siempre está listo para proteger Hyrule. A pesar de ser un joven sin mucha experiencia al principio, su coraje y su deseo de ayudar a los demás lo convierten en un verdadero líder.</p>
        <p>Con su espada y escudo, Link enfrenta criaturas peligrosas y resuelve misteriosos rompecabezas para salvar su mundo. Su espíritu de aventura es lo que lo hace tan especial y querido por todos.</p>
    </section>

    <section class="links-section">
        <h2>Explora Más</h2>
        <p>Descubre más sobre Link y sus aventuras:</p>

        <div class="game-images">
            <div>
                <a href="https://www.zelda.com/breath-of-the-wild/" target="_blank">
                    <img src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcQmAk-M2vhHTif2ZwXEcCHmm8-eVYF_YSOTGivkAaBr3AHqi70UvoCSbOxnapwW7DzHUl-eiR1Qh2Ol-0Zy0n2nw7kWHUjQyZXJB4qDig" alt="Breath of the Wild">
                    <p>Breath of the Wild</p>
                </a>
            </div>
            <div>
                <a href="https://www.zelda.com/tears-of-the-kingdom/" target="_blank">
                    <img src="https://gagadget.com/media/post_big/Tears-of-the-Kingdom-wallpaper-1170x720-1.jpg" alt="Tears of the Kingdom">
                    <p>Tears of the Kingdom</p>
                </a>
            </div>
        </div>
    </section>

    <div class="gif-container">
        <img src="https://i.pinimg.com/originals/dd/a2/83/dda283555874b8e6eab8f3cecdf8457b.gif" alt="Link con la Espada">
        <img src="https://i.pinimg.com/originals/57/81/e5/5781e52cef1e5024170b79d0e4953adc.gif" alt="Link Montando un Caballo">
    </div>
</body>
</html>
