# Guía de Instalación y Despliegue - Aplicación Web de Banesco

Esta guía te ayudará a montar y ejecutar la aplicación web de Banesco localmente en tu máquina.

## Requisitos Previos

- MySQL Workbench
- [Node.js](https://nodejs.org/) y [npm](https://www.npmjs.com/) (para el frontend)
- [Python](https://www.python.org/) y pip (para el backend)

## Pasos para Montar la Aplicación

### 1. Configuración de la Base de Datos

Ejecuta el siguiente script utilizando MySQL Workbench para configurar la base de datos:

bash

`/path/to/MySQL/Banesco.sql`

### 2. Configuración del Backend

Ejecuta el script de Python para habilitar el backend. Asegúrate de instalar las dependencias requeridas usando `pip` si aún no están instaladas:

bash

`$ pip install flask flask_mysqldb flask_cors $ python /path/to/Innova/flask-back_end/flask-back-end/App.py`

### 3. Configuración del Frontend

Inicia el frontend ejecutando el siguiente comando dentro de la carpeta `react-front_end`:

bash

`$ cd /path/to/react-front_end $ npm install   # Instalar dependencias (si aún no lo has hecho) $ npm start     # Iniciar la aplicación`

## Accediendo a la Aplicación

Una vez que hayas completado los pasos anteriores, puedes acceder a la aplicación web desde tu navegador ingresando la siguiente URL:

arduino

`http://localhost:3000`

¡Listo! Ahora deberías tener la aplicación de Banesco funcionando localmente en tu máquina.
