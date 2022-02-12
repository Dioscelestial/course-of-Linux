# Comandos basicos de linux

- **pwd**

Se usa para visualizar el directorio actual.

> Ejemplo:  
> User@name-PC:~$ pwd  
> /home/User  
<p align="center"><img src="/Images/pwd_ejemplo.png" /></p>

- **cd**

Se usa para moverse entre los directorios.

> Ejemplo:  
> User@Name-PC:~$ cd /  
> User@Name-PC:/$  
<p align="center"><img src="/Images/cd_ejemplo.png" /></p>

Tambien se utiliza **cd ..** para retroceder en los archivos.

> Ejemplo:  
> User@Name-PC:~$ cd ..  
> User@name-PC:/home$  
<p align="center"><img src="/Images/cdBack_ejemplo.png" /></p>

Tambien se utiliza **cd** para regresar a la carpeta de usuario.

> Ejemplo:  
> User@name-PC:~/.local/share/sounds$ cd  
> User@name-PC:~$
<p align="center"><img src="/Images/cdProfile_ejemplo.png" /></p>

Tambien se utiliza **cd /directorio/ejemplo** para ir directamente a la ruta especificada.

> Ejemplo:  
> User@Name-PC:~$ cd .local/share/sounds/
> User@name-PC:~/.local/share/sounds$ 
<p align="center"><img src="/Images/cdRoute_ejemplo.png" /></p>


- **ls**

Se usa para visualizar todos los directorios disponibles apartir del directorio en el que se encuentra.

> Ejemplo:  
> User@Name-PC:~$  
> Desktop Downloads Pictures Public Templates Videos  
> Documents Music piper snap ti workspace_v11  
<p align="center"><img src="/Images/ls_ejemplo.png" /></p>

    - *-l*

Es un parametro de **ls** el cual funciona para hacer un listado largo de los directorios

    - *-la*

Es un parametro de **ls** el cual funciona para hacer un listado largo de todos los directorios

- **clear**

Se usa para limpiar la pantalla y borrar todos los comandos anteriores.

> Ejemplo:  
> User@Name-PC:~$ Clear  
<p align="center"><img src="/Images/clear1_ejemplo.png" /></p>
<p align="center"><img src="/Images/clear2_ejemplo.png" /></p>

- **cat**

Se usa para visualizar el contenido de un archivo

> Ejemplo:

- **echo**

Se utiliza para imprimir un mensaje por pantalla

> Ejemplo:

## Modo Root

El usuario root en GNU/Linux es el usuario que tiene acceso administrativo al sistema.
Para habilitar el modo root, se usa **sudo su**.

> Ejemplo:  
> User@Name-PC:~$ sudo su  
> [sudo] password for User: []  
> root@User@Name-PC: /home/User#  

<p align="center"><img src="/Images/sudoSu_ejemplo.png" /></p>