# Pau Català — Portfolio

Portfolio web de **Pau Català Sanuy**, jinete de concurso completo (eventing).
Web estática, autónoma, sin build ni dependencias.

## Qué hay aquí

```
index.html          Web principal, a todo color
bn.html             Misma web en blanco y negro editorial
images/             Fotos (hero, cross-country, show-jumping, dressage, portrait, gallery)
videos/             Vídeos de fondo (portrait.mp4, riding.mp4)
publicar-leeme.md   Guía de publicación y lista de datos por rellenar
```

## Ver en local

Doble clic en `index.html`, o servir la carpeta:

```bash
python3 -m http.server 8125
```

Luego abrir http://localhost:8125

## Publicar

Ver `publicar-leeme.md`. Resumen: Netlify Drop, Vercel, Cloudflare Pages o
GitHub Pages (Settings → Pages → Deploy from branch `main` → `/root`).
El archivo `.nojekyll` ya está incluido para GitHub Pages.

## Pendiente antes de publicar

- Email y WhatsApp reales (ahora hay placeholders)
- URLs de Instagram / Facebook / YouTube
- ID de Formspree para el formulario de contacto
- Permisos de las fotos con marca de fotógrafo (PAKULA)
- `og:image` a URL absoluta cuando haya dominio

## Copia de trabajo

Máster en el SSD: `/Volumes/PortableSSD/pau-portfolio/`
