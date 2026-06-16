# Landing — Talleres de Defensa Personal · Krav Magá Bukan

Página de aterrizaje para anuncios de Meta. Su único objetivo: recibir a la gente y
mandarla por WhatsApp al instructor (Manuel). Sitio **estático** (sin servidor).

## Cómo cambiar los datos para un taller nuevo

1. Abre **`index.html`**.
2. Hasta arriba está el bloque **`✏️ ZONA EDITABLE`** (un `CONFIG = { ... }`).
3. Cambia solo esos valores: fechas, hora, lugar, precios, cupo, número de WhatsApp,
   público (mujeres / hombres / abierto) y la foto. **No toques nada más.**
   - Si solo hay **una** fecha → deja `fecha2: { num: "" }` y la segunda se oculta sola.
   - Si no hay precio de dos personas → deja `precio2: ""` y esa línea se oculta sola.
4. Guarda. En **GitHub Desktop**: escribe un resumen → *Commit to main* → *Push origin*.
   Netlify actualiza el sitio solo en unos segundos.

## Archivos

- `index.html` — la página (incluye la ZONA EDITABLE y el diseño).
- `assets/` — imágenes (escudo, foto del hero, libro, foto de entrenamiento).

## Cambiar la foto del hero

Pon la nueva imagen en `assets/` y actualiza `foto: "assets/tu-imagen.png"` en el CONFIG.
