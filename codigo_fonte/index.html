<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SysAgent | Neuropedagogia & Alta Performance</title>
    <style>
        /* =========================================
           CSS MODERNO: VARIÁVEIS, TEMAS E DESIGN SYSTEM
           ========================================= */
        :root {
            /* Paleta de Cores (Dark Mode Nativo) */
            --bg-base: #0f172a;
            --bg-surface: #1e293b;
            --bg-elevated: #334155;
            --text-primary: #f8fafc;
            --text-secondary: #cbd5e1;
            
            /* Cores de Destaque */
            --accent-primary: #38bdf8; /* Azul Tech */
            --accent-secondary: #818cf8; /* Roxo Intermediário */
            --accent-tertiary: #10b981; /* Verde Sucesso */
            --accent-danger: #ef4444; /* Vermelho Alerta */
            
            /* Espaçamentos e Bordas */
            --radius-md: 8px;
            --radius-lg: 16px;
            --transition-smooth: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        /* Reset Básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
        }

        body {
            background-color: var(--bg-base);
            color: var(--text-primary);
            min-height: 100vh;
            overflow-x: hidden;
        }

        /* =========================================
           LAYOUT: FLEXBOX E CSS GRID RESPONSIVOS
           ========================================= */
        .app-layout {
            display: flex;
            flex-direction: column;
            width: 100%;
        }

        @media (min-width: 1024px) {
            .app-layout { flex-direction: row; }
        }

        /* --- ASIDE: Barra Lateral Semântica --- */
        aside.sidebar {
            width: 100%;
            background-color: var(--bg-surface);
            border-right: 1px solid var(--bg-elevated);
            padding: 24px;
            display: flex;
            flex-direction: column;
            gap: 24px;
            z-index: 10;
        }

        @media (min-width: 1024px) {
            aside.sidebar {
                width: 350px;
                position: sticky;
                top: 0;
                height: 100vh;
            }
        }

        .agent-header h1 {
            font-size: 1.6rem;
            color: var(--accent-primary);
            margin-bottom: 4px;
        }

        /* Pseudo-classes e Navegação */
        nav.main-nav ul {
            list-style: none;
            display: flex;
            flex-direction: column;
            gap: 8px;
        }

        .nav-btn {
            width: 100%;
            text-align: left;
            padding: 14px 16px;
            background: transparent;
            border: 1px solid transparent;
            color: var(--text-secondary);
            border-radius: var(--radius-md);
            cursor: pointer;
            font-size: 1rem;
            font-weight: 500;
            transition: var(--transition-smooth);
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .nav-btn:hover, .nav-btn:focus-visible {
            background-color: rgba(56, 189, 248, 0.1);
            color: var(--accent-primary);
            outline: none;
        }

        .nav-btn[data-state="active"] {
            background-color: rgba(56, 189, 248, 0.15);
            color: var(--accent-primary);
            border-left: 4px solid var(--accent-primary);
        }

        /* Widget Pomodoro (Estados e Efeitos) */
        section.agent-widget {
            margin-top: auto;
            background-color: var(--bg-base);
            padding: 24px;
            border-radius: var(--radius-lg);
            border: 1px solid var(--bg-elevated);
            text-align: center;
        }

        .timer-display {
            font-size: 3.5rem;
            font-family: 'Courier New', Courier, monospace;
            font-weight: 700;
            color: var(--accent-tertiary);
            margin: 16px 0;
            letter-spacing: -2px;
        }

        .controls { display: flex; gap: 8px; justify-content: center; }

        .btn-core {
            padding: 10px 20px;
            border: none;
            border-radius: var(--radius-md);
            font-weight: bold;
            cursor: pointer;
            transition: var(--transition-smooth);
            color: white;
        }

        .btn-core:active { transform: scale(0.95); }
        .btn-core:disabled { opacity: 0.5; cursor: not-allowed; }
        
        .btn-start { background-color: var(--accent-tertiary); }
        .btn-start:hover:not(:disabled) { background-color: #059669; box-shadow: 0 4px 12px rgba(16, 185, 129, 0.3); }
        
        .btn-reset { background-color: var(--bg-elevated); color: var(--text-primary); }
        .btn-reset:hover { background-color: var(--accent-danger); }

        .stats-panel {
            margin-top: 16px;
            padding-top: 16px;
            border-top: 1px dashed var(--bg-elevated);
            font-size: 0.85rem;
            color: var(--text-secondary);
        }

        /* --- MAIN: Área Principal --- */
        main.content-area {
            flex: 1;
            padding: 24px;
            max-width: 1400px;
            margin: 0 auto;
        }

        @media (min-width: 1024px) {
            main.content-area { padding: 48px; }
        }

        /* =========================================
           ANIMAÇÕES KEYFRAMES (CSS Nativo)
           ========================================= */
        @keyframes slideFadeIn {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        .panel-view {
            display: none;
            animation: slideFadeIn 0.5s cubic-bezier(0.4, 0, 0.2, 1) forwards;
        }

        .panel-view[data-state="active"] { display: block; }

        /* --- Componentes do Cronograma --- */
        .view-header { margin-bottom: 32px; }
        .view-header h2 { font-size: 2.2rem; color: var(--text-primary); }
        .view-header p { color: var(--text-secondary); font-size: 1.1rem; margin-top: 8px; }

        /* Carousel Horizontal para os Dias de Folga */
        nav.days-track {
            display: flex;
            gap: 12px;
            overflow-x: auto;
            padding-bottom: 16px;
            margin-bottom: 32px;
            scrollbar-width: thin;
            scrollbar-color: var(--accent-primary) var(--bg-elevated);
        }

        nav.days-track::-webkit-scrollbar { height: 8px; }
        nav.days-track::-webkit-scrollbar-track { background: var(--bg-elevated); border-radius: 10px; }
        nav.days-track::-webkit-scrollbar-thumb { background: var(--accent-primary); border-radius: 10px; }

        .day-tab {
            flex: 0 0 auto;
            padding: 12px 24px;
            background-color: var(--bg-surface);
            border: 1px solid var(--bg-elevated);
            border-radius: var(--radius-lg);
            cursor: pointer;
            text-align: center;
            transition: var(--transition-smooth);
        }

        .day-tab:hover, .day-tab[data-selected="true"] {
            border-color: var(--accent-secondary);
            background-color: rgba(129, 140, 248, 0.15);
            transform: translateY(-2px);
        }

        /* CSS Grid para estruturar Timeline vs Contexto */
        .schedule-grid {
            display: grid;
            gap: 24px;
        }

        @media (min-width: 1024px) {
            .schedule-grid { grid-template-columns: 2fr 1fr; }
        }

        /* Lista da Timeline */
        .timeline-container {
            background-color: var(--bg-surface);
            border-radius: var(--radius-lg);
            border: 1px solid var(--bg-elevated);
            padding: 32px;
        }

        .timeline-list {
            margin-left: 16px;
            border-left: 2px solid var(--bg-elevated);
            padding-left: 32px;
            display: flex;
            flex-direction: column;
            gap: 32px;
        }

        /* Estilização dos Cards (Pseudo-elementos ::before) */
        .study-card {
            position: relative;
            background-color: var(--bg-base);
            border: 1px solid var(--bg-elevated);
            border-radius: var(--radius-md);
            padding: 24px;
            transition: var(--transition-smooth);
            opacity: 0;
            animation: slideFadeIn 0.4s ease forwards;
        }

        .study-card:hover {
            border-color: var(--accent-primary);
            box-shadow: 0 8px 24px rgba(0,0,0,0.2);
        }

        /* Bolinha da Timeline feita com CSS puro */
        .study-card::before {
            content: '';
            position: absolute;
            left: -41px;
            top: 24px;
            width: 16px;
            height: 16px;
            background-color: var(--bg-elevated);
            border: 3px solid var(--bg-surface);
            border-radius: 50%;
            transition: var(--transition-smooth);
        }

        .study-card[data-type="academic"]::before { background-color: var(--accent-primary); box-shadow: 0 0 12px var(--accent-primary); }
        .study-card[data-type="practical"]::before { background-color: var(--accent-secondary); box-shadow: 0 0 12px var(--accent-secondary); }

        .time-badge {
            display: inline-block;
            color: var(--accent-primary);
            font-weight: 700;
            font-size: 0.9rem;
            margin-bottom: 12px;
            background-color: rgba(56, 189, 248, 0.1);
            padding: 4px 12px;
            border-radius: 20px;
        }

        .card-summary {
            font-size: 0.95rem;
            color: var(--text-secondary);
            line-height: 1.6;
            margin-bottom: 20px;
            background-color: rgba(255,255,255,0.02);
            padding: 16px;
            border-left: 3px solid var(--bg-elevated);
            border-radius: 0 var(--radius-md) var(--radius-md) 0;
        }

        /* Botões de Links */
        .link-group h4 {
            font-size: 0.85rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: var(--text-secondary);
            margin-bottom: 12px;
            margin-top: 16px;
        }

        .link-row { display: flex; flex-wrap: wrap; gap: 8px; }

        .resource-btn {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 8px 16px;
            border-radius: 6px;
            font-size: 0.85rem;
            font-weight: 600;
            text-decoration: none;
            transition: var(--transition-smooth);
            border: 1px solid transparent;
        }

        .btn-pdf { background-color: rgba(239, 68, 68, 0.1); color: #fca5a5; border-color: rgba(239, 68, 68, 0.2); }
        .btn-pdf:hover { background-color: rgba(239, 68, 68, 0.2); color: #fff; }
        
        .btn-yt { background-color: rgba(249, 115, 22, 0.1); color: #fdba74; border-color: rgba(249, 115, 22, 0.2); }
        .btn-yt:hover { background-color: rgba(249, 115, 22, 0.2); color: #fff; }

        /* --- ASIDE: Contexto e Dicas --- */
        .context-sidebar { display: flex; flex-direction: column; gap: 24px; }
        .context-card { background-color: var(--bg-surface); padding: 24px; border-radius: var(--radius-lg); border: 1px solid var(--bg-elevated); }

        /* =========================================
           APIs NATIVAS DO HTML5 (<details> e <dialog>)
           ========================================= */
        details.method-item {
            background-color: var(--bg-surface);
            border: 1px solid var(--bg-elevated);
            border-radius: var(--radius-md);
            margin-bottom: 16px;
            overflow: hidden;
        }

        details.method-item summary {
            padding: 20px;
            font-weight: bold;
            color: var(--accent-secondary);
            cursor: pointer;
            list-style: none; /* Remove seta padrão */
            display: flex;
            justify-content: space-between;
        }

        details.method-item summary::-webkit-details-marker { display: none; }
        details.method-item summary::after { content: '↓'; transition: transform 0.3s; }
        details.method-item[open] summary::after { transform: rotate(180deg); }

        details.method-item .detail-content {
            padding: 0 20px 20px 20px;
            color: var(--text-secondary);
            line-height: 1.6;
        }

        /* Modal Nativo Otimizado */
        dialog.native-modal {
            margin: auto;
            padding: 32px;
            background-color: var(--bg-surface);
            color: var(--text-primary);
            border: 1px solid var(--accent-primary);
            border-radius: var(--radius-lg);
            max-width: 500px;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5);
        }

        dialog.native-modal::backdrop {
            background-color: rgba(15, 23, 42, 0.85);
            backdrop-filter: blur(4px);
        }
    </style>
</head>
<body>

    <div class="app-layout">
        <aside class="sidebar">
            <header class="agent-header">
                <h1>SysAgent</h1>
                <p style="color: var(--text-secondary); font-size: 0.9rem;">Mentor Neuropedagógico 12x36</p>
            </header>

            <nav class="main-nav" aria-label="Navegação Principal do Sistema">
                <ul>
                    <li><button class="nav-btn" data-target="schedule" data-state="active">📅 Matriz de Execução</button></li>
                    <li><button class="nav-btn" data-target="methodology" data-state="inactive">🧠 Protocolo R.E.A.L.</button></li>
                </ul>
            </nav>

            <section class="agent-widget" aria-label="Timer Pomodoro (50/10)">
                <h3 style="font-size: 1.1rem; color: var(--text-primary);">Foco Profundo (50/10)</h3>
                <div class="timer-display" id="timerOutput" aria-live="polite">50:00</div>
                <div class="controls">
                    <button class="btn-core btn-start" id="btnStartTimer">Iniciar Imersão</button>
                    <button class="btn-core btn-reset" id="btnResetTimer">Zerar</button>
                </div>
                <div class="stats-panel">
                    Carga cognitiva consolidada:<br>
                    <strong style="color: var(--accent-tertiary); font-size: 1.2rem;"><span id="focusMinutes">0</span> Minutos</strong>
                </div>
            </section>
        </aside>

        <main class="content-area">
            
            <section id="schedule" class="panel-view" data-state="active">
                <header class="view-header">
                    <h2>Mapeamento de Folgas e Acadêmico</h2>
                    <p>O algoritmo consolidou sua escala 12x36. Selecione o dia para compilar os materiais necessários.</p>
                </header>

                <nav class="days-track" id="daysTrackContainer" aria-label="Dias de Folga Computados">
                    </nav>

                <div class="schedule-grid">
                    <article class="timeline-container">
                        <h3 id="currentDateHeader" style="color: var(--accent-primary); margin-bottom: 32px; font-size: 1.5rem;">Carregando Interface...</h3>
                        <div class="timeline-list" id="timelineList">
                            </div>
                    </article>

                    <aside class="context-sidebar">
                        <article class="context-card">
                            <h3 style="color: var(--accent-secondary); margin-bottom: 16px;">Agente Fetch (API Externa)</h3>
                            <blockquote id="apiMotivation" style="font-style: italic; color: var(--text-secondary); line-height: 1.5; border-left: 2px solid var(--accent-secondary); padding-left: 12px;">
                                Acessando servidor de inteligência...
                            </blockquote>
                        </article>
                        
                        <article class="context-card">
                            <h3 style="color: var(--accent-tertiary); margin-bottom: 16px;">Arquitetura de Hardware</h3>
                            <p style="color: var(--text-secondary); font-size: 0.95rem; line-height: 1.6;">
                                O processador i5-8400 é excelente para a descompactação rápida de binários de jogos. Utilize o monitor 144Hz para notar frames não renderizados ao realizar o depuramento (debug) no DuckStation após a injeção do código hexadecimal, consolidando o conhecimento da aula noturna.
                            </p>
                        </article>
                    </aside>
                </div>
            </section>

            <section id="methodology" class="panel-view" data-state="inactive">
                <header class="view-header">
                    <h2>Protocolo de Retenção Neural</h2>
                    <p>Aplicando ciência da computação e neuropedagogia para contornar a fadiga do plantão.</p>
                </header>

                <article>
                    <details class="method-item" open>
                        <summary>1. Boot Cognitivo (07h30)</summary>
                        <div class="detail-content">
                            A escala 12x36 drena a capacidade de tomada de decisões. Ao acordar, seu córtex pré-frontal está limpo. Esta é a janela ideal para absorver tópicos abstratos e matemáticos densos (Arquitetura de Computadores II e Criptografia DFIR).
                        </div>
                    </details>
                    <details class="method-item">
                        <summary>2. Prática Intercalada (Interleaving)</summary>
                        <div class="detail-content">
                            Estudar o mesmo assunto o dia inteiro gera a "Ilusão de Fluência". O sistema divide o dia mudando o contexto drasticamente: da Teoria de Hardware (Manhã) para a Prática com Emuladores e Modding (Tarde), finalizando com a Aula Presencial (Noite). Essa quebra constante força a recuperação sináptica.
                        </div>
                    </details>
                    <details class="method-item">
                        <summary>3. Evocação Ativa e Descanso Visual</summary>
                        <div class="detail-content">
                            <strong>No ciclo Pomodoro (50/10):</strong> Estude 50 minutos ininterruptos. Nos 10 minutos de pausa, feche as abas. Explique em voz alta o que compreendeu do material lido. Mais importante: afaste-se do monitor. A memória de longo prazo é consolidada na pausa, não durante a leitura ativa.
                        </div>
                    </details>
                </article>
            </section>
        </main>
    </div>

    <dialog id="welcomeDialog" class="native-modal">
        <h2 style="color: var(--accent-primary); margin-bottom: 16px;">Sistemas Operacionais Otimizados</h2>
        <p style="color: var(--text-secondary); line-height: 1.6; margin-bottom: 24px;">
            A estrutura analisou sua escala. Os dias trabalhados (ímpares de maio, pares de junho) foram isolados. Seus dias de folga (28/05, 30/05 e os ímpares de junho) foram pré-compilados com resumos, PDFs e múltiplas aulas do YouTube.
        </p>
        <button id="btnCloseDialog" class="btn-core btn-start" style="width: 100%;">Conectar ao Servidor Local</button>
    </dialog>

    <script>
        /**
         * 1. BANCO DE DADOS (JSON Structure)
         * Mapeamento minucioso dos resumos táticos e múltiplos links (PDFs e YouTube)
         */
        const studyResources = {
            arqOrg: {
                summary: "Fundamentação Teórica. Abordagem sobre o fluxo de datagramas, pipeline de execução e como a CPU gerencia a hierarquia de memória cache.",
                pdfs: [
                    { title: "Livro Texto: Stallings (PDF)", url: "https://www.google.com/search?q=filetype:pdf+Arquitetura+e+Organiza%C3%A7%C3%A3o+de+Computadores+Stallings" },
                    { title: "Resumo: Pipeline e Processadores", url: "https://www.google.com/search?q=filetype:pdf+Pipeline+Arquitetura+de+Computadores" }
                ],
                vids: [
                    { title: "Vídeo 1: Pipeline e Hazards Explicados", url: "https://www.youtube.com/results?search_query=Pipeline+Arquitetura+de+Computadores" },
                    { title: "Vídeo 2: Memória Cache na Prática", url: "https://www.youtube.com/results?search_query=Memoria+Cache+Mapeamento" },
                    { title: "Vídeo 3: Modelo OSI e Datagramas", url: "https://www.youtube.com/results?search_query=Fragmenta%C3%A7%C3%A3o+de+Datagramas+Redes" }
                ]
            },
            labArq: {
                summary: "Aplicação da Lógica. O estudo do Assembly MIPS é a base que permite a compreensão e manipulação do código durante a Engenharia Reversa de jogos.",
                pdfs: [
                    { title: "Manual Prático: Assembly MIPS", url: "https://www.google.com/search?q=filetype:pdf+Linguagem+Assembly+MIPS+Instru%C3%A7%C3%B5es" }
                ],
                vids: [
                    { title: "Vídeo 1: Curso de MIPS Prático", url: "https://www.youtube.com/results?search_query=Assembly+MIPS+Tutorial+Pratico" },
                    { title: "Vídeo 2: Opcodes e Ghidra", url: "https://www.youtube.com/results?search_query=Ghidra+MIPS+Assembly+An%C3%A1lise" }
                ]
            },
            filosofia: {
                summary: "Raciocínio Crítico. A filosofia moderna molda o pensamento analítico necessário para debugar códigos e estruturar a arquitetura de softwares de grande porte.",
                pdfs: [
                    { title: "Fichamento: Razão e Modernidade", url: "https://www.google.com/search?q=filetype:pdf+Filosofia+Raz%C3%A3o+e+Modernidade+Descartes" }
                ],
                vids: [
                    { title: "Vídeo 1: Racionalismo (Descartes)", url: "https://www.youtube.com/results?search_query=Filosofia+Moderna+Racionalismo" },
                    { title: "Vídeo 2: Criticismo Kantiano", url: "https://www.youtube.com/results?search_query=Kant+Critica+da+Razao+Pura+Resumo" }
                ]
            },
            tai: {
                summary: "Estruturação de Projetos e Frontend. O Trabalho Acadêmico Integrado exige rigor na documentação ABNT e a construção de interfaces Web limpas usando HTML, CSS e JavaScript.",
                pdfs: [
                    { title: "Manual Oficial Normas ABNT", url: "https://www.google.com/search?q=filetype:pdf+Metodologia+Cientifica+ABNT+Projetos" },
                    { title: "Arquitetura Frontend", url: "https://www.google.com/search?q=filetype:pdf+Arquitetura+Frontend+Projetos+de+Interface" }
                ],
                vids: [
                    { title: "Vídeo 1: Formatação ABNT Completa", url: "https://www.youtube.com/results?search_query=Trabalho+Academico+ABNT+Formatacao" },
                    { title: "Vídeo 2: Construindo Layouts com CSS Grid", url: "https://www.youtube.com/results?search_query=CSS+Grid+Layout+Tutorial" },
                    { title: "Vídeo 3: Boas Práticas GitHub", url: "https://www.youtube.com/results?search_query=Git+Commit+Boas+Praticas" }
                ]
            },
            seguranca: {
                summary: "Cybersegurança e Forense Computacional. Estudo profundo do hash SHA-256 e MD5, além da prática de ataques baseados em dicionários documentados em relatórios técnicos.",
                pdfs: [
                    { title: "Guia Completo DFIR", url: "https://www.google.com/search?q=filetype:pdf+Computa%C3%A7%C3%A3o+Forense+DFIR+Criptografia" },
                    { title: "Paper: Ataques Hashcat", url: "https://www.google.com/search?q=filetype:pdf+Hashcat+Dictionary+Attack+Tutorial" }
                ],
                vids: [
                    { title: "Vídeo 1: A Matemática do SHA-256", url: "https://www.youtube.com/results?search_query=Como+funciona+Criptografia+SHA-256" },
                    { title: "Vídeo 2: Introdução ao DFIR", url: "https://www.youtube.com/results?search_query=Introdu%C3%A7%C3%A3o+a+Computa%C3%A7%C3%A3o+Forense+DFIR" },
                    { title: "Vídeo 3: Executando o Hashcat", url: "https://www.youtube.com/results?search_query=Hashcat+Ataque+Dicionario+Pratica" }
                ]
            },
            mentoring: {
                summary: "Preparação para o Mercado. Moldar o perfil técnico, melhorar habilidades de comunicação e direcionar projetos para atrair recrutadores de tecnologia.",
                pdfs: [
                    { title: "Plano de Carreira em TI", url: "https://www.google.com/search?q=filetype:pdf+Mentoria+Carreira+Tecnologia+Soft+Skills" }
                ],
                vids: [
                    { title: "Vídeo 1: Otimizando o Perfil GitHub", url: "https://www.youtube.com/results?search_query=Como+deixar+o+Github+atrativo+para+recrutadores" },
                    { title: "Vídeo 2: Soft Skills em Entrevistas", url: "https://www.youtube.com/results?search_query=Soft+Skills+Engenharia+de+Software" }
                ]
            },
            psx: {
                summary: "Modding e Análise Binária. Utilizar o jpsxdec para extração tátil, o HxD para edição hexadecimal dos arquivos ISO e rodar a depuração visual do emulador.",
                pdfs: [
                    { title: "Engenharia Reversa PS1 (Ghidra)", url: "https://www.google.com/search?q=filetype:pdf+Reverse+Engineering+PlayStation+1+ROMs" },
                    { title: "Manual Avançado HxD", url: "https://www.google.com/search?q=filetype:pdf+Hex+Editing+Games+HxD" }
                ],
                vids: [
                    { title: "Vídeo 1: Extração com jpsxdec", url: "https://www.youtube.com/results?search_query=jpsxdec+PlayStation+1+Modding" },
                    { title: "Vídeo 2: Editor de Memória DuckStation", url: "https://www.youtube.com/results?search_query=DuckStation+Memory+Editing" },
                    { title: "Vídeo 3: Hacking de Jogos Retrô", url: "https://www.youtube.com/results?search_query=Reverse+Engineering+PS1+Games" }
                ]
            }
        };

        /**
         * 2. ALGORITMO DA ESCALA 12x36 E ROTINAS
         */
        const daysOffArray = [
            { id: "28_05", label: "28/05/2026", week: "Quinta", template: "quinta" },
            { id: "30_05", label: "30/05/2026", week: "Sábado", template: "fds" },
            { id: "01_06", label: "01/06/2026", week: "Segunda", template: "segunda" },
            { id: "03_06", label: "03/06/2026", week: "Quarta", template: "quarta" },
            { id: "05_06", label: "05/06/2026", week: "Sexta", template: "sexta" },
            { id: "07_06", label: "07/06/2026", week: "Domingo", template: "fds" },
            { id: "09_06", label: "09/06/2026", week: "Terça", template: "terca" },
            { id: "11_06", label: "11/06/2026", week: "Quinta", template: "quinta" },
            { id: "13_06", label: "13/06/2026", week: "Sábado", template: "fds" },
            { id: "15_06", label: "15/06/2026", week: "Segunda", template: "segunda" },
            { id: "17_06", label: "17/06/2026", week: "Quarta", template: "quarta" },
            { id: "19_06", label: "19/06/2026", week: "Sexta", template: "sexta" },
            { id: "21_06", label: "21/06/2026", week: "Domingo", template: "fds" },
            { id: "23_06", label: "23/06", week: "Terça", template: "terca" },
            { id: "25_06", label: "25/06/2026", week: "Quinta", template: "quinta" },
            { id: "27_06", label: "27/06/2026", week: "Sábado", template: "fds" },
            { id: "29_06", label: "29/06/2026", week: "Segunda", template: "segunda" }
        ];

        const routineTemplates = {
            segunda: [
                { time: "08h00 - 10h30", title: "Arquitetura e Organização de Comp. II", type: "academic", desc: "Preparação teórica matinal sobre hardware e processamento.", res: studyResources.arqOrg },
                { time: "11h00 - 12h30", title: "Trabalho Acadêmico Integrado I", type: "academic", desc: "Pesquisa, redação e adequação de formatação.", res: studyResources.tai },
                { time: "14h30 - 17h00", title: "Lab: Engenharia Reversa (PSX)", type: "practical", desc: "Aplicação tátil de modding no setup local.", res: studyResources.psx },
                { time: "19h00 - 22h30", title: "Sessão Letiva Presencial (PUC Minas)", type: "academic", desc: "Aulas: Arq e Org II (19h) | TAI I (21h).", res: null }
            ],
            terca: [
                { time: "08h00 - 10h30", title: "Lab. Arquitetura e Organização de Comp. II", type: "academic", desc: "Teste de comandos lógicos MIPS e execução visual.", res: studyResources.labArq },
                { time: "11h00 - 12h30", title: "Filosofia Razão e Modernidade", type: "academic", desc: "Fichamento e construção argumentativa dos textos base.", res: studyResources.filosofia },
                { time: "14h30 - 17h00", title: "Lab: Engenharia Reversa (PSX)", type: "practical", desc: "Identificação de variáveis na memória hexadecimal.", res: studyResources.psx },
                { time: "19h00 - 22h30", title: "Sessão Letiva Presencial (PUC Minas)", type: "academic", desc: "Aulas: Lab Arq e Org II (19h) | Filosofia (21h).", res: null }
            ],
            quarta: [
                { time: "08h00 - 10h30", title: "Arquitetura e Organização de Comp. II", type: "academic", desc: "Aprofundamento na teoria de mapeamento e barramentos.", res: studyResources.arqOrg },
                { time: "11h00 - 12h30", title: "Trabalho Acadêmico Integrado II", type: "academic", desc: "Codificação Front-End, lógica JS e controle de versão.", res: studyResources.tai },
                { time: "14h30 - 17h00", title: "Lab: Engenharia Reversa (PSX)", type: "practical", desc: "Desmontagem (Disassembly) de trechos executáveis no Ghidra.", res: studyResources.psx },
                { time: "19h00 - 22h30", title: "Sessão Letiva Presencial (PUC Minas)", type: "academic", desc: "Aulas: Arq e Org II (19h) | TAI II (21h).", res: null }
            ],
            quinta: [
                { time: "08h00 - 11h30", title: "Segurança e Criptografia DFIR", type: "academic", desc: "Prática de Força Bruta e Dicionários para recuperação de Hashes.", res: studyResources.seguranca },
                { time: "14h30 - 17h00", title: "Lab: Engenharia Reversa (PSX)", type: "practical", desc: "Empacotamento de arquivos modificados e testes visuais.", res: studyResources.psx },
                { time: "19h00 - 20h40", title: "Janela Livre (Descanso Cognitivo)", type: "practical", desc: "Período vago na grade da PUC. Realizar relaxamento visual absoluto.", res: null },
                { time: "21h00 - 22h30", title: "Sessão Letiva Presencial (PUC Minas)", type: "academic", desc: "Aula de Segurança e Criptografia de Dados DFIR.", res: null }
            ],
            sexta: [
                { time: "08h00 - 10h30", title: "Mentoring III & Carreira", type: "academic", desc: "Ajuste de portfólio GitHub, mapeamento de vagas tech.", res: studyResources.mentoring },
                { time: "11h00 - 12h30", title: "Sprints Code & Review (TAI)", type: "academic", desc: "Comitar alterações finais dos projetos TAI na nuvem.", res: studyResources.tai },
                { time: "14h30 - 17h00", title: "Lab: Engenharia Reversa (PSX)", type: "practical", desc: "Sessão de documentação do mod desenvolvido na semana.", res: studyResources.psx },
                { time: "19h00 - 20h40", title: "Aula Online: Mentoring III", type: "academic", desc: "Conectar na aula remota através do computador.", res: null }
            ],
            fds: [
                { time: "09h00 - 12h00", title: "Imersão de Hardware: Eng. Reversa", type: "practical", desc: "Uso longo dedicado integralmente ao PS1, HxD e Ghidra, sem interrupções.", res: studyResources.psx },
                { time: "14h00 - 17h00", title: "Estudos Livres e Prática", type: "academic", desc: "Refatoração de projetos Web ou revisão de comandos em MIPS.", res: studyResources.labArq },
                { time: "18h00 - 21h00", title: "Desligamento e Logística (Escala)", type: "practical", desc: "Preparar o ambiente, uniforme e refeições para o plantão 12x36 iminente.", res: null }
            ]
        };

        /**
         * 3. INICIALIZAÇÃO DE EVENTOS E MANIPULAÇÃO DO DOM
         */
        document.addEventListener('DOMContentLoaded', () => {
            initNativeModal();
            initTabNavigation();
            buildDaysCarousel();
            initPomodoroEngine();
            fetchServerAdvice();
        });

        // Controle do Elemento Nativo <dialog>
        function initNativeModal() {
            const dialog = document.getElementById('welcomeDialog');
            const btnClose = document.getElementById('btnCloseDialog');
            dialog.showModal();
            btnClose.addEventListener('click', () => dialog.close());
        }

        // Sistema de abas baseado em Data Attributes (Semântico e invisível ao usuário)
        function initTabNavigation() {
            const navBtns = document.querySelectorAll('.nav-btn');
            const panels = document.querySelectorAll('.panel-view');

            navBtns.forEach(btn => {
                btn.addEventListener('click', (e) => {
                    const target = e.currentTarget.getAttribute('data-target');
                    
                    navBtns.forEach(b => b.setAttribute('data-state', 'inactive'));
                    e.currentTarget.setAttribute('data-state', 'active');
                    
                    panels.forEach(panel => {
                        panel.setAttribute('data-state', panel.id === target ? 'active' : 'inactive');
                    });
                });
            });
        }

        // Geração do Carousel Horizontal Dinâmico
        function buildDaysCarousel() {
            const container = document.getElementById('daysTrackContainer');
            
            daysOffArray.forEach((day, idx) => {
                const tab = document.createElement('div');
                tab.className = 'day-tab';
                tab.setAttribute('data-id', day.id);
                tab.setAttribute('data-selected', idx === 0 ? 'true' : 'false');
                tab.innerHTML = `
                    <span style="display:block; font-weight:700; font-size:1.1rem; color:var(--text-primary)">${day.label.substring(0,5)}</span>
                    <span style="font-size:0.85rem; color:var(--text-secondary)">${day.week}</span>
                `;
                
                tab.addEventListener('click', () => {
                    document.querySelectorAll('.day-tab').forEach(b => b.setAttribute('data-selected', 'false'));
                    tab.setAttribute('data-selected', 'true');
                    renderTimelineBlocks(day);
                });

                container.appendChild(tab);
            });

            // Auto-renderiza o primeiro dia
            renderTimelineBlocks(daysOffArray[0]);
        }

        // Renderização dos Cards com Dados Estruturados
        function renderTimelineBlocks(dayObj) {
            const header = document.getElementById('currentDateHeader');
            const list = document.getElementById('timelineList');
            
            header.innerText = `Protocolo Compilado — ${dayObj.label}`;
            list.innerHTML = '';

            const blocks = routineTemplates[dayObj.template];

            blocks.forEach((block, idx) => {
                const card = document.createElement('div');
                card.className = 'study-card';
                card.setAttribute('data-type', block.type);
                // Aplica delay cascata na animação
                card.style.animationDelay = `${idx * 0.15}s`;

                let resourcesHtml = '';

                // Se houver links associados no banco de dados para a matéria
                if (block.res) {
                    let pdfLinksStr = '';
                    block.res.pdfs.forEach(p => {
                        pdfLinksStr += `<a href="${p.url}" target="_blank" class="resource-btn btn-pdf">📄 ${p.title}</a>`;
                    });

                    let ytLinksStr = '';
                    block.res.vids.forEach(v => {
                        ytLinksStr += `<a href="${v.url}" target="_blank" class="resource-btn btn-yt">▶️ ${v.title}</a>`;
                    });

                    resourcesHtml = `
                        <div class="card-summary">
                            <strong>Visão Geral:</strong> ${block.res.summary}
                        </div>
                        <div class="link-group">
                            <h4>📚 Literatura e Documentos Base (PDF)</h4>
                            <div class="link-row">${pdfLinksStr}</div>
                        </div>
                        <div class="link-group">
                            <h4>📺 Referências Visuais Múltiplas (YouTube)</h4>
                            <div class="link-row">${ytLinksStr}</div>
                        </div>
                    `;
                }

                card.innerHTML = `
                    <div class="time-badge">⏱ ${block.time}</div>
                    <h4 style="font-size: 1.2rem; margin-bottom: 12px; color: var(--text-primary);">${block.title}</h4>
                    <p style="color: var(--text-secondary); margin-bottom: 20px; font-size: 0.95rem;">${block.desc}</p>
                    ${resourcesHtml}
                `;

                list.appendChild(card);
            });
        }

        /**
         * 4. BANCO DE DADOS LOCAL (LocalStorage) E TIMER
         * Persistência de estado para evitar perda ao atualizar a página.
         */
        function initPomodoroEngine() {
            let timerId = null;
            let timeRemaining = 50 * 60; // 50 min em segundos
            
            const display = document.getElementById('timerOutput');
            const btnStart = document.getElementById('btnStartTimer');
            const btnReset = document.getElementById('btnResetTimer');
            const focusStat = document.getElementById('focusMinutes');

            // Carrega estado do disco (navegador)
            let totalMinutes = parseInt(localStorage.getItem('sysAgentFocusDB')) || 0;
            focusStat.innerText = totalMinutes;

            function updateDisplay() {
                const m = Math.floor(timeRemaining / 60).toString().padStart(2, '0');
                const s = (timeRemaining % 60).toString().padStart(2, '0');
                display.innerText = `${m}:${s}`;
            }

            btnStart.addEventListener('click', () => {
                if (timerId) return;
                btnStart.innerText = 'Compilando Foco...';
                btnStart.style.opacity = '0.7';

                timerId = setInterval(() => {
                    timeRemaining--;
                    updateDisplay();

                    // Disparo do alarme ao fim do ciclo
                    if (timeRemaining <= 0) {
                        clearInterval(timerId);
                        timerId = null;
                        
                        // Incrementa o log e salva
                        totalMinutes += 50;
                        localStorage.setItem('sysAgentFocusDB', totalMinutes);
                        focusStat.innerText = totalMinutes;

                        alert('Processo concluído. Aplique a Evocação Ativa. Explique o que aprendeu, levante-se e inicie o descanso ocular longe do monitor.');
                        
                        timeRemaining = 50 * 60;
                        updateDisplay();
                        btnStart.innerText = 'Iniciar Imersão';
                        btnStart.style.opacity = '1';
                    }
                }, 1000);
            });

            btnReset.addEventListener('click', () => {
                clearInterval(timerId);
                timerId = null;
                timeRemaining = 50 * 60;
                updateDisplay();
                btnStart.innerText = 'Iniciar Imersão';
                btnStart.style.opacity = '1';
            });
        }

        /**
         * 5. ROTINA ASSÍNCRONA E FETCH API (Consumo Externo)
         */
        async function fetchServerAdvice() {
            const apiContainer = document.getElementById('apiMotivation');
            try {
                // Chamada GET para API pública geradora de strings
                const response = await fetch('https://api.adviceslip.com/advice');
                if (!response.ok) throw new Error('Network response failure');
                const data = await response.json();
                
                apiContainer.innerHTML = `"${data.slip.advice}" <br><br><span style="color: var(--accent-primary); font-weight: 600; font-size: 0.85rem;">— GET /advice (Status: 200 OK)</span>`;
            } catch (error) {
                console.error('Fetch Log:', error);
                apiContainer.innerHTML = "Servidor remoto inoperante. Utilize a persistência do seu cronograma local. O sucesso depende da constância da execução do algoritmo, não de motivação externa.";
            }
        }
    </script>
</body>
</html>