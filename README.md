# Web personal

Página web personal hecha a mano con HTML5 y CSS3, sin frameworks ni plantillas. Proyecto del módulo de Lenguajes de Marcas de 1.º de DAM.

## Funcionalidades

- Secciones: inicio, sobre mí, habilidades, proyectos y contacto.
- **Diseño responsive** para ordenador, tablet y móvil.
- **Menú hamburguesa** en móvil hecho solo con CSS (un `checkbox` oculto y el selector `:checked`).
- Formulario de contacto con **validación de HTML5** (`required`, `type="email"`, `minlength`) y bordes en rojo cuando un campo no es válido.

## Qué se practica

- HTML semántico: `header`, `nav`, `main`, `section`, `article`, `footer`.
- Flexbox para la cabecera, el formulario y las etiquetas.
- CSS Grid con `auto-fill` y `minmax()` para las tarjetas, que se recolocan solas según el ancho.
- Media queries y variables CSS (`:root`).

## Estructura

```
index.html
css/
└── estilos.css
```

## Verla

Basta con abrir `index.html` en el navegador. También se puede publicar con GitHub Pages: *Settings → Pages → Deploy from a branch → main*.
