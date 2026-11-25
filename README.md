<!DOCTYPE html>
<html lang="pt-BR" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Giovanna Lopes — Portfólio | Atleta e Estudante</title>

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Google Fonts: Cormorant Garamond (Serifada Editorial) & Inter (Moderna Sem Serifa) -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;1,400;1,500&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            serif: ['"Cormorant Garamond"', 'Georgia', 'serif'],
            sans: ['"Inter"', 'sans-serif'],
          },
          colors: {
            editorial: {
              bg: '#FFFFFF',
              surface: '#F4F4F4',
              subtle: '#E6E6E6',
              ink: '#111111',
              muted: '#555555',
              light: '#888888',
            }
          },
          letterSpacing: {
            editorial: '0.24em',
            wideTitle: '0.14em',
          }
        }
      }
    }
  </script>

  <style>
    /* Estilos editoriais minimalistas e puramente tipográficos */
    body {
      background-color: #FFFFFF;
      color: #111111;
      font-family: 'Inter', sans-serif;
      overflow-x: hidden;
    }

    /* Animação sutil de entrada ao rolar a página */
    .reveal {
      opacity: 0;
      transform: translateY(24px);
      transition: opacity 0.85s cubic-bezier(0.22, 1, 0.36, 1), transform 0.85s cubic-bezier(0.22, 1, 0.36, 1);
    }

    .reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* Linha divisória arquitetônica de 1px */
    .hairline {
      height: 1px;
      background-color: #E5E5E5;
    }
  </style>
