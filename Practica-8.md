# Practica 8
## Alejandro Limon Perez
---
1. ¿Cómo se inicializa un repositorio en Git?

    R: Se inicia iniciando cunta en github despues creas una carpeta en visual code donde guardaras
    tus cosas, despues vinculas tu cuenta de Github 
     ``` bash
    $ git config --global user.name
    Angry6irds

    $ git config --global user.email
    speedlimon34@gmail.com

      ```


2. ¿Cómo creas un repositorio en GitHub?

    R: Haces una carpeta, despues creas el archivo que modificaras dentro del repositorio ya modificado, haces un Readme para poder especificar que estas haciendo en el repositorio y despues le das a git init
    ``` bash
    $ mkdir Ejercicio
    $ touch README.md
    $ git init
    ```
3. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?

R: Empiexas desde el git init y sigues los paso para ir agregando los comandos para hacer tu primer commit
``` bash
$ git init
$ git add .
$ git commit -m "Primer commit"
$ git branch -M main
$ git remote add origin https://github.com/azul_10/Ejercicio.git
$ git push -u origin main
```

4. ¿Cuál es el flujo básico de trabajo en Git y GitHub?
``` bash
git add.
git commit -m "Cambios"
git push
```
5. ¿Para qué sirve el archivo .gitignore?
para ignorar cositas(hacer que ciertos programas puedan acceder a nuestro codigo)

6. ¿Cuál es el propósito de una rama?
Poder modificar el proyecto individualmente sin necesidad de tocarla rama principal

7. ¿Qué es una fusión?
Es la union de las diferentes ramas del proyecto a la rama principal

8. Explica los diferentes tipos de fusión que existen.
es cuando una rama se junta con el main sin modificaciones manuales y la otra con modificaciones manuales

9. ¿Cómo puedes ver el historial de tu repositorio?
Con git log

10. ¿Cuál es el propósito de una etiqueta?
El saber en que version del proyecto estas trabajndo y si los cambios que hiciste son mayores, menore o simples arreglos de bugs