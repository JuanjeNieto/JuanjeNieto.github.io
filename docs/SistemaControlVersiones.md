# Actividades - control de versiones



## Además de Git, ¿que otros sistemas de control de versiones existen?

__Git__ es el más conocido, pero existen otros como, CVS, Subversion, y Mercurial

## Además de Git, ¿que otros sistemas de control de versiones existen?

En Git tenemos el Working Directory, el área en el que trabajamos el proyecto; el Staging Area, que es donde dejamos los cambios que hemos hecho al proyecto, como si fuera un limbo; y el Repository, que es donde finalmente se suben los proyectos.

## En Git, ¿para qué sirve el comando `git config`?

Se usa para la configuración de los parámetros de Git de forma global o local.

## En Git, ¿para qué sirve el comando `git init`?

Es utilizado para crear un nuevo repositorio de Git, ya sea para convertir un proyecto en un repositorio o para crear uno vacío.

## En Git, ¿para qué sirve el comando `git clone`?

Este comando apunta a un directorio existente y lo clona o copia en otro repositorio existente.

## En Git, ¿para qué sirve el comando `git status`?

El comando Git status muestra el estado del Working Directory y del Staging Area. Permite ver los cambios que se han preparado, los que no y los archivos en los que Git no va a realizar el seguimiento.

## En Git, ¿para qué sirve el comando `git add`?

 Git add añade un cambio del directorio de trabajo en el Staging Area. De este modo, indica a Git que quieres incluir actualizaciones en un archivo concreto en la próxima confirmación.

## En Git, ¿para qué sirve el comando `git commit`

Este comando se usa para confirmar los cambios y añadirlos al Repository.

## En Git, ¿para qué sirve el comando `git log`?

Nos permite explorar el historial del repositorio y todos sus cambios, así como mostrarlos

## En Git, ¿para qué sirve el comando `git checkout -- nombrearchivo`?

Es un comando que nos mueve a la rama de ese archivo del repositorio

## En Git, ¿para qué sirve el comando `git branch`?

Nos crea diferentes ramas en el repositorio y nos permite trabajar con ellas, enumerarlas, eliminarlas...

## En Git, ¿para qué sirve el comando `git checkout`?

Es un comando que nos permite movernos por las ramas creadas del repositorio con el Git branch

## En Git, ¿para qué sirve el comando `git merge`?

Es un comando que se utiliza para unir las ramas en una sola, así unificando el desarrollo del proyecto.



## En Git, explica cómo funciona la fusión (merge) de tipo fast-forward.

Acelera el flujo del trabajo en el proceso de desarrollo del proyecto. Realiza fusiones con avance rápido en las situaciones donde exista un proceso lineal desde el xtremo de la rama actual y hasta la rama de destino.

## En Git, explica cómo funciona la fusión (merge) de tipo 3-way.

La razón por la que se llama 3-way merge es porque la confirmación de fusión se basa en 3  diferentes.

El ancestro común de nuestras ramas, en este caso comete el número C3. Este compromiso contiene código antes de que diverjamos en diferentes ramas.

Para fusionar los cambios de ambas ramas, Git mira las tres instantáneas diferentes: la instantánea anterior y la instantánea posterior. Basándose en estas instantáneas, Git combina los cambios mediante la creación de una nueva confirmación denominada Merge Commit.