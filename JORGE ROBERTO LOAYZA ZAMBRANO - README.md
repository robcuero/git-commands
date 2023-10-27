# Control de versiones

Git es un sistema de control de versiones que permite rastrear y gestionar cambios en proyectos, facilitando la colaboración y el seguimiento del historial de modificaciones.

## Empezando

En nuestro tutorial de Git, comenzaremos por instalar Git en tu sistema y configurar tu nombre y correo electrónico. Luego, te enseñaremos cómo iniciar un repositorio Git, trabajar en tu proyecto y registrar tus cambios utilizando diversos comandos.

### Requisitos previos

Instalar Git: Debes instalar Git en tu computadora. Puedes descargarlo desde el sitio web oficial de Git (https://git-scm.com) y seguir las instrucciones de instalación correspondientes a tu sistema operativo (Windows, macOS, Linux, etc.).

```
git --version
git version 2.33.0
```

### Configuracion

Ingresa un usuario y tu correo

```
git config --global user.name "Tu Nombre"
git config --global user.email "tu@email.com"
```

## Iniciar un nuevo repositorio

El comando git init se utiliza para iniciar un nuevo repositorio Git en un directorio

### Comando: `git init`

![Esta es una imagen de ejemplo](/assets/init.jpg)

## Verificar el estado actual de tu repositorio

Obtendrás información sobre los cambios que se han realizado en los archivos y carpetas dentro del repositorio en comparación con la rama actual y el área de trabajo.

### Comando: `git status`

![Esta es una imagen de ejemplo](/assets/status.jpg)

## Agregar cambios a staging area

Todos los archivos modificados y nuevos archivos en el directorio de trabajo se prepararán para ser confirmados en el próximo commit.

### Comando: `git add .`

![Esta es una imagen de ejemplo](/assets/add.jpg)

## Registrar o confirmar los cambios realizados

Permite adjuntar un mensaje que describa los cambios que se están confirmando

### Comando: `git commit -m "mi primer commit"`

![Esta es una imagen de ejemplo](/assets/commit.jpg)

## Verificar historial

### Comando: `git log`

Se utiliza para ver el historial de commits en un repositorio Git

![Esta es una imagen de ejemplo](/assets/log.jpg)

## Verirficar ramas

### Comando: `git branch`

Se utiliza en Git para mostrar la lista de ramas disponibles en un repositorio. Cuando ejecutas git branch en tu terminal, obtienes una lista de todas las ramas que existen en tu proyecto.

![Esta es una imagen de ejemplo](/assets/branch.jpg)

## Creacion de rama

### Comando: `git branch nombre-de-la-rama-a-crear`

Se utiliza en Git para crear una nueva rama en tu repositorio. Cuando ejecutas este comando, se crea una nueva rama con el nombre especificado

![Esta es una imagen de ejemplo](/assets/createBranch.jpg)

## Cambiarse de rama

### Comando: `git checkout nombre-de-la-rama-a-cambiarse `

Se utiliza en Git para cambiar de una rama a otra. Cuando ejecutas este comando, Git te llevará a la rama especificada y actualizará tu directorio de trabajo para reflejar el estado de esa rama

![Esta es una imagen de ejemplo](/assets/branchDevelop.jpg)

## Crear y cambiar a una nueva rama en un solo paso

### Comando: `git checkout -b nombre-de-la-rama-a-crear`

Se utiliza en Git para crear una nueva rama y cambiar inmediatamente a esa rama en un solo paso

![Esta es una imagen de ejemplo](/assets/checkoutB.jpg)

## Fusionar Cambios entre ramas

El comando git merge se utiliza para integrar los cambios realizados en una rama en otra. Permite combinar los cambios de una rama secundaria, como una característica o una corrección de errores.

![Esta es una imagen de ejemplo](/assets/resta.jpg)

### Comando: `git merge`

![Esta es una imagen de ejemplo](/assets/merge.jpg)

## Eliminar rama

Se utiliza para eliminar una rama en Git. Para usar este comando, debes especificar el nombre de la rama que deseas eliminar.

### Comando: `git branch - d nombre-de-la-rama-a-eliminar`

![Esta es una imagen de ejemplo](/assets/delete.jpg)

## Etiquetar Puntos en la Historia

se utiliza para marcar y etiquetar puntos específicos en la historia del repositorio, como versiones de lanzamiento o hitos importantes, facilitando la referencia y el seguimiento.

### Comando: `git tag nombre-de-la-etiqueta`

![Esta es una imagen de ejemplo](/assets/tag.jpg)

## Listar Etiquetas en un Repositorio Git

Se utiliza para mostrar una lista de etiquetas existentes en un repositorio Git.

### Comando: `git tag list`

![Esta es una imagen de ejemplo](/assets/taglist.jpg)

## Eliminar Etiquetas en Git

Esto eliminará la etiqueta especificada del repositorio. Asegúrate de tener en cuenta que esta acción es irreversible y que eliminará la etiqueta de forma permanente..

### Comando: `git tag -d nombre-de-la-etiqueta`

![Esta es una imagen de ejemplo](/assets/tagD.jpg)

## Reorganizar Cambios en una Rama

Se utiliza para reorganizar y aplicar los cambios de la rama actual en la parte superior de la rama develop. Esto crea una historia de commits más lineal y ordenada, lo que puede ser útil para integrar cambios de una rama secundaria en la rama principal.

### Comando: `git rebase nombre-de-la-rama`

![Esta es una imagen de ejemplo](/assets/rebase1.jpg)
![Esta es una imagen de ejemplo](/assets/rebase2.jpg)
![Esta es una imagen de ejemplo](/assets/rebase3.jpg)

## Aplicar un Commit Específico a la Rama Actual

Se utiliza para aplicar un commit específico en la rama actual. Esto es útil cuando deseas incorporar cambios individuales de otras ramas sin fusionar la rama completa.

### Comando: `git cherry-pick hash-del-commit`

![Esta es una imagen de ejemplo](/assets/cherry.jpg)

## Guardar Cambios Temporalmente

Se utiliza para guardar temporalmente los cambios en el directorio de trabajo que no están listos para ser confirmados en un commit. Esto

### Comando: `git stash`

![Esta es una imagen de ejemplo](/assets/stash.jpg)

## Listar Stashes en Git

Se utiliza para mostrar una lista de los stashes (almacenes temporales) que se han creado en un repositorio Git.

### Comando: `git stash list`

![Esta es una imagen de ejemplo](/assets/stashList.jpg)

## Aplicar y Eliminar el Stash Más Reciente en Git

Se utiliza para aplicar el stash más reciente de cambios guardados temporalmente en tu repositorio Git y, al mismo tiempo, eliminarlo de la lista de stashes.

### Comando: `git stash pop`

![Esta es una imagen de ejemplo](/assets/stashPop.jpg)

## Deshacer cambios en Git

Se utiliza para deshacer un commit creando un nuevo commit que revierte los cambios introducidos por ese commit.

### Comando: `git stash hash-del-commit`

![Esta es una imagen de ejemplo](/assets/revertC.jpg)

![Esta es una imagen de ejemplo](/assets/revert.jpg)

## Construido con

- [MarkDown](https://www.markdownguide.org/) - Lenguaje de marcado ligero

## Contribuyendo

Por favor leer [github](https://docs.github.com/es) la documentacion oficial para mas detalles.

## Autor

- **Jorge Loayza** - _Dev_ - [Linkedin](https://www.linkedin.com/in/jorge-roberto-loayza/)

## Licencia

2023 - ESPAM MFL
