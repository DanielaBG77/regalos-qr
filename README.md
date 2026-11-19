# Regalos QR — 6 Meses

Página web interactiva de regalo ubicada en `pedidos/6-meses/index.html`, diseñada para móvil y computador con galería de fotos, reproductor de canciones desde YouTube y carta.

## Características

- **Apertura interactiva:** Al tocar o hacer clic en el corazón se revela el contenido y comienza automáticamente la reproducción de las canciones.
- **Reproductor flotante:** Botón de pausa/reproducción en la esquina inferior derecha que se expande al pasar el mouse (o mediante el botón `‹` en pantallas táctiles) para mostrar título, progreso, canción anterior/siguiente, silencio y acceso rápido a la lista.
- **Vista para computador y móvil:** Mantiene el diseño móvil original debajo de `768px` y se adapta a pantallas de escritorio con múltiples tarjetas visibles, flechas de navegación, visor ampliado de fotos y carta centrada.

## Estructura del proyecto

- `pedidos/6-meses/index.html` — Página principal (HTML, CSS, JavaScript y configuración de contenido).
- `pedidos/6-meses/fotos/` — Galería de fotos (`001.jpg` a `054.jpg`).
- `pedidos/6-meses/discos/` — Carátulas de los discos (`01.jpg` a `39.jpg`).
- `pedidos/6-meses/cancion.jpg` — Imagen por defecto para canciones.
- `pedidos/6-meses/qr.png` — Código QR del regalo.
- `pedidos/6-meses/datos.json` — Archivo de datos del pedido.

## Cómo ejecutarlo localmente

1. Abre una terminal en la raíz del repositorio (`regalos-qr`).
2. Inicia un servidor HTTP local (necesario para que los embeds de YouTube funcionen):
   ```bash
   python -m http.server 8000
   ```
3. Abre en tu navegador:
   ```text
   http://localhost:8000/pedidos/6-meses/
   ```

---

*Una dedicatoria de Daniela a Heiller.*
