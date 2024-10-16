# Propuesta TP DSW

## Grupo
### Integrantes
* 51034 - Baldomá, Valentín 
* 50434 - Fernandez Da Silva, Joaquín Carlos
* 50480 - García, Nicolás


### Repositorios

* [Backend app](https://github.com/nicolasgcode/dsw-tp-backend.git)
* [Antiguo repositorio de frontend app](https://github.com/Patricionrp/dsw-tp-frontend.git)
* [Nuevo repositorio de frontend](https://github.com/nicolasgcode/courseapp-front.git)

## Tema
### Descripción
* Se trata de una página web en la que los usuarios pueden visualizar y suscribirse a cursos de su interés. En la misma el administrador es él encargado de la carga de los cursos y de material didáctico.

### Modelo
* [Modelo de Dominio](https://app.diagrams.net/#G1FbT6NLbCBV1oyPs5EaJUjWl8YRRR_ayW#%7B%22pageId%22%3A%22C5RBs43oDa-KdzZeNtuy%22%7D)



## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD User<br>2. CRUD Level<br>3. CRUD Topic<br>4. CRUD Subscription|
|CRUD dependiente|1. CRUD Course {depende de} CRUD Topic / Level<br>2. CRUD Purchase Record {depende de} CRUD Subscription / Course|
|Listado<br>+<br>detalle| 1. Listado de Courses filtrado por descripcion parcial => Descripcion - Cantdad de Niveles - Precio Total<br> 2. Listado de Users filtrado por Course, Topic, rango de fechas, muestra ......... => detalle  ......... |
|CUU/Epic|1. Create Course<br>2. Purchase Course|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD User<br>2. CRUD Level<br>3. CRUD Topic <br>4. CRUD Subscription<br>5. CRUD Course<br>6. CRUD PurchaseRecord<br>7. CRUD .......|
|CUU/Epic|1. Create Course<br>2. Purchase Level<br>3. Purchase Subscription<br>4.Cancel Subscription|


### Alcance Adicional Voluntario

...
