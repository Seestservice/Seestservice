<!DOCTYPE html>
<html lang="da">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SeestsService - Bilvask & Græsslåning</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; }
        header { background-color: #4A00E0; color: white; padding: 10px 0; text-align: center; }
        nav { display: flex; justify-content: center; background-color: #6A00E0; }
        nav a { padding: 14px 20px; color: white; text-decoration: none; }
        nav a:hover { background-color: #4700B3; }
        .container { padding: 20px; }
        .service { margin-bottom: 30px; }
        .prisliste { display: flex; justify-content: space-around; margin-top: 30px; }
        .pris { border: 1px solid #ddd; padding: 20px; background-color: white; text-align: center; }
        footer { background-color: #4A00E0; color: white; text-align: center; padding: 10px 0; position: fixed; width: 100%; bottom: 0; }
    </style>
</head>
<body>

    <header>
        <h1>SeestsService</h1>
        <p>Bilvask, Græsslåning, Vinduespudsning & Hækkeklipning</p>
    </header>

    <nav>
        <a href="#home">Hjem</a>
        <a href="#services">Services</a>
        <a href="#prisliste">Prisliste</a>
        <a href="#kontakt">Kontakt</a>
    </nav>

    <div class="container" id="home">
        <h2>Velkommen til SeestsService</h2>
        <p>Vi tilbyder professionel bilvask, græsslåning, vinduespudsning og hækkeklipning. Kontakt os i dag for et godt tilbud!</p>
    </div>

    <div class="container" id="services">
        <h2>Vores Services</h2>
        <div class="service">
            <h3>Bilvask</h3>
            <p>Vi tilbyder tre forskellige pakker: Bronze, Sølv og Guld. Se vores prisliste for flere detaljer.</p>
        </div>
        <div class="service">
            <h3>Græsslåning</h3>
            <p>Vi tilbyder professionel græsslåning. Kontakt os for at få et skræddersyet tilbud.</p>
        </div>
        <div class="service">
            <h3>Vinduespudsning</h3>
            <p>Vi pudser dine vinduer både indendørs og udendørs.</p>
        </div>
        <div class="service">
            <h3>Hækkeklipning</h3>
            <p>Vi klipper din hæk præcist og omhyggeligt.</p>
        </div>
    </div>

    <div class="container" id="prisliste">
        <h2>Prisliste</h2>
        <div class="prisliste">
            <div class="pris">
                <h3>Bronze</h3>
                <p>Støvsugning af måtter og hele bilen</p>
                <p><strong>125 kr.</strong></p>
            </div>
            <div class="pris">
                <h3>Sølv</h3>
                <p>Rengøring af måtter, sæder og støvsugning</p>
                <p><strong>225 kr.</strong></p>
            </div>
            <div class="pris">
                <h3>Guld</h3>
                <p>Dampvask, rengøring af døre og plast</p>
                <p><strong>300 kr.</strong></p>
            </div>
        </div>
    </div>

    <div class="container" id="kontakt">
        <h2>Kontakt os</h2>
        <p>Telefon: +45 20921314</p>
        <p>Email: info@seestsservice.dk</p>
        <p>Find os på sociale medier:</p>
        <p>
            <a href="#">Facebook</a> |
            <a href="#">Instagram</a> |
            <a href="https://wa.me/4520921314">WhatsApp</a>
        </p>
    </div>

    <footer>
        <p>© 2024 SeestsService - Alle rettigheder forbeholdes</p>
    </footer>

</body>
</html>
