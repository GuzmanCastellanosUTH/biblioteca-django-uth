#  Biblioteca Virtual

## Descripción del proyecto

Este proyecto es una **biblioteca virtual** que permite gestionar libros de manera digital. El sistema permite registrar libros, consultar su información, realizar préstamos y llevar el control de los mismos. Está pensado para facilitar la administración de una biblioteca de forma sencilla y accesible desde un navegador web.

## Tecnologías utilizadas

* Python 3.10+
* MySQL Server 8.0+
* MySQL (mysql-connector)
* Bootstrap 5
* Git
* Visual Studio Code
* Navegador web moderno

## Instrucciones de instalación

1. Clona el repositorio:

   bash
   git clone https://github.com/tu-usuario/biblioteca-virtual.git
   
2. Abre el proyecto en Visual Studio Code.
3. Asegúrate de tener instalado **Python 3.10 o superior**.
4. Instala las dependencias necesarias:

   bash
   pip install mysql-connector-python
   
5. Configura la base de datos en MySQL Server y actualiza las credenciales de conexión en el proyecto.
6. Ejecuta el archivo principal del sistema:

   bash
   python main.py
   
7. Accede al sistema desde tu navegador web.

## Estructura del proyecto


PRUEBA/
│── biblioteca_project/
│   │── __init__.py
│   │── settings.py
│   │── urls.py
│   │── asgi.py
│   │── wsgi.py
│
│── libros/
│   │── migrations/
│   │── __init__.py
│   │── admin.py
│   │── apps.py
│   │── models.py
│   │── tests.py
│   │── urls.py
│   │── views.py
│
│── media/
│   │── autores/
│   │── portadas/
│
│── static/
│   │── css/
│   │── images/
│   │── js/
│
│── templates/
│   │── base/
│   │── libros/
│
│── venv/
│── .env
│── .gitignore
│── manage.py
│── requirements.txt


## Información del autor

* Autor: Jesús Emiliano Guzmán Castellanos
* Carrera: desarrollo de software multiplataforma
* **Grupo: 5-1
