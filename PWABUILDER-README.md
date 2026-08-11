# Agenda Joven América — preparado para PWABuilder

## Próximo paso
Publicar **el contenido de esta carpeta** en un hosting HTTPS y obtener una URL pública.

Luego:
1. Abrir PWABuilder.
2. Introducir la URL HTTPS pública.
3. Ejecutar el análisis.
4. Entrar en el paquete Android.
5. Generar el paquete Android.
6. Para una instalación directa en el teléfono, usar el APK generado para sideload cuando PWABuilder lo ofrezca.

## Importante
- Mantener `manifest.json`, `sw.js`, `index.html` e `icons/` en las rutas actuales.
- No cambiar la estructura de URLs después de generar el paquete.
- La PWA debe poder abrir `https://TU-DOMINIO/` y cargar `manifest.json` y `sw.js`.
- El hosting debe servir los archivos mediante HTTPS.
