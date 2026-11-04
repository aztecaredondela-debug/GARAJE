[README.md](https://github.com/user-attachments/files/34362985/README.md)
# Mi garaje (PWA)

Registro de coche y moto: repostajes y consumo, revisiones, ruedas, averías, seguro, ITV, fotos y buscador de diagnóstico y repuestos.

## Subir a GitHub Pages
1. Crea un repositorio y sube el contenido de esta carpeta a la raíz.
2. Settings > Pages > Deploy from a branch > main / root.
3. Abre `https://TU_USUARIO.github.io/TU_REPO/` y en el móvil usa "Instalar app" o "Añadir a pantalla de inicio".

## Play Store
1. Con la web en HTTPS (GitHub Pages sirve), entra en https://www.pwabuilder.com, pega la URL y elige "Package for stores > Android".
2. Descarga el paquete (AAB) y súbelo a Google Play Console (cuenta de desarrollador: pago único de 25 USD).
3. Sigue las instrucciones de PWABuilder para el archivo `assetlinks.json` (Digital Asset Links).

## Notas
- Los datos se guardan en el dispositivo (localStorage). Usa el botón "Copia" para guardarlos o pasarlos a otro dispositivo.
- Si cambias archivos, sube el número de `CACHE` en `sw.js` para que se actualice la app instalada.
