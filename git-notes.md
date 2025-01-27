# GIT ADD

Este comando se usa para agregar archivos al área de preparación (staging area). Básicamente, le dices a Git que has hecho cambios y que quieres incluirlos en el próximo commit.

## Su comando es el siguiente:

``` git add .             # Agrega todos los archivos modificados```

# GIT COMMIT

Guarda los cambios que han sido añadidos al área de preparación, creando un punto en la historia del repositorio. Cada commit debe llevar un mensaje descriptivo para identificar qué cambios se realizaron.

## Su comando es el siguiente:

``` git commit -m "Agregué la sección de contacto en la página web"```

# GIT PUSH

Envía los commits guardados en el repositorio local al repositorio remoto (como GitHub, GitLab o Bitbucket).

## Su comando es el siguiente:

``` git push origin main   # Sube los cambios a la rama principal del repositorio remoto```