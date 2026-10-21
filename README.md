# Talleres de R: riesgos catastróficos y eventos extremos

Sitio estático con tres cuadernos Quarto ya ejecutados. La entrada es `index.html`.
Los datos de los ejercicios son simulados.

## Enlace público

https://manoloriveros.github.io/talleres-r-riesgos/

GitHub Pages publica los HTML de la rama `main`, desde la carpeta raíz.
No hace falta instalar R para leerlos. El archivo `.nojekyll` conserva los
HTML tal como los genera Quarto, sin procesarlos como plantillas.

## Actualizar los ejercicios

1. Editar los `.qmd` originales y volver a generar sus HTML con Quarto.
2. Actualizar los tres HTML del sitio, conservando sus nombres.
3. Enviar el cambio a la rama `main` de este repositorio. GitHub Pages publica
   la nueva versión en el mismo enlace cuando termina el despliegue.

La publicación no se actualiza por el solo hecho de editar un archivo local:
los nuevos HTML deben enviarse al repositorio. El código, las tablas y las
figuras se muestran desde los archivos ya renderizados.

## Configuración opcional para Vercel

`vercel.json` permite servir estos mismos archivos como sitio estático.
Si después se conecta Vercel, elegir framework **Other**, sin comando de
compilación ni instalación, y carpeta de salida `.`. Vercel no está activo
en esta publicación.
