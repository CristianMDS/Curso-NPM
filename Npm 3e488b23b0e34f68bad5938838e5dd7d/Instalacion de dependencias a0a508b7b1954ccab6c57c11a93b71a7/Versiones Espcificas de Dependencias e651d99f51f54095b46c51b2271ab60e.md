# Versiones Espcificas de Dependencias.

Al tener dependecias iguales pero de diferente version puede generar inconvenientes.

Por esta razon podemos utilizar:

- npm install [dependencias] -o: De esta forma se instala una dependencia de forma opcional.
- npm install [dependencia] —dry-run: Con este comando (—dry-run) simulara una instalacion de la dependencia, con el fin de primero evaluar si se genera un conflicto entre dependencias en nuestro proyecto. **Posteriormente se puede instalar usando (*save*) o (*save-dev*).**
- npm install [dependencia]@[version]: De esta forma se instala una version especifica de una dependencia, **Para tener en cuenta el sistema nos dira cuantos de los paquetes fueron auditados e instalados para mayor seguridad.**
    - **(Para el caso actual del curso se utilizo *npm install json-server@0.15.0*):** Esto dio como resultado 7 vulnerabilidades encontradas.
- npm install [dependencia]@**latest**: Si utilizamos en lugar de la version al finalizar el comando la palabra **LATEST** instalara la ultima version estable de la dependencia.
    - (**Para el caso actual del ejercicio se utilizao *npm install json-server@latest***): Esto dando como resultado 44 paquetes y 0 vulnerabilidades.
- npm install: Instala las dependencias que estén dentro de un *package.json*.