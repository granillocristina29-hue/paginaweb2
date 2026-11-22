<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Instituto Nacional Ernesto Flores | INEF - C.I.E. 12845</title>

    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        sv: {
                            blue: '#003366',
                            royal: '#0056b3',
                            gold: '#d4af37',
                            golddark: '#b89320',
                            accent: '#f0f4f8',
                            dark: '#0a192f'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">

    <style>
        body { font-family: 'Inter', sans-serif; }
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #f8f9fa; }
        ::-webkit-scrollbar-thumb { background: #003366; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #002244; }
        .bg-pattern {
            background-color: #003366;
            background-image: radial-gradient(#d4af37 0.75px, transparent 0.75px), radial-gradient(#d4af37 0.75px, #003366 0.75px);
            background-size: 30px 30px;
            background-position: 0 0, 15px 15px;
        }
        .carousel-slide img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
        }
    </style>
</head>

<body class="bg-gray-50 text-gray-800 flex flex-col min-h-screen">

    <div class="bg-sv-dark text-gray-300 text-xs py-1.5 px-4 border-b border-sv-gold/30">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-2">
            <div class="flex items-center gap-4">
                <span class="flex items-center gap-1.5 font-medium text-white">
                    <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span>
                    Gobierno de El Salvador | MINED
                </span>
                <span class="hidden md:inline text-gray-400">|</span>
                <span class="hidden md:inline text-gray-300">C.I.E. N° 12845 - San Salvador</span>
            </div>
            <div class="flex items-center gap-4 font-semibold">
                <a href="https://siges.sv" target="_blank" rel="noopener" class="text-sv-gold hover:text-yellow-300 transition-colors flex items-center gap-1">
                    <svg class="w-3.5 h-3.5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 16l-4-4m0 0l4-4m-4 4h14m-5 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h7a3 3 0 013 3v1"/></svg>
                    Acceso SIGES (Aula Virtual)
                </a>
                <span>|</span>
                <span class="text-gray-300">PBX: +(503) 2250-8900</span>
            </div>
        </div>
    </div>

    <header class="sticky top-0 z-50 bg-sv-blue text-white shadow-xl border-b-2 border-sv-gold">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <a href="#inicio" class="flex items-center gap-3.5 group">
                    <div class="w-12 h-12 p-1 rounded-full bg-white shadow-lg border-2 border-sv-gold flex items-center justify-center transition-transform group-hover:scale-105 overflow-hidden">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSuT8l-gQOitae6OU7_CZ_NlZKCIlw2kkQNbFhgQspO3A&s=10" alt="Logo INEF" class="w-full h-full object-contain">
                    </div>
                    <div class="flex flex-col">
                        <span class="font-black text-lg sm:text-xl tracking-tight leading-none text-white group-hover:text-sv-gold transition-colors">
                            INSTITUTO NACIONAL
                        </span>
                        <span class="text-xs sm:text-sm text-sv-gold font-bold tracking-widest uppercase">
                            "Ernesto Flores" (INEF)
                        </span>
                    </div>
                </a>

                <nav class="hidden lg:flex items-center gap-1 xl:gap-2 font-semibold text-sm">
                    <a href="#inicio" class="px-3 py-2 rounded-lg hover:bg-sv-royal hover:text-sv-gold transition-all">Inicio</a>
                    <a href="#oferta" class="px-3 py-2 rounded-lg hover:bg-sv-royal hover:text-sv-gold transition-all">Oferta Académica</a>
                    <a href="#avisos" class="px-3 py-2 rounded-lg hover:bg-sv-royal hover:text-sv-gold transition-all">Avisos MINED</a>
                    <a href="#nosotros" class="px-3 py-2 rounded-lg hover:bg-sv-royal hover:text-sv-gold transition-all">Nosotros</a>
                    <a href="#servicios" class="px-3 py-2 rounded-lg hover:bg-sv-royal hover:text-sv-gold transition-all">Servicios</a>
                    <a href="#calendario" class="px-3 py-2 rounded-lg hover:bg-sv-royal hover:text-sv-gold transition-all">Calendario 2026</a>
                    <a href="#contacto" class="ml-2 px-4 py-2 rounded-xl bg-sv-gold text-sv-blue font-extrabold hover:bg-yellow-400 shadow-md transition-all transform hover:-translate-y-0.5">
                        Contactar
                    </a>
                </nav>

                <div class="lg:hidden flex items-center">
                    <button id="mobile-menu-btn" class="p-2 rounded-lg text-white hover:bg-sv-royal focus:outline-none">
                        <svg id="menu-icon-open" class="h-7 w-7" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                        </svg>
                        <svg id="menu-icon-close" class="h-7 w-7 hidden" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
                        </svg>
                    </button>
                </div>
            </div>
        </div>

        <div id="mobile-menu" class="hidden lg:hidden bg-sv-blue border-t border-sv-royal px-4 pt-3 pb-6 space-y-2">
            <a href="#inicio" class="mobile-link block px-3 py-2 rounded-lg font-medium text-white hover:bg-sv-royal">Inicio</a>
            <a href="#oferta" class="mobile-link block px-3 py-2 rounded-lg font-medium text-white hover:bg-sv-royal">Oferta Académica</a>
            <a href="#avisos" class="mobile-link block px-3 py-2 rounded-lg font-medium text-white hover:bg-sv-royal">Avisos del MINED</a>
            <a href="#nosotros" class="mobile-link block px-3 py-2 rounded-lg font-medium text-white hover:bg-sv-royal">Historia y Misión</a>
            <a href="#servicios" class="mobile-link block px-3 py-2 rounded-lg font-medium text-white hover:bg-sv-royal">Servicios Estudiantiles</a>
            <a href="#calendario" class="mobile-link block px-3 py-2 rounded-lg font-medium text-white hover:bg-sv-royal">Calendario Escolar</a>
            <a href="#contacto" class="mobile-link block px-3 py-2.5 rounded-lg font-bold bg-sv-gold text-sv-blue text-center mt-2">Atención a Padres y Alumnos</a>
        </div>
    </header>

    <section id="inicio" class="relative bg-sv-blue text-white overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12 lg:py-20 relative z-10">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 items-center">
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-white/10 backdrop-blur-md border border-sv-gold/40 text-sv-gold text-xs font-bold uppercase tracking-wider">
                        <span class="w-2 h-2 rounded-full bg-sv-gold animate-ping"></span>
                        Matrículas Lectivas Abiertas 2026 - 2027
                    </div>

                    <h1 class="text-3xl sm:text-5xl font-black tracking-tight leading-tight">
                        Formación Técnica e Integral en el <span class="text-sv-gold">Instituto Nacional Ernesto Flores</span>
                    </h1>

                    <p class="text-base sm:text-lg text-gray-200 font-normal leading-relaxed max-w-2xl mx-auto lg:mx-0">
                        En el INEF promovemos la excelencia académica, disciplina e innovación tecnológica. Formamos bachilleres capacitados para la educación superior y la inserción laboral inmediata.
                    </p>

                    <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-2">
                        <a href="#contacto" class="w-full sm:w-auto px-7 py-3.5 rounded-xl bg-sv-gold text-sv-blue font-extrabold text-center hover:bg-yellow-400 shadow-xl shadow-black/20 transition-all transform hover:-translate-y-1">
                            Proceso de Admisión 2026
                        </a>
                        <a href="#oferta" class="w-full sm:w-auto px-7 py-3.5 rounded-xl border-2 border-white/40 hover:border-white text-white font-bold text-center hover:bg-white/10 transition-all">
                            Ver Bachilleratos
                        </a>
                    </div>

                    <div 
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-5">
                    <div class="relative rounded-2xl overflow-hidden shadow-2xl border-4 border-white/20 bg-sv-dark aspect-[4/3] group">
                        <div id="hero-carousel" class="w-full h-full relative">
                            <div class="carousel-slide absolute inset-0 opacity-100 transition-opacity duration-700">
                                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTyoEm4fbRcNu_bdyd8V1GY-HXUgnc2k-7jMW-1xqn9Pw&s=10" alt="Comunidad INEF">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent flex items-end p-5">
                                    <p class="text-white text-xs sm:text-sm font-semibold">Comunidad estudiantil INEF integrada y comprometida con el estudio.</p>
                                </div>
                            </div>

                            <div class="carousel-slide absolute inset-0 opacity-0 transition-opacity duration-700">
                                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTf0VykQp3l7jHZoysYsLkdUkn19Twjf5Lqzwn01fl3zA&s=10" alt="Tecnico en Desarrollo de software INEF">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent flex items-end p-5">
                                    <p class="text-white text-xs sm:text-sm font-semibold">Laboratorios de computación equipados para el área técnica en Software.</p>
                                </div>
                            </div>

                            <div class="carousel-slide absolute inset-0 opacity-0 transition-opacity duration-700">
                                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQAWzCO1dlU617JxvcCdaPN8s3YChhPJaW6vVHWXjM7tQ&s=10" alt="Tecnico productivo AgropecuarioINEF">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent flex items-end p-5">
                                    <p class="text-white text-xs sm:text-sm font-semibold">Tecnico productivo AgropecuarioINEF</p>
                                </div>
                            </div>

                            <div class="carousel-slide absolute inset-0 opacity-0 transition-opacity duration-700">
                                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRUTFq23zRIHBvkoqSQNqNeSVc8Cin3dWaZXjLW1jhQew&s=10" alt="Banda de Paz INEF">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent flex items-end p-5">
                                    <p class="text-white text-xs sm:text-sm font-semibold">Banda de Paz Institucional y actividades culturales INEF.</p>
                                </div>
                            </div>
                        </div>

                        <button id="carousel-prev" class="absolute left-3 top-1/2 -translate-y-1/2 w-9 h-9 rounded-full bg-black/50 hover:bg-sv-blue text-white flex items-center justify-center transition-all">
                            &#10094;
                        </button>
                        <button id="carousel-next" class="absolute right-3 top-1/2 -translate-y-1/2 w-9 h-9 rounded-full bg-black/50 hover:bg-sv-blue text-white flex items-center justify-center transition-all">
                            &#10095;
                        </button>

                        <div id="carousel-dots" class="absolute bottom-3 right-4 flex gap-1.5 z-20">
                            <button class="dot-btn w-2.5 h-2.5 rounded-full bg-white/50" data-index="0"></button>
                            <button class="dot-btn w-2.5 h-2.5 rounded-full bg-white/50" data-index="1"></button>
                            <button class="dot-btn w-2.5 h-2.5 rounded-full bg-white/50" data-index="2"></button>
                            <button class="dot-btn w-2.5 h-2.5 rounded-full bg-white/50" data-index="3"></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12 flex-grow">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8">
            <aside class="lg:col-span-3 space-y-6">
                <div class="bg-white p-5 rounded-2xl shadow-sm border border-gray-200 sticky top-28">
                    <h3 class="text-base font-black text-sv-blue mb-4 pb-2 border-b flex items-center gap-2">
                        <svg class="w-5 h-5 text-sv-gold" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/></svg>
                        Accesos Rápidos
                    </h3>
                    <ul class="space-y-2 text-xs font-semibold text-gray-700">
                        <li>
                            <a href="#oferta" class="flex items-center gap-2.5 p-2 rounded-xl hover:bg-sv-accent hover:text-sv-blue transition-colors">
                                <span class="w-2 h-2 rounded-full bg-sv-gold"></span>
                                Bachilleratos INEF
                            </a>
                        </li>
                        <li>
                            <a href="#avisos" class="flex items-center gap-2.5 p-2 rounded-xl hover:bg-sv-accent hover:text-sv-blue transition-colors">
                                <span class="w-2 h-2 rounded-full bg-sv-gold"></span>
                                Circulares y Avisos
                            </a>
                        </li>
                        <li>
                            <a href="#nosotros" class="flex items-center gap-2.5 p-2 rounded-xl hover:bg-sv-accent hover:text-sv-blue transition-colors">
                                <span class="w-2 h-2 rounded-full bg-sv-gold"></span>
                                Historia del Instituto
                            </a>
                        </li>
                        <li>
                            <a href="#servicios" class="flex items-center gap-2.5 p-2 rounded-xl hover:bg-sv-accent hover:text-sv-blue transition-colors">
                                <span class="w-2 h-2 rounded-full bg-sv-gold"></span>
                                Banda de Paz y Deportes
                            </a>
                        </li>
                        <li>
                            <a href="#calendario" class="flex items-center gap-2.5 p-2 rounded-xl hover:bg-sv-accent hover:text-sv-blue transition-colors">
                                <span class="w-2 h-2 rounded-full bg-sv-gold"></span>
                                Cronograma de Exámenes
                            </a>
                        </li>
                    </ul>

                    <div class="mt-6 p-4 rounded-xl bg-sv-accent border border-sv-royal/20 text-xs space-y-2">
                        <span class="inline-block px-2 py-0.5 rounded bg-sv-blue text-white font-bold text-[10px] uppercase">
                            MINED Informa
                        </span>
                        <p class="font-bold text-sv-blue">Paquetes Escolares INEF 2026</p>
                        <p class="text-gray-600 leading-relaxed">
                            Padres de familia del Instituto Nacional Ernesto Flores: pendientes de la entrega de uniformes y útiles según el calendario fijado.
                        </p>
                    </div>
                </div>
            </aside>

            <main class="lg:col-span-9 space-y-16">
                <section id="avisos" class="scroll-mt-28">
                    <div class="flex flex-col md:flex-row md:items-end justify-between mb-8">
                        <div>
                            <span class="text-sv-gold font-extrabold text-xs uppercase tracking-widest">Información Oficial</span>
                            <h2 class="text-2xl sm:text-3xl font-black text-sv-blue">Avisos y Comunicados INEF</h2>
                        </div>
                        <div class="flex gap-1.5 mt-3 md:mt-0" id="filter-buttons">
                            <button data-category="all" class="filter-btn active px-3 py-1.5 rounded-lg text-xs font-bold bg-sv-blue text-white shadow">Todos</button>
                            <button data-category="mined" class="filter-btn px-3 py-1.5 rounded-lg text-xs font-bold bg-gray-200 text-gray-700 hover:bg-gray-300">MINED</button>
                            <button data-category="academico" class="filter-btn px-3 py-1.5 rounded-lg text-xs font-bold bg-gray-200 text-gray-700 hover:bg-gray-300">Académico</button>
                        </div>
                    </div>

                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6" id="news-container">
                        <article class="notice-card mined bg-white rounded-2xl p-6 shadow-sm border border-gray-200 hover:border-sv-gold transition-all flex flex-col justify-between">
                            <div>
                                <div class="flex items-center justify-between mb-3">
                                    <span class="px-2.5 py-1 rounded-full text-[10px] font-black uppercase bg-blue-100 text-sv-blue">
                                        Prueba AVANZO 2026
                                    </span>
                                    <span class="text-xs text-gray-400 font-medium">Ministerio de Educación</span>
                                </div>
                                <h3 class="font-bold text-lg text-gray-900 mb-2">Prueba AVANZO en el INEF</h3>
                                <p class="text-gray-600 text-xs sm:text-sm leading-relaxed">
                                    Indicaciones para alumnos de 2° año General y 3° año Técnico sobre los ensayos y la prueba oficial en las aulas de cómputo del INEF.
                                </p>
                            </div>
                            <div class="mt-4 pt-4 border-t border-gray-100 flex items-center justify-between">
                                <span class="text-xs font-semibold text-gray-500">Dirigido a: Graduandos INEF</span>
                                <button onclick="openModal('Prueba AVANZO 2026 - INEF', 'La Prueba AVANZO evalúa las competencias en Matemática, Lenguaje, Ciencias y Sociales. Todos los alumnos del INEF deben verificar sus credenciales en SIGES antes de la prueba piloto.')" class="text-xs font-bold text-sv-royal hover:underline">
                                    Leer detalle &rarr;
                                </button>
                            </div>
                        </article>

                        <article class="notice-card academico bg-white rounded-2xl p-6 shadow-sm border border-gray-200 hover:border-sv-gold transition-all flex flex-col justify-between">
                            <div>
                                <div class="flex items-center justify-between mb-3">
                                    <span class="px-2.5 py-1 rounded-full text-[10px] font-black uppercase bg-amber-100 text-amber-800">
                                        Admisiones INEF 2026
                                    </span>
                                    <span class="text-xs text-gray-400 font-medium">Dirección Académica</span>
                                </div>
                                <h3 class="font-bold text-lg text-gray-900 mb-2">Ingreso de Nuevo Ingreso al INEF</h3>
                                <p class="text-gray-600 text-xs sm:text-sm leading-relaxed">
                                    Recepción de expediente académico para estudiantes de 9° grado interesados en ingresar al Instituto Nacional Ernesto Flores.
                                </p>
                            </div>
                            <div class="mt-4 pt-4 border-t border-gray-100 flex items-center justify-between">
                                <span class="text-xs font-semibold text-gray-500">Requisito: Certificado 9° Grado</span>
                                <button onclick="openModal('Admisiones INEF 2026', 'Requisitos INEF: Partida de nacimiento reciente, Certificado de 9° grado, Ficha de conducta, Fotocopia de DUI del responsable y 2 fotos tamaño cédula. Presentar en Secretaría.')" class="text-xs font-bold text-sv-royal hover:underline">
                                    Requisitos &rarr;
                                </button>
                            </div>
                        </article>
                    </div>
                </section>

                <section id="oferta" class="scroll-mt-28">
                    <div class="mb-8">
                        <span class="text-sv-gold font-extrabold text-xs uppercase tracking-widest">Planes de Estudio Acreditados</span>
                        <h2 class="text-2xl sm:text-3xl font-black text-sv-blue">Oferta Académica del Instituto Nacional Ernesto Flores</h2>
                    </div>

                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-200 hover:shadow-md transition-all flex flex-col justify-between">
                            <div>
                                <div class="h-44 w-full relative overflow-hidden">
                                    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSKD5V5MAsT5xTkQ_5bFrqaL1yvcqqYzP8w8CbkxP5vQw&s=10" alt="Bachillerato General INEF" class="w-full h-full object-cover">
                                    <span class="absolute top-3 right-3 px-2.5 py-1 rounded-md bg-sv-blue text-white font-bold text-xs shadow-md">2 Años</span>
                                </div>
                                <div class="p-6">
                                    <div class="flex items-center gap-2 mb-2">
                                        <span class="text-xl">📘</span>
                                        <h3 class="font-bold text-xl text-gray-900">Bachillerato General</h3>
                                    </div>
                                    <p class="text-gray-600 text-xs sm:text-sm leading-relaxed">
                                        Formación científica y humanística orientada a la continuidad de estudios superiores en la Universidad de El Salvador (UES) y universidades del país.
                                    </p>
                                </div>
                            </div>
                            <div class="px-6 pb-6">
                                <button onclick="openModal('Plan de Estudio - Bachillerato General INEF', 'Asignaturas: Matemática, Lenguaje y Literatura, Ciencias Naturales (Física, Química, Biología), Estudios Sociales, Inglés, Informática Educativa y Seminario de Investigación.')" class="w-full py-2.5 rounded-xl border border-sv-blue text-sv-blue font-bold hover:bg-sv-blue hover:text-white transition-colors text-xs">
                                    Ver Plan de Asignaturas
                                </button>
                            </div>
                        </div>

                        <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-200 hover:shadow-md transition-all flex flex-col justify-between">
                            <div>
                                <div class="h-44 w-full relative overflow-hidden">
                                    <img src="https://images.unsplash.com/photo-1517694712202-14dd9538aa97?auto=format&fit=crop&w=800&q=80" alt="BTV Desarrollo de Software INEF" class="w-full h-full object-cover">
                                    <span class="absolute top-3 right-3 px-2.5 py-1 rounded-md bg-amber-600 text-white font-bold text-xs shadow-md">3 Años</span>
                                </div>
                                <div class="p-6">
                                    <div class="flex items-center gap-2 mb-2">
                                        <span class="text-xl">💻</span>
                                        <h3 class="font-bold text-xl text-gray-900">BTV Desarrollo de Software</h3>
                                    </div>
                                    <p class="text-gray-600 text-xs sm:text-sm leading-relaxed">
                                        Especialización en lógica de programación, diseño y gestión de bases de datos, desarrollo web, mantenimiento de hardware y redes.
                                    </p>
                                </div>
                            </div>
                            <div class="px-6 pb-6">
                                <button onclick="openModal('Plan de Estudio - BTV Desarrollo de Software INEF', 'Módulos: Programación Orientada a Objetos, Bases de Datos SQL, Desarrollo Web HTML5/CSS/JS, Mantenimiento de Equipos, Redes de Cómputo e Inglés Técnico.')" class="w-full py-2.5 rounded-xl border border-sv-blue text-sv-blue font-bold hover:bg-sv-blue hover:text-white transition-colors text-xs">
                                    Ver Plan de Asignaturas
                                </button>
                            </div>
                        </div>

                        <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-200 hover:shadow-md transition-all flex flex-col justify-between">
                            <div>
                                <div class="h-44 w-full relative overflow-hidden">
                                    <img src="https://images.unsplash.com/photo-1554224155-8d04cb21cd6c?auto=format&fit=crop&w=800&q=80" alt="BTV Administrativo Contable INEF" class="w-full h-full object-cover">
                                    <span class="absolute top-3 right-3 px-2.5 py-1 rounded-md bg-purple-600 text-white font-bold text-xs shadow-md">3 Años</span>
                                </div>
                                <div class="p-6">
                                    <div class="flex items-center gap-2 mb-2">
                                        <span class="text-xl">📈</span>
                                        <h3 class="font-bold text-xl text-gray-900">BTV Administrativo Contable</h3>
                                    </div>
                                    <p class="text-gray-600 text-xs sm:text-sm leading-relaxed">
                                        Formación técnica en contabilidad empresarial, legislación tributaria y laboral, administración presupuestaria y herramientas contables digitales.
                                    </p>
                                </div>
                            </div>
                            <div class="px-6 pb-6">
                                <button onclick="openModal('Plan de Estudio - BTV Administrativo Contable INEF', 'Módulos: Contabilidad Financiera, Legislación Mercantil y Tributaria, Administración de Empresas, Auditoría Básica y Paquetes de Software Contable.')" class="w-full py-2.5 rounded-xl border border-sv-blue text-sv-blue font-bold hover:bg-sv-blue hover:text-white transition-colors text-xs">
                                    Ver Plan de Asignaturas
                                </button>
                            </div>
                        </div>

                        <div class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-200 hover:shadow-md transition-all flex flex-col justify-between">
                            <div>
                                <div class="h-44 w-full relative overflow-hidden">
                                   <img src="https://6aecdd61636bf09493c4ae0d.imgix.net/sandbox/f710e31d-7ec4-4a7a-b5b5-ff7c0c3f6fb0.jpg" alt="BTV Administrativo Contable INEF" class="w-full h-full object-cover">
                                     <span class="absolute top-3 right-3 px-2. five py-1 rounded-md bg-green-700 text-white font-bold text-xs shadow-md">3 Años</span>
                                </div>
                                <div class="p-6">
                                    <div class="flex items-center gap-2 mb-2">
                                        <span class="text-xl">🌱</span>
                                        <h3 class="font-bold text-xl text-gray-900">BTV Agropecuario</h3>
                                    </div>
                                    <p class="text-gray-600 text-xs sm:text-sm leading-relaxed">
                                        Formación técnico-práctica en producción agrícola y pecuaria, manejo de suelos y cultivos, sanidad animal y gestión de proyectos productivos sostenibles.
                                    </p>
                                </div>
                            </div>
                            <div class="px-6 pb-6">
                                <button onclick="openModal('Plan de Estudio - BTV Agropecuario INEF', 'Módulos: Producción Agrícola, Producción Pecuaria, Manejo de Suelos y Riego, Sanidad Vegetal y Animal, Agroindustria Básica y Gestión de Proyectos Productivos.')" class="w-full py-2.5 rounded-xl border border-sv-blue text-sv-blue font-bold hover:bg-sv-blue hover:text-white transition-colors text-xs">
                                    Ver Plan de Asignaturas
                                </button>
                            </div>
                        </div>
                    </div>
                </section>

                <section id="nosotros" class="scroll-mt-28 bg-sv-accent p-8 rounded-2xl border border-sv-royal/10">
                    <div class="max-w-3xl">
                        <span class="text-sv-gold font-extrabold text-xs uppercase tracking-widest">Nuestra Institución</span>
                        <h2 class="text-2xl sm:text-3xl font-black text-sv-blue mb-4">Historia y Misión del INEF</h2>
                        <p class="text-gray-700 text-sm leading-relaxed mb-4">
                            El Instituto Nacional Ernesto Flores (INEF), identificado bajo el código C.I.E. 12845, es una institución pública comprometida con la formación de bachilleres integrales, fomentando la excelencia académica, el civismo y la inserción técnica.
                        </p>
                        <p class="text-gray-700 text-sm leading-relaxed">
                            Bajo las directrices del Ministerio de Educación de El Salvador, nuestra misión es capacitar a los jóvenes en competencias técnicas, tecnológicas y humanas para que aporten activamente al desarrollo de la sociedad.
                        </p>
                    </div>
                </section>

                <section id="servicios" class="scroll-mt-28">
                    <div class="mb-8">
                        <span class="text-sv-gold font-extrabold text-xs uppercase tracking-widest">Desarrollo Integral</span>
                        <h2 class="text-2xl sm:text-3xl font-black text-sv-blue">Servicios y Actividades INEF</h2>
                    </div>

                    <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                        <div class="bg-white p-5 rounded-xl border border-gray-200">
                            <h4 class="font-bold text-sv-blue text-base mb-2">🥁 Banda de Paz INEF</h4>
                            <p class="text-gray-600 text-xs leading-relaxed">Agrupación musical representativa en eventos patrios y culturales de la región.</p>
                        </div>
                        <div class="bg-white p-5 rounded-xl border border-gray-200">
                            <h4 class="font-bold text-sv-blue text-base mb-2">⚽ Deportes Institucionales</h4>
                            <p class="text-gray-600 text-xs leading-relaxed">Selecciones estudiantiles de fútbol sala, baloncesto y torneos intramuros.</p>
                        </div>
                        <div class="bg-white p-5 rounded-xl border border-gray-200">
                            <h4 class="font-bold text-sv-blue text-base mb-2">🧠 Orientación Estudiantil</h4>
                            <p class="text-gray-600 text-xs leading-relaxed">Atención psicopedagógica, orientación vocacional y ferias universitarias.</p>
                        </div>
                    </div>
                </section>

                <section id="calendario" class="scroll-mt-28">
                    <div class="mb-6">
                        <span class="text-sv-gold font-extrabold text-xs uppercase tracking-widest">Fechas Clave</span>
                        <h2 class="text-2xl sm:text-3xl font-black text-sv-blue">Calendario Lectivo INEF 2026</h2>
                    </div>

                    <div class="bg-white rounded-2xl border border-gray-200 overflow-hidden shadow-sm text-xs sm:text-sm">
                        <div class="divide-y divide-gray-100">
                            <div class="p-4 flex justify-between items-center hover:bg-gray-50">
                                <div>
                                    <span class="font-bold text-sv-blue block">Evaluaciones del Primer Periodo</span>
                                    <span class="text-gray-500 text-xs">Exámenes parciales y revisión de proyectos</span>
                                </div>
                                <span class="px-3 py-1 bg-sv-accent text-sv-blue font-bold rounded-lg text-xs">Marzo 2026</span>
                            </div>
                            <div class="p-4 flex justify-between items-center hover:bg-gray-50">
                                <div>
                                    <span class="font-bold text-sv-blue block">Feria de Logros Técnicos INEF</span>
                                    <span class="text-gray-500 text-xs">Exposición de proyectos finales BTV (Software, Contabilidad y Agropecuario)</span>
                                </div>
                                <span class="px-3 py-1 bg-sv-accent text-sv-blue font-bold rounded-lg text-xs">Julio 2026</span>
                            </div>
                            <div class="p-4 flex justify-between items-center hover:bg-gray-50">
                                <div>
                                    <span class="font-bold text-sv-blue block">Aplicación Prueba AVANZO</span>
                                    <span class="text-gray-500 text-xs">Evaluación nacional de graduandos</span>
                                </div>
                                <span class="px-3 py-1 bg-sv-accent text-sv-blue font-bold rounded-lg text-xs">Octubre 2026</span>
                            </div>
                        </div>
                    </div>
                </section>

                <section id="contacto" class="scroll-mt-28 bg-white p-8 rounded-2xl shadow-sm border border-gray-200">
                    <div class="max-w-2xl">
                        <span class="text-sv-gold font-extrabold text-xs uppercase tracking-widest">Comunicación Directa</span>
                        <h2 class="text-2xl sm:text-3xl font-black text-sv-blue mb-6">Atención a Padres y Alumnos INEF</h2>

                        <form class="space-y-4" onsubmit="event.preventDefault(); openModal('Mensaje Enviado', 'Su mensaje ha sido enviado exitosamente a la Secretaría del Instituto Nacional Ernesto Flores. Le responderemos en un plazo máximo de 48 horas hábiles.');">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label class="block text-xs font-bold text-gray-700 mb-1">Nombre Completo</label>
                                    <input type="text" required class="w-full px-3 py-2 border border-gray-300 rounded-lg text-sm focus:outline-none focus:border-sv-blue">
                                </div>
                                <div>
                                    <label class="block text-xs font-bold text-gray-700 mb-1">Correo / Teléfono de Contacto</label>
                                    <input type="text" required class="w-full px-3 py-2 border border-gray-300 rounded-lg text-sm focus:outline-none focus:border-sv-blue">
                                </div>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Asunto de la Consulta</label>
                                <select class="w-full px-3 py-2 border border-gray-300 rounded-lg text-sm focus:outline-none focus:border-sv-blue">
                                    <option>Admisión y Matrícula 2026</option>
                                    <option>Solicitud de Certificados y Constancias</option>
                                    <option>Atención Psicopedagógica</option>
                                    <option>Consulta General</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 mb-1">Mensaje</label>
                                <textarea rows="4" required class="w-full px-3 py-2 border border-gray-300 rounded-lg text-sm focus:outline-none focus:border-sv-blue"></textarea>
                            </div>
                            <button type="submit" class="w-full sm:w-auto px-6 py-3 rounded-xl bg-sv-blue text-white font-bold text-sm hover:bg-sv-royal transition-colors">
                                Enviar Mensaje
                            </button>
                        </form>
                    </div>
                </section>
            </main>
        </div>
    </div>

    <footer class="bg-sv-dark text-gray-400 text-xs py-10 border-t border-sv-gold/20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid grid-cols-1 md:grid-cols-3 gap-8 mb-8">
            <div>
                <h4 class="text-white font-bold text-sm mb-3">INSTITUTO NACIONAL "ERNESTO FLORES"</h4>
                <p class="leading-relaxed text-gray-400">Código de Infraestructura Escolar (C.I.E.): 12845<br>San Salvador, El Salvador, C.A.</p>
            </div>
            <div>
                <h4 class="text-white font-bold text-sm mb-3">Horario de Secretaría INEF</h4>
                <p class="leading-relaxed">Lunes a Viernes: 7:00 AM – 4:00 PM<br>Atención a Padres: Previa Cita</p>
            </div>
            <div>
                <h4 class="text-white font-bold text-sm mb-3">Enlaces Institucionales</h4>
                <ul class="space-y-1 text-gray-400">
                    <li><a href="https://www.mined.gob.sv" target="_blank" class="hover:text-sv-gold">Ministerio de Educación (MINED)</a></li>
                    <li><a href="https://siges.sv" target="_blank" class="hover:text-sv-gold">Plataforma SIGES</a></li>
                </ul>
            </div>
        </div>
        <div class="border-t border-gray-800 pt-6 text-center text-gray-500 max-w-7xl mx-auto px-4">
            <p>&copy; 2026 Instituto Nacional Ernesto Flores (INEF) - Todos los derechos reservados.</p>
        </div>
    </footer>

    <div id="info-modal" class="fixed inset-0 bg-black/60 backdrop-blur-sm z-50 hidden flex items-center justify-center p-4">
        <div class="bg-white rounded-2xl max-w-md w-full p-6 shadow-2xl space-y-4">
            <h3 id="modal-title" class="text-lg font-black text-sv-blue"></h3>
            <p id="modal-content" class="text-xs sm:text-sm text-gray-600 leading-relaxed"></p>
            <div class="pt-2 text-right">
                <button onclick="closeModal()" class="px-5 py-2 rounded-xl bg-sv-blue text-white font-bold text-xs hover:bg-sv-royal">
                    Cerrar
                </button>
            </div>
        </div>
    </div>

    <script>
        const menuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        const iconOpen = document.getElementById('menu-icon-open');
        const iconClose = document.getElementById('menu-icon-close');

        menuBtn.addEventListener('click', () => {
            const isHidden = mobileMenu.classList.contains('hidden');
            if (isHidden) {
                mobileMenu.classList.remove('hidden');
                iconOpen.classList.add('hidden');
                iconClose.classList.remove('hidden');
            } else {
                mobileMenu.classList.add('hidden');
                iconOpen.classList.remove('hidden');
                iconClose.classList.add('hidden');
            }
        });

        document.querySelectorAll('.mobile-link').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
                iconOpen.classList.remove('hidden');
                iconClose.classList.add('hidden');
            });
        });

        const slides = document.querySelectorAll('.carousel-slide');
        const dots = document.querySelectorAll('.dot-btn');
        let currentSlide = 0;
        let carouselInterval;

        function showSlide(index) {
            slides.forEach((slide, i) => {
                slide.style.opacity = i === index ? '1' : '0';
            });

            dots.forEach((dot, i) => {
                if (i === index) {
                    dot.classList.remove('bg-white/50');
                    dot.classList.add('bg-sv-gold', 'w-5');
                } else {
                    dot.classList.remove('bg-sv-gold', 'w-5');
                    dot.classList.add('bg-white/50');
                }
            });

            currentSlide = index;
        }

        function nextSlide() {
            showSlide((currentSlide + 1) % slides.length);
        }

        function prevSlide() {
            showSlide((currentSlide - 1 + slides.length) % slides.length);
        }

        document.getElementById('carousel-next').addEventListener('click', () => {
            nextSlide();
            resetTimer();
        });

        document.getElementById('carousel-prev').addEventListener('click', () => {
            prevSlide();
            resetTimer();
        });

        dots.forEach(dot => {
            dot.addEventListener('click', (e) => {
                const index = parseInt(e.target.getAttribute('data-index'));
                showSlide(index);
                resetTimer();
            });
        });

        function resetTimer() {
            clearInterval(carouselInterval);
            carouselInterval = setInterval(nextSlide, 5000);
        }

        showSlide(0);
        resetTimer();

        const filterBtns = document.querySelectorAll('.filter-btn');
        const noticeCards = document.querySelectorAll('.notice-card');

        filterBtns.forEach(btn => {
            btn.addEventListener('click', () => {
                const category = btn.dataset.category;

                filterBtns.forEach(b => {
                    b.classList.remove('bg-sv-blue', 'text-white', 'shadow');
                    b.classList.add('bg-gray-200', 'text-gray-700');
                });

                btn.classList.remove('bg-gray-200', 'text-gray-700');
                btn.classList.add('bg-sv-blue', 'text-white', 'shadow');

                noticeCards.forEach(card => {
                    const matches = category === 'all' || card.classList.contains(category);
                    card.style.display = matches ? 'flex' : 'none';
                });
            });
        });

        function openModal(title, content) {
            document.getElementById('modal-title').textContent = title;
            document.getElementById('modal-content').textContent = content;
            document.getElementById('info-modal').classList.remove('hidden');
        }

        function closeModal() {
            document.getElementById('info-modal').classList.add('hidden');
        }
    </script>
</body>
</html>
