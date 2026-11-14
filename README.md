# FerreKsa × Pamela — Taller editable

Sitio estático compatible con GitHub Pages.

- `index.html`: editor de 16 láminas (Laila/Johana/Pamela), notas, decisiones, y vista de 15 láminas para dirección.
- `presentacion-duenos.html`: presentación inicial; reemplazarla por el HTML descargado al actualizar.
- `presentacion-chicas.html`: presentación interna inicial.
- `ferreksa-acuerdos.json`: versión publicada inicial; puede reemplazarse por exportación de acuerdos.

## Cómo funciona

El editor guarda los cambios automáticamente en **localStorage del dispositivo**. El botón `Actualizar versión dueños` transfiere **solo fragmentos de textos modificados** a la lámina correspondiente, preservando la redacción independiente de dirección en el resto. Las decisiones del equipo se anotan y los acuerdos aprobados aparecen en un anexo del HTML exportado. La versión de dirección también se puede editar.

> No hay sincronización multiusuario en GitHub Pages: para compartir cambios entre dispositivos, exportar/importar JSON o actualizar el repo. Evitar colocar datos privados de empleados, proveedores o acuerdos internos sensibles en un repositorio público.

## Publicar

1. Crear repositorio en GitHub.
2. Subir todos los archivos de esta carpeta (los dos `plantilla-*.html` son respaldos).
3. Settings → Pages → Deploy from a branch → main / root.
4. Abrir `https://USUARIO.github.io/REPO/`.
5. Al finalizar la reunión, descargar `presentacion-duenos.html`, `ferreksa-acuerdos.json` y reemplazarlos mediante un commit.

Recursos visuales remotos provenientes de los repositorios de FerreKsa; requieren conexión a Internet.
