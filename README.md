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
        <img src="logo.png" alt="RioFly Aviation Logo" style="max-width: 150px; display: block; position: absolute; top: 20px; left: 20px;">
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
        <p>Na RioFly Aviation, contamos com uma frota diversificada e moderna, composta por helicópteros e aviões que atendem diferentes tipos de missão. Cada aeronave é rigorosamente mantida para garantir segurança, conforto e desempenho excepcionais. Conheça algumas das nossas principais aeronaves:</p>

        <h3>🚁 Frota Rotativa:</h3>
        <ul>
            <li><strong>R66:</strong> Helicóptero leve, ideal para voos executivos de curta distância e sobrevoos turísticos. Combina agilidade com baixo custo operacional.</li>
            <li><strong>AW109:</strong> Helicóptero biturbina, perfeito para missões VIP e traslados corporativos, com excelente desempenho e conforto superior.</li>
            <li><strong>Bell 407:</strong> Aeronave versátil, indicada tanto para transporte executivo quanto para operações especiais. Destaca-se pela confiabilidade e espaço interno.</li>
            <li><strong>Esquilo (AS350):</strong> Muito utilizado para voos panorâmicos e transporte em áreas de difícil acesso. Robusto e altamente adaptável.</li>
        </ul>

        <h3>🛩 Frota Fixa:</h3>
        <ul>
            <li><strong>Phenom 100:</strong> Jato leve, ideal para viagens rápidas e eficientes entre cidades próximas. Oferece conforto e rapidez.</li>
            <li><strong>Phenom 300:</strong> Jato executivo de médio porte, com autonomia para voos mais longos e capacidade para maior número de passageiros, mantendo alto padrão de luxo.</li>
            <li><strong>King Air B200:</strong> Turboélice bimotor, muito utilizado para operações em pistas curtas e aeroportos com infraestrutura limitada. Combina segurança e desempenho.</li>
            <li><strong>Citation CJ3:</strong> Jato executivo com excelente alcance e velocidade, ideal para voos regionais com conforto e eficiência.</li>
        </ul>
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
        <p>📧 Email: rioflyaviation@gmail.com</p>
        <p>💬 Discord: <a href="https://discord.gg/q4kZJX47" target="_blank">Clique aqui para entrar no nosso servidor</a></p>
        <p>📍 Base: SBJR - Jacarepaguá, Rio de Janeiro</p>
    </section>

    <footer>
        <p>&copy; 2025 RioFly Aviation - Todos os direitos reservados.</p>
    </footer>
</body>
</html>
