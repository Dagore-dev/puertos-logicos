# JOB 5. Puertos lógicos

## Puertos de interés

Los puertos son consultados en el [siguiente enlace](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers) a fecha de 17/10/2022. Algunos puertos con aplicaciones destacables son:

`32976`. De *LogMeIn Hamachi*, un servicio muy básico de VPN.
`24444`. De *NetBeans*, el conocido IDE.
`17011`. De *Worms multiplayer*, un juego perteneciente a la serie de videojuegos homónima y ampliamente conocida.
`17500`. De *Dropbox LanSyn Protocol*, responsable de la sincronización del directorio local de *Dropbox* con el remoto.
`2033`. De *Civilization IV multiplayer*, la cuarta entrega de la famosa serie de juegos de estrategia y gestión de recursos.

## Comprobación de puertos abiertos

Los puertos abiertos en un equipo con windows por sistema operativo se puede encontrar empleando el comando `netstat -ano` en una terminal elevada. 

![](/assets/images/puertos-abiertos.png)

En el administrador de tareas se puede inspeccionar qué ficheros lanzan cada uno de los procesos como se muestra en la siguiente captura. LLama la atención el elevado número de puertos que emplea el proceso `10556`, que se corresponde con una instancia de `svchost.exe`

![](/assets/images/procesos.png)

## Puertos empleados por BBDD


