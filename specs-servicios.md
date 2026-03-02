# Especificaciones para Nueva Sección: Servicios

## 1. Objetivo y Diseño
Debes integrar una nueva sección de "Servicios" en la Landing Page existente. 
* **Estilo:** Moderno, corporativo y dinámico.
* **Estructura UI (Crucial):** Como hay mucho contenido, implementa un **Sistema de Pestañas (Tabs)**. En pantallas grandes, muestra un menú lateral o superior con los 5 servicios. Al hacer clic, el contenido principal debe cambiar suavemente (fade-in) mostrando la información y fotos del servicio activo. En móviles, esto puede colapsar en un Acordeón.
* **Imágenes de prueba:** Utiliza etiquetas `<img>` apuntando a `https://placehold.co/800x600/180099/FFFFFF?text=Imagen+[Nombre+Servicio]` para simular las galerías.

## 2. Textos Generales de la Sección
* **Título de la Sección:** Servicios
* **Subtítulo/Introducción:** Ingeniería 360° para la Continuidad de su Industria.
* **Descripción:** En New Proyect, integramos capacidades críticas para garantizar la eficiencia de sus activos. Desde la intervención especializada de equipos estáticos y rotativos, hasta obras civiles de envergadura y gestión de procura internacional, ofrecemos un respaldo técnico total. Nuestro compromiso es transformar el mantenimiento en una ventaja competitiva para su operación.

## 3. Contenido de los 5 Servicios (Para inyectar en las Pestañas/Acordeón)

### Servicio 1: Inspección Técnica y Ensayos No Destructivos (END)
* **Desglose:** La prevención es la base de la rentabilidad. Aplicamos metodologías avanzadas de inspección para evaluar la condición real de sus equipos, identificar riesgos antes de que se conviertan en fallas y garantizar el cumplimiento de las normativas internacionales de seguridad.
* **Puntos Clave:**
  * Evaluación de Integridad Mecánica: Estudios iniciales, medición de espesores (ultrasonido) y análisis de verticalidad en tanques.
  * Ensayos No Destructivos (END): Líquidos penetrantes, partículas magnéticas, inspección visual (VT) y pruebas de hermeticidad.
  * Ingeniería de Corrosión y Reportes: Mapeo de corrosión e informes de certificación técnica.
* **Galería:** Incluir un grid de 2 a 3 imágenes de prueba (placeholders).

### Servicio 2: Integridad Mecánica y Mantenimiento de Equipos
* **Desglose:** Maximizamos la disponibilidad de sus activos mediante intervenciones técnicas de alta precisión. Combinamos ingeniería de detalle con ejecución especializada para garantizar que sus equipos estáticos y rotativos operen bajo los más altos estándares de eficiencia y seguridad.
* **Puntos Clave:**
  * Equipos Estáticos y de Transferencia de Calor: Intercambiadores, calderas, hornos reformadores y recipientes a presión (código ASME).
  * Equipos Rotativos y Sistemas de Bombeo: Bombas centrífugas, overhaul de motores eléctricos y balanceo dinámico.
  * Válvulas de Control y Seguridad: Mantenimiento, calibración y pruebas de banco.
  * Valor Agregado: Gestión de paradas de planta (Turnarounds) y ejecución basada en normas API, ASME y AWS.
* **Galería:** Incluir un grid de 3 imágenes de prueba.

### Servicio 3: Mantenimiento Mayor e Integridad de Tanques de Almacenamiento
* **Desglose:** Garantizamos la vida útil y la seguridad operativa de sus sistemas de almacenamiento. Ejecutamos proyectos de recuperación mayor de tanques de crudo, integrando ingeniería de precisión, soldadura calificada y tratamientos de superficie avanzados.
* **Puntos Clave:**
  * Fase de Preparación: Desgasificación, limpieza mecánica e inspección bajo Norma API 653.
  * Reparación Estructural y Mecánica: Sustitución de láminas de piso/cuerpo y reparación de techos (fijos o flotantes).
  * Obra Civil y Tratamientos: Adecuación de diques, reparación de anillos de concreto, sandblasting y recubrimientos epóxicos.
  * Pruebas Finales: Pruebas hidrostáticas, vacuum test y certificación de aptitud.
* **Galería:** Incluir un grid de 3 imágenes de prueba.

### Servicio 4: Ingeniería Civil y Movimientos de Tierra
* **Desglose:** Toda gran obra comienza desde el suelo. En New Proyect, transformamos el terreno para adaptarlo a las exigencias de la industria pesada. Combinamos precisión técnica en replanteos con la potencia operativa necesaria para ejecutar movimientos de tierra, excavaciones y sistemas de contención.
* **Puntos Clave:**
  * Movimientos de Tierra: Excavaciones masivas, nivelación, compactación de suelos y vialidad interna.
  * Sistemas de Contención: Replanteo y construcción de diques, impermeabilización de cubetos y muros estructurales.
  * Cimentaciones Especiales: Perforaciones industriales, bases para equipos pesados y canalizaciones subterráneas.
* **Galería:** Incluir un grid de 2 imágenes de prueba.

### Servicio 5: Gestión de Procura y Suministros Globales
* **Desglose:** Sabemos que un componente crítico puede detener toda una línea de producción. Optimizamos su cadena de suministro mediante una gestión de procura inteligente, conectando sus necesidades técnicas con los mejores fabricantes nacionales e internacionales. No solo entregamos materiales; entregamos disponibilidad operativa.
* **Puntos Clave:**
  * Procura Internacional: Equipos OEM, logística "Puerta a Planta" y búsqueda de componentes obsoletos.
  * Suministros Locales: Materiales de construcción industrial (normas ASTM/API), insumos de mantenimiento y consumibles de soldadura.
  * Equipos Críticos: Válvulas de seguridad, bombas industriales e instrumentación de campo.
  * Ventaja: Validación técnica por ingenieros, trazabilidad total y reducción de Lead Times.
* **Galería:** Incluir un grid de 2 imágenes de prueba.

## 4. Instrucciones Técnicas para Cursor
1. Usa JavaScript (Vanilla) para crear la lógica del cambio de pestañas. Solo un contenido debe ser visible a la vez.
2. Agrega atributos de animación `data-aos="fade-in"` al contenedor del contenido dinámico para que la transición entre servicios sea elegante.
3. Utiliza la paleta de colores: `#180099` para la pestaña activa y `#C5C5C5` para bordes o pestañas inactivas.