# Actualizaciones de Nébula

Canal firmado de actualizaciones y paquetes para probar la aplicación. Las apps verifican firmas y sumas SHA-256. El perfil, las sesiones y el código privado no se publican aquí.

- [Android TV 1.12.0: interfaz nativa y control remoto](https://github.com/john2k2/nebula-actualizaciones/releases/tag/native-v1.12.0).
- [Celular Android 1.11.2: búsqueda por voz y descargas offline](https://github.com/john2k2/nebula-actualizaciones/releases/tag/native-v1.11.2).
- [Windows 1.10.0](https://github.com/john2k2/nebula-actualizaciones/releases/tag/native-v1.10.0).

TV 1.12.0 abre pantallas nativas Kotlin/Compose: destacado con fondo, filas de portadas, catálogo, buscador, biblioteca, fichas, temporadas y ajustes. Conserva negro y rojo, con foco blanco para navegar con flechas, OK y Atrás. La caché indexa metadatos y mantiene bloques de fuentes comprimidos y cifrados; las imágenes tienen límites de memoria y disco. LibVLC reproduce dentro de la aplicación. Se comprobó imagen y audio de MoviePlus y Xuper en un Chromecast físico.

Instalar el APK TV sobre la versión existente conserva favoritos, progreso y ajustes. Las herramientas adicionales permanecen en Ajustes → Interfaz anterior. Los APK publicados son debug para pruebas. El paquete TV corresponde al Chromecast de 32 bits (armeabi-v7a).

Celular y Windows continúan recibiendo cambios compatibles de HTML, CSS y JavaScript por archivos, sin descargar el paquete completo. Las pantallas Compose de TV requieren actualizar el APK; el catálogo y sus imágenes se actualizan por separado. La app de TV comprueba las versiones completas en el mismo canal firmado. Android solicita confirmar la instalación.

El buscador usa el teclado y el dictado configurados en Android. Las pruebas verifican respuestas de voz simuladas, cancelación y retorno del foco; la precisión acústica depende del micrófono y servicio del dispositivo. La resolución de la interfaz y la del video son independientes: el Chromecast comprobado mantiene su interfaz a 1080p sobre una pantalla 4K.

En celular, abrir una película, elegir una fuente y pulsar Descargar. Los archivos se abren desde Biblioteca → Descargas. Se admiten archivos directos y HLS VOD sin protección; en vivo y fuentes protegidas no se guardan.

`stable.json` contiene el manifiesto firmado. Los archivos de `blobs/` se distribuyen como datos binarios para preservar sus sumas.