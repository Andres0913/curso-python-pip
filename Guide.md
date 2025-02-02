
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

# Iniciar VS con Ubuntus
- code . 

# Comandos Linux

- ll - lista de archivos
- mkdir - Crear archivo
- cd - Entrar carpetas
- pwd - Ubicación
- cd .. - Regresar carpeta

# Instalar librerias en Ubuntus

- sudo apt install python3-matplotlib 

# Ver librerias

Pip3 freeze

# Verificar donde esta python y pip

- which python3
- which pip3

# Si estas en linus o wsl debes instalar

- sudo apt install -y python3-venv

# Poner cada proyecto en su propio ambiente, entrar en cada carpeta.

- python3 -m venv env

# Activar el ambiente

- source env/bin/activate

# Salir del ambiente virtual

- deactivate

# Podemos instalar las librerias necesarias en el ambiente virtual como por ejemplo

- pip3 install matplotlib==3.5.0

# Verificar las instalaciones

- pip3 freeze



