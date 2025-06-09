<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boxclub Zizou</title>

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">

    <style>
        body {
            margin: 0; /* Entfernt alle Standard-Margins */
            font-family: "Roboto", sans-serif;
        }

        .hintergrundbild1, .hintergrundbild2 {
            width: 100%;
            height: auto; /* Auto Höhe für das erste Bild */
            display: block; /* Stellt sicher, dass der Browser keine zusätzlichen Abstände einfügt */
        }

        .hintergrundbild2 {
            height: 100vh; /* Höhe für das zweite Bild */
            position: relative; /* Position für das Text-Overlay */
        }

        /* Überschrift und Slogan */
        .header {
            color: rgb(255, 255, 255);
            position: absolute;
            top: 10px;
            left: 50%;
            transform: translateX(-50%);
            text-align: center;
            z-index: 2; /* Text über Bildern */
        }

        .links {
            position: absolute;
            top: 50px;
            left: 20px;
            text-align: center;
            justify-content: space-between;
            font-size: 20px;
            font-family: "Roboto", sans-serif;
            z-index: 2; /* Links über Bildern */
        }

        /* Styling für Anker-Links */
        .links a {
            color: white; /* Linkfarbe */
            text-decoration: none; /* Entfernt Unterstreichung */
        }

        .links a:hover {
            color: #ffcc00; /* Farbe beim Hovern */
            text-decoration: underline; /* Unterstreichung beim Hovern */
        }

        /* Textbereich für Über uns */
        .Überuns {
            position: absolute; /* Absolute Positionierung für Text-Overlay */
            top: 20%; /* Vertikal zentrieren */
            left: 15%; /* Horizontal zentrieren */
            transform: translate(-50%, -50%); /* Zentrierung */
            text-align: center; /* Text zentrieren */
            color: white; /* Textfarbe */
            z-index: 2; /* Text über Bildern */
        }
    </style>
</head>
<body>

    <header>
        <div class="header">
            <h1>Boxclub Zizou</h1>
            <p><b>Wir machen einen Champion aus dir!</b></p>
        </div>

        <div class="links">
            <a href="#Überuns">Über uns</a>
            <a href="#Trainingszeiten">Trainingszeiten</a>
            <a href="#Kontakt">Kontakt</a>
        </div>
    </header>

    <img src="Bilder/box-1514845_1280.jpg" class="hintergrundbild1">
    
    <div class="hintergrundbild2">
        <img src="Bilder/Screenshot.png" style="width: 100%; height: 100%; object-fit: cover;">
        <div class="Überuns">
            <h2>Über uns</h2>
            <p>Wir machen dich zum Champion!</p>
            <p>Unseren erfolgreichen Verein</p>
            <p>der schon viele Turniere gewonnen hat</p>
            <p>gibt es schon seit 2000!</p>
        </div>
    </div>

</body>
</html>
