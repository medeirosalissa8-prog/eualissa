<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vestibular UEA 2025 - Guia Completo de Estudos</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #006400;
            --secondary: #228B22;
            --accent: #32CD32;
            --light: #F5F5F5;
            --dark: #333;
            --text: #333;
            --bg: #f9f9f9;
            --card-bg: white;
            --shadow: 0 4px 6px rgba(0,0,0,0.1);
            --transition: all 0.3s ease;
        }

        .dark-mode {
            --primary: #4CAF50;
            --secondary: #388E3C;
            --accent: #8BC34A;
            --light: #2C2C2C;
            --dark: #F5F5F5;
            --text: #F5F5F5;
            --bg: #1E1E1E;
            --card-bg: #2C2C2C;
            --shadow: 0 4px 6px rgba(0,0,0,0.3);
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            transition: var(--transition);
        }
        
        body {
            background-color: var(--bg);
            color: var(--text);
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), var(--secondary));
            color: white;
            padding: 1.5rem;
            text-align: center;
            box-shadow: var(--shadow);
            position: relative;
        }
        
        .header-content {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .top-bar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 100%;
            margin-bottom: 1rem;
        }
        
        .theme-switch {
            background: rgba(255, 255, 255, 0.2);
            border: none;
            color: white;
            padding: 0.5rem 1rem;
            border-radius: 20px;
            cursor: pointer;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .logo-container {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1rem;
        }
        
        .logo {
            font-size: 2.5rem;
            margin-right: 1rem;
        }
        
        h1 {
            font-size: 2.2rem;
            margin-bottom: 0.5rem;
        }
        
        .subtitle {
            font-size: 1.1rem;
            opacity: 0.9;
        }
        
        .search-container {
            width: 100%;
            max-width: 600px;
            margin: 1rem auto;
        }
        
        .search-box {
            width: 100%;
            padding: 0.8rem 1.5rem;
            border-radius: 30px;
            border: none;
            box-shadow: var(--shadow);
            font-size: 1rem;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        .filters {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            margin-bottom: 2rem;
            justify-content: center;
        }
        
        .filter-btn {
            padding: 0.5rem 1.5rem;
            border-radius: 20px;
            border: 2px solid var(--primary);
            background: transparent;
            color: var(--primary);
            cursor: pointer;
            font-weight: 500;
        }
        
        .filter-btn.active, .filter-btn:hover {
            background: var(--primary);
            color: white;
        }
        
        .intro {
            text-align: center;
            margin-bottom: 2.5rem;
            padding: 2rem;
            background: var(--card-bg);
            border-radius: 10px;
            box-shadow: var(--shadow);
        }
        
        .intro p {
            margin-bottom: 1.5rem;
            font-size: 1.1rem;
        }
        
        .countdown {
            background: var(--primary);
            color: white;
            padding: 1rem;
            border-radius: 10px;
            margin: 1rem 0;
            display: inline-block;
        }
        
        .disciplinas-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 2rem;
            margin-bottom: 3rem;
        }
        
        .disciplina-card {
            background: var(--card-bg);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: transform 0.3s ease;
            height: 100%;
            display: flex;
            flex-direction: column;
        }
        
        .disciplina-card:hover {
            transform: translateY(-5px);
        }
        
        .card-header {
            background: var(--primary);
            color: white;
            padding: 1.2rem;
            font-size: 1.3rem;
            font-weight: bold;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .card-toggle {
            background: none;
            border: none;
            color: white;
            cursor: pointer;
            font-size: 1.2rem;
        }
        
        .card-body {
            padding: 1.5rem;
            flex-grow: 1;
        }
        
        .card-body ul {
            list-style-type: none;
        }
        
        .card-body li {
            padding: 0.5rem 0;
            border-bottom: 1px solid #eee;
        }
        
        .card-body li:last-child {
            border-bottom: none;
        }
        
        .card-body li::before {
            content: "•";
            color: var(--accent);
            font-weight: bold;
            display: inline-block;
            width: 1em;
            margin-left: -1em;
        }
        
        .card-footer {
            padding: 1rem 1.5rem;
            background: #f5f5f5;
            display: flex;
            justify-content: space-between;
        }
        
        .card-btn {
            padding: 0.5rem 1rem;
            border-radius: 5px;
            border: none;
            background: var(--secondary);
            color: white;
            cursor: pointer;
            display: flex;
            align-items: center;
            gap: 0.5rem;
        }
        
        .obras-literarias {
            background: var(--card-bg);
            border-radius: 10px;
            padding: 2rem;
            margin-bottom: 2.5rem;
            box-shadow: var(--shadow);
        }
        
        .obras-header {
            color: var(--primary);
            margin-bottom: 1.5rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--accent);
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .obra-item {
            margin-bottom: 1.5rem;
            padding: 1rem;
            background: rgba(0, 0, 0, 0.05);
            border-radius: 8px;
            border-left: 4px solid var(--secondary);
        }
        
        .dicas-estudo {
            background: var(--card-bg);
            border-radius: 10px;
            padding: 2rem;
            margin-bottom: 2.5rem;
            box-shadow: var(--shadow);
        }
        
        .dicas-header {
            color: var(--primary);
            margin-bottom: 1.5rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--accent);
        }
        
        .simulado-section {
            background: var(--card-bg);
            border-radius: 10px;
            padding: 2rem;
            margin-bottom: 2.5rem;
            box-shadow: var(--shadow);
        }
        
        .simulado-header {
            color: var(--primary);
            margin-bottom: 1.5rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid var(--accent);
        }
        
        .question {
            margin-bottom: 1.5rem;
            padding: 1rem;
            background: rgba(0, 0, 0, 0.05);
            border-radius: 8px;
        }
        
        .options {
            margin-top: 0.5rem;
        }
        
        .option {
            margin: 0.5rem 0;
        }
        
        .submit-btn {
            padding: 0.8rem 1.5rem;
            border-radius: 5px;
            border: none;
            background: var(--primary);
            color: white;
            cursor: pointer;
            font-size: 1rem;
            margin-top: 1rem;
        }
        
        footer {
            background: var(--dark);
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 2rem;
        }
        
        .footer-content {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 1rem;
        }
        
        .social-links a {
            color: white;
            font-size: 1.5rem;
        }
        
        .hidden {
            display: none;
        }
        
        @media (max-width: 768px) {
            .disciplinas-grid {
                grid-template-columns: 1fr;
            }
            
            h1 {
                font-size: 1.8rem;
            }
            
            .filters {
                flex-direction: column;
                align-items: center;
            }
            
            .top-bar {
                flex-direction: column;
                gap: 1rem;
            }
        }
        
        /* Animações */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .animate {
            animation: fadeIn 0.5s ease forwards;
        }
        
        .delay-1 { animation-delay: 0.1s; }
        .delay-2 { animation-delay: 0.2s; }
        .delay-3 { animation-delay: 0.3s; }
        .delay-4 { animation-delay: 0.4s; }
        .delay-5 { animation-delay: 0.5s; }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <div class="top-bar">
                <button class="theme-switch" id="themeSwitch">
                    <i class="fas fa-moon"></i> Modo Escuro
                </button>
                <div class="logo-container">
                    <span class="logo">📚</span>
                    <div>
                        <h1>Vestibular UEA 2025</h1>
                        <p class="subtitle">Guia Completo de Estudos</p>
                    </div>
                </div>
                <div></div> <!-- Elemento vazio para alinhamento -->
            </div>
            
            <div class="search-container">
                <input type="text" class="search-box" id="searchInput" placeholder="Pesquisar assunto...">
            </div>
        </div>
    </header>
    
    <div class="container">
        <section class="intro animate">
            <h2>Prepare-se para o Vestibular da Universidade do Estado do Amazonas</h2>
            <p>Este guia contém todo o conteúdo programático do vestibular UEA 2025, organizado por disciplinas e tópicos. Utilize este material para planejar seus estudos e garantir sua aprovação!</p>
            
            <div class="countdown">
                <p>Faltam <strong id="days">120</strong> dias para o vestibular!</p>
            </div>
        </section>
        
        <div class="filters">
            <button class="filter-btn active" data-filter="all">Todas</button>
            <button class="filter-btn" data-filter="humanas">Humanas</button>
            <button class="filter-btn" data-filter="exatas">Exatas</button>
            <button class="filter-btn" data-filter="biologicas">Biológicas</button>
            <button class="filter-btn" data-filter="linguagens">Linguagens</button>
        </div>
        
        <section class="disciplinas-grid">
            <div class="disciplina-card animate delay-1" data-category="linguagens">
                <div class="card-header">
                    <span>Língua Portuguesa</span>
                    <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="card-body">
                    <ul>
                        <li>Gêneros textuais: podcast, jornalísticos, acadêmicos, informativos</li>
                        <li>Recursos expressivos e discursivos</li>
                        <li>Coesão e coerência textual</li>
                        <li>Sintaxe: verbos modais, tempos e modos verbais</li>
                        <li>Concordância e regência verbal e nominal</li>
                        <li>Variações linguísticas</li>
                        <li>Literatura brasileira: Quinhentismo, Barroco, Arcadismo</li>
                        <li>Literatura portuguesa</li>
                        <li>Literatura indígena, africana e marginal</li>
                        <li>Intertextualidade e interdiscursividade</li>
                        <li>Análise linguística/semiótica</li>
                        <li>Norma culta e coloquialismo</li>
                        <li>Paráfrase, paródia e estilizações</li>
                    </ul>
                </div>
                <div class="card-footer">
                    <button class="card-btn"><i class="fas fa-book"></i> Ver Mais</button>
                    <button class="card-btn"><i class="fas fa-question-circle"></i> Simulados</button>
                </div>
            </div>
            
            <div class="disciplina-card animate delay-1" data-category="linguagens">
                <div class="card-header">
                    <span>Redação</span>
                    <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="card-body">
                    <ul>
                        <li>Texto dissertativo-argumentativo</li>
                        <li>Estruturação de ideias</li>
                        <li>Argumentação e contra-argumentação</li>
                        <li>Norma culta da língua portuguesa</li>
                        <li>Coerência e coesão textual</li>
                        <li>Tese e desenvolvimento</li>
                        <li>Elementos de persuasão</li>
                        <li>Recursos argumentativos</li>
                        <li>Hierarquia das informações</li>
                        <li>Diferenciação entre fatos e opiniões</li>
                    </ul>
                </div>
                <div class="card-footer">
                    <button class="card-btn"><i class="fas fa-book"></i> Ver Mais</button>
                    <button class="card-btn"><i class="fas fa-question-circle"></i> Simulados</button>
                </div>
            </div>
            
            <div class="disciplina-card animate delay-2" data-category="linguagens">
                <div class="card-header">
                    <span>Arte</span>
                    <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="card-body">
                    <ul>
                        <li>Artes visuais, dança, música e teatro</li>
                        <li>Patrimônio material e imaterial</li>
                        <li>Contextos político, histórico e cultural</li>
                        <li>Diversidade linguística na arte</li>
                        <li>Manifestações artísticas amazônicas</li>
                        <li>Tecnologias digitais na arte</li>
                        <li>Estereótipos e preconceitos na arte</li>
                        <li>Estilos de produção artística</li>
                        <li>Gêneros e estilos artísticos</li>
                        <li>Fruição estética das produções</li>
                        <li>Circulação de produções artísticas</li>
                    </ul>
                </div>
                <div class="card-footer">
                    <button class="card-btn"><i class="fas fa-book"></i> Ver Mais</button>
                    <button class="card-btn"><i class="fas fa-question-circle"></i> Simulados</button>
                </div>
            </div>
            
            <div class="disciplina-card animate delay-2" data-category="linguagens">
                <div class="card-header">
                    <span>Língua Inglesa</span>
                    <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="card-body">
                    <ul>
                        <li>Compreensão e interpretação textual</li>
                        <li>Análise de discursos globalizados</li>
                        <li>Textos normativos e legais</li>
                        <li>Variantes da língua inglesa</li>
                        <li>Manifestações artísticas e culturais</li>
                        <li>Análise de textos publicitários</li>
                        <li>Posicionamento crítico frente a fake news</li>
                        <li>Inglês como língua global</li>
                        <li>Recursos linguísticos e multissemióticos</li>
                        <li>Apreciação crítica de livros, filmes, música</li>
                    </ul>
                </div>
                <div class="card-footer">
                    <button class="card-btn"><i class="fas fa-book"></i> Ver Mais</button>
                    <button class="card-btn"><i class="fas fa-question-circle"></i> Simulados</button>
                </div>
            </div>
            
            <div class="disciplina-card animate delay-3" data-category="exatas">
                <div class="card-header">
                    <span>Matemática</span>
                    <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="card-body">
                    <ul>
                        <li>Números e álgebra: razão, proporção, porcentagem</li>
                        <li>Juros simples e composto</li>
                        <li>Sistema Internacional de medidas</li>
                        <li>Funções: 1º e 2º grau, exponencial, logarítmica</li>
                        <li>Trigonometria: seno, cosseno, relações métricas</li>
                        <li>Matemática financeira</li>
                        <li>Geometria: perímetro, área, volume</li>
                        <li>Polígonos regulares e projeções cartográficas</li>
                        <li>Probabilidade e estatística</li>
                        <li>Matrizes, determinantes e sistemas lineares</li>
                        <li>Geometria espacial: prismas, pirâmides, cones</li>
                        <li>Princípio de Cavalieri</li>
                    </ul>
                </div>
                <div class="card-footer">
                    <button class="card-btn"><i class="fas fa-book"></i> Ver Mais</button>
                    <button class="card-btn"><i class="fas fa-question-circle"></i> Simulados</button>
                </div>
            </div>
            
            <div class="disciplina-card animate delay-3" data-category="humanas">
                <div class="card-header">
                    <span>História</span>
                    <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="card-body">
                    <ul>
                        <li>Mundo antigo: Grécia, Roma, África, Oriente</li>
                        <li>Brasil Colonial e Imperial</li>
                        <li>República e movimentos sociais</li>
                        <li>Regimes militares e redemocratização</li>
                        <li>Guerra Fria e nova ordem mundial</li>
                        <li>História do Amazonas e da Amazônia</li>
                        <li>Questões indígenas e quilombolas</li>
                        <li>Período áureo da Borracha</li>
                        <li>SUDAM, SUFRAMA e Zona Franca de Manaus</li>
                        <li>Pluralidade étnica e cultural no Amazonas</li>
                        <li>Movimentos sociais: negro, indígena, feminista, LGBTQ+</li>
                    </ul>
                </div>
                <div class="card-footer">
                    <button class="card-btn"><i class="fas fa-book"></i> Ver Mais</button>
                    <button class="card-btn"><i class="fas fa-question-circle"></i> Simulados</button>
                </div>
            </div>
            
            <div class="disciplina-card animate delay-4" data-category="humanas">
                <div class="card-header">
                    <span>Geografia</span>
                    <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="card-body">
                    <ul>
                        <li>Cartografia e representações espaciais</li>
                        <li>População e indicadores socioeconômicos</li>
                        <li>Globalização e blocos econômicos</li>
                        <li>Questões ambientais e sustentabilidade</li>
                        <li>Geografia do Amazonas e da Amazônia</li>
                        <li>Conflitos territoriais e movimentos sociais</li>
                        <li>Relações de trabalho e empreendedorismo</li>
                        <li>Biomas brasileiros e conservação ambiental</li>
                        <li>Territórios indígenas e quilombolas</li>
                        <li>Urbanização e problemas urbanos</li>
                        <li>Recursos hídricos e questões energéticas</li>
                    </ul>
                </div>
                <div class="card-footer">
                    <button class="card-btn"><i class="fas fa-book"></i> Ver Mais</button>
                    <button class="card-btn"><i class="fas fa-question-circle"></i> Simulados</button>
                </div>
            </div>
            
            <div class="disciplina-card animate delay-4" data-category="humanas">
                <div class="card-header">
                    <span>Filosofia</span>
                    <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="card-body">
                    <ul>
                        <li>Ética e moral</li>
                        <li>Diversidade cultural brasileira e amazônica</li>
                        <li>Filosofia política e Estado Democrático</li>
                        <li>Bioética e tecnologias</li>
                        <li>Filosofia da arte e indústria cultural</li>
                        <li>Questões de gênero, raça e etnia</li>
                        <li>Trabalho e dignidade humana</li>
                        <li>Filosofia ambiental e desenvolvimento sustentável</li>
                        <li>Filosofia e Literatura Amazonense</li>
                        <li>Direitos Humanos e Desigualdade</li>
                        <li>Pensamento decolonial</li>
                    </ul>
                </div>
                <div class="card-footer">
                    <button class="card-btn"><i class="fas fa-book"></i> Ver Mais</button>
                    <button class="card-btn"><i class="fas fa-question-circle"></i> Simulados</button>
                </div>
            </div>
            
            <div class="disciplina-card animate delay-5" data-category="humanas">
                <div class="card-header">
                    <span>Sociologia</span>
                    <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="card-body">
                    <ul>
                        <li>Relações sociais e conflitos interétnicos</li>
                        <li>Pensamento decolonial</li>
                        <li>Manifestações religiosas na Amazônia</li>
                        <li>Movimentos sociais e participação política</li>
                        <li>Globalização e sociedade em rede</li>
                        <li>Questões ambientais e sociedade de riscos</li>
                        <li>Trabalho e relações de production</li>
                        <li>Organização social indígena e afrodescendente</li>
                        <li>Democracia, Cidadania e Direitos Humanos</li>
                        <li>Economia e trabalho na sociedade capitalista</li>
                        <li>Desigualdade social e exclusão</li>
                    </ul>
                </div>
                <div class="card-footer">
                    <button class="card-btn"><i class="fas fa-book"></i> Ver Mais</button>
                    <button class="card-btn"><i class="fas fa-question-circle"></i> Simulados</button>
                </div>
            </div>
            
            <div class="disciplina-card animate delay-5" data-category="biologicas">
                <div class="card-header">
                    <span>Biologia</span>
                    <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="card-body">
                    <ul>
                        <li>Citologia e organização celular</li>
                        <li>Origem da vida e evolução</li>
                        <li>Genética e biotecnologia</li>
                        <li>Ecologia e conservação ambiental</li>
                        <li>Saúde e nutrição</li>
                        <li>Corpo humano: tecidos e sistemas</li>
                        <li>Biologia molecular e DNA</li>
                        <li>Ciclos biogeoquímicos</li>
                        <li>Biodiversidade amazônica</li>
                        <li>Transgênicos e agrotóxicos</li>
                        <li>IST's e métodos contraceptivos</li>
                        <li>Genética mendeliana</li>
                    </ul>
                </div>
                <div class="card-footer">
                    <button class="card-btn"><i class="fas fa-book"></i> Ver Mais</button>
                    <button class="card-btn"><i class="fas fa-question-circle"></i> Simulados</button>
                </div>
            </div>
            
            <div class="disciplina-card animate delay-5" data-category="exatas">
                <div class="card-header">
                    <span>Física</span>
                    <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="card-body">
                    <ul>
                        <li>Conceitos fundamentais (espaço, tempo, energia)</li>
                        <li>Astrofísica e astronomia</li>
                        <li>Dinâmica e leis de Newton</li>
                        <li>Termologia e calor</li>
                        <li>Ondas e acústica</li>
                        <li>Eletricidade e magnetismo</li>
                        <li>Física moderna e nuclear</li>
                        <li>Máquinas térmicas e energia</li>
                        <li>Óptica: reflexão, refração e lentes</li>
                        <li>Energias renováveis e matriz energética</li>
                        <li>Radioatividade e aplicações</li>
                    </ul>
                </div>
                <div class="card-footer">
                    <button class="card-btn"><i class="fas fa-book"></i> Ver Mais</button>
                    <button class="card-btn"><i class="fas fa-question-circle"></i> Simulados</button>
                </div>
            </div>
            
            <div class="disciplina-card animate delay-5" data-category="exatas">
                <div class="card-header">
                    <span>Química</span>
                    <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
                </div>
                <div class="card-body">
                    <ul>
                        <li>Estrutura atômica e tabela periódica</li>
                        <li>Ligações químicas e funções inorgânicas</li>
                        <li>Reações químicas e estequiometria</li>
                        <li>Termoquímica e cinética química</li>
                        <li>Eletroquímica e corrosão</li>
                        <li>Química orgânica e funções orgânicas</li>
                        <li>Química ambiental e sustentabilidade</li>
                        <li>Química na Amazônia: recursos naturais</li>
                        <li>Poluição e tratamento de água e esgoto</li>
                        <li>Biocombustíveis e química verde</li>
                        <li>Polímeros e materiais sintéticos</li>
                    </ul>
                </div>
                <div class="card-footer">
                    <button class="card-btn"><i class="fas fa-book"></i> Ver Mais</button>
                    <button class="card-btn"><i class="fas fa-question-circle"></i> Simulados</button>
                </div>
            </div>
        </section>
        
        <section class="obras-literarias">
            <div class="obras-header">
                <h2>Obras Literárias Obrigatórias</h2>
                <button class="card-toggle"><i class="fas fa-chevron-down"></i></button>
            </div>
            <div class="obra-content">
                <div class="obra-item">
                    <h3>Macunaíma - Mário de Andrade</h3>
                    <p>Publicado em 1928, esta obra é um marco do Modernismo brasileiro. O romance apresenta o "herói sem nenhum caráter" que representa as contradições do povo brasileiro, misturando lendas, mitos e tradições de diferentes regiões do Brasil.</p>
                    <p><strong>Temas principais:</strong> identidade nacional, cultura brasileira, sincretismo cultural, mitologia indígena</p>
                </div>
                
                <div class="obra-item">
                    <h3>Triste Fim de Policarpo Quaresma - Lima Barreto</h3>
                    <p>Publicado em 1915, esta obra é uma sátira ao nacionalismo exagerado e às mazelas da República Velha. A história segue o major Quaresma, um patriota extremado que propõe o tupi-guarani como língua oficial do Brasil.</p>
                    <p><strong>Temas principais:</strong> nacionalismo, burocracia, realidade social brasileira, idealismo</p>
                </div>
                
                <div class="obra-item">
                    <h3>Caligrafia de Deus - Márcio Souza</h3>
                    <p>Obra representativa da literatura amazonense, que aborda questões regionais com profundidade. Márcio Souza é um dos principais escritores da Amazônia, conhecido por retratar a complexidade social e cultural da região.</p>
                    <p><strong>Temas principais:</strong> realidade amazônica, identidade regional, conflitos sociais, cultura local</p>
                </div>
            </div>
        </section>
        
        <section class="simulado-section">
            <div class="simulado-header">
                <h2>Simulado Online</h2>
                <p>Teste seus conhecimentos com questões do vestibular UEA</p>
            </div>
            
            <div class="question">
                <p><strong>1. (UEA 2022)</strong> Sobre a obra "Macunaíma" de Mário de Andrade, é correto afirmar:</p>
                <div class="options">
                    <div class="option">
                        <input type="radio" name="q1" id="q1a">
                        <label for="q1a">a) É uma obra que segue rigidamente os padrões do romance realista do século XIX.</label>
                    </div>
                    <div class="option">
                        <input type="radio" name="q1" id="q1b">
                        <label for="q1b">b) Apresenta um herói sem caráter, representante das contradições do povo brasileiro.</label>
                    </div>
                    <div class="option">
                        <input type="radio" name="q1" id="q1c">
                        <label for="q1c">c) Foi escrita no período do Quinhentismo brasileiro.</label>
                    </div>
                    <div class="option">
                        <input type="radio" name="q1" id="q1d">
                        <label for="q1d">d) Tem como cenário principal o sertão nordestino.</label>
                    </div>
                </div>
            </div>
            
            <div class="question">
                <p><strong>2. (UEA 2022)</strong> Sobre o período áureo da borracha na Amazônia, é correto afirmar:</p>
                <div class="options">
                    <div class="option">
                        <input type="radio" name="q2" id="q2a">
                        <label for="q2a">a) Teve início no século XVII, com a descoberta das seringueiras.</label>
                    </div>
                    <div class="option">
                        <input type="radio" name="q2" id="q2b">
                        <label for="q2b">b) Ocorreu entre meados do século XIX e início do século XX.</label>
                    </div>
                    <div class="option">
                        <input type="radio" name="q2" id="q2c">
                        <label for="q2c">c) Beneficiou principalmente a população indígena da região.</label>
                    </div>
                    <div class="option">
                        <input type="radio" name="q2" id="q2d">
                        <label for="q2d">d) Teve pouco impacto na economia brasileira da época.</label>
                    </div>
                </div>
            </div>
            
            <button class="submit-btn">Enviar Respostas</button>
        </section>
        
        <section class="dicas-estudo">
            <h2 class="dicas-header">Dicas de Estudo</h2>
            <ul>
                <li><strong>Planejamento:</strong> Organize um cronograma de estudos que cubra todas as disciplinas ao longo da semana.</li>
                <li><strong>Leitura das obras:</strong> Leia as obras literárias obrigatórias com atenção, fazendo anotações sobre personagens, enredo e contextos históricos.</li>
                <li><strong>Resolução de exercícios:</strong> Pratique com questões de vestibulares anteriores para se familiarizar com o estilo da prova.</li>
                <li><strong>Redação:</strong> Treine a produção de textos dissertativo-argumentativos semanalmente, com diferentes temas.</li>
                <li><strong>Revisões periódicas:</strong> Reserve tempo para revisar conteúdos já estudados, consolidando o aprendizado.</li>
                <li><strong>Estudo ativo:</strong> Faça resumos, mapas mentais e explique os conteúdos para outras pessoas.</li>
                <li><strong>Descanso e saúde:</strong> Mantenha uma rotina equilibrada com horas de sono adequadas, alimentação balanceada e prática de exercícios físicos.</li>
            </ul>
        </section>
    </div>
    
    <footer>
        <div class="footer-content">
            <p>Site de Estudos para o Vestibular UEA 2025</p>
            <p>Desenvolvido com base no conteúdo programático oficial</p>
            <div class="social-links">
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-youtube"></i></a>
                <a href="#"><i class="fab fa-tiktok"></i></a>
            </div>
        </div>
    </footer>

    <script>
        // Alternar modo escuro/claro
        const themeSwitch = document.getElementById('themeSwitch');
        themeSwitch.addEventListener('click', () => {
            document.body.classList.toggle('dark-mode');
            if (document.body.classList.contains('dark-mode')) {
                themeSwitch.innerHTML = '<i class="fas fa-sun"></i> Modo Claro';
            } else {
                themeSwitch.innerHTML = '<i class="fas fa-moon"></i> Modo Escuro';
            }
        });

        // Filtros de disciplinas
        const filterButtons = document.querySelectorAll('.filter-btn');
        const disciplinaCards = document.querySelectorAll('.disciplina-card');
        
        filterButtons.forEach(button => {
            button.addEventListener('click', () => {
                // Remover classe active de todos os botões
                filterButtons.forEach(btn => btn.classList.remove('active'));
                // Adicionar classe active ao botão clicado
                button.classList.add('active');
                
                const filter = button.getAttribute('data-filter');
                
                disciplinaCards.forEach(card => {
                    if (filter === 'all') {
                        card.style.display = 'flex';
                    } else {
                        if (card.getAttribute('data-category') === filter) {
                            card.style.display = 'flex';
                        } else {
                            card.style.display = 'none';
                        }
                    }
                });
            });
        });

        // Busca de conteúdos
        const searchInput = document.getElementById('searchInput');
        searchInput.addEventListener('keyup', () => {
            const searchTerm = searchInput.value.toLowerCase();
            
            disciplinaCards.forEach(card => {
                const cardContent = card.textContent.toLowerCase();
                if (cardContent.includes(searchTerm)) {
                    card.style.display = 'flex';
                } else {
                    card.style.display = 'none';
                }
            });
        });

        // Contador regressivo para o vestibular (exemplo: 1 de dezembro de 2025)
        function updateCountdown() {
            const now = new Date();
            const vestDate = new Date('2025-12-01');
            const diff = vestDate - now;
            
            const days = Math.floor(diff / (1000 * 60 * 60 * 24));
            document.getElementById('days').textContent = days;
        }
        
        updateCountdown();
        
        // Botões de expandir/recolher
        const toggleButtons = document.querySelectorAll('.card-toggle');
        toggleButtons.forEach(button => {
            button.addEventListener('click', () => {
                const cardBody = button.closest('.card-header').nextElementSibling;
                cardBody.classList.toggle('hidden');
                
                if (cardBody.classList.contains('hidden')) {
                    button.innerHTML = '<i class="fas fa-chevron-down"></i>';
                } else {
                    button.innerHTML = '<i class="fas fa-chevron-up"></i>';
                }
            });
        });

        // Animação de entrada dos elementos
        document.addEventListener('DOMContentLoaded', () => {
            const animatedElements = document.querySelectorAll('.animate');
            animatedElements.forEach(element => {
                element.style.opacity = '0';
            });
            
            setTimeout(() => {
                animatedElements.forEach(element => {
                    element.style.opacity = '1';
                });
            }, 100);
        });
    </script>
</body>
</html>
