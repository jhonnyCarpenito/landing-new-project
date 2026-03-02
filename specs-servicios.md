# Especificaciones de Refactorización: Sección Servicios (Full Text + Galerías)

## 1. Objetivo y Nuevo Enfoque UI/UX
El cliente ha solicitado que el texto de los servicios se muestre **en su totalidad, sin recortes**, e incluir galerías de imágenes. Debes refactorizar la sección utilizando un enfoque de **Tarjetas (Cards) + Paneles Laterales Deslizantes (Drawers) o Ventanas Modales (Modals)**.

* **Vista Principal:** Un Grid de 5 tarjetas elegantes. Cada tarjeta mostrará el título del servicio, un icono/imagen representativa y un botón "Ver Especificaciones Técnicas".
* **Interacción (JavaScript):** Al hacer clic en el botón, se debe abrir un Modal o un Drawer.
* **Contenido del Modal:** Dentro del Modal se volcará TODO el texto detallado a continuación, seguido de una galería de imágenes de prueba (Placeholders).

## 2. Textos de Introducción (Sección Principal)
* **Título:** SERVICIOS
* **Subtítulo:** Ingeniería 360° para la Continuidad de su Industria
* **Descripción:** En New Proyect, integramos capacidades críticas para garantizar la eficiencia de sus activos. Desde la intervención especializada de equipos estáticos y rotativos, hasta obras civiles de envergadura y gestión de procura internacional, ofrecemos un respaldo técnico total. Nuestro compromiso es transformar el mantenimiento en una ventaja competitiva para su operación.

## 3. Contenido Íntegro para los Modales/Drawers

### Modal Servicio 1: Inspección Técnica y Ensayos No Destructivos (END)
* **Texto Principal:** La prevención es la base de la rentabilidad. En New Proyect, aplicamos metodologías avanzadas de inspección para evaluar la condición real de sus equipos, identificar riesgos antes de que se conviertan en fallas y garantizar el cumplimiento de las normativas internacionales de seguridad.
* **1. Evaluación de Integridad Mecánica:** Realizamos diagnósticos profundos para determinar la vida remanente y el estado operativo de sus instalaciones críticas.
    * Estudios de Inspección Inicial: Auditoría técnica integral antes de paradas de planta o puestas en marcha.
    * Medición de Espesores (Ultrasonido): Monitoreo de pérdida de material por corrosión o erosión en tuberías, recipientes a presión y tanques.
    * Análisis de Verticalidad y Asentamiento: Control geométrico preciso en tanques de almacenamiento para prevenir fallas estructurales.
* **2. Ensayos No Destructivos (END):** Detección de discontinuidades sin alterar la integridad de la pieza o equipo.
    * Líquidos Penetrantes y Partículas Magnéticas: Localización de grietas y defectos superficiales o subsuperficiales en soldaduras y componentes críticos.
    * Inspección Visual (VT): Evaluaciones directas e indirectas bajo estándares internacionales (API, ASME, AWS).
    * Pruebas de Hermeticidad: Verificación de fugas en sistemas de tuberías y sellos.
* **3. Ingeniería de Corrosión y Reportes Técnicos:** No solo entregamos datos, entregamos soluciones.
    * Mapeo de Corrosión: Identificación de zonas críticas para planificación de parches o reemplazos.
    * Informes de Certificación: Documentación técnica detallada para auditorías y cumplimiento legal.
* **¿Por qué confiar su inspección con nosotros?**
    * Precisión Milimétrica: Equipos de medición de última generación calibrados bajo normas internacionales.
    * Personal Certificado API: Inspectores con amplia experiencia en entornos industriales exigentes.
    * Optimización de Costos: Al identificar el problema exacto, evitamos reparaciones innecesarias y extendemos la vida útil de sus activos.
* **-> [INSTRUCCIÓN PARA CURSOR: Insertar aquí un Grid de 3 imágenes usando la URL: `https://placehold.co/600x400/180099/FFFFFF?text=Galeria+END`]**

