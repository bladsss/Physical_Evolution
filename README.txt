PHYSICAL EVOLUTION v0.1
=======================

Contenido:
- index.html: aplicación.
- manifest.json: configuración de PWA.
- sw.js: caché básica para uso offline después de la primera carga.

Qué funciona:
- Registro de gimnasio, calistenia y cardio.
- Estado físico y registro de mediciones.
- Historial y gráficas básicas.
- Exportar/importar copia de seguridad JSON.
- Datos almacenados localmente en el navegador.

Importante:
- Esta versión NO establece el Mes 0 ni crea una predicción oficial.
- Los datos se guardan en el almacenamiento local del navegador. Exporta copias periódicas.
- Para instalar como PWA, aloja los archivos en un sitio HTTPS y abre la página en Chrome/Android. La instalación depende del navegador y del alojamiento.
- Abrir index.html directamente permite probar la interfaz en algunos navegadores, pero el modo PWA y el service worker requieren HTTP/HTTPS (normalmente HTTPS).
- No hay cuenta, nube ni sincronización entre dispositivos en esta versión.
- No borres los datos del navegador sin exportar una copia si deseas conservar los registros.
