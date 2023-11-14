# CD_UD02_Tarea2

# Boletín Tarea UD02. Trabajo Colaborativo. Fork, Pull Request y merges. 

## Para qué es este repo?

Este repo plantea unos ejercicios sencillos sobre la colaboración entre proyectos GIT usando Fork, Pull Request y merge.


## Pre-requisitos

Como requisitos previos se asumen:

- Nociones básicas de GIT
- Cuenta generada en github. 
- Nociones de HTML
- Antes de afrontar la tarea debes haber leído y comprendido el contenido de la unidad.
- Selección de herramientas de edición. *Visual Code* o similares.

## Antes de ponerte a trabajar

### Haz un fork del repositorio original

Haz un fork del repositorio original y **configúralo en tu espaio de usuario**.

### Clona el repositorio en tu máquina de trabajo

```shell
git clone <url de tu fork>
```

**Modifiques** el fichero `README.md` añadiendo tu nombre en el apartado de autores. 

### Ramas 

Crea una rama con tu nombre y trabaja ahí los ejercicios que se proponen. Una vez que termines los ejercicios debes integrarlos en tu rama main.
Puedes crearte las ramas que necesites para el trabajo, pero en el momento de la entrega se tendrá en cuenta lo que haya en la rama **main**.

### Revisa si se han producido actualizaciones en las especificaciones

Cada vez que retomes tu trabajo asegúrate tener la última versión de las especificaciones. Para ello:

0.  Si añadiste una URL remota diferentes debes eliminarla primero. 
   `git remote rm profesor`
1. (*Sólo la primera vez*) Añade como repo remoto el repo del profesor desde el que has creado tu fork.

    `git remote add profesor <url-repoProfesor>`
    En este caso: 
    `git remote add profesor  git@github.com:sabelassm/CD_UD02_Tarea1.git`

2. (*Cada vez que retomes trabajo*) Revisa novedades y obtenlas del repo del profesor

    `git fetch profesor main`

Si has seguido las indicaciones de este README no deberían producirse conflictos. Si se produjesen adviértelo al profesor.

    ```bash
    # Asegúrate primero de estar en tu rama de trabajo o release branch
    git checkout rama
    
    # Después mézclate en tu rama actual las novedades
    git merge profesor/main
    ```

## Trabajando en el día a día

A medida que vayas trabajando, debes ir subiendo el código que generes al repositorio. Para ello, debes ejecutar los siguientes comandos: 

    ```bash
    # Añade los cambios
    git add .
    
    # Confirma los cambios
    git commit -m "mensaje"

    # Sube los cambios a tu repositorio
    git push -u origin rama_de_trabajo
    ```

## Entrega de la tarea

Una vez termines todas las tareas asociadas a la unidad debes subir a la tarea del mestre la url del repositorio que hayáis generado y  realizar un **pull request** al repositorio original.  

## Autores
**Adrian Vidal Piñeiro**

