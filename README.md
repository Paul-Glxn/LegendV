<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Legend V - GTA RP PS4</title>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Grundlegende Styles */
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Roboto', sans-serif;
            background: linear-gradient(135deg, #1a1a1a, #0f0f0f);
            color: #fff;
            scroll-behavior: smooth;
        }
        header {
            background: #0d0d0d;
            text-align: center;
            padding: 60px 20px;
        }
        header h1 {
            font-family: 'Orbitron', sans-serif;
            font-size: 3rem;
            color: #ff0055;
            text-shadow: 2px 2px #000;
        }
        header p {
            font-size: 1.2rem;
            margin-top: 10px;
            color: #ccc;
        }

        /* Navigation */
        nav {
            position: sticky;
            top: 0;
            background: #111;
            padding: 10px 0;
            text-align: center;
            z-index: 100;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
        }
        nav a:hover {
            color: #ff0055;
        }

        /* Sektionen */
        section {
            padding: 80px 20px;
            max-width: 1200px;
            margin: auto;
        }
        section h2 {
            font-family: 'Orbitron', sans-serif;
            font-size: 2.5rem;
            color: #ff0055;
            text-align: center;
            margin-bottom: 40px;
        }
        section p {
            font-size: 1.1rem;
            line-height: 1.8;
            text-align: center;
            max-width: 900px;
            margin: auto;
            color: #ccc;
        }

        /* Features */
        .features {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-top: 40px;
        }
        .feature-box {
            background: #1a1a1a;
            border: 2px solid #ff0055;
            border-radius: 15px;
            padding: 30px;
            flex: 1 1 250px;
            text-align: center;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .feature-box:hover {
            transform: translateY(-10px);
            box-shadow: 0 0 20px #ff0055;
        }
        .feature-box h3 {
            font-family: 'Orbitron', sans-serif;
            font-size: 1.5rem;
            margin-bottom: 15px;
        }

        /* Discord Widget */
        .discord-widget {
            text-align: center;
            margin-top: 50px;
        }
        .discord-widget iframe {
            border-radius: 15px;
            border: 2px solid #ff0055;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 40px 20px;
            background: #0d0d0d;
            color: #777;
        }

        @media(max-width:768px){
            .features { flex-direction: column; }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Legend V</h1>
        <p>Wir beleben die PS4 RP Szene neu und bringen GTA RP auf ein neues Level!</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#features">Features</a>
        <a href="#about">Über Legend V</a>
        <a href="#discord">Discord</a>
    </nav>

    <!-- Features Section -->
    <section id="features">
        <h2>Unsere Features</h2>
        <div class="features">
            <div class="feature-box">
                <h3>Team Dashboard</h3>
                <p>Behalte alle wichtigen Infos im Überblick – Teammeetings, Abmeldungen und mehr direkt auf Discord.</p>
            </div>
            <div class="feature-box">
                <h3>Eigene Webseiten</h3>
                <p>Alles strukturiert und stylisch – dein Zugang zu Legend V jederzeit online.</p>
            </div>
            <div class="feature-box">
                <h3>PS4 RP</h3>
                <p>Erlebe GTA RP auf der PS4 wie nie zuvor – realistische Rollen, Events und actionreiche Missionen.</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>Über Legend V</h2>
        <p>
            Legend V ist mehr als ein Server – es ist eine Community, die GTA RP neu definiert.  
            Tritt ein, lerne neue Leute kennen und schreibe deine eigene Legende in Los Santos.  
            Ob Teamspieler, Solo-Abenteurer oder Story-Liebhaber – bei uns findet jeder seinen Platz.
        </p>
    </section>

    <!-- Discord Section -->
    <section id="discord">
        <h2>Join uns auf Discord</h2>
        <p>Tritt unserer Community bei, chatte, plane Events und bleibe immer up-to-date!</p>
        <div class="discord-widget">
            <iframe src="https://discordapp.com/widget?id=1438534888281210984&theme=dark" width="350" height="500" allowtransparency="true" frameborder="0" sandbox="allow-popups allow-popups-to-escape-sandbox allow-same-origin allow-scripts"></iframe>
        </div>
        <p style="margin-top:20px;">Direkter Link: <a href="https://discord.gg/2yvhHA6c3P" target="_blank" style="color:#ff0055;">discord.gg/2yvhHA6c3P</a></p>
    </section>

    <!-- Footer -->
    <footer>
        &copy; 2025 Legend V | GTA 5 RP PS4 | Alle Rechte vorbehalten
    </footer>

</body>
</html>
