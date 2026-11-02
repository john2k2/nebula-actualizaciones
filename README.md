# Actualizaciones de Nébula

Este repositorio contiene el canal firmado de actualizaciones y los paquetes de instalación para probar la aplicación. Las apps verifican la firma y descargan únicamente los archivos que cambiaron. Los datos personales, las sesiones y el código privado no forman parte de este canal.

- [Celular Android 1.11.2: búsqueda por voz y descargas offline](https://github.com/john2k2/nebula-actualizaciones/releases/tag/native-v1.11.2).
- [Android TV 1.11.2: búsqueda por voz y control remoto](https://github.com/john2k2/nebula-actualizaciones/releases/tag/native-v1.11.2).
- [Instalación inicial de Windows 1.10.0](https://github.com/john2k2/nebula-actualizaciones/releases/tag/native-v1.10.0).

En Windows 1.10.0, abrir Ajustes → Actualizaciones para recibir las mejoras de interfaz sin reinstalar el paquete. En Android, instalar una vez el APK 1.11.2 de celular o TV sobre la versión existente; conserva los datos y añade el dictado al buscador. También mantiene las correcciones del actualizador y de la barra de avance con el mando. El APK de celular incorpora el servicio offline. Los cambios de interfaz posteriores se reciben mediante parches. Los APK publicados son versiones debug para pruebas.

El buscador usa el teclado del sistema. El micrófono abre el dictado configurado en Android; en Google TV se comprobó el cuadro real de Google en español. Se probó escritura con 28 pulsaciones D-pad en el teclado de una imagen Google TV y un recorrido de navegación de 60 pulsaciones. Se verificaron resultados de voz simulados, cancelación y error; la precisión del micrófono físico queda por probar. La transmisión y la instalación en el Chromecast físico también quedan por probar.

Para descargar una película, abrir su ficha, elegir una fuente y pulsar Descargar. Los archivos guardados se abren desde Biblioteca → Descargas. Se admiten archivos directos y HLS VOD sin protección. En vivo y fuentes protegidas no se guardan.

`stable.json` es el manifiesto firmado. Los archivos de `blobs/` se distribuyen como datos binarios para preservar sus sumas SHA-256.
