# FerreKsa × Pamela · Estable

Una sola aplicación `index.html`, sin iframes, con navegación directa y responsive.

- Reunión interna: `index.html`
- Dueños: `index.html?view=duenos`
- Enlaces clásicos: `presentacion-chicas.html` y `presentacion-duenos.html` redirigen a la app.
- Editar y acuerdos: se guardan **solamente en el navegador**.
- «Actualizar dueños» lleva cambios de texto con correspondencia y los acuerdos aprobados quedan en el HTML exportado.
- Exportar JSON permite llevar cambios a otro navegador; descargar HTML genera documento autónomo.
- GitHub Pages no sincroniza borradores ni actualiza el repositorio desde la web.

## Subir
Usa el script `PUBLICAR_MAC.command` con `gh`, `git`, `rsync` instalados. Hace backup local antes de copiar y verifica el despliegue sin destruir archivos ajenos.
