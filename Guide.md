
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

- Requirements.txt = Archivo que gestiona todas las dependencias y en que versiones se necesitan.

# Generar el archivo con el siguiente comando

- pip3 freeze > requirements.txt

# Revisar lo que hay dentro del archivo

- cat requirements.txt

# Instalar las dependencias necesarias para contribuir más rápido en proyectos

- pip3 install -r requirements.txt

# Request: A un servicio externo, conectarse a un servicio externo y traer eso datos

# Instalar la dependencia dentro del entorno virtual

- pip3 install requests
# Verificar la instalacion

- pip3 freeze
# Crear el archivo para que cualquier persona pueda desplegar el proyecto

 - pip freeze > requeriments.txt

# Para construir el contenedor
- docker-compose build

# Debemos tener inicializado el docker. Para lanzar digitamos el comando

- docker-compose up -d

# Para ver el estado del contenedor
- docker-compose ps

# Para ejecutar el contenedor

- docker-compose exec app-csv bash