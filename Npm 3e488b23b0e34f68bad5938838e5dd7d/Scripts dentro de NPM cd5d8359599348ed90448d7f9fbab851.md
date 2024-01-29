# Scripts dentro de NPM

Podemos crear una nueva carpeta “**src**” ****dentro colocar nuestros scripts **js:**

![Untitled](Scripts%20dentro%20de%20NPM%20cd5d8359599348ed90448d7f9fbab851/Untitled.png)

Y en el archivo **package.json** podemos colocar un nombre de comando para ejecutar nuestro script desde la terminal:

![Untitled](Scripts%20dentro%20de%20NPM%20cd5d8359599348ed90448d7f9fbab851/Untitled%201.png)

Utilizando esta estructura: ***“*[nombre del comando]*”: “*node [ruta donde se encuentra nuestro script]*”.*** Utilizando el comando node primero para ejecutar el script, adicional se pueden convinar scripts usando el operador **&&.**

- **NOTA:** Si el primer script falla el segundo no se ejecutara.

Para ejecutar estos nuevos comandos debemos usar “**npm run [comando]**”.

[Npx (Node package Execute).](Scripts%20dentro%20de%20NPM%20cd5d8359599348ed90448d7f9fbab851/Npx%20(Node%20package%20Execute)%20bc58207e42874816b4ad658fec9c1eae.md)