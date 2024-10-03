
# ¡Hola, soy Angel Vargas y este es mi repo! 👋

## Comandos básicos para ejecutar el Dockerfile

### 1. Construir la imagen a partir del Dockerfile:
```bash
docker build -t [mi-imagen] .
```
Este comando construirá la imagen de Docker y la etiquetará como `mi-imagen`.

### 2. Ejecutar un contenedor basado en la imagen:
```bash
docker run -d --name [mi-contenedor] [mi-imagen]
```
Este comando ejecutará el contenedor en segundo plano usando la imagen `mi-imagen` y lo nombrará `mi-contenedor`.

### 3. Ver los contenedores en ejecución:
```bash
docker ps
```
Con este comando puedes verificar si tu contenedor está en ejecución.

### 4. Acceder al bash del contenedor:

Si deseas acceder al bash del contenedor en ejecución, puedes utilizar el siguiente comando:

```bash
docker exec -it [mi-contenedor] /bin/bash
```
Este comando abrirá una terminal interactiva dentro del contenedor `mi-contenedor`.

---