# AMÉ Specialty Coffee — sitio web

Landing page de una sola página para **AMÉ Specialty Coffee** (Santa Cruz de la Sierra, Bolivia).

## Ver el sitio
Abrí `index.html` en el navegador, o servilo localmente:

```bash
python3 -m http.server 8000
```

y entrá a http://localhost:8000. Es HTML/CSS/JS estático, sin build: se puede publicar tal cual en Netlify, Vercel, GitHub Pages o cualquier hosting.

## Secciones
- **Hero** — reel del Viernes Acústico + estado “Abierto/Cerrado” en hora de Santa Cruz (07:00–23:00).
- **Nuestra idea** — frase de la marca (post del Día del Café).
- **La carta** — fotos y reels de barra y cocina, más la lista de productos.
- **Viernes Acústico** — terraza de Equipetrol, 21:00.
- **Sucursales** — Equipetrol y Banzer (Shopping Fidalga), con links a Google Maps.
- **Reservas** — WhatsApp 750 26695, Instagram y Facebook.

## Medios
Todas las fotos y videos salen del Instagram de la marca (@ame.specialtycoffee), optimizados para web (`assets/img/*.webp`, `assets/video/*.mp4` sin audio). El logo del header está redibujado en SVG a partir del logo de perfil.

## Para revisar antes de publicar
- Confirmar horario (07:00–23:00 todos los días) y que ambas sucursales estén en Shopping Fidalga.
- Ajustar los links de Google Maps si tienen la ficha exacta del local.
- Si tienen el logo original en vector (SVG/AI), reemplazar el símbolo `#ame-logo` en `index.html`.
