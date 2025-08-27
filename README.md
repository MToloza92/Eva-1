Taller Mecánico - Django

Esta es una aplicación web desarrollada con Django para la gestión de un taller mecánico. La aplicación permite administrar Mecánicos, Vehículos y Procedimientos a través de Django Admin.

Estructura del proyecto

Proyecto: taller

Apps:

mecanico → Gestiona mecánicos (nombre, contacto, especialidad)

vehiculo → Gestiona vehículos (patente única, modelo, año, dueño)

procedimiento → Gestiona procedimientos (nombre, descripción, mecánico, vehículo)

Requisitos

Python 3.13+

Django 5.2+

SQLite (por defecto)

Instalación

Clonar el repositorio:
git clone <URL_DEL_REPOSITORIO>
cd taller

Crear y activar entorno virtual (opcional pero recomendado):
python -m venv venv
venv\Scripts\activate # Windows
source venv/bin/activate # Linux / Mac

Instalar dependencias:
pip install django

Aplicar migraciones:
python manage.py makemigrations
python manage.py migrate

Crear superusuario para acceder a Django Admin:
python manage.py createsuperuser

Ejecutar el servidor:
python manage.py runserver

Acceder a Django Admin:
http://127.0.0.1:8000/admin/

Desde allí podrás crear, listar, modificar y eliminar Mecánicos, Vehículos y Procedimientos.

Notas

No se implementaron vistas públicas ni URLs adicionales; toda la gestión se realiza mediante Django Admin.

Cada entidad se implementó como una app independiente según los requerimientos.
