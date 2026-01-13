# T2PDA2
Plantilla web de planeación docente con "Dual-View" (Dashboard interactivo + Formato de impresión oficial). Construido con HTML5 y TailwindCSS (CDN). #education #teacher-tools #tailwindcss #html5 #print-layout #nem #lasallista
# 📚 Secuencia Didáctica Digital: Diversidad Cultural (PDA 2)

![Estado del Proyecto](https://img.shields.io/badge/Estado-Finalizado-success)
![Tecnología](https://img.shields.io/badge/Stack-HTML%20%2B%20Tailwind-blue)
![Licencia](https://img.shields.io/badge/Licencia-MIT-yellow)

Una herramienta digital para la planificación docente diseñada bajo el marco de la **Nueva Escuela Mexicana (NEM)** y la filosofía **Lasallista**. Este proyecto soluciona el problema de tener formatos aburridos de planeación, convirtiéndolos en una experiencia web interactiva que mantiene la rigurosidad administrativa al imprimir.

## 🚀 Características Principales

### 🖥️ Vista Web Interactiva (Dashboard)
- **Diseño Moderno:** UI limpia utilizando **Tailwind CSS**.
- **Interactividad:** Secciones colapsables (acordeones) para las fases de la secuencia didáctica, optimizando el espacio en pantalla.
- **Recursos Integrados:** Enlaces directos a recursos externos y herramientas de IA (Gemini).
- **Identidad Institucional:** Paleta de colores oficial (Azul La Salle y Dorado) e iconografía profesional con **Lucide Icons**.

### 🖨️ Smart Print Layout (Formato de Impresión)
- **Transformación Automática:** Al presionar `CTRL + P` o el botón de imprimir, la web se transforma.
- **Cumplimiento Administrativo:** Oculta la interfaz web y reestructura todo el contenido en una **tabla formal y simplificada**.
- **Ahorro de Tinta:** Elimina fondos oscuros y elementos innecesarios para una impresión limpia en blanco y negro.

## 🛠️ Stack Tecnológico

No requiere instalación de dependencias ni compiladores. Funciona directamente en el navegador (Client-side only).

* **HTML5 Semántico**
* **CSS Framework:** [Tailwind CSS](https://tailwindcss.com/) (vía CDN script).
* **Fuentes:** Google Fonts (Inter, Montserrat, Roboto Slab).
* **Iconos:** [Lucide](https://lucide.dev/) (vía CDN).
* **JavaScript:** Vanilla JS mínimo para la lógica de los acordeones.

## 📋 Contexto Educativo

* **Nivel:** Secundaria (Fase 6).
* **Materia:** Español II.
* **PDA:** La diversidad étnica, cultural y lingüística de México.
* **Metodología:** Aprendizaje Basado en Proyectos (ABP) + Rutinas de Pensamiento Visible.
* **Vinculación:** ODS 10 y 16 (RedPEA UNESCO) y Valores Lasallistas (Fraternidad y Justicia).

## 🔧 Cómo usar este código

1.  **Clonar o Descargar:**
    ```bash
    git clone [https://github.com/tu-usuario/nombre-del-repo.git](https://github.com/tu-usuario/nombre-del-repo.git)
    ```
2.  **Ejecutar:**
    Simplemente abre el archivo `index.html` en tu navegador web favorito (Chrome, Edge, Firefox). No necesitas levantar un servidor local.
3.  **Personalizar:**
    Edita el HTML para cambiar los textos, fechas o contenidos de las sesiones según tus necesidades.

## 📄 Estructura del Código

El archivo `index.html` contiene dos grandes bloques controlados por CSS:

1.  `<div id="web-layout">`: Contiene todo el diseño visual, headers, botones y acordeones.
2.  `<div id="print-layout">`: Contiene la estructura de tabla `<table`> que solo es visible bajo la media query `@media print`.

## 🤝 Contribución

Si eres docente y te gusta la programación, siéntete libre de hacer un *fork* y adaptar la plantilla a tu materia o colegio.

---
Hecho con ❤️ para la educación en México.
