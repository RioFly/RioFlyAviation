<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RioFly Aviation - Táxi Aéreo</title>
    <style>
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #333;
        }
        header {
            background: linear-gradient(135deg, #002244, #004488);
            color: white;
            padding: 80px 20px;
            text-align: center;
            position: relative;
        }
        header h1 {
            margin: 0;
            font-size: 3.5em;
            letter-spacing: 2px;
        }
        header p {
            font-size: 1.3em;
            margin-top: 10px;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #001d3d;
        }
        nav li {
            margin: 0 20px;
        }
        nav li a {
            display: block;
            color: white;
            text-decoration: none;
            padding: 15px;
            font-weight: bold;
            transition: background-color 0.3s, color 0.3s;
        }
        nav li a:hover {
            background-color: #003f7d;
            color: #ffd700;
            border-radius: 5px;
        }
        .banner {
            background-image: url('https://images.unsplash.com/photo-1541807084-5c52b6b30f5b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80');
            background-size: cover;
            background-position: center;
            color: white;
            text-align: center;
            padding: 120px 20px;
        }
        .banner h2 {
            font-size: 2.8em;
            margin: 0;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        section {
            max-width: 1200px;
            margin: 40px auto;
            padding: 20px;
        }
        section h2 {
            color: #002244;
            border-bottom: 2px solid #004488;
            padding-bottom: 10px;
        }
        section p, section ul {
            font-size: 1.1em;
            line-height: 1.6;
        }
        ul li {
            margin-bottom: 8px;
        }
        footer {
            background-color: #001d3d;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://media.discordapp.net/attachments/1268995649362333760/1385640335224340571/1750373219340.png?ex=6856cd9f&is=68557c1f&hm=4a5f402a3e5e1314ea0b3fa737dadae930add7bc5311fe0a818f5485e7a1dc1f&=&format=webp&quality=lossless" alt="RioFly Aviation Logo" style="max-width: 150px; display: block; position: absolute; top: 20px; left: 20px; background-color: transparent;">

        <h1>RioFly Aviation</h1>
        <p>Táxi Aéreo - Conectando Destinos com Excelência!</p>
    </header>

    <nav>
        <ul>
            <li><a href="#home">Início</a></li>
            <li><a href="#sobre">Sobre Nós</a></li>
            <li><a href="#frota">Frota</a></li>
            <li><a href="#servicos">Serviços</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>

    <div class="banner" id="home">
        <h2>Voe alto com segurança, conforto e tecnologia de ponta!</h2>
    </div>

    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>A RioFly Aviation é referência em táxi aéreo executivo no Rio de Janeiro. Baseados em Jacarepaguá (SBJR), oferecemos soluções de transporte aéreo sob medida, com foco em segurança, agilidade e atendimento personalizado.</p>
    </section>

    <section id="frota">
        <h2>Nossa Frota</h2>
        <p>Dispomos de aeronaves modernas e versáteis para diferentes tipos de missão. Desde turboélices eficientes até jatos executivos de alto desempenho, nossa frota garante conforto e pontualidade em cada voo.</p>
    </section>

    <section id="servicos">
        <h2>Serviços</h2>
        <ul>
            <li>Atendemos todo o Brasil</li>
            <li>Destinos mais requisitados:
                <ul>
                    <li>Angra dos Reis</li>
                    <li>São Paulo (Congonhas / Campo de Marte)</li>
                    <li>Búzios</li>
                    <li>Belo Horizonte</li>
                    <li>Brasília</li>
                </ul>
            </li>
            <li>Voos fretados</li>
            <li>Transporte VIP</li>
            <li>Voos de turismo</li>
            <li>Eventos e campanhas especiais</li>
        </ul>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <p>📧 Email: contato@rioflyaviation.com</p>
        <p>💬 Discord: <a href="https://discord.gg/q4kZJX47" target="_blank">Clique aqui para entrar no nosso servidor</a></p>
        <p>📍 Base: SBJR - Jacarepaguá, Rio de Janeiro</p>
    </section>

    <footer>
        <p>&copy; 2025 RioFly Aviation - Todos os direitos reservados.</p>
    </footer>
</body>
</html>
