# Comandos basicos de linux

- **pwd**

Se usa para visualizar el directorio actual.

> Ejemplo:
> User@name-PC:~$ pwd
> /home/User
> ![pwd](/Images/pwd_ejemplo.png)

- **cd**

Se usa para moverse entre los directorios.

> Ejemplo:
> User@Name-PC:~$ cd / 
> User@Name-PC:/$
> ![cd](/Images/cd_ejemplo.png)

Tambien se utiliza **cd ..** para retroceder en los archivos.

> Ejemplo:
> User@Name-PC:~$ cd ..
> User@name-PC:/home$
> ![cdBack](/Images/cdBack_ejemplo.png)

- **ls**

Se usa para visualizar todos los directorios disponibles apartir del directorio en el que se encuentra.

> Ejemplo:
> User@Name-PC:~$
> Desktop Downloads Pictures Public Templates Videos
> Documents Music piper snap ti workspace_v11
> ![ls](/Images/ls_ejemplo.png)

- **Clear**

Se usa para limpiar la pantalla y borrar todos los comandos anteriores.

> Ejemplo:
> User@Name-PC:~$ Clear
> ![clear](/Images/clear_ejemplo.png)

## Modo Root

El usuario root en GNU/Linux es el usuario que tiene acceso administrativo al sistema.
Para habilitar el modo root, se usa **sudo su**.

> Ejemplo:
> User@Name-PC:~$ sudo su
> '[sudo]' password for User: []
> root@User@Name-PC: /home/User#

>> ![sudoSu](/Images/sudoSu_ejemplo.png)