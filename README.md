
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COMPANY SERVICE</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0; /* Jasnoszare tło */
        }

        .header {
            background-color: #0056b3; /* Niebieskie tło dla nagłówka */
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-bottom: 20px;
            font-size: 36px;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .sector-line {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }

        .sector {
            flex: 1;
            padding: 20px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin-right: 10px;
        }

        .sector img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .sector-description {
            flex: 2;
            padding: 20px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            margin-right: 10px;
        }

        .link-box {
            padding: 10px 20px;
            background-color: #0056b3;
            color: white;
            border-radius: 5px;
            text-align: center;
            cursor: pointer;
        }

        .link-box:hover {
            background-color: #003d80;
        }

        .link-box a {
            color: white;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="header">COMPANY SERVICE</div>
    <div class="container">
        <!-- Sektor 1 -->
        <div class="sector-line">
            <div class="sector">
                <img src="data:image/png;base64,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" alt="Grafika">
            </div>
            <div class="sector-description">
                Finansoweposilki.pl to nowa marka na rynku pożyczek online. Zaskoczył Cię wysoki rachunek za wodę? A może zepsuła Ci się lodówka i potrzebujesz sfinansować zakup nowej? Oferujemy ekspresowe wsparcie finansowe. Udzielamy pożyczek przez internet od 300 do 5000 zł na maksymalnie 30 dni. Gwarantujemy: minimum formalności, szybką decyzję oraz przelew gotówki na konto nawet w kilka minut. Wszystko po to, aby pomóc Ci opłacić pilne i niespodziewane rachunki.
            </div>
            <div class="link-box">
                <a href="https://redirecting8.eu/p/rJXM/P2mQ/s68L">Przejdź do strony</a>
            </div>
        </div>

        <!-- Sektor 2 -->
        <div class="sector-line">
            <div class="sector">
                <img src="your_image_url.jpg" alt="Grafika">
            </div>
            <div class="sector-description">
                Miejsce na opis
            </div>
            <div class="link-box">
                <a href="#">Przejdź do strony</a>
            </div>
        </div>

        <!-- Sektor 3 -->
        <div class="sector-line">
            <div class="sector">
                <img src="your_image_url.jpg" alt="Grafika">
            </div>
            <div class="sector-description">
                Miejsce na opis
            </div>
            <div class="link-box">
                <a href="#">Przejdź do strony</a>
            </div>
        </div>

        <!-- Sektor 4 -->
        <div class="sector-line">
            <div class="sector">
                <img src="your_image_url.jpg" alt="Grafika">
            </div>
            <div class="sector-description">
                Miejsce na opis
            </div>
            <div class="link-box">
                <a href="#">Przejdź do strony</a>
            </div>
        </div>

        <!-- Sektor 5 -->
        <div class="sector-line">
            <div class="sector">
                <img src="your_image_url.jpg" alt="Grafika">
            </div>
            <div class="sector-description">
                Miejsce na opis
            </div>
            <div class="link-box">
                <a href="#">Przejdź do strony</a>
            </div>
        </div>

        <!-- Sektor 6 -->
        <div class="sector-line">
            <div class="sector">
                <img src="your_image_url.jpg" alt="Grafika">
            </div>
            <div class="sector-description">
                Miejsce na opis
            </div>
            <div class="link-box">
                <a href="#">Przejdź do strony</a>
            </div>
        </div>

        <!-- Sektor 7 -->
        <div class="sector-line">
            <div class="sector">
                <img src="your_image_url.jpg" alt="Grafika">
            </div>
            <div class="sector-description">
                Miejsce na opis
            </div>
            <div class="link-box">
                <a href="#">Przejdź do strony</a>
            </div>
        </div>

        <!-- Sektor 8 -->
        <div class="sector-line">
            <div class="sector">
                <img src="your_image_url.jpg" alt="Grafika">
            </div>
            <div class="sector-description">
                Miejsce na opis
            </div>
            <div class="link-box">
                <a href="#">Przejdź do strony</a>
            </div>
        </div>

        <!-- Sektor 9 -->
        <div class="sector-line">
            <div class="sector">
                <img src="your_image_url.jpg" alt="Grafika">
            </div>
            <div class="sector-description">
                Miejsce na opis
            </div>
            <div class="link-box">
                <a href="#">Przejdź do strony</a>
            </div>
        </div>

        <!-- Sektor 10 -->
        <div class="sector-line">
            <div class="sector">
                <img src="your_image_url.jpg" alt="Grafika">
            </div>
            <div class="sector-description">
                Miejsce na opis
            </div>
            <div class="link-box">
                <a href="#">Przejdź do strony</a>
            </div>
        </div>

    </div>
</body>
</html>
