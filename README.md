# Portafolio Artístico - Escultora

Este repositorio contiene el código fuente del portafolio profesional para la escultora Beatriz González de la Vega. El sitio está diseñado como una plataforma de visualización de obra escultórica, enfocada en la elegancia, la tipografía cuidada y una experiencia de usuario fluida.

## 🛠 Tecnologías Utilizadas

El proyecto está construido utilizando **Astro**, aprovechando su enfoque orientado a componentes y su excelente rendimiento para sitios web orientados a contenido.

*   **Framework:** [Astro](https://astro.build/)
*   **Lenguajes:** HTML5, CSS3, JavaScript (ES6+)
*   **Estilos:** CSS puro (CSS Variables, Flexbox, Grid, Column-count para maquetación tipo Pinterest)
*   **Fuentes:** Google Fonts (Inter, Outfit) y Adobe Garamond Pro
*   **Interacciones:** API nativa `IntersectionObserver` para animaciones al scroll

## 🏗 Estructura del Proyecto

```text
/src
├── components/      # Componentes reutilizables (Hero, Galería, Contacto, Header, Footer)
├── layouts/         # Layout principal (MainLayout.astro) que gestiona el head y estructura global
├── pages/           # Rutas del sitio (Home, Galería, Biografía, Contacto)
└── styles/          # Estilos globales y variables CSS