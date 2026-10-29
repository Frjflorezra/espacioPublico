# Medellín · Los lugares que nos encuentran

Presentación interactiva del inventario y diagnóstico del espacio público, actualizada para GitHub Pages el 29 de octubre de 2026.

## Subir al repositorio

1. Clona tu repositorio con GitHub Desktop.
2. Copia **todo el contenido de esta carpeta**, incluidos los archivos que comienzan con punto, dentro del repositorio clonado. `index.html` y `assets` deben quedar en su raíz. Conserva la carpeta `.git` del clon.
3. En GitHub Desktop, guarda los cambios con Commit y súbelos con Push. El PDF del libro supera el tamaño permitido por el cargador web de GitHub; usa Desktop o Git.
4. En GitHub, abre **Settings > Pages**. En **Source**, elige **Deploy from a branch**; selecciona la rama que subiste (normalmente `main`) y **/(root)**. Pulsa **Save**.
5. Cuando termine la publicación, abre el enlace que aparece en Pages y compártelo.

`.nojekyll` permite servir directamente los archivos. Esta carpeta ya está generada: no requiere instalar dependencias ni ejecutar una compilación.

Guía oficial: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Contenido

- `index.html`: interfaz, mapas, límites territoriales, datos, imágenes de la presentación, estilos y código integrados.
- `assets/book-pages/`: las 330 imágenes del libro interactivo.
- `assets/Medellin-entre-montanas.pdf`: libro original.
- `assets/technical/`: ocho PDF técnicos, ocho vistas previas y 92 láminas.

El paquete contiene aproximadamente 120 MB. Las rutas relativas admiten una publicación como `https://tu-usuario.github.io/tu-repositorio/`.

## Para presentar

El enlace publicado requiere conexión. Para la socialización sin internet, conserva la carpeta original **Aplicacion EPEE** o el paquete offline. La información recolectada se integra en SGEP, módulo de SGVIAL de uso institucional. El enlace a SGVIAL abre el sistema institucional en otra pestaña y requiere conexión.

El inventario oficial reúne 3.063 EPEE y un área de 14.405.379,41 m². La clasificación corresponde a 1.198 parques, 107 plazas, 1.749 zonas verdes recreacionales y 9 miradores. Mapa, lista y estadísticas comparten los filtros. La comuna o corregimiento también se puede elegir directamente junto a las estadísticas. Se muestran cantidades de mobiliario, superficies en m² y árboles o palmas por clase, con sus unidades separadas. Los usos sociales cuentan espacios con respuestas registradas. El balance distrital oficial conserva su referencia fija. El capítulo del inventario se recorre por Panorama, Elementos y Mapa, mostrando una vista a la vez. Del dato al lugar es el apartado 3, con tres fichas fotográficas y dos comparaciones cartográficas. Las fichas técnicas son el apartado 4 y las alertas el 5; el libro, apartado 6, cierra el recorrido. Los ejemplos y la comparación histórica de cobertura están integrados y funcionan sin conexión.

## Actualizaciones

Esta carpeta es una copia lista para publicar. Los archivos editables y las herramientas de reconstrucción permanecen en **Aplicacion EPEE**. Para generar otra copia después de una actualización, se puede ejecutar `tools/prepare_github_pages.py` desde ese proyecto, indicando una carpeta nueva con `--destination`.
