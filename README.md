# 🌿 ConsECO | Alquiler de Glamping

Sitio web estático y responsive para **ConsECO**, una empresa ficticia de alojamientos sustentables y glamping (camping de lujo). Es un proyecto de práctica de **maquetación web con HTML, CSS y Sass**, hecho durante la Tecnicatura Universitaria en Desarrollo Web (UNER).

La temática une las dos cosas que estudié: desarrollo web y turismo sostenible.

🔗 **Demo:** https://zequisanchez.github.io/conseco/

---

## 🛠️ Tecnologías

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat&logo=sass&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat&logo=bootstrap&logoColor=white)

- **HTML5**: estructura semántica (`header`, `nav`, `section`, `article`, `footer`) y meta etiquetas para SEO.
- **CSS3 + Sass (SCSS)**: estilos separados en parciales por página, con variables de colores y fuentes.
- **Bootstrap 5**: sistema de grillas, barra de navegación colapsable y componentes de formulario.
- **AOS (Animate On Scroll)** y **Animate.css**: animaciones al hacer scroll y al cargar la página.
- **Google Fonts**: Montserrat y Raleway.

> El sitio no tiene JavaScript propio: solo usa los scripts de Bootstrap (para el menú) y de AOS (para las animaciones).

## ✨ Características

- Diseño **responsive** con media queries para tablet y celular.
- Menú de navegación que se colapsa en pantallas chicas.
- Animaciones de entrada y al hacer scroll.
- Formularios de **reserva** (destino, fechas, cantidad de pasajeros) y de **contacto**, con validación nativa de HTML5 (`required`, `type="email"`, `min`/`max`).
- Botón para volver arriba y enlaces a redes sociales.

## 📄 Páginas

| Página | Contenido |
|---|---|
| **Home** | Portada con banner y beneficios del glamping |
| **Reservar** | Buscador de alojamientos y glampings destacados |
| **Glamping** | Qué es el glamping, turismo sostenible y de naturaleza |
| **Nosotros** | Presentación de la empresa |
| **Contacto** | Formulario de consultas |

## 📁 Estructura

```
conseco/
├── index.html          # Home
├── paginas/            # Reservar, Glamping, Nosotros, Contacto
├── scss/               # Código fuente de los estilos (parciales por sección)
│   ├── style.scss      # Archivo principal que importa los parciales
│   ├── _variables.scss
│   ├── _mediaqueries.scss
│   └── ...
├── css/                # CSS compilado desde Sass
└── imagenes/           # Fotos, logos e íconos SVG
```

## 🚀 Cómo verlo

1. Cloná el repositorio:
   ```bash
   git clone https://github.com/zequisanchez/conseco.git
   ```
2. Abrí `index.html` en el navegador. No hace falta instalar nada.

Si querés modificar los estilos, editá los archivos de `scss/` y compilalos a `css/style.css`, por ejemplo con la extensión **Live Sass Compiler** de VS Code o con:

```bash
sass scss/style.scss css/style.css
```

## 👤 Autor

**Ezequiel Sánchez**: Técnico Universitario en Desarrollo Web (UNER) · Licenciado en Turismo (UNLA)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ezequieleduardosanchez)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/zequisanchez)


Ezequiel Sánchez: Técnico Universitario en Desarrollo Web (UNER) · Licenciado en Turismo (UNLA)

LinkedIn GitHub
