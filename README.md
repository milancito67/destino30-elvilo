# DESTINO 30 · ELVILO

Mini aplicación web progresiva (PWA) complementaria al libro **No eres una opción, eres destino**.

## Incluye
- 30 jornadas en cinco etapas, con reflexión, misión y desafío.
- Seguimiento del progreso, diario y manifiesto personal.
- Exportación del diario y manifiesto a archivos de texto.
- Guardado automático local en el navegador.
- Diseño adaptable a móviles y escritorio.
- Estructura PWA: icono, manifest y caché para uso posterior sin conexión.

## Datos y privacidad
Las notas y el progreso se guardan en el navegador del propio dispositivo, no en un servidor. No se sincronizan entre dispositivos y pueden perderse si se borran los datos del navegador. Se recomienda exportar una copia del diario.

## Publicar en GitHub Pages
1. Crea un repositorio nuevo en GitHub.
2. Sube `index.html`, `manifest.webmanifest`, `sw.js` e `icon.svg`.
3. Abre **Settings → Pages**, selecciona la rama principal y la carpeta raíz.
4. Cuando GitHub Pages publique el sitio HTTPS, prueba la URL en móvil y escritorio.
5. Crea un QR que apunte a esa URL exacta y colócalo en el ebook. El QR final se genera después de tener la URL pública.

## Antes de vender
Esta versión no incluye cuentas, bloqueo para compradores ni validación de compra. Para sincronizar datos entre dispositivos o restringir el acceso a compradores, hace falta añadir autenticación y un backend. Prueba el sitio en varios navegadores antes del lanzamiento.
