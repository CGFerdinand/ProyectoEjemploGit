# Introducción a Git

## Descripción
El programa muestra un mensaje impreso que al inicio era hola mundo y posteriormente se cambió a hola git

## Instrucciones de uso
Para la ejecución del programa HolaMundo.java es necesario abrir la terminal y dirigirse al directorio donde se guardó el archivo HolaMundo.java, posteriormente se necesita compilar el archivo con el comando javac HolaMundo.java, esto creará un archivo HolaMundo.class, posteriormente para ejecutarlo se escribe java HolaMundo.

## Comandos utilizados
Los comandos que se utilizaron en git fueron los siguientes:
1. git config --global user.name "nombre del usuario"
2. git config -- global user.email "email del usuario"
3. git init
4. git remote add origins https://github.com/CGFerdinand/ProyectoEjemploGit.git
5. touch .gitignore
6. git add -A
7. git commit -m "mensaje"
8. git push origin master
9. git status

### Notas sobre .gitignore
Se creó este archivo para evitar que se suban los archivos con la extensión .log al repositorio remoto

El programa al ser ejecutado imprime en pantalla el mensaje Hola Git y para verificar que no se subió ningun archivo log se utiliza el comando git status 