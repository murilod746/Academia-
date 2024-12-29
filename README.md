<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academia Exemplo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5; /* Cor de fundo neutra */
            color: #333; /* Cor do texto neutra */
        }
        header {
            background-color: #fff; /* Cor de fundo do cabeçalho neutra */
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Sombra sutil para destaque */
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        .banner {
            background-image: url('banner.jpg'); /* Substitua pelo caminho da sua imagem */
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #fff;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 40px;
        }
        footer {
            background-color: #fff;
            text-align: center;
            padding: 10px;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <header>
        <h1>Academia Exemplo</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#sobre">Sobre Nós</a>
            <a href="#planos">Planos e Preços</a>
            <a href="#horarios">Horários de Aulas</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>
    <section class="banner" id="home">
        <h2>Bem-vindo à Academia Exemplo</h2>
    </section>
    <div class="container">
        <section class="section" id="sobre">
            <h2>Sobre Nós</h2>
            <p>Bem-vindo à Academia Exemplo, onde sua saúde e bem-estar são nossa prioridade. Oferecemos uma variedade de equipamentos modernos e aulas para atender às suas necessidades de fitness.</p>
        </section>
        <section class="section" id="planos">
            <h2>Planos e Preços</h2>
            <ul>
                <li>Plano Mensal: R$100</li>
                <li>Plano Trimestral: R$270</li>
                <li>Plano Anual: R$1000</li>
            </ul>
        </section>
        <section class="section" id="horarios">
            <h2>Horários de Aulas</h2>
            <p>Consulte nossa grade de aulas para encontrar o melhor horário para você.</p>
        </section>
        <section class="section" id="contato">
            <h2>Contato</h2>
            <form>
                <label for="nome">Nome:</label><br>
                <input type="text" id="nome" name="nome"><br>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email"><br>
                <label for="mensagem">Mensagem:</label><br>
                <textarea id="mensagem" name="mensagem"></textarea><br>
                <input type="submit" value="Enviar">
            </form>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Academia Exemplo. Todos os direitos reservados.</p>
    </footer>
</body>
</html>