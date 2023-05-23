# Git Cheatsheet

Git es un sistema de control de versiones distribuido, gratuito y de código abierto diseñado para manejar todo, desde proyectos pequeños hasta muy grandes con velocidad y eficiencia.

## Comandos

```bash
  git config --global user.name "[nombre]"
```
Configura el nombre que quieres que aparezca en tus commits

```bash
  git config --global user.email "[email address]"
```
Configura el email que quieres que aparezca en tus commits

```bash
  git config --global color.ui auto
```
Habilita la útil colorización de líneas de comando para comandos de git

```bash
  git config --list
```
Muestra la configuración de tu git

```bash
  git init
```
Inicializa un repositorio de git existente

```bash
  git clone [url]
```
Clona un repositorio existente

```bash
  git status
```
Muestra los archivos modificados en el working directory, que estan staged para tu siguiente commit

```bash
  git add [archivo]
```
Añade un archivo para el siguiente commit (stage)

```bash
  git add .
```
Añade todos los archivos

```bash
  git commit -m "[Mensaje descriptivo]"
```
Hace commit hacia la rama

```bash
  git commit -a
```
Hace commit de todos los archivos modificados y los añade al staging area

```bash
  git rm [archivo]
```
Elimina el archivo del directorio de trabajo y lo prepara para el siguiente commit

```bash
  git rm --cached [archivo]
```
Elimina el archivo del control de versiones pero lo mantiene en tu directorio de trabajo

```bash
  git mv [archivo-original] [archivo-renombre]
```
Cambia el nombre del archivo y lo prepara para el siguiente commit

```bash
  git log
```
Muestra todos los commits de la rama actual

```bash
  git branch
```
Muestra los branches
```bash
  git branch [nombre-branch]
```
Crea un nuevo branch
```bash
  git checkout
```
Permite desplazarte entre las ramas creadas por git branch