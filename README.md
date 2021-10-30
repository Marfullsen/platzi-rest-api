# Fundamentos de API RESTful

## ¿Qué es platzi-rest-api?
Repositorio con los ejercicios de la clase de Api REST dictada por Mauro Chojrin.

## Contenidos del curso
- Comprender los objetivos y pre-requisitos del curso\
  1- Qué aprenderás sobre API REST\
  2- Qué es una API y para qué sirve
- Conocer los conceptos principales de REST\
  3- Qué es y cómo funciona el protocolo HTTP\
  4- ¿Qué significa REST? y ¿qué es una API RESTful?
- Aprender a consumir servicios REST\
  5- Cómo realizar una petición REST e interpretar sus resultados
- Aprender a producir servicios REST\
  6- Exponer datos a través de HTTP GET\
  7- Exponer un recurso en particular a través de HTTP GET\
  8- Incorporar datos a través de HTTP POST\
  9- Modificar datos a través de HTTP PUT\
  10- Eliminar datos a través de HTTP DELETE
- Conocer diferentes modos de restringir el acceso a las API Rest\
  11- Autenticación vía HTTP\
  12- Autenticación vía HMAC\
  13- Autenticación vía Access Tokens
- Aprender a tratar errores en la comunicación vía REST\
  14- Manejo de errores de un servicio REST
- Aprender a utilizar una API Rest para la comunicación FrontEnd/BackEnd\
  15- Introducción a Ajax\
  16- Get via Ajax\
  17- Post via Ajax\
  18- Deploy
- Conocer buenas prácticas del diseño de APIs REST\
  19- 7 Buenas prácticas del diseño de APIs RESTful
  
## 7 Buenas prácticas del diseño de APIs RESTful
1. Siempre utiliza sustantivos para nombrar tus recursos.
2. Añade los nombres en plural para las urls.
3. Las modificaciones a recursos deben hacerse con su verbo HTTP correspondiente: POST, PUT o DELETE.
4. Para devolver recursos asociados a otro recurso utiliza url que incorporen subrecursos: /Autos/1/Choferes.
5. Navegabilidad vía vínculos.
6. Cuando devuelvas colecciones deben ser filtrables, ordenables y paginables.
7. Versiona tu API, añade el número de versión en la url: v1/Autos.
