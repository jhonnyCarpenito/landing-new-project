# Especificaciones de Desarrollo: MVP Landing Page "New Proyect" (Fase de Venta)

## 1. Rol y Objetivo
Actúa como un Desarrollador Front-End Senior experto en UI/UX y conversión. Tu objetivo es crear un MVP de una Landing Page (SPA estática) para la empresa "New Proyect". El propósito principal de este código es deslumbrar al cliente para ganar el contrato de desarrollo. El diseño debe ser extremadamente dinámico, moderno, minimalista, elegante y transmitir autoridad corporativa.

## 2. Stack Tecnológico (Estricto)
* **Estructura:** HTML5 semántico.
* **Estilos:** Tailwind CSS (vía CDN).
* **Interactividad:** Vanilla JavaScript (ES6+). 
* **Animaciones (El Efecto WOW):** Integra la librería AOS (Animate On Scroll) vía CDN (CSS y JS) e inicialízala. Utiliza clases `data-aos="fade-up"`, `data-aos="fade-right"`, etc., en las secciones, tarjetas y textos para que aparezcan suavemente al hacer scroll.
* **Iconografía:** Usa Heroicons o FontAwesome (vía CDN) con diseños minimalistas.

## 3. Guía de Diseño y UI/UX (Moderno y Elegante)
* **Paleta de Colores:**
    * Color Primario: `#180099` (Azul corporativo profundo. Usar en botones, overlay del hero y acentos).
    * Color Secundario: `#C5C5C5` (Gris claro. Usar para fondos sutiles, líneas divisorias y bordes).
    * Fondos: Blanco puro (`#FFFFFF`) y secciones alternas en `#F9FAFB` (gris muy claro) para separar contenido de forma limpia.
* **Tipografía:** Importa 'Inter' o 'Montserrat' desde Google Fonts. Usa pesos ligeros (300, 400) para párrafos y audaces (700, 800) para títulos.
* **Dinámica visual:**
    * **Navbar Glassmorphism:** El menú de navegación debe ser "sticky" (fijo en la parte superior) con un efecto de desenfoque (`backdrop-blur-md bg-white/80`) para que se vea premium.
    * **Tarjetas Interactivas:** Las cards de valores y experiencia deben tener `transition-all duration-300 hover:-translate-y-2 hover:shadow-2xl`.

## 4. Estructura de Contenido (Copywriting Exacto)

### Navbar (Sticky & Glassmorphism)
* Logo: ``
* Enlaces (Smooth Scroll): Inicio, Especialización, Experiencia, Filosofía.
* Botón CTA a la derecha: "Solicitar Presupuesto" (Fondo `#180099`, texto blanco, hover brillante).

### Sección 1: Hero Section (Impacto Visual)
* **Diseño:** Altura completa (`min-h-screen`). Imagen de fondo industrial de alta calidad con un overlay o gradiente lineal usando `#180099` (opacidad 70%) a negro.
* **Título (Animación fade-down):** New Proyect: Ingeniería y Mantenimiento Industrial Integral.
* **Subtítulo (Animación fade-up):** En New Proyect, combinamos experiencia, innovación y compromiso para asegurar la operatividad y eficiencia de tus equipos, minimizando tiempos de inactividad y optimizando tus procesos productivos.
* **Botones:** Dos botones. Uno primario ("Nuestros Servicios") y uno secundario con borde ("Conoce nuestra historia").

### Sección 2: ¿Quiénes Somos? (Especialización)
* Diseño de dos columnas (Grid). Izquierda: Texto. Derecha: Imagen representativa.
* **Etiqueta superior:** Tu Socio en Ingeniería y Mantenimiento Industrial.
* **Título:** Especialización Industrial.
* **Texto:** Somos una empresa dedicada exclusivamente a servicios de ingenieria mantenimiento y reparación de plantas y equipos industriales, con un enfoqus claro en la excelencia operativa.

### Sección 3: Por Qué Elegirnos (Tarjetas Dinámicas)
* Grid de 2 columnas para estas dos métricas clave. Cada tarjeta debe tener un icono grande y elegante.
* **Tarjeta 1 (AOS fade-right):** * *Título:* Más de 10 Años de Experiencia.
    * *Texto:* Con una década de trayectoria, garantizamos la operatividad, eficiencia y fiabilidad de tus instalaciones, apoyándonos en un profundo conocimiento del sector.
* **Tarjeta 2 (AOS fade-left):** * *Título:* Compromiso Total.
    * *Texto:* Nuestro compromiso se centra en la seguridad, la calidad y la mejora continua, asegurando que cada proyecto cumpla con los más altos estándares y expectationa.

### Sección 4: Nuestra Filosofía (Misión y Visión)
* Diseño de fondo oscuro (usar `#180099` de fondo y texto blanco/gris `#C5C5C5`) para crear contraste en la página.
* **Misión:** Ser una organización líder a nivel mundial en la ejecución de obras civiles, mecánicas, de electricidad e instrumentación, reconocida por la alta calidad de sus proyectos, tiempos de entrega, calidad del personal, y con un marcado sentido de pertenencia en cada uno de sus trabajadores. Optimizando constantemente cada uno de los recursos utilizados en el desarrollo de cada proceso y servicio de la empresa en el mercado.
* **Visión:** Ser una organización competitiva a nivel mundial capaz de cumplir y mantener los más altos estándares de servicios para la ejecución de Proyectos IPC, con total responsabilidad, entrega, ética, integridad y fe. Contando para ello con una estructura de equipos, maquinaria, capital humano idóneo para cada disciplina en particular o como Contratista General, innovando constantemente en nuevas tecnologías que nos permitan asegurar la calidad de nuestros procesos y satisfacer las demandas de nuestros clientes.

### Sección 5: Valores (Grid de Iconos)
* **Texto:** Nuestra organización se fundamenta en un conjunto de valores y políticas básicas que orientan las actuaciones de todos sus trabajadores:
* **Grid de Valores:** Muestra los siguientes valores en un grid responsivo de 3 o 4 columnas. Cada valor debe ser una pequeña caja interactiva: Integridad, Ética, Profesionalismo, Dedicación, Lealtad, Sentido de Pertenencia, Productividad, Excelencia, Respeto.

### Footer
* Simple y elegante. Fondo negro o gris muy oscuro. Textos en `#C5C5C5`. Incluye el año actual y "New Proyect".

## 5. Instrucciones Finales
1. Genera un único archivo `index.html` con todo el código integrado.
2. Asegúrate de incluir los scripts de Tailwind y AOS al final del `<body>`.
3. El diseño debe ser impecable en dispositivos móviles (Mobile First).