### Modal Servicio 2: Integridad Mecánica y Mantenimiento de Equipos
* **Texto Principal:** Maximizamos la disponibilidad de sus activos mediante intervenciones técnicas de alta precisión. En New Proyect, combinamos ingeniería de detalle con ejecución especializada para garantizar que sus equipos estáticos y rotativos operen bajo los más altos estándares de eficiencia y seguridad.
* **1. Equipos Estáticos y de Transferencia de Calor:** Especialistas en la recuperación de la eficiencia térmica y la integridad estructural de unidades sometidas a altas presiones y temperaturas.
    * Intercambiadores de Calor y Aeroenfriadores: Limpieza mecánica y química, retubado, reparación de haces de tubos y pruebas hidrostáticas.
    * Calderas y Hornos Reformadores: Mantenimiento de sistemas de combustión, sustitución de refractarios, cambio de tuberías (coils) y optimización de quemadores.
    * Recipientes a Presión: Reparaciones soldadas bajo código ASME, cambio de juntas y adecuación de boquillas.
* **2. Equipos Rotativos y Sistemas de Bombeo:** Soluciones enfocadas en reducir la vibración, el desgaste prematuro y el consumo energético.
    * Bombas Centrífugas: Overhaul completo, reconstrucción de ejes, cambio de sellos mecánicos, rodamientos e impulsores.
    * Motores Eléctricos: Diagnóstico de fallas, mantenimiento preventivo y correctivo, y alineación láser para garantizar una transmisión de potencia óptima.
    * Balanceo Dinámico: Eliminación de vibraciones críticas para extender la vida útil de los componentes mecánicos.
* **3. Válvulas de Control y Seguridad:** Precisión en el control de procesos para evitar fugas y garantizar la seguridad operativa.
    * Mantenimiento y Calibración: Desarmado, limpieza, rectificado de asientos y calibración de actuadores y posicionadores.
    * Pruebas de Banco: Certificación de estanqueidad y disparo según normativas internacionales.
* **Nuestro Valor Agregado en el Taller y Campo:**
    * Ingeniería de Recuperación: No solo reparamos; analizamos la causa raíz de la falla para proponer mejoras que optimicen el rendimiento original del equipo.
    * Gestión de Paradas de Planta (Turnarounds): Capacidad de movilización masiva de personal y herramientas para intervenciones en tiempos críticos.
    * Estándares Internacionales: Ejecución basada en normas API, ASME y AWS.
* **-> [INSTRUCCIÓN PARA CURSOR: Insertar aquí un Grid de 3 imágenes usando la URL: `https://placehold.co/600x400/180099/FFFFFF?text=Mantenimiento+Equipos`]**

### Modal Servicio 3: Mantenimiento Mayor e Integridad de Tanques de Almacenamiento
* **Texto Principal:** Garantizamos la vida útil y la seguridad operativa de sus sistemas de almacenamiento. Ejecutamos proyectos de recuperación mayor de tanques de crudo, integrando ingeniería de precisión, soldadura calificada y tratamientos de superficie avanzados.
* **1. Fase de Preparación y Diagnóstico Inicial:**
    * Desgasificación y Limpieza Mecánica: Extracción de lodos y limpieza profunda.
    * Inspección Bajo Norma API 653: Evaluación técnica mediante Ensayos No Destructivos (END).
    * Estudios de Verticalidad y Asentamiento: Verificación geométrica.
* **2. Reparación Estructural y Mecánica:**
    * Sustitución de Láminas de Piso y Cuerpo: Reemplazo de planchas mediante soldaduras certificadas.
    * Reparación de Techos (Fijos o Flotantes): Mantenimiento de pontones y sistemas de sellado.
    * Intervención de Boquillas y Accesorios: Sustitución o refuerzo de "manways".
* **3. Obra Civil y Contención:**
    * Adecuación de Diques de Seguridad: Replanteo y reconstrucción de muros.
    * Reparación de Anillos de Concreto: Inyección de grietas y nivelación.
* **4. Tratamiento de Superficies y Recubrimientos:**
    * Preparación de Superficie (Sandblasting): Limpieza abrasiva a metal blanco o comercial.
    * Aplicación de Recubrimientos Epóxicos: Esquemas de pintura de alto desempeño.
* **5. Pruebas Finales y Puesta en Marcha:**
    * Pruebas Hidrostáticas, de Vacío (Vacuum Test) y Certificación de Aptitud.
