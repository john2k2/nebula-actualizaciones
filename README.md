# Actualizaciones de Nébula

Este repositorio contiene el canal firmado de actualizaciones y los paquetes de instalación para probar la aplicación. Las apps verifican la firma y descargan únicamente los archivos que cambiaron. Los datos personales, las sesiones y el código privado no forman parte de este canal.

- [Celular Android 1.11.0: descargas offline](https://github.com/john2k2/nebula-actualizaciones/releases/tag/native-v1.11.0).
- [Android TV 1.11.1: control remoto y barra de avance](https://github.com/john2k2/nebula-actualizaciones/releases/tag/native-v1.11.1).
- [Instalación inicial de Windows 1.10.0](https://github.com/john2k2/nebula-actualizaciones/releases/tag/native-v1.10.0).

En Windows 1.10.0, abrir Ajustes → Actualizaciones para recibir las mejoras de interfaz sin reinstalar el paquete. En Android, instalar una vez el APK 1.11.0 de celular o 1.11.1 de TV sobre la versión existente; conserva los datos y corrige un bloqueo de limpieza de cachés del actualizador. El APK de celular también incorpora el servicio offline. TV 1.11.1 corrige el avance real del video al mover la barra con el control, incluso en pausa. Los cambios de interfaz posteriores se reciben mediante parches. Los APK publicados son versiones debug para pruebas.

El recorrido de TV incluye teclado de búsqueda con el mando, selectores, filtros, menús y Biblioteca. Se comprobó con 75 pulsaciones D-pad y tres pruebas de instrumentación en un emulador 4K, usando material propio para reproducir audio y video. La transmisión y la instalación en el Chromecast físico quedan por probar.

Para descargar una película, abrir su ficha, elegir una fuente y pulsar Descargar. Los archivos guardados se abren desde Biblioteca → Descargas. Se admiten archivos directos y HLS VOD sin protección. En vivo y fuentes protegidas no se guardan.

`stable.json` es el manifiesto firmado. Los archivos de `blobs/` se distribuyen como datos binarios para preservar sus sumas SHA-256.
