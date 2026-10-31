# Búsqueda de contenido en Archivos

APS Conecta mantiene este fork de [Files Full Text Search](https://github.com/nextcloud/files_fulltextsearch) para Nextcloud 34. Conserva el identificador `files_fulltextsearch`, la licencia y la interfaz originales.

Incorpora la [corrección de identificadores de usuario](https://github.com/nextcloud/files_fulltextsearch/pull/463), integrada en la rama `stable34` de origen mediante el commit `26bd54ddcec5e26b1e5e905d7417910d2a6a0baf`.

El flujo compartido de APS compila la interfaz y publica los cuatro activos firmados de la aplicación. El script heredado se conserva en `src/legacy-files.js` y se copia sin cambios a su ruta de ejecución durante la construcción.

Consulte el [manual de desarrollo](https://aps-conecta.github.io/documentation/dev/instalador/) y el [README original](https://github.com/nextcloud/files_fulltextsearch/blob/26bd54ddcec5e26b1e5e905d7417910d2a6a0baf/README.md).
