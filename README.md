# -SecureGuard-
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Secure Guard</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>Secure Guard</h1>
        <p>Protegendo seus dados com inovação e integridade desde 2004.</p>
    </header>

    <nav>
        <ul>
            <li><a href="#sobre">Sobre Nós</a></li>
            <li><a href="#missao">Missão</a></li>
            <li><a href="#valores">Valores</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>

    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>
            Bem-vindo à Secure Guard, líderes em proteção de dados desde 2004. Nosso compromisso é fornecer soluções inovadoras e seguras
            para garantir a integridade e confidencialidade dos seus dados.
        </p>
    </section>

    <section id="missao">
        <h2>Nossa Missão</h2>
        <p>
            Na Secure Guard, nossa missão é liderar a vanguarda da proteção de dados, capacitando organizações e indivíduos a salvaguardar
            suas informações mais preciosas. Compreendemos que os dados são ativos fundamentais na era digital, e é nosso compromisso assegurar
            que esses ativos sejam gerenciados com integridade, confidencialidade e respeito.
        </p>
    </section>

    <section id="valores">
        <h2>Nossos Valores</h2>
        <ul>
            <li><strong>Integridade:</strong> Agimos com honestidade e transparência em todos os aspectos do nosso trabalho, mantendo os mais altos padrões éticos.</li>
            <li><strong>Inovação Constante:</strong> Estamos comprometidos com a busca contínua por soluções inovadoras e práticas, antecipando as necessidades futuras de segurança de dados.</li>
            <li><strong>Empatia e Respeito:</strong> Valorizamos a diversidade e respeitamos as diferentes perspectivas. Nosso compromisso com a empatia impulsiona a criação de ambientes seguros e inclusivos.</li>
            <li><strong>Colaboração Ativa:</strong> Reconhecemos que a segurança de dados é um esforço coletivo. Trabalhamos em estreita colaboração com clientes, parceiros e a comunidade para fortalecer a segurança digital como um todo.</li>
            <li><strong>Educação e Capacitação:</strong> Buscamos capacitar indivíduos e organizações por meio da educação, fornecendo recursos e conhecimentos que promovam uma compreensão profunda e informada sobre a segurança de dados.</li>
            <li><strong>Responsabilidade Ambiental:</strong> Comprometemo-nos a minimizar nosso impacto ambiental, adotando práticas sustentáveis e promovendo a responsabilidade ambiental em todas as operações.</li>
            <li><strong>Adaptação à Mudança:</strong> Abraçamos a mudança como uma constante na paisagem da segurança cibernética, sendo ágeis e adaptáveis para enfrentar os desafios emergentes.</li>
            <li><strong>Compromisso com a Privacidade:</strong> A privacidade é um direito fundamental. Comprometemo-nos a proteger a privacidade dos indivíduos e a promover práticas que respeitem esse direito.</li>
        </ul>
    </section>

    <section id="contato">
        <h2>Entre em Contato</h2>
        <form id="contactForm">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="mensagem">Mensagem:</label>
            <textarea id="mensagem" name="mensagem" required></textarea>

            <button type="submit">Enviar Mensagem</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Secure Guard</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    background-color: #f8f8f8;
}

header {
    background-color: #2c3e50;
    color: white;
    text-align: center;
    padding: 20px;
}

nav {
    background-color: #34495e;
