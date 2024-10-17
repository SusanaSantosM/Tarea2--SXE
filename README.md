# Tarea2--SXE
### 1.- Descarga la imagen "alpine" SIN ARRANCARLA y comprueba que está en tu equipo
Descargamos la imagen iso en la máquina virtual con el comando:  

``docker pull alpine``

Se descarga la imagen en un repositorio Docker.


### 2.- Crea un contenedor sin ponerle nombre. ¿Está arrancado? Obtén el nombre
Usamos el comando:

``docker run alpine``

El contenedor está creado y para ver el nombre usamos otro comando que es:

``docker ps -a``

Este en el apartado NAMES indica el nombre del contenedor.


