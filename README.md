# Iniciar git
sudo apt update
sudo apt install git

git config --global user.name "Tu Nombre"
git config --global user.email "tu_correo@ejemplo.com"

# crear un repositorio

cd <directorio del proyecto>
git init

# flujo de trabajo

El flujo de trabajo es:
- creas un archivo.
- lo pruebas
- lo agregas a git
- git add .
- git commit -m
- git pull origin main
- git push origin main

# Game Project

Para correr el juego debes seguir las siguientes isntrucciones en la terminal:

``` sh
cd game
Python3 main.py
```