# Viaja Conmigo Turismo — Sitio Web

Sitio web estático (HTML + CSS + JS, sin frameworks) para la agencia **Viaja Conmigo Turismo**.

## Estructura

```
index.html        Página principal (todo el sitio es de una sola página, con secciones ancladas)
css/style.css      Estilos, paleta de colores y tipografías de marca
js/main.js         Menú móvil, año del footer y animaciones al hacer scroll
assets/favicon.svg Ícono del sitio
```

## Cómo verlo

Abrí `index.html` directamente en el navegador, o corré un servidor local, por ejemplo:

```
npx serve .
```

## Cómo personalizar

- **Número de WhatsApp**: buscá `5521987654321` en `index.html` y reemplazalo por el número real (formato: código de país + código de área + número, sin espacios ni símbolos).
- **Instagram**: buscá `viajaconmigoturismook` en `index.html`.
- **Fotos reales**: las secciones de Destinos y Departamentos usan bloques de color con la paleta de marca a modo de placeholder (`.destino-media`, `.depto-media` en `css/style.css`). Para poner fotos reales, agregá las imágenes en `assets/` y reemplazá esos `<div>` por `<img>`, o agregá `background-image` en el CSS.
- **Colores**: están centralizados como variables al inicio de `css/style.css` (`--red`, `--navy`, `--cream`, `--gray`, `--white`).
- **Textos**: todo el contenido (destinos, tips, testimonios) está directamente en `index.html`, fácil de editar.

## Publicarlo online

Es un sitio 100% estático, así que se puede subir gratis a:
- **Netlify** o **Vercel**: arrastrando la carpeta del proyecto.
- **GitHub Pages**: activándolo en la configuración del repositorio.
