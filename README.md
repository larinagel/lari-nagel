<!DOCTYPE html>
<html lang="pt-BR">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Meu site básico</title>
        <link rel="stylesheet" href="styles.css">
    </head>
    <body>
        <header>
            <h1>Olá, mundo!</h1>
        </header>
        <main>
            <p>Este é um site simples com HTML, CSS e JavaScript.</p>
            <button onclick="mostrarAlerta()">Clique aqui</button>
        </main>
        <script src="script.js"></script>
    </body>
</html>
body {
    font-family: Arial, sans-serif;
    background-color: #f4f1f4;
    text-align: center;
    margin: 0;
    padding: 0;
}

h1 {
    color: #333;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    background-color: #4CAF50; /* Green background for the button */
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #45a049; /* Darker green when hovering */
}
function mostrarAlerta() {
    alert("Você clicou no botão!");
}
