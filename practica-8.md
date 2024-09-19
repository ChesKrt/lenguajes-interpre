1.  ¿Como se crea un repositorio en Git?

Al momento de iniciar un repositorio se debe poner el siguienite comando en el git bash

```bash
git init 
```

2.  ¿Cómo creas un repositorio en Github?

Ya teniendo una cuenta de Github se encontrara un icono "**+**" y al pulsarlo se dará la opción de crear un nuevo repositorio, es esa opción que se debe escoger

3.  ¿Cómo vinculas un repositorio local de Git con uno remoto en Github?

Por lo general este el procedimiento que sigo al hacer un repositorio:

```bash
git branch -M main
```

```bash
git remote add origin y el URL del repositorio
```
Y por seguridad siempre mando un commit para saber si todo el procedimiento salio bien

4.  ¿Cuál es el flujo básico de trabajo en Git y Github?

 Se trabaja en los documentos requeridos 

Se usa un 
```bash
git add 
```
Y después un 
```bash
git commit -m ""
```
Para subir los cambios al repositorio local

Por último se usa un 
```bash
git push
``` 
Para mandar todos los cambios junto al commit al repositorio en Github

5.  ¿Para que sirve el archivo .gitignore?

Para que los archivos que se marquen en el .gitignore no sean subidos al repositorio local y posteriormente el repositorio en Github

6.  ¿Cuál es el proposito de una rama?

Poder trabajar en el repositorio de una forma *externa* sin modificar la rama main. Útil en trabajos con más personas

7.  ¿Qué es una fusión?

Juntar una rama con otra rama o directamente con la rama main, juntando las modificaciones que se hicieron en la rama a la rama que la mando llamar

8.  Explica los diferentes tipos de fusión que existen

Existe la fusión automatica que mayormente pasa cuando no hay cambios entre ramas que se afecten mutuamente como la creación de nuevos archivos

Y existe la fusión manual que es cuando hay un archivo de una rama que fue modificado, en ese caso se debe revisar el contenido del archivo modificado y proceder con la modificación

9.  ¿Cómo puedes ver el historial de tu repositorio?

Siempre lo hago usando el codigo:

```bash
git log --oneline
```

10.  ¿Cuál es el proposito de hacer una etiqueta?

Hacer diferenciadores entre las versiones que se suben al repositorio de Github. Esto mantiene los cambios hechos en el repositorio de manera "*intacta*" por si se quiere acceder a una versión anterior