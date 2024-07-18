<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mes Travaux</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
        }
        header {
            background-color: #003366;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #00539C;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin: 20px;
            padding: 20px;
            width: 300px;
        }
        .card img {
            max-width: 100%;
            border-radius: 8px 8px 0 0;
        }
        footer {
            background-color: #003366;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mes Travaux</h1>
    </header>
    <nav>
        <a href="#cartes-de-visite">Cartes de Visite</a>
        <a href="#bloc-notes">Bloc-Notes</a>
        <a href="#calendriers">Calendriers</a>
        <a href="#horaires-forex">Horaires Forex</a>
    </nav>
    <section id="cartes-de-visite">
        <h2>Cartes de Visite</h2>
        <div class="container">
            <div class="card">
                <img src="exemple-carte1.jpg" alt="Exemple de Carte de Visite 1">
                <p>Carte de visite professionnelle avec design moderne.</p>
            </div>
            <div class="card">
                <img src="exemple-carte2.jpg" alt="Exemple de Carte de Visite 2">
                <p>Carte de visite créative pour les artistes et les créateurs.</p>
            </div>
        </div>
    </section>
    <section id="bloc-notes">
        <h2>Bloc-Notes</h2>
        <div class="container">
            <div class="card">
                <img src="exemple-blocnote1.jpg" alt="Exemple de Bloc-Notes 1">
                <p>Bloc-notes personnalisé pour une organisation optimale.</p>
            </div>
            <div class="card">
                <img src="exemple-blocnote2.jpg" alt="Exemple de Bloc-Notes 2">
                <p>Bloc-notes avec couverture en cuir et papier recyclé.</p>
            </div>
        </div>
    </section>
    <section id="calendriers">
        <h2>Calendriers</h2>
        <div class="container">
            <div class="card">
                <img src="exemple-calendrier1.jpg" alt="Exemple de Calendrier 1">
                <p>Calendrier mural avec photos personnalisées.</p>
            </div>
            <div class="card">
                <img src="exemple-calendrier2.jpg" alt="Exemple de Calendrier 2">
                <p>Calendrier de bureau pratique et élégant.</p>
            </div>
        </div>
    </section>
    <section id="horaires-forex">
        <h2>Horaires Forex</h2>
        <div class="container">
            <div class="card">
                <img src="exemple-horaire1.jpg" alt="Exemple d'Horaires Forex 1">
                <p>Tableau des horaires Forex avec les principales sessions de trading.</p>
            </div>
            <div class="card">
                <img src="exemple-horaire2.jpg" alt="Exemple d'Horaires Forex 2">
                <p>Horaires Forex détaillés pour une meilleure gestion du trading.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Mes Travaux. Tous droits réservés.</p>
    </footer>
</body>
</html>
