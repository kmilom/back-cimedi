Pasos para la creación de proyecto en Django Framework:
1. Crear entorno virtual para el proyecto: python -m venv env
2. Activar el entorno virtual: env\Scripts\activate
3. Instalar Django Framework: pip install django

Para inicializar el proyecto Django: python manage.py runserver

El archivo requeriments.txt contiene todas las dependencias instaladas en el proyecto. Para crearlo se usa: pip freeze > requeriments.txt

Pasos para participar en el proyecto:
1. Clonar el repositorio: git clone https://github.com/kmilom/backcimedi.git
2. Crear el entorno virtual: python -m venv env
3. Activar el entorno virtual: env\Scripts\activate
4. Instalar dependencias listadas en requeriments.txt: pip install -r requeriments.txt

Configuración para conectar a la base de datos:
1. Crear archivo '.env' en el directorio principal del proyecto.
2. Crear las variables de entorno dentro de este archivo.
3. Haciendo uso de la librería 'dotenv', importar y configurar las variables de entorno dentro del archivo 'settings.py'.