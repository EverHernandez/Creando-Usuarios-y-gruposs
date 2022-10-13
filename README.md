# Creando-Usuarios-y-gruposs

Explicacion paso a paso de como crear usuarios y grupos

-Para comenzar tenemos que entrar con el usuario root

-Para crear usuario utilizamos en comando useradd, lo utilizaremos asi useradd jose useradd ever ya creamos los usuarios, los verificamos con este comando: nano /etc/passwd luego damos Ctrl + x para salir

-luego ponemos una contraseña a los usuarios con el siguiente comando passwd + elnombre de usuario passwd ever y nos
pedira que escribas una contaseña, luego nos pide que la vuelvas a escribir la contraseña se hace lo mismo con este usuario passwd jose se verifican las contraseñas con este comando : nano / etc / sombra

-Lo siguiente que haremos es crear el grupo con el comando groupadd asi: groupadd casa se verifica con el comando: cat /etc/group

-Agregar los usuarios al grupo con el comando adduser asi: adduser ever casa adduser jose casa verificar los usuarios del grupo con el comando getent asi: getent group casa

-Cambiar el nombre del grupo con el comando groupmod asi: groupmod se le da enter y le apareceran una opciones, como lo que queremos es cambiar de nombre seria el -n asi: groupmod -n familia casa se verifica con el comando: cat / etc/grupo
