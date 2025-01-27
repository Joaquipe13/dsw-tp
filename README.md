# Propuesta TP DSW

## Grupo
### Integrantes
* 50434 - Fernandez Da Silva, Joaquín Carlos


### Repositorios

* [Nuevo repositorio de Backend](https://github.com/Joaquipe13/TP-DSW-Backend.git)
* [Nuevo repositorio de Frontend](https://github.com/Joaquipe13/TP-DSW-Frontend.git)

## Tema
### Descripción
* Se trata de una página web en la que los usuarios pueden visualizar y suscribirse a cursos de su interés. En la misma el administrador es él encargado de la carga de los cursos y de material didáctico.

### Modelo
* [Modelo de Dominio](https://drive.google.com/file/d/1qR9otqCTNsJ8Rc4ZEshNRn3iVKGQfjGd/view?usp=sharing)



## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD User<br>2. CRUD Topic|
|CRUD dependiente|1. CRUD Course {depende de} CRUD Topic|
|Listado<br>+<br>detalle| 1. Listado de Courses filtrado por descripcion parcial Descripcion - Cantdad de Niveles - Precio Total => detalle  muesta Crud Course |
|CUU/Epic|1. Create Course|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD User<br>2. CRUD Topic<br>3. CRUD Course <br>4. CRUD Level<br>5. CRUD Unit<br>6. CRUD CoursePurchaseRecord|
|CUU/Epic|1. Create Course<br>2. Purchase Course|


Alcance Adicional Voluntario
|Req|Detalle|
|:-|:-|
|Listados|1. Listado de CoursePurchaseRecords filtrado por: rango de fechas muestra id, Subscription duration, Subscription description, User name, purchaseAt, activeAt, totalAmount<br> 2. Listado de CoursePurchaseRecords filtrado por: rango de fechas muestra id, title, User name, purchaseAt, totalAmount => detalle  muesta Crud Course|
|CRUD |1. CRUD Subscription<br>2. CRUD SubsPurchaseRecord|
|CUU/Epic|1. Create Subscription<br>2. Purchase Subscription|
|Otros|1. Envío de confirmación de compra por email|
