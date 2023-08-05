 Bitacora Comandos Camila Rueda
| Función                                  | Comando                                    | Ejemplos                                                                                                 |
|------------------------------------------|--------------------------------------------|----------------------------------------------------------------------------------------------------------|
| Ver el estado de los contenedores        | `sudo docker ps -a`                       |                                                                                                          |
| Ver carpetas de la ruta y ocultas| `ls -la`                                   |                                                                                                       |
| Eliminar contenedores detenidos | `sudo docker rm $(sudo docker ps -a -f status=exited -q)` |                                                                                                          |
| Ver contenido de un archivo              | `cat (nombre+extension)`                   | `cat Historial.txt` (ver el contenido del archivo Historial.txt)                   |
| Buscar imagen en Docker Hub               | `docker search ubuntu`                    |                                                                                                          |
| Descargar imagen de contenedor            | `docker pull ubuntu`                      |                                                                                                          |
| Cambiar directorio                       | `cd (Nombre de la Carpeta)`                | `cd /Home/cruedac419` (ingresar al directorio Home del Usuario cruedac419)                               |
| Iniciar sesión en otro usuario           | `su (usuario)`                             | `sudo messi`                              |
| Loggeo con root                          | `sudo su`                                 | `sudo su` (ingresar como super usuario)                         |
| Ver imágenes instaladas                   | `docker images`                           |                                                                                                          |
| Ver Tabla de Reglas del Firewall          | `sudo systemctl cat openvpn-iptables.service` |                                                                                                     |
| Iniciar contenedor detenido               | `sudo docker start <ID>`                  |                                                                                                          |
| Ver la ubicación del equipo              | `pwd`                                      |                                                                                                      |
| Eliminar imágenes de Docker               | `docker rmi <Image>`                      |                                                                                                          |
| Ver estado de contenedores                | `sudo docker ps -a`                       |                                                                                                          |
| Conocer Ip Address                       | `ip a`                                     |                                                                                                      |
| Actualizar                               | `sudo apt upgrade`                         | `sudo apt upgrade` (instala los repositorios actualizados)                                             |
| Dar permisos a todos los usuarios         | `sudo chmod 777 -R *`                      | `/Home/cruedac419/# sudo cmod        |
| Visualizar Carpetas                      | `tree`                                     | `tree` (muestra las carpetas en la ruta en forma de árbol)                                              |
| Copiar archivos                          | `cp (Nombre+ Extension/Directorio)`        | `cp Historial.txt /Home/cruedac419/`  |
| Iniciar contenedor detenido               | `sudo docker start <ID>`                  |                                                                                                          |
| Limpiar contenidos de Pantalla           | `clear`                                    |                                                                                                      |
| Actualizar                               | `sudo apt update`                          | `sudo apt update` (actualiza y descarga los repositorios del SO)                                        |
| Ver el estado de los contenedores        | `sudo docker ps -a`                       |                                                                                                          |
| Ver estado, iniciar o detener servicio    | `sudo systemctl (status/start/stop)`      | `sudo systemctl start openvpn-server@server.service` (iniciar un servicio)                               |
| Ver que lo que he digitado               | `history`                                  |                                                                                                          |
| Ver carpetas que hay en la ruta          | `ls -l`                                    |                                                                                                     |
| Mover archivos                           | `mv (Nombre+ Directorio)`        | `mv Archivo0 /Home/messi/`    |
| Monitor de Procesos SO              | `htop`                                     | `htop`                                                          |
| Ver carpetas que hay en la ruta y ocultas| `ls -la`                                   |                                                                                                      |
| Estado de los contenedores        | `sudo docker ps -a`                       |                                                                                                          |
| Eliminar contenedores                     | `docker rm <ID>`                          |                                                                                                          |
| Eliminar contenedor tras cerrarse         | `docker run --rm <image_name>`            |                                                                                                          |
| Crear carpeta nueva                      | `mkdir (Nombre Carpeta )`                  | `mkdir diruno` |
| Instalar monitor de Procesos SO           | `sudo apt install htop`                   | `sudo apt install htop`      |
| Ir a directorio home                     | `cd home` o `ls -CD`                      | cd home                       |
| Cambiar contraseña de usuario            | `sudo passwd (usuario)`                    | `sudo passwd cruedac419`                                  |
| Ver imágenes instaladas                   | `docker images`                           |                                                                                                          |
| Ejecutar nuevo contenedor usando imagen  | `docker run ubuntu`                       |                                                                                                          |
                                                                                                    |
| Actualizar                               | `sudo apt update`                          | `sudo apt update` (actualiza y descarga los repositorios del SO)                                        |
| Descargar imagen de contenedor            | `docker pull ubuntu`                      |                                                                                                        
| Crear archivo                            | `nano (nombre+extension)`                  | `nano s05.sh`  |
| Ver el estado de los contenedores        | `sudo docker ps -a`                       |                                                                                                          |
| Eliminar todos los contenedores detenidos | `sudo docker rm $(sudo docker ps -a -f status=exited -q)` |                                                                                                          |
| Ver estado de contenedores                | `sudo docker ps -a`                       |                                                                                                          |
