# PMD · Gobierno Municipal de Guadalupe

Prototipo web navegable del Sistema de Planeación Municipal de Desarrollo.

## Abrir el prototipo

Abre la carpeta en Visual Studio Code y ejecuta `index.html` en un navegador web. No requiere instalación ni servidor.

Para publicarlo en GitHub, crea un repositorio vacío en tu cuenta y ejecuta desde esta carpeta:

```powershell
git remote add origin URL_DEL_REPOSITORIO
git branch -M main
git push -u origin main
```

## Credenciales de demostración

| Perfil | Usuario | Contraseña |
| --- | --- | --- |
| Administrador | `admin.pmd` | `AdminPMD2026!` |
| Finanzas | `finanzas.pmd` | `FinanzasPMD2026!` |
| Super Admin — Soporte de Sistemas | `superadmin.pmd` | `SoportePMD2026!` |

No se incluyen usuarios Enlace inicialmente. El Administrador puede crearlos desde **Enlaces y dependencias**, definiendo el usuario y la contraseña de cada acceso.

Los datos del prototipo se guardan localmente en el navegador usado para abrirlo.

## Estructura PMD y ficha técnica

- El catálogo inicial contiene la estructura importada del archivo PMD proporcionado: 6 ejes, 33 objetivos, 73 estrategias, 286 líneas de acción y 21 dependencias.
- El Administrador puede reemplazar la estructura desde **Catálogo PMD → Importar Excel PMD**. La carga se habilita únicamente del 1 al 31 de enero.
- La ficha técnica se llena en línea con los campos del formato PbR-SED. **Imprimir / Guardar PDF** abre la ventana nativa de impresión, desde la cual se puede elegir “Guardar como PDF”.
- Después de imprimir, el Enlace tiene siete días para adjuntar la ficha firmada y responder si ya está firmada.

Prueba de actualización.
