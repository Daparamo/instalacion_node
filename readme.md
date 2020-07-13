Paso 1: Descargar nvm
En nuestra terminal de ubuntu ejecutamos el siguiente comando para descargar nvm:

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
.

Paso 2: Agregar soporte a nvm para que sea reconocido como comando en la terminal
Si ejecutamos el comando “nvm” despues de descargarlo en el paso 1 nos aparecera un mensaje en la terminal de que no reconoce el comando. Para solucionar esto debemos ejecutar el siguiente comando:

source ~/.bashrc
.

Paso 3: Instalar node js
Para instalar la versión mas reciente ejecuta el siguiente comando:

nvm install node
.

Para instalar una versión especifica de node puedes ejecutar el siguiente comando:

nvm install 12.18.1



Tomado de: 
https://platzi.com/comentario/1450553/
