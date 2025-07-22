# bdata-tarea3

## Orden de ejecución:
1. `build_image.sh` para crear la imagen del contenedor principal
2. `run-postgrs.sh` para crear la imagen de postgres y ejecutar un contenedor con ella
3. `run_image.sh` para ejecutar un contenedor con la imagen principal

**---** lo siguiente es estando dentro del contenedor, i.e. con la consola `bash 5.0#` **---**

4. `load_jupyter_notebook.sh` para levantar el proceso de Jupyter Notebook y poder trabajar

5. Abrir jupyter en el puerto 8.8.8.8 con el enlace que le muestra la consola

6. para más adelante, correr `connect-psgres.sh` y así tener conexión con la BD