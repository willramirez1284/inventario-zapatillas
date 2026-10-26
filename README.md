# Inventario de zapatillas

Aplicación web adaptable para iPhone, iPad y computador. Registra pares por modelo y combinación de tallas US, EUR y CM, guarda los datos en este navegador y permite exportar a Excel (`.xlsx`) o respaldar/restaurar en JSON. Las fotos opcionales se incluyen en el Excel y el respaldo.

## Publicar en GitHub Pages

1. En el repositorio, abre **Settings → Pages**.
2. En **Build and deployment**, elige **Deploy from a branch**, rama `main`, carpeta `/(root)` y guarda.
3. Espera la publicación y abre la dirección que aparece en Pages.
4. En iPhone, abre el sitio con Safari y pulsa **Compartir → Añadir a pantalla de inicio**.

No requiere instalar programas ni un servidor. ExcelJS se carga desde jsDelivr para crear `.xlsx` con fotos; la exportación Excel necesita internet. Los datos se guardan solo en el dispositivo y navegador actuales. Usa **RESPALDAR JSON** para transferirlos a otro dispositivo.

## Uso

- Ingresa al menos una talla y pulsa **REGISTRAR 1 PAR**. Cada toque añade un par y deja el formulario listo para el siguiente.
- Las combinaciones de modelo y tallas se conservan en filas separadas y ordenadas de menor a mayor.
- Agrega una foto desde la cámara o la fototeca. Edita modelo, equivalencias o cantidad desde la tabla.
- Descargar Excel o JSON no borra el inventario. Para importar un respaldo, selecciona el JSON y confirma el reemplazo del inventario existente.
- Limpiar requiere dos confirmaciones. Descarga y revisa primero el Excel.