* **-> [INSTRUCCIÓN PARA CURSOR: Insertar aquí un Grid de 4 imágenes usando la URL: `https://placehold.co/600x400/180099/FFFFFF?text=Tanques+Almacenamiento`]**

### Modal Servicio 4: Ingeniería Civil y Movimientos de Tierra
* **Texto Principal:** Toda gran obra comienza desde el suelo. En New Proyect, transformamos el terreno para adaptarlo a las exigencias de la industria pesada. Combinamos precisión técnica en replanteos con la potencia operativa necesaria para ejecutar movimientos de tierra, excavaciones y sistemas de contención que garantizan la estabilidad de sus activos.
* **1. Movimientos de Tierra y Preparación de Sitios:**
    * Excavaciones Masivas y de Precisión: Para fundaciones de equipos y sótanos industriales.
    * Nivelación y Compactación de Suelos: Preparación de sub-bases.
    * Terracerías y Vialismo Interno: Construcción de vías de acceso.
* **2. Sistemas de Contención y Diques de Almacenamiento:**
    * Replanteo y Construcción de Diques: Diseño y ejecución de muros de contención.
    * Impermeabilización de Cubetos y Muros de Contención Estructurales.
* **3. Perforaciones y Cimentaciones Especiales:**
    * Perforaciones Industriales y Bases para Equipos Pesados.
    * Canalizaciones Subterráneas: Perforación y zanjado.
* **Capacidad Operativa:**
    * Precisión Topográfica, Maquinaria Propia y Cumplimiento Ambiental.
* **-> [INSTRUCCIÓN PARA CURSOR: Insertar aquí un Grid de 2 imágenes usando la URL: `https://placehold.co/600x400/180099/FFFFFF?text=Obras+Civiles`]**

### Modal Servicio 5: Gestión de Procura y Suministros Globales
* **Texto Principal:** Sabemos que un componente crítico puede detener toda una línea de producción. Optimizamos su cadena de suministro mediante una gestión de procura inteligente, conectando sus necesidades técnicas con los mejores fabricantes nacionales e internacionales. No solo entregamos materiales; entregamos disponibilidad operativa.
* **1. Procura Internacional (Importación Especializada):**
    * Equipos OEM, Logística "Puerta a Planta" y Búsqueda de Componentes Obsoletos.
* **2. Procura Nacional y Suministros Locales:**
    * Materiales de Construcción Industrial (ASTM/API), Insumos para Mantenimiento y Consumibles de Soldadura.
* **3. Suministro de Equipos Críticos:**
    * Válvulas de control, bombas industriales, motores y sistemas de control.
* **¿Por qué elegir nuestra gestión de procura?**
    * Validación Técnica por ingenieros, Trazabilidad Total (Dossier de Calidad) y Reducción de Lead Times.
* **-> [INSTRUCCIÓN PARA CURSOR: Insertar aquí un Grid de 2 imágenes usando la URL: `https://placehold.co/600x400/180099/FFFFFF?text=Gestion+Procura`]**

## 4. Estilos y Estructura Técnica (Tailwind + Vanilla JS)
1.  **Tarjetas (Grid Principal):** Crea un `<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">`. Cada tarjeta debe tener un diseño limpio, sombra suave (`shadow-lg`), el color primario `#180099` al hacer hover y un botón distintivo.
2.  **Modales/Drawers:** Utiliza un contenedor superpuesto (`fixed inset-0 bg-black bg-opacity-50 z-50`) oculto por defecto. El contenido debe tener fondo blanco, máximo ancho (`max-w-4xl`), scroll vertical y un botón claro de "Cerrar".
3.  **Galerías de Imágenes (IMPORTANTE):** Al final del contenido de cada modal, crea un `<div class="grid grid-cols-1 sm:grid-cols-2 gap-4 mt-8">` e inserta las etiquetas `<img>` apuntando a las URLs de `placehold.co` indicadas en los textos, asegurando que tengan `class="w-full h-auto rounded-lg shadow-md object-cover"`.
4.  **Lógica JS:** Añade el script para manejar la apertura y cierre dinámico de estos modales.