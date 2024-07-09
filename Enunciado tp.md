# Propuesta TP DSW

## Grupo
### Integrantes
* 51034 - Baldomá, Valentín 
* 50434 - Fernandez Da Silva, Joaquín Carlos
* 50480 - García, Nicolás
* 47539 - Riquelme, Patricio

### Repositorios
* [frontend app](https://github.com/Patricionrp/dsw-tp-frontend.git)
* [backend app](https://github.com/bullettears/dsw-tp-backend.git)

## Tema
### Descripción
* Se trata de una página web en la que los usuarios pueden visualizar y suscribirse a cursos de su interés. En la misma el administrador es él encargado de la carga de los cursos y de material didáctico.

### Modelo
![imagen del modelo](https://app.diagrams.net/#G1FbT6NLbCBV1oyPs5EaJUjWl8YRRR_ayW#%7B%22pageId%22%3A%22C5RBs43oDa-KdzZeNtuy%22%7D)



## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD User<br>2. CRUD Level<br>3. CRUD Topic<br>4. CRUD Subscription|
|CRUD dependiente|1. CRUD Course {depende de} CRUD Topic<br>2. CRUD Purchase Record {depende de} Subscription / Level|
|Listado<br>+<br>detalle| 1. Listado de Courses filtrado por Topic y/o rango de fechas, muestra => Descripcion - Cantdad de Niveles - Precio Total<br> 2. Listado de Users filtrado por Course, Topic, rango de fechas, muestra ......... => detalle  ......... |
|CUU/Epic|1. Create Course<br>2. Purchase Level|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD User<br>2. CRUD Level<br>3. CRUD Topic <br>4. CRUD Subscription<br>5. CRUD Course<br>6. CRUD PurchaseRecord<br>7. CRUD .......|
|CUU/Epic|1. Create Course
<br>2. Purchase Level<br>3. Purchase Subscription<br>4.Cancel Subscription|


### Alcance Adicional Voluntario

