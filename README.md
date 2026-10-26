# Práctica 8 — Deployment final y defensa oral en vivo

## Descripción del proyecto

Aplicación web desarrollada con Django que permite administrar servicios mediante operaciones de consulta, creación, edición, eliminación y búsqueda. El proyecto utiliza autenticación de usuarios y una base de datos MySQL.

Esta entrega corresponde a la Unidad 4, Semana 8, de la asignatura Aplicaciones Web. Su objetivo es publicar la versión final de la aplicación, comprobar su funcionamiento y preparar la defensa oral.

## Portafolio académico

- **Portafolio completo:** https://portafolio-moma-evtx.onrender.com/
- **Proyecto integrador en vivo — INE Personal MOMA:** https://u4s7-mann-arvizu-martin-osiel.onrender.com/

## Tecnologías utilizadas

- Python
- Django
- MySQL en la nube mediante Aiven
- Tailwind CSS
- Gunicorn
- Render
- Git y GitHub

## Funcionalidades principales

- Registro e inicio de sesión de usuarios.
- Consulta de servicios registrados.
- Creación, edición y eliminación de servicios.
- Búsqueda de servicios por título.
- Paginación de resultados.
- Acceso a funciones protegidas mediante autenticación.

## Base de datos y despliegue

La aplicación utiliza MySQL mediante Aiven. Las credenciales de conexión y demás configuraciones sensibles deben gestionarse mediante variables de entorno.

El despliegue se realiza en Render, donde se instalan las dependencias, se recopilan los archivos estáticos y se ejecutan las migraciones de Django.

- **Portafolio publicado:** https://portafolio-moma-evtx.onrender.com/
- **Aplicación de la Práctica 8:** https://u4s8-mann-arvizu-martin-osiel.onrender.com/
- **Repositorio de la Semana 7:** https://github.com/MannArvizuMartinOsiel/u4s7-Mann-Arvizu-Martin-Osiel
- **Repositorio de la Semana 8:** https://github.com/MannArvizuMartinOsiel/u4s8-mann-arvizu-martin-osiel

## Pruebas de funcionamiento

- Verificar que la aplicación abra mediante HTTPS.
- Comprobar el inicio de sesión y el acceso a las páginas protegidas.
- Crear, consultar, editar y eliminar servicios.
- Verificar la búsqueda y la paginación.
- Comprobar que cada usuario solo pueda consultar sus propios servicios.
- Confirmar que los datos se conserven en la base de datos de producción.

## Versión final

La entrega final se identifica con la etiqueta de Git `v1.0` y su correspondiente publicación en GitHub Releases.

**Enlace del Release:** AGREGAR URL DEL RELEASE `v1.0` CUANDO ESTÉ PUBLICADO.
## Descripción de las unidades

- **Unidad 1. Análisis y planeación del proyecto:** Se definió la idea general del sistema, su propósito, los objetivos y los requerimientos principales para orientar su desarrollo.

- **Unidad 2. Diseño del sistema:** Se estableció la estructura del sistema, incluyendo el diseño de la base de datos, las entidades, sus relaciones y la organización de sus componentes.

- **Unidad 3. Desarrollo e implementación:** Se desarrollaron las funcionalidades principales utilizando Django, se integró la base de datos MySQL y se realizaron pruebas para comprobar el funcionamiento del sistema.

- **Unidad 4. Despliegue y mantenimiento:** Se preparó el proyecto para su publicación en línea, se configuraron los servicios necesarios para su funcionamiento y se documentaron aspectos de mantenimiento, respaldo y entrega de la versión final.
