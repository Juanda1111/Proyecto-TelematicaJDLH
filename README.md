# Proyecto-TelematicaJDLH
Proyecto final de telematica realizado en un entorno de nube en ubuntu

# Recomendaciones
Habilitar los puertos 80, 5600 y 8080

![image](https://github.com/Juanda1111/Proyecto-TelematicaJDLH/assets/115760221/23b5af2f-e39e-4c4e-bc79-c32dceb04b7a)

Luego cuando estemos en la maquina actualizamos los paquetes con el comando sudo apt update
Despues Instalamos docker compose con sudo apt install docker-compose
Finalmente usamos los comandos sudo docker pull ubuntu:latest y sudo docker pull mysql:latest

# Clonar git

Ahora clonaremos este repositorio con el comando git clone https://github.com/Juanda1111/Proyecto-TelematicaJDLH.git
Entramos a la carpeta Proyectp-TelematicaJDLH
Se debe entrar a la carpeta Web y en el archivo web.py cambiar el localhost por la ip publica

![image](https://github.com/Juanda1111/Proyecto-TelematicaJDLH/assets/115760221/051e2459-9f9f-409b-9c78-b18ba75250ac)

Finalmente con el comando sudo docker-compose up iniciamos los contenerdores y poniendo la ip publica en un navegador podremos correr el programa


