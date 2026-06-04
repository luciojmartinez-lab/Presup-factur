# Presupuestos y facturas

Aplicación estática para crear presupuestos y facturas, previsualizarlos en formato A4 y guardarlos como PDF desde la opción de imprimir del navegador.

## Uso

Abre `index.html` en el navegador, rellena los datos y pulsa `Imprimir PDF`. En el diálogo de impresión elige `Guardar como PDF`.

El nombre sugerido para el PDF usa el formato antiguo: `P-65478` para presupuestos y `FRA-26082` para facturas.

La app guarda los datos en el navegador con `localStorage`. Usa `Backup` para descargar una copia de seguridad y `Restaurar` para cargarla en otro navegador o móvil.

## Netlify

El proyecto no necesita compilación. En Netlify se puede publicar directamente la raíz del repositorio:

- Build command: vacío
- Publish directory: `.`

Lo recomendable es crear un repositorio en GitHub y conectar Netlify a ese repositorio para que cada cambio se publique automáticamente.
