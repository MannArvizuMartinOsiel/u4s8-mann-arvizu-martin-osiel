# Proyecto Web — Práctica 8

## Descripción del proyecto

Aplicación web desarrollada con Django que permite a los usuarios administrar sus servicios registrados. Incluye funcionalidades para consultar, crear, editar, eliminar y buscar servicios, con acceso mediante autenticación de usuarios.

Este proyecto corresponde a la entrega final de la Unidad 4, Semana 8: Deployment final y defensa oral en vivo.

## Tecnologías utilizadas

- **Python:** lenguaje de programación.
- **Django:** framework para el desarrollo web.
- **MySQL:** sistema gestor de base de datos.
- **Aiven:** servicio de base de datos MySQL en la nube.
- **Tailwind CSS:** estilos y diseño de la interfaz.
- **Gunicorn:** servidor de aplicaciones para producción.
- **Render:** plataforma de despliegue.
- **Git y GitHub:** control de versiones y almacenamiento del código fuente.

## Funcionalidades

- Registro e inicio de sesión de usuarios.
- Consulta de servicios registrados.
- Creación de nuevos servicios.
- Edición de servicios existentes.
- Eliminación de servicios.
- Búsqueda de servicios por título.
- Paginación de resultados.
- Separación de los servicios según el usuario autenticado.

## Aplicación desplegada

**URL de producción:** [AGREGAR AQUÍ LA URL DE RENDER]

## Requisitos para ejecutar el proyecto localmente

- Python instalado.
- Git instalado.
- Acceso a una base de datos MySQL.
- Archivo `requirements.txt` con las dependencias del proyecto.

## Instalación local

1. Clonar el repositorio:

   ```bash
   git clone URL_DEL_REPOSITORIO
   ```

2. Entrar en la carpeta del proyecto:

   ```bash
   cd NOMBRE_DE_LA_CARPETA
   ```

3. Crear y activar un entorno virtual.

   En Windows:

   ```powershell
   python -m venv venv
   .\venv\Scripts\Activate.ps1
   ```

4. Instalar las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

5. Configurar las variables de entorno necesarias para Django y la conexión a MySQL.

6. Aplicar las migraciones:

   ```bash
   python manage.py migrate
   ```

7. Iniciar el servidor local:

   ```bash
   python manage.py runserver
   ```

8. Abrir `http://127.0.0.1:8000/` en el navegador.

## Base de datos

El proyecto utiliza MySQL mediante Aiven. Las credenciales y los datos de conexión se configuran mediante variables de entorno para evitar incluir información sensible en el repositorio.

## Seguridad y aislamiento de usuarios

La aplicación requiere autenticación para acceder a las funciones protegidas. El aislamiento de usuarios debe comprobarse iniciando sesión con dos cuentas diferentes y verificando que cada una pueda consultar y administrar únicamente los servicios que le corresponden.

## Despliegue

La aplicación se publica en Render utilizando Gunicorn. Durante el proceso de despliegue se instalan las dependencias, se recopilan los archivos estáticos y se aplican las migraciones de la base de datos.

Las variables de entorno se configuran desde el panel de Render.

## Historial de trabajo

- **Semana 7:** desarrollo y pruebas de la aplicación web.
- **Semana 8:** preparación de la entrega final, despliegue en producción, pruebas de funcionamiento y publicación de la versión final `v1.0`.

## Autor

**Nombre:** Martin Osiel Mann Arvizu

**Asignatura:** Aplicación Web

**Actividad:** Unidad 4 — Semana 8

**Entrega:** Deployment final y defensa oral en vivo

