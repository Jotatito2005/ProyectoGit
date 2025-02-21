# repo01

Este es un proyecto con la finalidad de aprender GIT y funcionalidades básicas.

## Creación del repositorio

1. Se creó el directorio `repo01` localmente.
2. Se inicializó un repositorio Git vacío con el comando `git init`.
3. Se añadió este archivo `readme.md`.
4. Se realizó el primer commit con el comando `git commit -m "Primer commit: Se añade readme.md"`.

## Conexión a GitHub

Este repositorio local está conectado al repositorio remoto en GitHub: https://docs.github.com/es/repositories/creating-and-managing-repositories/about-repositories

Los pasos para establecer la conexión fueron:

1. Se creó el repositorio `repo01` en GitHub.
2. Se copió la URL del repositorio remoto.
3. Se ejecutó `git remote add origin <URL_del_repositorio_remoto>`.
4. Se verificó la conexión con `git remote -v`.

## Comandos y funcionalidades aprendidas

Durante el aprendizaje de Git, se utilizaron los siguientes comandos y funcionalidades:

### Staging Area (Área de Preparación)

El "staging area" es un área intermedia donde se preparan los cambios antes de confirmarlos (commit).

*   `git add <archivo>`: Añade el archivo especificado al "staging area".
*   `git add .`: Añade todos los cambios del directorio actual al "staging area".
*   `git rm --cached <archivo>`: Elimina el archivo del "staging area" pero lo mantiene en el directorio de trabajo.

### Commits (Confirmaciones)

Los commits son instantáneas del repositorio en un momento determinado.

*   `git commit -m "Mensaje del commit"`: Crea un nuevo commit con el mensaje especificado.
*   `git commit -a -m "Mensaje del commit"`: Añade todos los cambios y crea un commit con el mensaje especificado.
*   `git log`: Muestra el historial de commits.

### Otros comandos útiles

*   `git status`: Muestra el estado del repositorio.
*   `git diff`: Muestra las diferencias entre el directorio de trabajo y el "staging area".
*   `git pull`: Descarga los cambios del repositorio remoto y los fusiona con la rama local.
*   `git push`: Envía los commits locales al repositorio remoto.

