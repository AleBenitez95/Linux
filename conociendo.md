## Conociendo el servidor Linux.
```
En amarillo sale los comandos y en zul los resultados.
```

### Nombre del host

![hostname](img/hostname.png)

A excepción de hostname -I que es para saber la ip, los demas comandos nos daran el nombre de la máquina.

### Cambiar hostnamme sin reiniciar

![hostname2](img/hostname2.png)

Con el comando hostnamectl set-home xxxx podemos cambiar el nombre del host.

![hostname3](img/hostname3.png)

### Versión del sistema

![version](img/version.png)

Con estos comandos podremos saber la versión del sistema, siendo lo azul el nombre popular del sistema y entre parentesis su respectivo apodo.

### Memoria RAM

![ram](img/ram.png)

Al usar free nos sale la memoria RAM, siendo mem la memoria física y la Inter (swap) la memoria de intercambio de la ram con el disco duro SSD por si la RAM está saturada.

### CPU

![cpu](img/cpu.png)

Aqui vemos detalles de la cpu, su arquitectura, el numero de cpus, su fabricante y modelo.

![cpu2](img/cpu2.png)

Te dice cuántos procesadores lógicos (o hilos de CPU) están disponibles para el sistema.

### Versión del núcleo y arquitectura

![nucleo](img/nucleo.png)

Te dice la versión del núcleo y su arquitectura.

### Discos y particiones

![discos](img/discos.png)

Con este comando podemos ver las particiones del disco duro y su punto de montaje.

![discos2](img/discos2.png)

Aqui tambien nos da el formato de cada partición

### Sistemas montados
![sisyemaFicheros](img/sistemaFicheros.png)

Con estos comandos podemos ver sus puntos de montajes ademas de su uso en %, y el formato.
### Tamaño de una carpeta
![carpeta](img/carpeta.png)

Podemos ver el espacio de los directorios.

### Usuarios y grupos del sistema
![usuarios](img/usuarios.png)
![usuariosShadow](img/usuarioShadow.png)
![grupo](img/group.png)
![grupo2](img/groupShadow.png)

Con estos comandos podemos ver el usuario y grupo al que pertenece, con getent shadow, el segundo campo es su contraseña y esta cifrada.


### Información y Configuración de la red

![red](img/red.png)

Aqui hemos configurado una ip estática, con su máscara, y puerta de enlace.

![nslookup](img/dns.png)

Aqui comprobamos la respuesta de dns y en azul sale el dns que responde.

![nslookup2](img/dnsConfig.png)

Aqui configuramos los dns.

![ping](img/ping.png)


Aqui hacemos ping siendo el apartado time, el tiempo de respuesta en milisegundos.

### Reiniciar la red

![reinicioRed](img/reinicioRed.png)

Con este comando podemos reiniciar la red y cargar nuevas configuraciones.
