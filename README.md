# Reestructura de nuestro servidor:

Consigna:

Con base en las clases previamente vistas, realizar los cambios necesarios en tu proyecto para que se base en un modelo de capas.

Aspectos a incluir:

- El proyecto debe contar con capas de routing, controlador, dao, con nuestras vistas bien separadas y con las responsabilidades correctamente delegadas.

- Además, mover del proyecto todas las partes importantes y comprometedoras en un archivo .env para poder leerlo bajo variables de entorno en un archivo config.js


Formato:

Link al repositorio de Github para poder clonar, además. adjunto el archivo .env para poder relacionar las variables de entorno.


## Instrucciones:

Instalar dependencias: npm i

Ejecutar: npm start

## Ejemplos:

Vista Home:
GET http://localhost:8080/

Vista de login:
http://localhost:8080/login

Vista de registro:
http://localhost:8080/register

Vista de productos: (protegida)
http://localhost:8080/products

Vista de perfil: (protegida)
http://localhost:8080/profile

Vista de current: (protegida)
http://localhost:8080/current

NOTA: si el usuario ya está logueado, no puede volver a loguearse o registrarse.
En ambos casos el usuario es redirigido a la vista de perfil.

## Sistema de roles:

Rol de administrador:

- Usuario: adminCoder@coder.com
- Contraseña: adminCod3r123
