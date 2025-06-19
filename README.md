<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lanna Cortivo Pereira - Portfólio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <div class="container">
            <h1>Lanna Cortivo Pereira</h1>
            <nav>
                <ul>
                    <li><a href="#sobre">Sobre</a></li>
                    <li><a href="#projetos">Projetos</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="inicio">
        <div class="container">
            <img src="https://i.pinimg.com/564x/64/b9/9e/64b99eb78e07d1f3e5b21be7b5202456.jpg" alt="Foto de Lanna" class="foto">
            <h2>Olá! Eu sou a Lanna 👋</h2>
            <p>Estudante do último ano do ensino médio e cursando pré-vestibular. Apaixonada por tecnologia, por aprender idiomas e explorar culturas diferentes.</p>
        </div>
    </section>

    <section id="sobre" class="sobre">
        <div class="container">
            <h2>Sobre mim</h2>
            <p>Sou uma pessoa curiosa, com aprendizado rápido, apaixonada por descobrir novas culturas, aprender idiomas e entender como as coisas funcionam. Estou começando minha jornada no mundo da tecnologia e sempre buscando aprender mais.</p>
        </div>
    </section>

    <section id="projetos" class="projetos">
        <div class="container">
            <h2>Projetos</h2>
            <p>Em breve você verá alguns projetos meus aqui! 🚀</p>
        </div>
    </section>

    <section id="contato" class="contato">
        <div class="container">
            <h2>Contato</h2>
            <p>Entre em contato comigo pelo email:</p>
            <p><a href="mailto:lanna.pereir4@gmail.com">lanna.pereir4@gmail.com</a></p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2025 Lanna Cortivo Pereira | Feito com ♥</p>
        </div>
    </footer>

</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f9f9f9;
    color: #333;
    line-height: 1.6;
}

.container {
    width: 90%;
    max-width: 1000px;
    margin: 0 auto;
}

header {
    background-color: #4e4bff;
    color: #fff;
    padding: 20px 0;
}

header h1 {
    text-align: center;
    font-size: 2.5rem;
}

header nav ul {
    display: flex;
    justify-content: center;
    gap: 30px;
    list-style: none;
    margin-top: 10px;
}

header nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

header nav a:hover {
    text-decoration: underline;
}

.inicio {
    text-align: center;
    padding: 50px 0;
}

.inicio .foto {
    width: 200px;
    border-radius: 100%;
    border: 5px solid #4e4bff;
    margin-bottom: 20px;
}

.inicio h2 {
    font-size: 2rem;
    margin-bottom: 10px;
}

.sobre, .projetos, .contato {
    background-color: #fff;
    margin: 20px 0;
    padding: 40px 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

.sobre h2, .projetos h2, .contato h2 {
    color: #4e4bff;
    margin-bottom: 20px;
}

footer {
    background-color: #4e4bff;
    color: white;
    text-align: center;
    padding: 15px 0;
}

a {
    color: #4e4bff;
}

a:hover {
    text-decoration: underline;
}
