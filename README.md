# Taller Mecánico - Django

Esta es una aplicación web desarrollada con Django para la gestión de un taller mecánico. La aplicación permite administrar **Mecánicos**, **Vehículos** y **Procedimientos** a través de Django Admin.

## Estructura del proyecto

- **Proyecto:** `taller`
- **Apps:**
  - `mecanico` → Gestiona mecánicos (nombre, contacto, especialidad)
  - `vehiculo` → Gestiona vehículos (patente única, modelo, año, dueño)
  - `procedimiento` → Gestiona procedimientos (nombre, descripción, mecánico, vehículo)

## Requisitos

- Python 3.13+
- Django 5.2+
- SQLite (por defecto)

## Instalación

1. Clonar el repositorio:

```bash
git clone <URL_DEL_REPOSITORIO>
cd taller
