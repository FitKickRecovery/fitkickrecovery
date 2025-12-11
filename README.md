
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FitKick Recovery – Sportverletzungen, Regeneration & Zubehör</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f5f7fa;
            color: #222;
        }

        header {
            background: #1a1f36;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header img {
            width: 160px;
            margin-bottom: 10px;
        }

        nav {
            background: #0e1226;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 12px;
            text-decoration: none;
            font-weight: bold;
        }

        .section {
            padding: 40px 20px;
            max-width: 1100px;
            margin: auto;
        }

        .section h2 {
            text-align: center;
            color: #1a1f36;
            margin-bottom: 25px;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .product-card {
            background: white;
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            text-align: center;
        }

        .product-card img {
            max-width: 100%;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .btn {
            display: block;
            background: #0077ff;
            color: white;
            padding: 12px;
            margin-top: 15px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
        }

        footer {
            background: #1a1f36;
            color: white;
            padding: 40px 20px;
            text-align: center;
            margin-top: 40px;
        }

        footer a {
            color: #88b4ff;
        }
    </style>
</head>

<body>

    <!-- HEADER -->
    <header>
        <img src="images/logo.png" alt="FitKick Recovery Logo">
        <h1>FitKick Recovery</h1>
        <p>Sportverletzungen • Regeneration • Trainingszubehör</p>
    </header>

    <!-- NAVIGATION -->
    <nav>
        <a href="#kids">Kinder</a>
        <a href="#adults">Erwachsene</a>
        <a href="#recovery">Recovery</a>
        <a href="#kontakt">Kontakt</a>
    </nav>

    <!-- KIDS SECTION -->
    <div class="section" id="kids">
        <h2>Kinder – Sport & Verletzungsprävention</h2>

        <div class="products">

            <div class="product-card">
                <img src="images/kids-bandage.jpg" alt="Bandage Kinder">
                <h3>Elastische Kinderbandage</h3>
                <p>Leichte Unterstützung für Knie, Fußgelenk oder Handgelenk.</p>
                <a class="btn" href="" target="_blank">Affiliate-Link</a>
            </div>

            <div class="product-card">
                <img src="images/kids-ball.jpg" alt="Kinder Fußball Soft">
                <h3>Weicher Trainings-Fußball</h3>
                <p>Perfekt für Indoor & Outdoor ohne Verletzungsgefahr.</p>
                <a class="btn" href="" target="_blank">Affiliate-Link</a>
            </div>

        </div>
    </div>

    <!-- ADULTS SECTION -->
    <div class="section" id="adults">
        <h2>Erwachsene – Sportverletzungen & Schutz</h2>

        <div class="products">

            <div class="product-card">
                <img src="images/adult-bandage.jpg" alt="Bandage Erwachsene">
                <h3>Kompressions-Kniebandage</h3>
                <p>Perfekt für Fußball, Fitness & Alltag.</p>
                <a class="btn" href="" target="_blank">Affiliate-Link</a>
            </div>

            <div class="product-card">
                <img src="images/tape.jpg" alt="Kinesio Tape">
                <h3>Kinesiologisches Tape</h3>
                <p>Unterstützt Muskeln & Gelenke bei Schmerzen oder kleinen Verletzungen.</p>
                <a class="btn" href="" target="_blank">Affiliate-Link</a>
            </div>

        </div>
    </div>

    <!-- RECOVERY -->    
    <div class="section" id="recovery">
        <h2>Recovery – Regeneration & Pflege</h2>

        <div class="products">

            <div class="product-card">
                <img src="images/massagegun.jpg" alt="Massagepistole">
                <h3>Massagepistole</h3>
                <p>Fördert Erholung nach Training & Verletzungen.</p>
                <a class="btn" href="" target="_blank">Affiliate-Link</a>
            </div>

            <div class="product-card">
                <img src="images/coldpack.jpg" alt="Kältepack">
                <h3>Kälte/Wärme Gel-Pack</h3>
                <p>Ideal bei Prellungen, Zerrungen & Schwellungen.</p>
                <a class="btn" href="" target="_blank">Affiliate-Link</a>
            </div>

        </div>
    </div>

    <!-- FOOTER -->
    <footer>
        <h3>FitKick Recovery</h3>
        <p>Affiliate-Website über Sportverletzungen & Regeneration.</p>

        <p><a href="#impressum">Impressum</a> • <a href="#datenschutz">Datenschutz</a></p>

        <div id="kontakt">
            <h4>Kontakt</h4>
            <p>Email: kontakt@fitkickrecovery.de</p>
        </div>

        <div id="impressum" style="margin-top:30px;">
            <h4>Impressum</h4>
            <p>Max Mustermann<br> Musterstraße 1<br> 12345 Musterstadt</p>
        </div>

        <div id="datenschutz" style="margin-top:30px;">
            <h4>Datenschutz</h4>
            <p>Diese Website nutzt Affiliate-Links. Als Amazon-Partner verdienen wir an qualifizierten Verkäufen.</p>
        </div>
    </footer>

</body>
</html>
