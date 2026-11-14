# Clínica Sonria & Prestigio – sitio web (prototipo estático)

Contenido: `index.html`, `assets/` (logo oficial) e `images/` (fotos por añadir).
Se abre con doble clic en `index.html` o se publica en cualquier hosting estático (Render, Cloudflare Pages, Netlify).

## Publicar en Render (sitio estático)
1. Sube esta carpeta a un repositorio privado de GitHub.
2. En Render: New → Static Site → conecta el repositorio. Build Command vacío, Publish Directory `.`
3. Settings → Custom Domains → agrega el dominio y copia los registros DNS en el registrador.

## Pendiente de confirmar con la clínica (no inventado)
- Nombre: el logo dice «Sonria» sin tilde; el documento de requisitos dice «Sonría». Elegir una grafía para los textos.
- «+18 años desde 2007» y dirección «C.C. Mamy, Local 61, Alta Vista Norte» vienen del mockup aprobado: confirmar.
- Horario de atención (aparece «por confirmar»).
- Nombres y credenciales del equipo (hay marcadores de ejemplo).
- Fotos reales: `images/hero.jpg` e `images/clinica.jpg`.
- Logo en vector (SVG/AI/PDF): el actual sale de una imagen pequeña.
- WhatsApp configurado: 0424-9348150 (enlace wa.me/584249348150).

## Nota
Este es el prototipo visual. La versión final del documento de requisitos (Next.js, TypeScript, Tailwind, panel de citas) se construye en el repositorio `sonria-y-prestigio-web`, usando este `index.html` como referencia.
