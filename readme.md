# Portafolio Profesional — Evaluación P2 (ICINF1107)

Portafolio web individual desarrollado como mockup de interfaz y primera pieza de presentación profesional, abarcando los contenidos del bloque RA1 de la asignatura Desarrollo de Frontend (ICINF1107).

---

## 📋 Ficha Técnica del Proyecto
* **Asignatura:** ICINF1107 — Desarrollo de Frontend
* **Carrera:** Ingeniería Civil en Informática (Sección 3)
* **Institución:** Universidad Católica de Temuco
* **Docente:** Cristian Iglesias Vera
* **Modalidad:** Presentación Oral Individual (P2)
* **Semestre / Año:** 2° Semestre, 2026

---

## 🚀 Descripción del Proyecto y Audiencia
Este sitio web es un portafolio profesional interactivo y responsivo diseñado bajo un enfoque centrado en el usuario. Su propósito principal es servir como carta de presentación ante docentes, reclutadores técnicos o clientes, mostrando de forma clara y accesible el perfil técnico y los proyectos académicos desarrollados durante el periodo lectivo.

---

## 🛠️ Tecnologías Utilizadas
* **HTML5 Semántico:** Estructurado mediante etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`) para garantizar una jerarquía limpia, accesible y navegable.
* **CSS3 Explicito (Externo):** Estilos aplicados mediante una hoja externa (`style.css`), organizados mediante variables globales (`:root`) para consistencia en la paleta cromática y diseño fluido.
* **Render & GitHub:** Control de versiones con Git y despliegue continuo en la nube para acceso multiplataforma en tiempo real.

---

## 📱 Diseño Responsivo (3 Breakpoints)
La interfaz fue maquetada pensando en la adaptabilidad multiplataforma, implementando 3 puntos de quiebre (*breakpoints*) bien definidos mediante `@media`:

1. **Móvil (`< 600px`):** Ajuste de la navegación a un menú táctil de botones compactos, tipografía fluida y distribución de contenido en una sola columna (`1fr`).
2. **Tablet (`600px - 1023px`):** Reorganización de la retícula de proyectos a 2 columnas para una lectura cómoda en pantallas medianas.
3. **Escritorio (`≥ 1024px`):** Apertura completa del layout en cuadrícula adaptativa optimizada para pantallas de alta resolución.

---

## ♿ Accesibilidad y Buenas Prácticas (WCAG / WAI-ARIA)
* **WAI-ARIA:** Implementación de roles semánticos (`role="banner"`, `role="navigation"`, `role="main"`, `role="contentinfo"`) y atributos para tecnologías de asistencia (`aria-label`, `aria-labelledby`, `aria-required`, `aria-hidden`).
* **Navegación por Teclado:** Foco visual evidente (`:focus`, `outline`) en todos los elementos interactivos (enlaces, botones e insumos de formulario).
* **Contraste de Color:** Paleta de contraste elevado (cumpliendo pautas WCAG) para asegurar la legibilidad de textos sobre fondos oscuros.
* **Formulario Accesible:** Uso de etiquetas `<label>` vinculadas directamente a sus correspondientes `<input>` mediante el atributo `for`.

---

## 📂 Estructura de Archivos del Proyecto
```text
portafolio-evaluacion/
│
├── index.html        # Estructura principal en HTML5 semántico con atributos WAI-ARIA
├── style.css         # Hoja de estilos CSS externa con los 3 breakpoints responsivos
└── README.md         # Documentación técnica y fundamentación del proyecto
