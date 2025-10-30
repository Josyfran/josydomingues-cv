<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Josy Domingues | Estrategista B2B & Growth</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            /* Fundo sutil de mapa/coordenadas para a sensação de viagem/LATAM (Azul claro/Lilás) */
            background-color: #f7f7ff;
            background-image: radial-gradient(#d1d5db 1px, transparent 0);
            background-size: 40px 40px;
            position: relative;
        }

        .main-container {
            position: relative;
            z-index: 10;
        }

        .section-card {
            background-color: rgba(255, 255, 255, 0.95); /* Levemente transparente */
            backdrop-filter: blur(5px);
            border: 1px solid #e5e7eb;
            transition: all 0.3s ease;
        }
        
        .nav-button {
            transition: all 0.3s ease;
            position: relative;
            font-weight: 600;
        }

        .nav-button.active {
            color: #4338ca; /* Indigo 700 */
        }
        
        /* Linha sob o botão ativo - Verde Limão */
        .nav-button.active::after {
            content: '';
            position: absolute;
            bottom: -5px;
            left: 50%;
            transform: translateX(-50%);
            width: 80%;
            height: 3px;
            background-color: #84cc16; /* Lime 500 - Humanização */
            border-radius: 9999px;
        }
        
        .job-details {
            animation: slideIn 0.5s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Novas Classes de Cores */
        .color-innovation { color: #4338ca; } /* Indigo 700 */
        .color-human { color: #84cc16; } /* Lime 500 */
        .bg-innovation { background-color: #4338ca; } 
        .bg-human { background-color: #84cc16; }
    </style>
</head>
<body class="text-gray-800">

    <!-- === Main Content Area === -->
    <div class="main-container container mx-auto p-4 md:p-10 max-w-6xl">
        
        <!-- === CABEÇALHO E IDENTIFICAÇÃO === -->
        <header class="p-6 md:p-8 rounded-xl shadow-xl mb-10 bg-white border-b-4 border-lime-500 section-card">
            <div class="flex flex-col md:flex-row justify-between items-start">
                <div>
                    <h1 class="text-4xl font-extrabold color-innovation tracking-tight">Josy Francisco Domingues</h1>
                    <h2 class="text-xl text-gray-700 font-medium mt-1">Estrategista de Eventos B2B & Growth | Liderança LATAM | SaaS & Automação</h2>
                </div>
                
                <div class="text-right mt-4 md:mt-0 text-sm text-gray-600 space-y-1">
                    <p>📍 Saquarema – RJ</p>
                    <p>✉ <a href="mailto:josyyfrann@gmail.com" class="hover:text-lime-500">josyyfrann@gmail.com</a></p>
                    <p>☎ (21) 97384-0942</p>
                    <p class="font-semibold text-lime-600">Disponibilidade para Viagens Brasil/LATAM</p>
                </div>
            </div>
        </header>

        <!-- === NAVEGAÇÃO INTERATIVA (A ROTA) === -->
        <nav class="flex justify-center space-x-4 md:space-x-12 mb-10 p-3 rounded-full bg-white shadow-md sticky top-0 z-20">
            <button class="nav-button active text-base md:text-lg px-2 py-1" data-target="section-resumo">1. Visão Estratégica</button>
            <button class="nav-button text-base md:text-lg px-2 py-1" data-target="section-trajetoria">2. Trajetória</button>
            <button class="nav-button text-base md:text-lg px-2 py-1" data-target="section-toolkit">3. Habilidades & Fit</button>
            <button class="nav-button text-base md:text-lg px-2 py-1" data-target="section-formacao">4. Formação</button>
        </nav>

        <!-- === CONTEÚDO DAS SEÇÕES === -->
        <div id="sections-container" class="space-y-12">

            <!-- 1. VISÃO ESTRATÉGICA (O Pitch Principal) -->
            <section id="section-resumo" class="section section-card p-6 md:p-10 rounded-xl shadow-lg border-l-8 border-indigo-700">
                <h3 class="text-3xl font-bold color-innovation mb-4">⭐ Visão Estratégica (O Resumo do Viajante)</h3>
                <p class="text-lg text-gray-700 leading-relaxed">
                    Com mais de 10 anos em <b>Marketing, Inovação e Eventos</b>, sou uma profissional data-driven e resiliente com experiência em ambientes de alta performance e tecnologia (HealthTechs, Eventos de Inovação). Minha paixão é conectar a excelência operacional de eventos (do RFP ao NPS), automação de funis (Growth & Automação) e neuromarketing para gerar resultados tangíveis.
                </p>
                
                <div class="mt-6 p-4 rounded-lg bg-indigo-50 border-l-4 border-lime-500">
                    <h4 class="font-bold text-lg color-innovation mb-2">Por que 100% de Alinhamento com a Stays/Despegar?</h4>
                    <ul class="list-disc list-inside space-y-1 text-gray-700 ml-4 text-sm">
                        <li><b>Tech & SaaS:</b> Experiência em software e automação (CRM, n8n, Make) e atuação em projetos de tecnologia (UXMed, AlquimIA).</li>
                        <li><b>LATAM Focus:</b> Em aprimoramento contínuo em espanhol, com facilidade de comunicação multicultural e paixão pela expansão regional.</li>
                        <li><b>Cultura Horizontal:</b> Perfil colaborativo, curioso e adaptável ao ritmo de startups.</li>
                    </ul>
                    <p class="mt-3 text-sm font-semibold color-innovation">Busco aplicar esse know-how para elevar marcas no Brasil e na América Latina.</p>
                </div>
            </section>

            <!-- 2. TRAJETÓRIA PROFISSIONAL (A Jornada Detalhada) -->
            <section id="section-trajetoria" class="section section-card p-6 md:p-10 rounded-xl shadow-lg hidden">
                <h3 class="text-3xl font-bold color-innovation mb-6">🚀 Trajetória Profissional (Experiencia de Liderazgo)</h3>

                <!-- Acordion for Jobs -->
                <div class="space-y-6">

                    <!-- UXMed -->
                    <div class="border-b pb-4">
                        <h4 class="text-xl font-extrabold text-indigo-800">UXMed – Coordenadora de Projetos e Inovação</h4>
                        <p class="text-sm italic text-gray-500 mb-3">Nov/2022 – Atual | Remoto | Healthtech</p>
                        <ul class="list-disc list-inside space-y-2 text-gray-700 ml-4">
                            <li>**Planejamento Ponta a Ponta:** Coordenação do ciclo completo de eventos B2B (webinars e presenciais), garantindo a entrega **dentro do budget e prazo**.</li>
                            <li>**Growth & Automação:** Líder no desenvolvimento de fluxos de **automação** (RD Station, Make, n8n) para relacionamento e nutrição, otimizando o *customer journey* (CX/UX).</li>
                            <li>**Análise de Impacto:** Criação de *dashboards* de performance (KPIs, NPS) para garantir a **tomada de decisão baseada em dados** e otimização contínua.</li>
                        </ul>
                    </div>

                    <!-- Base Eventos -->
                    <div class="border-b pb-4">
                        <h4 class="text-xl font-extrabold text-indigo-800">Base Eventos (Rio Innovation Week e LER) – Produtora de Eventos Corporativos</h4>
                        <p class="text-sm italic text-gray-500 mb-3">2021 – 2022 | Rio de Janeiro – RJ</p>
                        <ul class="list-disc list-inside space-y-2 text-gray-700 ml-4">
                            <li>**Excelência Operacional:** Gestão completa da arena HealthTech no RIW, incluindo **curadoria de conteúdo**, coordenação de equipes, fornecedores e controle rígido de budget (RFP).</li>
                            <li>**Experiência Imersiva:** Atuação em ambiente de **inovação e tecnologia**, com foco em cenografia, A/V e geração qualificada de *leads*.</li>
                            <li>**Comunicação Integrada:** Suporte estratégico ao marketing para campanhas de divulgação e relacionamento com patrocinadores.</li>
                        </ul>
                    </div>

                    <!-- AlquimIA -->
                    <div class="pb-4">
                        <h4 class="text-xl font-extrabold text-indigo-800">AlquimIA Automações – Fundadora & CEO</h4>
                        <p class="text-sm italic text-gray-500 mb-3">2020 – 2022 | Empreendimento Próprio | SaaS & Tecnologia</p>
                        <ul class="list-disc list-inside space-y-2 text-gray-700 ml-4">
                            <li>**Otimização de Custos:** Criação e implementação de soluções de **automação e chatbots com IA**, integrando CRMs e canais digitais para redução de custos B2B.</li>
                            <li>**Gestão por ROI:** Gerenciamento de projetos com foco em **performance e Retorno sobre Investimento (ROI)**.</li>
                        </ul>
                    </div>

                </div>
            </section>

            <!-- 3. TOOLKIT E DIFERENCIAIS (Habilidades e Fit Cultural) -->
            <section id="section-toolkit" class="section section-card p-6 md:p-10 rounded-xl shadow-lg hidden">
                <h3 class="text-3xl font-bold color-innovation mb-6">🛠️ Habilidades & Fit Cultural</h3>

                <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
                    <!-- Toolkit -->
                    <div>
                        <h4 class="text-2xl font-bold text-gray-800 mb-4 border-b-2 border-lime-400 pb-2">Toolkit Estratégico (Suas Ferramentas)</h4>
                        
                        <div class="space-y-4">
                            <div class="bg-indigo-50 p-4 rounded-lg shadow-sm">
                                <p class="font-bold text-lg color-innovation">Eventos B2B LATAM</p>
                                <p class="text-sm text-gray-600">Planejamento, RFP, Roteiro, Cenografia, A/V, *Speakers*. **Domínio da Operação (Requisito Principal)**</p>
                            </div>
                            <div class="bg-indigo-50 p-4 rounded-lg shadow-sm">
                                <p class="font-bold text-lg color-innovation">Growth & Automação</p>
                                <p class="text-sm text-gray-600">RD Station Marketing/CRM, **Make (n8n)**, Funis de Nutrição e Aquisição. **Software e Automação (Diferencial Stays)**</p>
                            </div>
                            <div class="bg-indigo-50 p-4 rounded-lg shadow-sm">
                                <p class="font-bold text-lg color-innovation">Data & Finanças</p>
                                <p class="text-sm text-gray-600">Looker Studio, Sheets, Planejamento de **Budget**, Controle de Custos. **Foco em Resultados e Decisão Baseada em Dados**</p>
                            </div>
                            <div class="bg-indigo-50 p-4 rounded-lg shadow-sm">
                                <p class="font-bold text-lg color-innovation">Soft Skills & Cultura</p>
                                <p class="text-sm text-gray-600">**Espanhol Intermediário** (em desenvolvimento), Liderança Colaborativa, **Resiliência e Adaptabilidade**. **Ética, Transparência, Aprendizagem Contínua**</p>
                            </div>
                        </div>
                    </div>

                    <!-- Diferenciais Stays -->
                    <div class="flex flex-col">
                        <h4 class="text-2xl font-bold text-gray-800 mb-4 border-b-2 border-lime-400 pb-2">🌍 Diferenciais Stays (Matching Cultural)</h4>
                        <div class="flex-grow space-y-4">
                            <div class="p-4 bg-lime-50 rounded-lg shadow-sm border-l-4 border-lime-500">
                                <p class="font-bold text-gray-800">✅ Foco B2B Tech</p>
                                <p class="text-sm text-gray-600">Experiência com eventos e marketing no setor de tecnologia e software (SaaS).</p>
                            </div>
                            <div class="p-4 bg-lime-50 rounded-lg shadow-sm border-l-4 border-lime-500">
                                <p class="font-bold text-gray-800">✅ Compliance & Risco</p>
                                <p class="text-sm text-gray-600">Capacidade de liderar a operação no dia do evento, gerindo riscos e aspectos de *compliance* e segurança.</p>
                            </div>
                            <div class="p-4 bg-lime-50 rounded-lg shadow-sm border-l-4 border-lime-500">
                                <p class="font-bold text-gray-800">✅ Patrocínios e Co-Marketing</p>
                                <p class="text-sm text-gray-600">Atuação prévia na gestão de parceiros e patrocinadores.</p>
                            </div>
                            <div class="p-4 bg-lime-50 rounded-lg shadow-sm border-l-4 border-lime-500">
                                <p class="font-bold text-gray-800">✅ Visão 360</p>
                                <p class="text-sm text-gray-600">Combino a excelência operacional (Produtora de Eventos) com a visão de funil e métricas (Estrategista de Marketing).</p>
                            </div>
                        </div>
                    </div>
                </div>
            </section>

            <!-- 4. FORMAÇÃO (A Rota de Aprendizagem) -->
            <section id="section-formacao" class="section section-card p-6 md:p-10 rounded-xl shadow-lg hidden">
                <h3 class="text-3xl font-bold color-innovation mb-6">🎓 Rota de Aprendizagem (Formación)</h3>
                <p class="text-gray-700 mb-6 text-sm">O aprendizado contínuo é um valor. Esta seção lista a base acadêmica e as certificações que complementam sua experiência prática.</p>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div>
                        <h4 class="text-xl font-bold text-gray-800 mb-3 border-b border-indigo-200 pb-1">Formação Acadêmica</h4>
                        <ul class="space-y-3">
                            <li class="p-3 bg-gray-50 rounded-lg border-l-4 border-indigo-500">
                                <p class="font-semibold text-gray-900">Graduação em Marketing</p>
                                <p class="text-sm text-gray-600">Estácio de Sá</p>
                            </li>
                            <li class="p-3 bg-gray-50 rounded-lg border-l-4 border-indigo-500">
                                <p class="font-semibold text-gray-900">Bacharelado em Sistemas de Informação</p>
                                <p class="text-sm text-gray-600">(em andamento) – Estácio de Sá</p>
                            </li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="text-xl font-bold text-gray-800 mb-3 border-b border-indigo-200 pb-1">Certificações de Bordo</h4>
                        <ul class="space-y-3">
                            <li class="p-3 bg-gray-50 rounded-lg border-l-4 border-lime-500">
                                <p class="font-semibold text-gray-900">Growth Marketing</p>
                                <p class="text-sm text-gray-600">GLA</p>
                            </li>
                            <li class="p-3 bg-gray-50 rounded-lg border-l-4 border-lime-500">
                                <p class="font-semibold text-gray-900">Gerenciamento de Projetos e Metodologias Ágeis</p>
                                <p class="text-sm text-gray-600">Alumni Coppead</p>
                            </li>
                            <li class="p-3 bg-gray-50 rounded-lg border-l-4 border-lime-500">
                                <p class="font-semibold text-gray-900">Automação e Chatbots</p>
                                <p class="text-sm text-gray-600">Automatik Labs</p>
                            </li>
                        </ul>
                    </div>
                </div>
            </section>

        </div>
    </div>

    <footer class="text-center p-6 mt-12 bg-white border-t border-gray-200 shadow-inner">
        <p class="text-sm text-gray-600">Pronto para embarcar na expansão da Stays na América Latina.</p>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const navButtons = document.querySelectorAll('.nav-button');
            const sections = document.querySelectorAll('.section');
            
            function showSection(targetId) {
                sections.forEach(section => {
                    section.classList.add('hidden');
                });
                document.getElementById(targetId).classList.remove('hidden');
            }

            function updateNavigation(activeButton) {
                navButtons.forEach(btn => btn.classList.remove('active'));
                activeButton.classList.add('active');
            }

            navButtons.forEach(button => {
                button.addEventListener('click', () => {
                    const targetId = button.getAttribute('data-target');
                    updateNavigation(button);
                    showSection(targetId);
                });
            });

            // Initialize: Show the first section
            const initialButton = document.querySelector('.nav-button.active');
            if (initialButton) {
                showSection(initialButton.getAttribute('data-target'));
            }
        });
    </script>
</body>
</html>
