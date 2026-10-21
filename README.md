# Talleres de R: riesgos catastróficos y eventos extremos

Sitio estático con tres cuadernos Quarto ya ejecutados. La entrada es `index.html`.
Los datos de los ejercicios son simulados.

## Publicación

Vercel sirve estos HTML directamente, sin instalar R ni ejecutar cálculos en el servidor.
El proyecto usa el ajuste de framework **Other**, sin comando de compilación,
y la carpeta de salida `.`. La rama de producción es `main`.

## Actualizar los ejercicios

1. Editar los `.qmd` originales y volver a generar sus HTML con Quarto.
2. Actualizar los tres HTML del sitio, conservando sus nombres.
3. Guardar el cambio en `main`. Con la integración Git activa, Vercel publica
   la nueva versión en el mismo enlace del proyecto.

La publicación no se actualiza por el solo hecho de editar un archivo local:
los nuevos HTML deben enviarse al repositorio. El código, las tablas y las
figuras se muestran desde los archivos ya renderizados.

