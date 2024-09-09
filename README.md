# Django-React-CRUD

Este proyecto es una aplicación CRUD (Crear, Leer, Actualizar, Eliminar) que utiliza Django para el backend y React para el frontend. Está diseñada para gestionar libros y permite realizar operaciones básicas sobre ellos mediante una API REST.

## Estructura del Proyecto

El proyecto está dividido en dos partes principales:

1. **Backend (Django)**: 
   - Carpeta: `server/newproject/`
   - Funciona como un servidor REST con Django, manejando las solicitudes CRUD.
   - Archivos importantes:
     - `asgi.py`: Configuración de ASGI para el despliegue.
     - `settings.py`: Configuración general del proyecto Django.
     - `urls.py`: Mapea las rutas de la API.
     - `wsgi.py`: Configuración de WSGI para el despliegue.

2. **Frontend (React)**: 
   - Carpeta: `client/`
   - Interfaz de usuario donde los usuarios pueden interactuar con la aplicación. Realiza peticiones a la API de Django para crear, leer, actualizar y eliminar libros.

## Requisitos

- **Python 3.10+**
- **Django 4+**
- **Node.js 16+**
- **npm o yarn** (gestor de paquetes para el frontend)
  
## Instalación

### Clonar el repositorio

```bash
git clone https://github.com/aron15951/Django-React-CRUD.git
cd Django-React-CRUD

