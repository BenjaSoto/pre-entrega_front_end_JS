# 🛒 Kova Store

Kova Store es una tienda online desarrollada con HTML y CSS puro. Permite explorar un catálogo de productos por categoría, conocer información de contacto y enviar consultas mediante un formulario integrado.

## 🚀 Demo

Podés ver el proyecto en vivo en GitHub Pages:

🔗 https://benjasoto.github.io/pre-entrega_front_end_JS/

## 📌 Objetivos del proyecto

Este proyecto fue creado para poner en práctica conceptos de front-end como:

- Layout con Flexbox y media queries
- Diseño responsive para mobile, tablet y desktop
- HTML semántico
- CSS con degradados, transiciones y variables de color
- Formularios conectados a Formspree

## 📄 Páginas y secciones

| Sección | Descripción |
|---|---|
| Header | Navbar con logo, links y botón de login |
| Productos | Grilla de cards con filtros por categoría |
| Contacto | Info de contacto + formulario de consulta |
| Footer | Links secundarios, redes sociales y copyright |

## 📱 Responsive Design

El sitio adapta su layout según el tamaño de pantalla usando media queries:

- **Desktop** (+768px): 4 productos por fila
- **Tablet** (425px – 768px): 2 productos por fila
- **Mobile** (-430px): 1 producto por fila, navegación apilada y contacto en columna

## 🛠️ Stack tecnológico

- HTML5
- CSS3
- Google Fonts — Nunito
- Formspree

## 🎨 Paleta de colores

| Rol | Hex |
|---|---|
| Fondo principal | `#000000` |
| Superficie cards | `#2a2733` |
| Acento violeta | `#534AB7` |
| Texto secundario | `#666666` |
| Texto principal | `#ffffff` |

## 📁 Estructura de archivos

```
kova-store/
├── index.html
├── css/
│   └── styles.css
└── img/
    ├── logo.png
    ├── mail.png
    ├── mobile.png
    ├── clock.png
    ├── location.png
    ├── whatsapp.svg
    ├── instagram.svg
    └── productos/
        ├── mouse.webp
        ├── campera.webp
        ├── zapatilla.jpg
        └── sofa.webp
```