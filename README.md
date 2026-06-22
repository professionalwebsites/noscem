<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WeltBlick24 - Nachrichtenportal</title>
    <style>
        body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #000;
    color: #fff;
}

/* Header */
header {
    background: #111;
    color: #fff;
    padding: 20px;
    text-align: center;
    border-bottom: 3px solid #f29100;
}

/* Navigation */
nav {
    background: #1a1a1a;
    padding: 10px;
    text-align: center;
    border-bottom: 2px solid #f29100;
}

nav a {
    color: #fff;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
    transition: color 0.3s;
}

nav a:hover {
    color: #f29100;
}

/* Hauptbereich */
.container {
    max-width: 1200px;
    margin: auto;
    padding: 20px;
}

/* Top-Meldung */
.top-story {
    background: #111;
    padding: 20px;
    border-radius: 8px;
    margin-bottom: 20px;
    border: 2px solid #f29100;
    box-shadow: 0 0 10px rgba(204, 102, 0, 0.3);
}

.top-story h2 {
    color: #f29100;
}

/* News Grid */
.news-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
}

/* News-Karten */
.news-card {
    background: #111;
    padding: 15px;
    border-radius: 8px;
    border: 2px solid #f29100;
    transition: all 0.3s ease;
}

.news-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 0 15px rgba(204, 102, 0, 0.5);
}

/* Kategorien */
.category {
    color: #f29100;
    font-size: 12px;
    font-weight: bold;
    text-transform: uppercase;
}

/* Überschriften */
h1, h2, h3 {
    color: #fff;
}

/* Footer */
footer {
    background: #111;
    color: #fff;
    text-align: center;
    padding: 15px;
    margin-top: 30px;
    border-top: 3px solid #f29100;
}
    </style>

    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>No Scamm</h1>
    <p>24 Stunden kommen und erscheinen neue Nachrichten</p>
</header>

<nav>
    <a href="#">Politik</a>
    <a href="#">Sport</a>
    <a href="#">Wirtschaft</a>
    <a href="#">Welt</a>
    <a href="#">Vermischtes</a>
</nav>

<div class="container">

    <section class="top-story">
        <h2>Top-Meldung</h2>

        <article>
            <h3>Kap Verde erzielt in zwei WM-Spielen genauso viele Tore wie Italien in den letzten vier Weltmeisterschaften</h3>
            <p>
                Fußballfans weltweit reiben sich verwundert die Augen.
                Während Kap Verde bei seinem WM-Debüt offensiv überzeugt,
                suchen italienische Statistiker weiterhin nach Treffern aus den letzten Turnieren.
            </p>
        </article>
    </section>

    <section class="news-grid">

        <article class="news-card">
            <span class="category">Sport</span>
            <h3>Türkische Mannschaft zeigt Rücksicht</h3>
            <p>
                Die Türkische Nationalmannschaft hat sich im Spiel gegen Paraguay entschlossen, keine Tore zu schiessen damit die Bevölkerung nicht um 4 Uhr morgens aufgeweckt wird. W Arda Güleeeeer
            </p>
        </article>

        <article class="news-card">
            <span class="category">Wirtschaft</span>
            <h3>Dönerpreise steigen!!!</h3>
            <p>
                Die Dönerpreise werden wieder teurer, da die Kühe streiken. Weil Veganer Döner nicht Döner heissen darf verzweifeln gerde viele Dönersüchtige. 
            </p>
        </article>

        <article class="news-card">
            <span class="category">Politik</span>
            <h3>Bald Neuwahlen?</h3>
            <p> 69 % der deutschen Bevölkerungen wollen Marcel Thomas Andreas Eris als ihren neuen Kanzler gemeinsam seiner Frau Agatha. 
                
            </p>
        </article>

        <article class="news-card">
            <span class="category">Technologie</span>
            <h3>KI beantwortet Frage in nur 0,3 Sekunden</h3>
            <p>
                Nutzer verbringen anschließend 20 Minuten damit,
                die Antwort zu überprüfen.
            </p>
        </article>

        <article class="news-card">
            <span class="category">Welt</span>
            <h3>Die Erde hat eigentlich eine Bananenform</h3>
            <p>
               Diese Aussagen wurden von einem Hobbywissentschaftler (P. Häberli, ) gemacht, nachdem er ein paar lecker Bierchen getrunken hat
            </p>
        </article>

        <article class="news-card">
            <span class="category">Vermischtes</span>
            <h3>Mann öffnet Kühlschrank zum fünften Mal</h3>
            <p>
                Quellen berichten, dass sich der Inhalt seit dem
                letzten Öffnen nicht verändert hat.
            </p>
        </article>

    </section>

</div>

<footer>
    ©️ 2026  | • No Scemm
</footer>

</body>
</html>
