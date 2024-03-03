# e-commerce Chapter-One

Este proyecto surge como la culminación de nuestro aprendizaje en Mindhub como Desarroladores full Stack Java. La motivación principal fue integrar nuestros conocimientos individuales y abordar una necesidad real mediante el desarrollo de una aplicación web colaborativa.

## Trabajo en Equipo

Desarrollado por un equipo multidisciplinario, este proyecto destaca nuestra capacidad para colaborar eficientemente. Cada miembro aportó habilidades únicas, lo que enriqueció el proceso de desarrollo y fomentó una dinámica de equipo sólida.


## Tecnologías Utilizadas

#### ** Front-end:**
- HTML
- CSS
- JavaScript
- Vue.js
- Boostrap

#### Back-end:
 - Java
 - Spring Boot
 - Hibernate
 - Gradle 
  Base de Datos: PosgreSql

## Funcionalidades
 La aplicacion te permite crear usuarios: uno para los clientes y otro para los administradores.
 los clientes pueden ver todos los libros que esten cargados en la libreria, con su respectivo stock. Pueden agregarlos al carrito y modificar la cantidad de libros en el mismo para luego poder realizar la compra. Tambien existe un registro de las compras que fue realizando el cliente.
 Por otro lado el admin puede modificar el stock de los libros y agregar nuevos.

##EndPonits
#### **Books**
- GET: /api/books
- POST: /api/books
- POST:  /api/books/addStock

#### **ClientBook**
- POST: /api/clientBook
- POST:  /api/books/delete

#### **Client**
- GET: /api/clients
- POST: /api/clients
- GET:  /api/books/current

#### **orderDetail**
- POST: /api/orderDetail
- GET:  /api/orderDetail/orderDetail/{id}

#### **orderDetail**
- GET: /api/orderTotal/{id}
