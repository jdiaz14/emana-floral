# Emana Floral

Prototipo de tienda virtual creado para el proyecto Shopper Metaverso,
generado con **Harvys**, el asistente de e-commerce del Profesor Harvey Sanabria.

## Archivos

| Archivo | Qué contiene |
|---|---|
| `index.html` | La estructura de la página (portada, catálogo, carrito, pago, footer). |
| `styles.css` | El diseño: colores y fuentes en las variables de `:root`, al inicio del archivo. |
| `script.js` | Los datos de la tienda (productos, precios, pagos, WhatsApp) al inicio y el funcionamiento (filtros, carrito, WhatsApp, top, duelo). |
| `img/` | Las fotos de los productos. |

## Verla en tu computador

Abre `index.html` con doble clic.

## Publicarla en GitHub Pages

1. Crea un repositorio nuevo en GitHub (público).
2. Sube **todos** los archivos de esta carpeta (incluida la carpeta `img/`) a la raíz del repositorio.
   - Desde la web: *Add file → Upload files* y arrastra todo.
   - Desde la terminal: `git init`, `git add .`, `git commit -m "Mi tienda"`, `git branch -M main`,
     `git remote add origin <url-del-repo>`, `git push -u origin main`.
3. En el repositorio ve a *Settings → Pages*.
4. En *Source* elige **Deploy from a branch**, rama **main** y carpeta **/ (root)**. Guarda.
5. Espera 1–2 minutos: tu tienda queda en `https://<tu-usuario>.github.io/<nombre-del-repo>/`.

> El prototipo no procesa pagos reales; los pedidos llegan por WhatsApp.
