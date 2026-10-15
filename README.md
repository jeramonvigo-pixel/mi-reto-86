# Mi Reto 86

Aplicación web móvil para llevar el seguimiento personal de peso, cintura, ingesta diaria y entrenamientos. Guarda todos los datos en `localStorage` del navegador; no utiliza cuentas ni los envía a un servidor.

## Instalar en Android como app

La carpeta debe publicarse en un alojamiento web con HTTPS. Abre la dirección en Chrome para Android y elige **Instalar aplicación** o **Añadir a pantalla de inicio**. La app conserva el historial en ese navegador y permite exportar una copia JSON y registros CSV.

## Archivos

- `index.html`: interfaz y lógica.
- `manifest.webmanifest`: metadatos de instalación.
- `sw.js`: caché para abrirla sin conexión tras la primera visita.
- `icon.svg`: icono de la aplicación.

Este proyecto es una PWA instalable; no contiene un APK firmado.
