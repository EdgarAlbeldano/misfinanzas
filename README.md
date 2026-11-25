# Mis Finanzas (App Web / PWA)

Aplicación personal de finanzas con sincronización opcional en Google Sheets, personalización de tarjetas de débito/crédito, suscripciones en crédito o débito, historial con filtros avanzados, tasas de rendimiento integradas, metas de ahorro independientes y soporte para instalarla como app en iOS y Android.

## Contenido de la carpeta
- `index.html`: Aplicación completa (Suscripciones con cargo a tarjeta de crédito o débito, menú de historial con búsqueda y filtros dinámicos por fecha, categoría, meta o tarjeta en cada recuadro de movimientos, gestión unificada de cuentas, tarjetas e intereses, metas independientes y corte de mes en Excel).
- `manifest.webmanifest`: Configuración PWA (nombre, colores, modo pantalla completa e iconos).
- `sw.js`: Service Worker para instalación en celular y funcionamiento sin conexión.
- `apple-touch-icon.png` (180×180), `icon-192.png` (192×192) y `icon-512.png` (512×512): Iconos de la app.

## Subir a GitHub Pages
1. Crea un repositorio nuevo en GitHub (por ejemplo `mis-finanzas`).
2. Sube **todos los archivos** que están dentro de esta carpeta a la raíz del repositorio.
3. Ve a **Settings → Pages**, en *Source* selecciona **Deploy from a branch**, elige `main` y `/ (root)`, y guarda.
4. En un par de minutos tendrás tu enlace `https://tu-usuario.github.io/mis-finanzas/`.

## Instalar en celular
- **iPhone (Safari):** Abre el enlace de GitHub Pages, toca el botón **Compartir** y selecciona **Agregar a inicio**.
- **Android (Chrome):** Abre el enlace, toca el menú **⋮** y selecciona **Instalar aplicación** (o *Agregar a pantalla principal*).
