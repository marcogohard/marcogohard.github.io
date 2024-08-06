<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ocram Service</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e0e0e0;
            color: black;
        }
        header {
            background-color: black;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 2rem;
        }
        .panel {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            margin: 1rem;
            padding: 2rem;
            width: 300px;
            text-align: left;
            border: 2px solid black;
        }
        .panel img {
            max-width: 100px;
            margin-bottom: 1rem;
            display: block;
            margin-left: auto;
            margin-right: auto;
        }
        .panel h2 {
            text-align: center;
            color: #c500ff;
            background-color: #e0e0e0;
            padding: 5px;
            border-radius: 4px;
        }
        .price {
            font-weight: bold;
            color: #c500ff;
            margin: 10px 0;
            background-color: #e0e0e0;
            padding: 5px;
            border-radius: 4px;
            display: inline-block;
        }
        .service-overview {
            margin-top: 10px;
        }
        .service-overview h3 {
            color: #c500ff;
            background-color: #e0e0e0;
            padding: 5px;
            border-radius: 4px;
            display: inline-block;
        }
        .service-overview ul {
            padding-left: 20px;
            margin-top: 5px;
        }
        .service-overview li::marker {
            color: #c500ff;
        }
        footer {
            background-color: black;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ocram Service</h1>
    </header>

  <div class="container">
        <div class="panel">
            <img src="dazn-logo.png" alt="DAZN">
            <h2>DAZN</h2>
            <p class="price">Price: 6,99 euro</p>
            <div class="service-overview">
                <h3>Service Overview:</h3>
                <ul>
                    <li>All SerieA</li>
                    <li>All LaLiga</li>
                    <li>And much more</li>
                </ul>
            </div>
        </div>

 <div class="panel">
            <img src="netflix-logo.png" alt="Netflix">
            <h2>Netflix</h2>
            <p class="price">Price: 6,99 euro</p>
            <div class="service-overview">
                <h3>Service Overview:</h3>
                <p>This service will give you Netflix lifetime privileges. It allows you to watch Netflix from four devices at the same time and download to six, all in Ultra HD and without commercial interruptions.</p>
            </div>
        </div>
       <div class="panel">
            <img src="spotify-logo.png" alt="Spotify">
            <h2>Spotify</h2>
            <p class="price">Price: 6,99 euro</p>
            <div class="service-overview">
                <h3>Service Overview:</h3>
                <p>This service will give you Spotify premium lifetime privileges.</p>
                <ul>
                    <li>Ad-free music</li>
                    <li>Download for offline listening</li>
                    <li>Play tracks in any order</li>
                    <li>High audio quality</li>
                    <li>Listen with friends in real time</li>
                    <li>Organise your listening queue</li>
                </ul>
            </div>
        </div>

   <div class="panel">
            <img src="disney-plus-logo.png" alt="Disney Plus">
            <h2>Disney Plus</h2>
            <p class="price">Price: 6,99 euro</p>
            <div class="service-overview">
                <h3>Service Overview:</h3>
                <ul>
                    <li>All Disney movies and series</li>
                    <li>All Pixar movies and series</li>
                    <li>All Marvel movies and series</li>
                    <li>All Star Wars movies and series</li>
                    <li>National Geographic</li>
                    <li>Exclusive original programs</li>
                    <li>Documentaries</li>
                    <li>And much more</li>
                </ul>
            </div>
        </div>
    </div>

  <footer>
        <p>&copy; 2024 Ocram Service. Tutti i diritti riservati.</p>
    </footer>
</body>
</html>
