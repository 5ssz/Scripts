# Listar paquetes instalados en Ubuntu
## Comandos
En Ubuntu, existen varios comandos que permiten listar el software instalado en el sistema. En esta guía, veremos los siguientes:
- apt
- dpkg
- snap
- flatpak

## apt
El comando `apt` es una herramienta de gestión de paquetes que se utiliza para instalar, actualizar y desinstalar software en Ubuntu. Para listar los paquetes instalados con `apt` y archivos `.deb`, abrimos la terminal y escribimos:
```shell
apt list --installed
```
En caso de buscar algun paquete en concreto, podemos utilizar el comando `grep`:

```shell
apt list --installed | grep "nombre-paquete"
```

## dpkg.
El comando `dpkg` es una herramienta de bajo nivel que se utiliza para instalar, configurar y administrar paquetes de Debian. Para listar todos los paquetes instalados podemos utilizar cualquiera de los siguientes comandos:
```shell
dpkg-query -l
```
```shell
dpkg -l
```

Como con `apt`, aquí también podemos filtar usando el comando `grep`:
```shell
dpkg-query -l | grep "nombre-paquete"
```

## snap
Snap es un sistema de gestión de paquetes que permite instalar, actualizar y administrar aplicaciones en Ubuntu.
```shell
snap list
```
La lista nos indicará que aplicaciones son de un editor verificado mediante un check verde.

## flatpak
Flakpak es otro sistema de gestión de paquetes (podemos instalar y ejecutar aplicaciones de Ubuntu).
```shell 
flatpak list
```
Es importante tener en cuenta que este comando solo listará los paquetes instalados a través de Flatpak, no aquellos instalados mediante otros métodos.


**Cada comando es útil en diferentes situaciones, por lo tanto, es recomendable conocerlos y utilizarlos según sea necesario**
