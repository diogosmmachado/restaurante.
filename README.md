# restaurante.
restaurantes-site/
│
├── index.html
├── style.css
└── script.js
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurantes</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Restaurantes da Cidade</h1>
    </header>
    <main>
        <h2>Lista de Restaurantes</h2>
        <ul>
            <li>Restaurante A</li>
            <li>Restaurante B</li>
            <li>Restaurante C</li>
        </ul>
    </main>
    <footer>
        <p>&copy; 2024 Restaurantes</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #f8f8f8;
    padding: 20px;
    text-align: center;
}

main {
    padding: 20px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #f8f8f8;
    position: relative;
    bottom: 0;
    width: 100%;
}
