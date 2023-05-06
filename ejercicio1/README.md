# S2 Git

## Abrir la consola e imprimir la ubicación actual.

```sh
pwd
```

## Crear una carpeta llamada ejercicios en el escritorio desde la consola, si no estas en la ruta del escritorio, muevete a ella.

```sh
cd Desktop
mkdir ejercicios
```
## Cambiar la ubicación a la nueva carpeta que crearon.

```sh
ls -la #listo el contenido del directorio actual
cd ejercicios
```
## Abrir la carpeta con VSCode.

```sh
code .
```
## En VSCode crear una carpeta ejercicio1.

Creé un nuevo folder utilizando la interface gráfica de VScode

## Crear un archivo llamado README.md (vacío) dentro de la carpeta ejercicio1.

Creé un nuevo file utilizando la interface gráfica de VScode dentro del folder ejercicio1

## Configurar nombre e email globalmente en git.
```sh
git config --global user.name "Andry"
git config --global user.email "andry.carolina88@gmail.com"
```

## Inicializar el repositorio de git desde la línea de comandos desde la carpeta ejercicios.

```sh
git init
```

## Crear un primer commit con el mensaje “Versión Inicial”.

```sh
git add .
git commit -m "Version inicial" 
```

## Agregar al README.md los comandos que ejecutaron en cada paso.

## Crear un nuevo commit con el mensaje “Agrega solución primer ejercicio”

```sh
git add .
git commit -m "Agrega solución primer ejercicio" 
```

## Publicar a Github en un repositorio llamado aspirantes-mir-ejercicio-1.
## Enviar el link del repositorio en Github a su mentor(a).