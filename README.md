# dca-scv-git
Repositorio para la práctica de SCV de la asignatura DCA.

## Compilar el proyecto
    mkdir build
    cd build
    cmake ..
    make

## Ejecutar el proyecto
Una vez compilado en la carpeta `build`, ejecutar el binario llamado `hw` que se genera dentro de la misma carpeta.

    cd build
    ./hw

## Comandos ejecutados para probar el bisect
(estando en el commit `cc89667`)

    git bisect start
    git bisect bad
    git bisect good 49dae9d
    # Compilar y ejecutar
    git bisect bad
    # Compilar y ejecutar
    git bisect good
    git bisect reset
