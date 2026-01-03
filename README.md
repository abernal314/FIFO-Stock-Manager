# Gestor FIFO de Acciones V1

Aplicación web simple (un solo archivo HTML) para registrar compras y ventas de acciones aplicando el método FIFO. Está en español y guarda los datos en el navegador (localStorage). Incluye:

- Formulario para añadir transacciones (fecha, tipo, empresa, cantidad, precio).
- Cálculo FIFO para emparejar ventas con compras y obtener G/P realizado.
- Exportación e importación en CSV (cabecera: fecha,tipo,empresa,cantidad,precio).
- Resumen por empresa y gráficos (Chart.js CDN).

Archivo principal: `Gestor Acciones.html`

Cómo usar
1. Abrir `Gestor Acciones.html` en un navegador.
2. Añadir compras y ventas en el formulario.
3. Usar "Exportar CSV" para guardar el historial o "Importar CSV" para restaurarlo.

Subir a GitHub
- Inicialicé un repositorio Git local y realicé el commit inicial. Para subir a GitHub necesitas crear un repositorio remoto y ejecutar:

```powershell
# desde la carpeta del proyecto
git remote add origin https://github.com/<tu-usuario>/<tu-repo>.git
git branch -M main
git push -u origin main
```