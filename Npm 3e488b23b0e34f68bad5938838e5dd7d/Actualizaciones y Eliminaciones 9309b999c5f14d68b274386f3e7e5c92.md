# Actualizaciones y Eliminaciones.

1. **npm install**: se usa cuando descargamos o clonamos un proyecto de un repositorio y necesitamos que nos instale todas las dependencias necesarias.
2. **npm outdate**: Muestra los cambios.
3. **npm install name_package@latest:** actualiza la dependencia a la version mas reciente.

**Nota**: algunas dependencias dependen asi mismo de otras, razon por la cual en ocasiones se nos pedira actualizar primero otras dependencias para actualizar lo que estemos ejecutando.

- Por ejemplo en este caso al ejecutar el comando ***npm install react@latest*** nos pide que primero debemos instalar la version mas reciente de react-dom.
    
    ![Untitled](Actualizaciones%20y%20Eliminaciones%209309b999c5f14d68b274386f3e7e5c92/Untitled.png)
    

Para este caso las dependencias solicitan la misma version pero en ocasiones puede ser distinto, razon por la cual hay que prestar atencion al mensaje.

- La solucion es ejecutar ***npm install react-dom@latest.***