# Publicar un Paquete.

Para publicar nuestro paquete, primero debemos probar la libreria que estamos creando, por esto se debe seguir el siguiente orden de comandos:

1. **npm link:** Este comando audita nuestro proyecto y adicionalmente agrega los paquetes.
2. **npm install -g** [ruta de nuestra dependencia]: Este comando ejecuta la instalacion de nuestra libreria para probarla en nuestro **entorno local** de esta forma podemos ver si todo funciona correctamente.
    1. **NOTA:** Algunar veces si nuestra ruta incluye una carpeta con un nombre separado por EJ. “Project Npm” al colocarla junto al comando **npm install -g** recuerda utilizar el back-slash para denotar esa separacion en nuestra consola o terminal de esta forma “**Project\ Npm”.**
3. **rdm-msg-cdms-platzi:** Utilizaremos el comando asignado en el **package.json** para ejecutar nuestra funcion, en este caso se llama igual que la carpeta de nuestro proyecto o libreria.
    1. **NOTA:** En ocasiones puede fallar simplimente por escribir unicamente en nuestro archivo **global.js** de la carpeta ***Bin*** lenguaje de Javascript. Primero debemos especificar que es un archivo global usando de **node** “***#!/usr/bin/env node***”. 

**Finalmente** para publicar el proyecto (Libreria) en npm, debemos **crear una cuenta.** Luego de crear la cuenta en [npmjs.com](http://npmjs.com) procedemos a ingresar nuestras credenciales en la consola de la siguiente forma:

1. **npm adduser:** Este comando lo utilizamos para ingresar nuestra credenciales.
2.