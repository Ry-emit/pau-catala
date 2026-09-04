# Pau Català — Web · cómo publicarla

Esta carpeta ES la web completa y estática — **HTML autónomo** (un solo archivo con su CSS y
JavaScript dentro). No depende de ningún runtime ni servidor especial; funciona en cualquier
hosting y abriéndola con doble clic. Contenido:

```
index.html      ← la web entera (HTML + CSS + JS autónomo)
images/         ← las fotos de Pau en B&N
```

> Nota: esta es la versión LISTA PARA PUBLICAR. La otra versión (`.dc.html` + `support.js`) es
> solo para editar dentro de Claude Design y NO funciona subida a un hosting.

---

## ⚠️ ANTES de publicar — rellenar (5 min)
La web está lista al 95%. Faltan datos que solo tiene Pau. Abre `index.html` en un editor y busca:

- [ ] **Email** — busca `pau@[domain].com` → pon su email real (2 sitios: enlace y texto)
- [ ] **WhatsApp** — busca `wa.me/34000000000` y `+34 …` → número real
- [ ] **Redes** — busca los 3 `href="#"` de Instagram / Facebook / YouTube → URLs reales
      (borra la red que no use)
- [ ] **Formulario de contacto** — busca `formspree.io/f/your-id`:
      crea un formulario gratis en **formspree.io** (2 min) y pega tu ID. Sin esto, el
      formulario no envía (pero el email/WhatsApp directos sí funcionan).
- [ ] **Fotos de competición** — varias llevan marca del fotógrafo (**PAKULA**). Pide permiso o
      licencia antes de publicarlas, o sustitúyelas por fotos propias.

*(Àlex/Claude puede rellenar todo esto en 1 min si le pasas los datos.)*

---

## Cómo publicarla (elige una)

### Opción A — Netlify Drop (la más fácil, gratis, sin cuenta)
1. Ve a **https://app.netlify.com/drop**
2. Arrastra **toda esta carpeta** (`publish`) a la ventana.
3. En segundos tienes una URL live tipo `random-name.netlify.app`. ¡Ya está publicada!
4. (Opcional) Crea cuenta gratis para cambiar el nombre y conectar un dominio propio.

### Opción B — Dominio propio (recomendado para portfolio pro)
1. Compra un dominio, p.ej. **paucatala.com** (Namecheap, Cloudflare, GoDaddy… ~10 €/año).
2. Publica con Netlify / Vercel / Cloudflare Pages (todos gratis) y conecta el dominio en su panel.

### Opción C — GitHub Pages
1. Sube esta carpeta a un repo de GitHub.
2. Settings → Pages → Deploy from branch → `/root`. URL: `usuario.github.io/repo`.

---

## Notas técnicas
- Es HTML autónomo (`index.html` / `bn.html`) + `images/` + `videos/`. No hay build ni dependencias.
- Para el SEO/redes: el `<title>`, meta description y Open Graph ya están puestos. Cuando tengas
  dominio, cambia la imagen OG a URL absoluta (busca `og:image`) para que se vea bien al compartir.
- Idioma `en`, responsive, accesible, B&N por CSS.

---

## Dos versiones incluidas
- **`index.html`** — versión **A TODO COLOR** (fotos y vídeos en color). Es la PRINCIPAL (la que sale por defecto).
- **`bn.html`** — la misma web en **blanco y negro editorial** (las fotos revelan color al pasar/tocar; el lightbox siempre a color).

Al publicar tendrás: `tu-sitio.netlify.app/` (color) y `tu-sitio.netlify.app/bn.html` (B&N).
