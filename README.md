# manual-git

Git es una herramienta genial, aquí se describen algunos comandos básicos

- git init: inicia un repositorio en mi computador






## manual de terminal

- pwd : indica cual es la carpeta actual , en donde estoy.
- cd carpeta: entra en la carpeta
- cd ..     : sale de la carpeta
- mkdir carpeta: crea una carpeta
- rm : borra un archivo
- rm -rf carpeta: borra una carpeta y todo su contenido
- code .    : abre visual studio code con la carpeta donde yo ejecuté el comando
- touch archivo : crea un archivo
- ls : lista los  elementos dentro de la carpeta actual
- ls -la: lista los elementos dentro de la carpeta actual de manera detallada con la opcion a, lista los elementos ocultos



Comandos básicos de GIT
- git config
Uno de los comandos más usados en git es git config, que puede ser usado para establecer una configuración específica de usuario, como sería el caso del email, un algoritmo preferido para diff, nombre de usuario y tipo de formato, etc… Por ejemplo, el siguiente comando se usa para establecer un email:
git config --global user.email sam@google.com
- git init
Este comando se usa para crear un nuevo repertorio GIT:
git init
- git add
Este comando puede ser usado para agregar archivos al index. Por ejemplo, el siguiente comando agrega un nombre de archivo temp.txt en el directorio local del index:
git add temp.txt
- git clone
Este comando se usa con el propósito de revisar repertorios. Si el repertorio está en un servidor remoto se tiene que usar el siguiente comando:
git clone alex@93.188.160.58:/path/to/repository
