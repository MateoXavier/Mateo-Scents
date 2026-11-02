# Mateo Scents

Sitio estático de perfumería publicado con GitHub Pages.

## Desarrollo

Instalá Node.js 20.19 o posterior. Desde la raíz del proyecto:

```sh
npm ci
npm run build
```

Los estilos se editan en `scss/`. El comando genera `css/style.css` y su mapa de fuentes; incluí ambos archivos al guardar cambios de estilos.

Para probar las páginas localmente, ejecutá `python3 -m http.server 8000` desde la raíz y abrí `http://localhost:8000`.

## Contenido pendiente

El canal de Nobleman necesita una URL confirmada. Hasta entonces se muestra como pendiente en lugar de ofrecer un enlace vacío.
