# Seguridad y Solucion de Errores

- **npm audit** --> Audita las dependencias que tenemos instaladas en busca de vulnerabilidades.
    - **Nota**: Nos muestra las vulnerabilidades y el peligro que representan low, medium, moderate, high, critical.
- **npm audit fix** --> Audita e intenta arreglar las vulnerabilidades de nuestras dependencias. **npm**
    - **Nota:** Este comando nos ayuda a solucionar algunas de las vulnerabilidades encontradas.
- **audit --json** --> Muestra los resultados de la auditoría a manera más profunda en formato json.
- **npm audit fix --force** --> Corrige los problemas encontrados en las librerías instalando otras dependencias por debajo si es necesario.
    - **Nota**: Es probable que con el primer **fix** no podamos solucionar todo de esta forma forzamos a npm a solucionar las vulnerabilidades de las dependencias.

⚠⚠ **ADVERTENCIA** ⚠⚠ 

En ocaciones ninguna de las auditorias soluciona todas las vulnerabilidades razon por la cual es mejor actualizar la dependencia a su version **@latest**  o bien sea conocida por la ultima version de la dependencia.