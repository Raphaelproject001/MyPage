<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Página com CSS</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bem-vindo à Minha Página!</h1>
    </header>
    
    <main>
        <section>
            <h2>Sobre</h2>
            <p>Este é um parágrafo de exemplo. Aqui você pode adicionar informações sobre o que você quiser.</p>
        </section>
        
        <section>
            <h2>Contato</h2>
            <p>Você pode me contatar pelo e-mail exemplo@dominio.com.</p>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2024 Minha Página</p>
    </footer>
</body>
</html>
/* Reset básico de margens e paddings */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

header h1 {
    margin: 0;
}

main {
    padding: 1rem;
}

section {
    margin-bottom: 1rem;
    padding: 1rem;
    background: #fff;
    border-radius: 5px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
    position: fixed;
    width: 100%;
    bottom: 0;
}
