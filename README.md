# Invitación XV años – María Alejandra

Dos archivos: `index.html` (la invitación completa, con fotos incluidas) y `og-image.jpg` (la imagen que aparece al compartir el enlace por WhatsApp).

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en github.com (botón **New**). Usa un nombre difícil de adivinar, p. ej. `xv-ma-7k2q9`. Déjalo **Public** (Pages gratis lo requiere).
2. **Add file → Upload files**: sube `index.html` y `og-image.jpg` a la raíz y haz *Commit*.
3. **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, carpeta `/(root)` → *Save*.
4. En 1–2 minutos tu invitación estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.

## Vista previa al compartir (WhatsApp)
Abre `index.html` y busca esta línea cerca del inicio:
`<meta property="og:image" content="https://TU-USUARIO.github.io/TU-REPOSITORIO/og-image.jpg">`
Reemplaza `TU-USUARIO` y `TU-REPOSITORIO` por los tuyos y vuelve a subir el archivo. (WhatsApp guarda la vista previa en caché; si cambias algo, prueba con el enlace seguido de `?v=2`.)

## Qué editar
- **Fecha/hora y cuenta regresiva:** busca `2026-11-28T19:00:00-05:00` (el `-05:00` es hora de Colombia).
- **Lugar:** busca `Finca Villa Aura`.
- **Mapa:** busca `maps.google.com/maps?q=`. Si el mapa no cargara, en Google Maps usa *Compartir → Incorporar un mapa* y pega el `src` del iframe que te da.
- **Enlace al tocar el mapa:** `https://maps.app.goo.gl/rDXEJn4y9imBEERLA` (en iPhone abre Apple Maps automáticamente).
- **Vestimenta y confirmación:** busca `Código de vestimenta` y `20 de noviembre`.

## Privacidad
Con GitHub Pages gratis, el repositorio y la página son públicos: cualquiera con el enlace verá el nombre, las fotos y el lugar. La página trae `noindex` para que Google no la liste, pero no es privada. Comparte el enlace solo con los invitados.