</head>
<body class="antialiased selection:bg-[#111111] selection:text-white">

  <!-- =========================================================
       CABEÇALHO FIXO MINIMALISTA
  ========================================================== -->
  <header class="fixed top-0 left-0 right-0 z-50 bg-white/95 backdrop-blur-md border-b border-neutral-200/80 transition-all duration-300">
    <div class="max-w-6xl mx-auto px-6 sm:px-10 h-16 flex items-center justify-between">
      <!-- Nome à esquerda -->
      <a href="#inicio" class="font-serif text-xl sm:text-2xl tracking-tight text-[#111111] hover:opacity-70 transition-opacity">
        Giovanna Lopes
      </a>

      <!-- Links de Navegação à direita (Desktop) -->
      <nav aria-label="Navegação principal" class="hidden md:flex items-center space-x-8 text-[11px] uppercase tracking-editorial text-[#555555]">
        <a href="#inicio" class="hover:text-[#111111] transition-colors py-2">Início</a>
        <a href="#sobre" class="hover:text-[#111111] transition-colors py-2">Sobre</a>
        <a href="#proposito" class="hover:text-[#111111] transition-colors py-2">Propósito</a>
        <a href="#educacao" class="hover:text-[#111111] transition-colors py-2">Educação</a>
        <a href="#sonhos" class="hover:text-[#111111] transition-colors py-2">Sonhos</a>
      </nav>

      <!-- Botão Menu Mobile -->
      <button 
        id="mobileMenuBtn" 
        type="button" 
        aria-label="Abrir menu de navegação"
        aria-expanded="false"
        class="md:hidden p-2.5 text-[#111111] rounded-sm hover:bg-[#F4F4F4] transition-colors"
      >
        <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="1.5" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 7.5h16.5M3.75 12h16.5m-16.5 4.5h16.5" />
        </svg>
      </button>
    </div>

    <!-- Menu Mobile Dropdown -->
    <div id="mobileMenu" class="hidden md:hidden bg-white border-b border-neutral-200 px-6 py-5 space-y-3">
      <a href="#inicio" class="block text-xs uppercase tracking-editorial text-[#555555] hover:text-[#111111] py-2">Início</a>
      <a href="#sobre" class="block text-xs uppercase tracking-editorial text-[#555555] hover:text-[#111111] py-2">Sobre</a>
      <a href="#proposito" class="block text-xs uppercase tracking-editorial text-[#555555] hover:text-[#111111] py-2">Propósito</a>
      <a href="#educacao" class="block text-xs uppercase tracking-editorial text-[#555555] hover:text-[#111111] py-2">Educação</a>
      <a href="#sonhos" class="block text-xs uppercase tracking-editorial text-[#555555] hover:text-[#111111] py-2">Sonhos</a>
    </div>
  </header>

  <main>
    <!-- =========================================================
         HERO SECTION (COMPOSIÇÃO PURAMENTE TIPOGRÁFICA)
    ========================================================== -->
    <section id="inicio" class="min-h-screen pt-28 pb-20 px-6 sm:px-10 flex flex-col justify-between bg-white">
      <!-- Linha de topo discreta -->
      <div class="max-w-5xl w-full mx-auto">
        <div class="flex items-center justify-between text-[11px] uppercase tracking-editorial text-[#888888] pb-4 border-b border-neutral-200">
          <span>Edição Pessoal</span>
          <span>Taekwondo &amp; Sistemas</span>
        </div>
      </div>

      <!-- Bloco Central Tipográfico -->
      <div class="max-w-5xl w-full mx-auto my-auto py-14 sm:py-20 flex flex-col items-center text-center">
        
        <!-- Título superior em fonte serifada elegante -->
        <p class="font-serif font-normal text-4xl sm:text-6xl md:text-7xl lg:text-[5.5rem] leading-none tracking-tight text-[#111111]">
          Giovanna Lopes
        </p>

        <!-- Filete arquitetônico central -->
        <div class="w-16 h-[1px] bg-[#111111] my-7 sm:my-9"></div>

        <!-- Título principal grande em fonte sem serifa moderna -->
        <h1 class="font-sans font-light text-4xl sm:text-6xl md:text-7xl lg:text-[5.5rem] tracking-[0.2em] text-[#111111] uppercase leading-none pl-[0.2em]">
          PORTFÓLIO
        </h1>

        <!-- Subtítulo -->
        <p class="mt-8 sm:mt-10 font-sans text-sm sm:text-base font-normal text-[#555555] tracking-widest uppercase">
          Atleta e estudante
        </p>

        <!-- Botão minimalista "SOBRE MIM" -->
        <div class="mt-10 sm:mt-12">
          <a 
            href="#sobre" 
            class="inline-block bg-[#F4F4F4] hover:bg-[#111111] text-[#111111] hover:text-white border border-neutral-300 hover:border-[#111111] text-xs font-medium uppercase tracking-[0.24em] px-10 py-4 rounded-sm transition-all duration-300"
          >
            SOBRE MIM
          </a>
        </div>
      </div>

      <!-- Destaques Numéricos Minimalistas na Base do Hero -->
      <div class="max-w-5xl w-full mx-auto">
        <div class="grid grid-cols-2 sm:grid-cols-4 border-t border-neutral-200 pt-6 gap-6 text-left">
          <div>
            <span class="block font-serif italic text-xl sm:text-2xl text-[#111111]">09 anos</span>
            <span class="block text-[11px] uppercase tracking-wider text-[#888888] mt-1">Início no Esporte</span>
          </div>
          <div>
            <span class="block font-serif italic text-xl sm:text-2xl text-[#111111]">Faixa Preta</span>
            <span class="block text-[11px] uppercase tracking-wider text-[#888888] mt-1">Taekwondo</span>
          </div>
          <div>
            <span class="block font-serif italic text-xl sm:text-2xl text-[#111111]">Seleção</span>
            <span class="block text-[11px] uppercase tracking-wider text-[#888888] mt-1">Representação Brasileira</span>
          </div>
          <div>
            <span class="block font-serif italic text-xl sm:text-2xl text-[#111111]">Técnico</span>
            <span class="block text-[11px] uppercase tracking-wider text-[#888888] mt-1">Desenvolvimento de Sistemas</span>
          </div>
        </div>
      </div>
    </section>

    <div class="max-w-5xl mx-auto px-6 sm:px-10"><div class="hairline"></div></div>

    <!-- =========================================================
         SEÇÃO 01 — UM POUCO SOBRE MIM
    ========================================================== -->
    <section id="sobre" class="py-24 sm:py-32 px-6 sm:px-10 bg-white">
      <div class="max-w-5xl mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12 lg:gap-16 items-start">
        
        <!-- Coluna de Texto Principal (7 colunas) -->
        <div class="lg:col-span-7 reveal">
          <span class="block font-sans text-xs font-medium tracking-editorial text-[#888888] mb-3">
            01
          </span>
          <h2 class="font-sans text-3xl sm:text-4xl md:text-5xl font-normal uppercase tracking-wideTitle text-[#111111] leading-[1.15]">
            UM POUCO<br />SOBRE MIM
          </h2>

          <div class="mt-8 sm:mt-10 sm:pl-10 border-l border-neutral-300">
            <p class="font-sans text-sm sm:text-base leading-[1.9] text-[#555555] font-normal">
              Atleta desde os 9 anos, sou campeã sul-americana, medalhista pan-americana, integrante da Seleção Brasileira e faixa preta. Minha trajetória é marcada por dedicação, disciplina e superação. Atualmente, estou concluindo o Ensino Médio integrado ao curso técnico, conciliando os estudos com minha paixão pelo esporte e a busca por novas conquistas.
            </p>
          </div>
        </div>

        <!-- Coluna de Destaques Puramente Tipográficos (5 colunas) -->
        <div class="lg:col-span-5 reveal">
          <div class="border-t border-neutral-300 divide-y divide-neutral-200">
            
            <div class="py-6 flex items-baseline justify-between gap-4">
              <div>
                <span class="block text-[11px] uppercase tracking-editorial text-[#888888] mb-1">
                  Trajetória no Taekwondo
                </span>
                <p class="font-serif text-xl sm:text-2xl text-[#111111]">
                  Desde os 9 anos
                </p>
              </div>
              <span class="font-sans text-xs text-[#888888]">01.1</span>
            </div>

            <div class="py-6 flex items-baseline justify-between gap-4">
              <div>
                <span class="block text-[11px] uppercase tracking-editorial text-[#888888] mb-1">
                  Representação &amp; Graduação
                </span>
                <p class="font-serif text-xl sm:text-2xl text-[#111111]">
                  Seleção Brasileira • Faixa Preta
                </p>
              </div>
              <span class="font-sans text-xs text-[#888888]">01.2</span>
            </div>

            <div class="py-6 flex items-baseline justify-between gap-4">
              <div>
                <span class="block text-[11px] uppercase tracking-editorial text-[#888888] mb-1">
                  Conquistas Internacionais
                </span>
                <p class="font-serif text-xl sm:text-2xl text-[#111111]">
                  Campeã Sul-Americana &amp; Medalhista Pan-Americana
                </p>
              </div>
              <span class="font-sans text-xs text-[#888888]">01.3</span>
            </div>

          </div>
        </div>

      </div>
    </section>

    <!-- =========================================================
         SEÇÃO 02 — PROPÓSITO & FAMÍLIA
    ========================================================== -->
    <section id="proposito" class="py-24 sm:py-32 px-6 sm:px-10 bg-[#F4F4F4] border-y border-neutral-200/80">
      <div class="max-w-5xl mx-auto grid grid-cols-1 lg:grid-cols-12 gap-12 lg:gap-16 items-center">
        
        <!-- Bloco Complementar em Destaque Tipográfico (5 colunas) -->
        <div class="lg:col-span-5 order-2 lg:order-1 reveal">
          <div class="bg-white p-8 sm:p-10 rounded-sm border border-neutral-200">
            <span class="block text-[11px] uppercase tracking-editorial text-[#888888] mb-4">
              Valores Pessoais
            </span>
            <p class="font-serif italic text-xl sm:text-2xl leading-relaxed text-[#111111]">
              “Disciplina no esporte, equilíbrio nos estudos e propósito na vida pessoal.”
            </p>
            <div class="mt-6 pt-6 border-t border-neutral-200 flex items-center justify-between text-[11px] uppercase tracking-widest text-[#888888]">
              <span>Essência</span>
              <span>Futuro &amp; Família</span>
            </div>
          </div>
        </div>

        <!-- Texto Principal da Seção 02 (7 colunas) -->
        <div class="lg:col-span-7 order-1 lg:order-2 reveal">
          <span class="block font-sans text-xs font-medium tracking-editorial text-[#888888] mb-3">
            02
          </span>
          <h2 class="font-sans text-xs uppercase tracking-editorial text-[#555555] mb-6">
            Propósito &amp; Família
          </h2>

          <p class="font-serif text-2xl sm:text-3xl md:text-[2.1rem] leading-[1.45] text-[#111111] font-normal">
            Fora essa preocupação com a carreira e vida profissional, desejo ter uma família. Tenho o sonho de ser mãe e acredito que seja um dos meus desejos poder proporcionar uma vida boa para meus filhos.
          </p>

          <div class="mt-8 flex items-center gap-4">
            <span class="w-10 h-[1px] bg-[#111111]"></span>
            <span class="font-serif italic text-base text-[#555555]">Giovanna Lopes</span>
          </div>
        </div>

      </div>
    </section>

    <!-- =========================================================
         SEÇÃO 03 — EDUCAÇÃO
    ========================================================== -->
    <section id="educacao" class="py-24 sm:py-32 px-6 sm:px-10 bg-white">
      <div class="max-w-5xl mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 lg:gap-16 items-start reveal">
          
          <!-- Título Editorial (5 colunas) -->
          <div class="lg:col-span-5">
            <span class="block font-sans text-xs font-medium tracking-editorial text-[#888888] mb-3">
              03
            </span>
            <h2 class="font-sans text-3xl sm:text-4xl md:text-5xl font-normal uppercase tracking-wideTitle text-[#111111]">
              EDUCAÇÃO
            </h2>
          </div>

          <!-- Conteúdo e Cartões Editoriais sem Imagens (7 colunas) -->
          <div class="lg:col-span-7">
            <p class="font-serif italic text-2xl sm:text-3xl text-[#111111] mb-4">
              Educação
            </p>
            <p class="font-sans text-sm sm:text-base uppercase tracking-wider leading-relaxed text-[#555555] font-medium">
              TERMINANDO O ENSINO MÉDIO, E CONCLUINDO O CURSO DE DESENVOLVIMENTO DE SISTEMAS
            </p>

            <!-- Cartões Editoriais Minimalistas -->
            <div class="mt-10 grid grid-cols-1 sm:grid-cols-2 gap-6">
              <!-- Cartão 1 -->
              <div class="p-7 rounded-sm bg-[#F4F4F4] border border-neutral-200 hover:border-[#111111] transition-colors duration-300">
                <div class="flex items-center justify-between text-[11px] uppercase tracking-editorial text-[#888888] mb-6">
                  <span>Formação Básica</span>
                  <span>03.1</span>
                </div>
                <h3 class="font-serif text-2xl text-[#111111] mb-2">
                  Ensino Médio Integrado
                </h3>
                <p class="font-sans text-xs leading-relaxed text-[#555555]">
                  Fase final da educação básica conciliada com a rotina de treinos e competições de alto rendimento.
                </p>
              </div>

              <!-- Cartão 2 -->
              <div class="p-7 rounded-sm bg-[#F4F4F4] border border-neutral-200 hover:border-[#111111] transition-colors duration-300">
                <div class="flex items-center justify-between text-[11px] uppercase tracking-editorial text-[#888888] mb-6">
                  <span>Formação Técnica</span>
                  <span>03.2</span>
                </div>
                <h3 class="font-serif text-2xl text-[#111111] mb-2">
                  Técnico em Desenvolvimento de Sistemas
                </h3>
                <p class="font-sans text-xs leading-relaxed text-[#555555]">
                  Conclusão do curso técnico com foco em lógica, estruturação de software e tecnologia.
                </p>
              </div>
            </div>
          </div>

        </div>
      </div>
    </section>

    <div class="max-w-5xl mx-auto px-6 sm:px-10"><div class="hairline"></div></div>

    <!-- =========================================================
         SEÇÃO 04 — SONHOS
    ========================================================== -->
    <section id="sonhos" class="py-24 sm:py-32 px-6 sm:px-10 bg-white">
      <div class="max-w-5xl mx-auto">
        
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 lg:gap-16 items-start reveal">
          <!-- Cabeçalho da Seção (5 colunas) -->
          <div class="lg:col-span-5">
            <span class="block font-sans text-xs font-medium tracking-editorial text-[#888888] mb-3">
              04
            </span>
            <h2 class="font-sans text-3xl sm:text-4xl md:text-5xl font-normal uppercase tracking-wideTitle text-[#111111]">
              SONHOS
            </h2>
          </div>

          <!-- Texto Editorial + Lista Minimalista Numerada (7 colunas) -->
          <div class="lg:col-span-7">
            <p class="font-serif text-2xl sm:text-3xl leading-[1.55] text-[#111111] font-normal">
              Sonho em um dia lutar as Olimpíadas, e o Mundial de Taekwondo. Desejo conciliar o esporte com a faculdade, e por fim consolidar meu futuro e ter uma boa carreira que eu vá me orgulhar no futuro.
            </p>

            <!-- Marcos Futuros em Lista Minimalista Numerada -->
            <div class="mt-12 border-t border-neutral-300 divide-y divide-neutral-200">
              
              <div class="py-5 flex items-center justify-between gap-4 group">
                <div class="flex items-baseline gap-6">
                  <span class="font-sans text-xs tracking-editorial text-[#888888]">01</span>
                  <h3 class="font-sans text-sm sm:text-base uppercase tracking-wider font-medium text-[#111111]">
                    Jogos Olímpicos
                  </h3>
                </div>
                <span class="font-serif italic text-sm text-[#888888] group-hover:text-[#111111] transition-colors">
                  Meta Esportiva
                </span>
              </div>

              <div class="py-5 flex items-center justify-between gap-4 group">
                <div class="flex items-baseline gap-6">
                  <span class="font-sans text-xs tracking-editorial text-[#888888]">02</span>
                  <h3 class="font-sans text-sm sm:text-base uppercase tracking-wider font-medium text-[#111111]">
                    Mundial de Taekwondo
                  </h3>
                </div>
                <span class="font-serif italic text-sm text-[#888888] group-hover:text-[#111111] transition-colors">
                  Alto Rendimento
                </span>
              </div>

              <div class="py-5 flex items-center justify-between gap-4 group">
                <div class="flex items-baseline gap-6">
                  <span class="font-sans text-xs tracking-editorial text-[#888888]">03</span>
                  <h3 class="font-sans text-sm sm:text-base uppercase tracking-wider font-medium text-[#111111]">
                    Ensino Superior &amp; Carreira Consolidada
                  </h3>
                </div>
                <span class="font-serif italic text-sm text-[#888888] group-hover:text-[#111111] transition-colors">
                  Futuro Profissional
                </span>
              </div>

            </div>
          </div>
        </div>

      </div>
    </section>
  </main>

  <!-- =========================================================
       RODAPÉ MINIMALISTA
  ========================================================== -->
  <footer class="bg-[#F4F4F4] border-t border-neutral-200 py-12 px-6 sm:px-10">
    <div class="max-w-5xl mx-auto flex flex-col sm:flex-row items-center justify-between gap-6">
      <p class="font-serif text-lg sm:text-xl text-[#111111] tracking-tight">
        Giovanna Lopes — Portfólio
      </p>

      <button 
        type="button" 
        onclick="window.scrollTo({ top: 0, behavior: 'smooth' })"
        class="text-xs uppercase tracking-editorial px-6 py-3 rounded-sm bg-white border border-neutral-300 text-[#111111] hover:bg-[#111111] hover:text-white hover:border-[#111111] transition-all duration-300 flex items-center gap-2.5"
      >
        <span>Voltar ao topo</span>
        <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" stroke-width="1.8" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" d="M4.5 15.75l7.5-7.5 7.5 7.5" />
        </svg>
      </button>
    </div>
  </footer>

  <!-- =========================================================
       INTERATIVIDADE & ANIMAÇÕES SUAVES
  ========================================================== -->
  <script>
    // Controle do Menu Mobile
    const mobileMenuBtn = document.getElementById('mobileMenuBtn');
    const mobileMenu = document.getElementById('mobileMenu');

    mobileMenuBtn.addEventListener('click', () => {
      const isHidden = mobileMenu.classList.toggle('hidden');
      mobileMenuBtn.setAttribute('aria-expanded', String(!isHidden));
    });

    // Fecha o menu mobile ao selecionar um link
    mobileMenu.querySelectorAll('a').forEach(link => {
      link.addEventListener('click', () => {
        mobileMenu.classList.add('hidden');
        mobileMenuBtn.setAttribute('aria-expanded', 'false');
      });
    });

    // Animação sutil ao rolar (Scroll Reveal)
    const revealElements = document.querySelectorAll('.reveal');
    const revealObserver = new IntersectionObserver((entries) => {
      entries.forEach(entry => {
        if (entry.isIntersecting) {
          entry.target.classList.add('visible');
          revealObserver.unobserve(entry.target);
        }
      });
    }, {
      threshold: 0.12,
      rootMargin: '0px 0px -40px 0px'
    });

    revealElements.forEach(el => revealObserver.observe(el));
  </script>
</body>
</html>