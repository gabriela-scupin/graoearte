☕ Grão & Arte — Torrefação e Café Especial

Uma página web responsiva desenvolvida para a Grão & Arte, focada na apresentação de cafés especiais, microlotes exclusivos, explicação do processo artesanal de torra e comercialização de planos de assinatura.

Este projeto foi desenvolvido como parte das atividades práticas do curso, simulando uma entrega profissional de desenvolvimento front-end com foco em semântica HTML, organização CSS moderna, acessibilidade e responsividade.

📌 Sumário

Visão Geral e Objetivo

Tecnologias e Conceitos Aplicados

Arquitetura de Arquivos

Funcionalidades e Requisitos Atendidos

Design System

Desafios Técnicos e Aprendizados

Licença e Autoria

☕ Visão Geral e Objetivo

O objetivo principal deste projeto é aplicar conceitos avançados de estruturação web semântica e estilização moderna sem a dependência de frameworks externos. A aplicação representa a presença digital da cafeteria fictícia Grão & Arte, voltada para um público exigente de apreciadores de cafés especiais (pontuação >85 SCA).

🚀 Tecnologias e Conceitos Aplicados

HTML5 Semântico: Uso rigoroso de tags como <header>, <nav>, <main>, <section>, <article>, <details>, <summary> e <footer> para garantir acessibilidade e SEO.

CSS3 Moderno:

Variáveis Globais (CSS Custom Properties): Centralização de tokens do Design System.

Flexbox Layout: Estruturação fluida e responsiva das seções e cards.

Metodologia BEM (Block Element Modifier): Padronização de nomes de classes para manter a manutenibilidade do código.

Escala Relativa (REM / % / Viewport Units): Uso de rem para tipografia e espaçamentos, porcentagens e vh/vw para layouts adaptáveis, evitando pixels fixos.

Google Fonts: Importação e aplicação das famílias tipográficas Merriweather e Open Sans.

API do WhatsApp: Integração de botão flutuante interativo direcionando diretamente ao suporte oficial.

Git & GitHub: Versionamento de código estruturado com commits frequentes.

📂 Arquitetura de Arquivos

A organização de arquivos do projeto segue a estrita separação de responsabilidades (RNF04):

grao-e-arte/
├── assets/
│   ├── images/          # Imagens do projeto e ilustrações dos microlotes
│   └── icons/           # Ícones (ex: ícone do WhatsApp)
├── css/
│   ├── reset.css        # Normalização e regras da escala raiz (REM)
│   ├── variables.css    # Tokens do Design System (:root)
│   └── style.css        # Estilos principais organizados em BEM
├── index.html           # Documento HTML5 semântico
└── README.md            # Documentação oficial do projeto


⚙️ Funcionalidades e Requisitos Atendidos

[x] Header Fixo com Rolagem Suave: Navegação principal fixa no topo (position: fixed) com compensação de recuo e navegação suave (scroll-behavior: smooth).

[x] Hero Banner de Tela Cheia: Apresentação da marca ocupando 100% da área visível (100vh).

[x] Catálogo de Microlotes: Exibição dos cafés Reserva da Serra, Chapada Diamantina e Vulcânico em cards flexíveis.

[x] Seção Processo Artesanal: Explicação detalhada da colheita ao perfilamento de torra.

[x] Clube de Assinatura: Cards comparativos dos planos Entusiasta, Barista e Mestre da Torra.

[x] FAQ Interativo: Lista de perguntas e respostas dinâmicas e semânticas com <details> e <summary>.

[x] Rodapé Fixo: Informações institucionais fixadas na parte inferior da tela.

[x] Botão Flutuante do WhatsApp: Atalho rápido posicionado no canto inferior direito conectado ao contato oficial do SENAI Henrique Lupo.

[x] Microinterações: Efeitos de :hover, transição suave (cubic-bezier) e elevação de sombra nos cards e botões.

🎨 Design System

As variáveis do projeto foram estruturadas em CSS Custom Properties no escopo :root:

Cores Principais:

Background Principal: #fdfbf7

Background Cards: #ffffff

Header/Footer: #2c1810

Detalhes/Textos Destaque: #78350f, #b45309, #d97706

Tipografia:

Títulos: 'Merriweather', serif

Textos: 'Open Sans', sans-serif

Unidades de Medida: Escala base em rem calculada na raiz (html { font-size: 62.5%; }).

🛠️ Desafios Técnicos e Aprendizados

Compensação do Header Fixo: Ajustar a navegação interna de anchor links (#href) para que o cabeçalho fixo não cobrisse os títulos das seções ao rolar a página. O uso de scroll-margin-top nas seções resolveu o problema de forma limpa.

Consistência BEM: Manter a disciplina de nomenclatura de classes em todos os componentes para evitar especificidade excessiva no CSS.

Layout Fluido sem Pixels Fixos: Transicionar a mentalidade de design fixo para o uso exclusivo de rem, % e unidades de viewport (vh/vw), garantindo uma adaptação responsiva mais fluida entre múltiplos dispositivos.

📝 Licença e Autoria

Projeto desenvolvido para fins educacionais no curso do SENAI Henrique Lupo.

Desenvolvedor: Gabriela Scupin

Ano: 2026