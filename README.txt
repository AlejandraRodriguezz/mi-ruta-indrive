# Mi Ruta – Control InDrive

App web progresiva (PWA) para registrar jornadas e ingresos.

## Archivos
- `index.html`: aplicación.
- `manifest.webmanifest`: configuración instalable.
- `sw.js`: caché para funcionamiento sin conexión después de la primera visita.
- `icon.svg`: icono.

## Publicar gratis con GitHub Pages
1. Crea una cuenta en GitHub si no tienes una.
2. Crea un repositorio nuevo, por ejemplo `mi-ruta-indrive`.
3. Sube los cuatro archivos de esta carpeta a la raíz del repositorio.
4. Abre Settings → Pages.
5. En Build and deployment, selecciona Deploy from a branch; elige `main` y `/ (root)`, y guarda.
6. Espera a que GitHub publique el sitio. La dirección tendrá el formato `https://TU-USUARIO.github.io/mi-ruta-indrive/`.

**Privacidad:** GitHub Pages hace pública la página y el código, pero los registros personales de jornadas se guardan localmente en el navegador del teléfono y no se envían al repositorio. No incluyas información personal en el código ni en el repositorio.

## Instalar en el teléfono
- Android: abre el enlace publicado en Chrome → menú ⋮ → Instalar aplicación o Añadir a pantalla de inicio.
- iPhone: abre el enlace en Safari → Compartir → Añadir a pantalla de inicio.

La instalación PWA requiere servir el sitio desde HTTPS. La app no tiene sincronización en la nube. Usa Historial → Copia JSON para respaldar y Restaurar copia JSON para recuperar tus datos.
