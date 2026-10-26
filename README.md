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

## Historial de unidades y entregas

### Unidad 1 — Portafolio estático (HTML + Tailwind)

- [Práctica 1 — Código en GitHub](https://github.com/MannArvizuMartinOsiel)
- [Práctica 2 — Código en GitHub](https://github.com/MannArvizuMartinOsiel)
- [Práctica 2 — Sitio en Render](https://ine-personal-moma.onrender.com/)

### Unidad 2 — App Django + MySQL en Render

- [Código de la Unidad 2 en GitHub](https://github.com/MannArvizuMartinOsiel)

*El portafolio marca el sitio de Render de esta unidad como pendiente.*

### Unidad 3 — Gestión de servicios (Django)

- [Código de la práctica U3S5 en GitHub](https://github.com/MannArvizuMartinOsiel)
- [Sitio de la práctica U3S5 en Render](https://u3s5-mannarvizu-martiosiel.onrender.com/)
- [Código de la práctica U3S6 en GitHub](https://github.com/MannArvizuMartinOsiel)
- [Sitio de la práctica U3S6 en Render](https://u3s6-mann-arvizu-martinosiel.onrender.com/)

### Unidad 4 — Proyecto integrador final

- [Práctica 1 — Código en GitHub](https://github.com/MannArvizuMartinOsiel)
- [Práctica 1 — Sitio en Render](https://u4s7-mann-arvizu-martin-osiel.onrender.com/)
- [Práctica 2 — Código en GitHub](https://github.com/MannArvizuMartinOsiel)
- [Práctica 2 — Sitio en Render](https://u4s8-mann-arvizu-martin-osiel.onrender.com/)

## Datos académicos

- **Asignatura:** Aplicaciones Web
- **Unidad:** Unidad 4
- **Actividad:** Práctica 8
- **Tema:** Deployment final y defensa oral en vivo
- **Autor:** Martin Osiel Mann Arvizu
- **Institución:** Universidad Tecnológica de Hermosillo
- **Grupo:** 4-1
