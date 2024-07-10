# prabangus.lt
Mada, stilius, drabužiai
<!DOCTYPE html>
<html lang="lt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mano Portfolio</title>
    <style>
        body {
            font-family: 'Calibri', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff;
            color: #000;
        }
        header {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            text-align: center;
            margin: 1em 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #000;
            font-weight: bold;
        }
        section {
            padding: 2em;
            max-width: 800px;
            margin: 0 auto;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .work-item {
            width: 45%;
            margin: 1em 0;
        }
        footer {
            background-color: #000;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mano Portfolio</h1>
    </header>
    <nav>
        <a href="#about">Apie Mane</a>
        <a href="#works">Mano Darbai</a>
        <a href="#contact">Kontaktai</a>
    </nav>
    <section id="about">
        <h2>Apie Mane</h2>
        <p>Čia parašyk apie save: kas esi, ką darai, kokie tavo interesai ir kompetencijos.</p>
    </section>
    <section id="works">
        <h2>Mano Darbai</h2>
        <div class="container">
            <div class="work-item">
                <h3>Darbas 1</h3>
                <p>Trumpas aprašymas apie šį darbą.</p>
            </div>
            <div class="work-item">
                <h3>Darbas 2</h3>
                <p>Trumpas aprašymas apie šį darbą.</p>
            </div>
            <!-- Pridėk daugiau darbų čia -->
        </div>
    </section>
    <section id="contact">
        <h2>Kontaktai</h2>
        <p>Čia parašyk savo kontaktinę informaciją arba pridėk kontaktinę formą.</p>
    </section>
    <footer>
        <p>&copy; 2024 Mano Vardas. Visos teisės saugomos.</p>
    </footer>
</body>
</html>
