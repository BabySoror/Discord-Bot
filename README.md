## Como hacer un bot de discord

------------

### Creacion del bot
#### Para crear un bot de discord vaya a [Discord Developer Portal](https://discord.com/developers/applications "Discord Developer Portal") y cree su bot, no se olvide de darle permisos de adm y invitarlo a su servidor

------------

## Ahora vamos a abrir termux y poner los siguientes comandos
- ``pkg update -y && pkg upgrade -y``
- ``pkg install python -y``
- ``pkg install python3 -y``
- ``pkg install nano -y``
#### Ahora instalamos la api discord.py [[Documentación](https://discordpy.readthedocs.io/en/stable/ "Documentación")]
- ``python3 -m pip install -U discord.py``
#### Después de instalar todo hacemos un archivo con nano llamado index.py ``nano index.py``
#### Y después ponemos el siguiente código

-----------

![Screenshot_20211109-221805_Termux](https://user-images.githubusercontent.com/93983251/141032268-cbb01dc5-1d7f-4649-94cc-9e34e33e24f9.jpg)



#### Donde dice ``bot.run("Token")`` remplazar donde dice token por el token del bot
## Iniciando el bot
#### Despues de hacer todo nos vamos a la termianl y ponemos ``python index.py`` y nos vamos a discord al grupo donde lo dejamos y nos deberia responder si está todo bien como se muestra en la imagen
![Screenshot_20211109-221849_Termux](https://user-images.githubusercontent.com/93983251/141032509-9c2477d0-45c9-4cb0-b54d-ff591dcb0356.jpg)
![Screenshot_20211109-221950_Discord](https://user-images.githubusercontent.com/93983251/141032511-60a76cb6-7cea-425d-96e0-f0971c36d149.jpg)
