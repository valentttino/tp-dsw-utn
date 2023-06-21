# Propuesta TP DSW

## Grupo
### Integrantes

* 49704 - Boggio, Valentino.
* 49687 - Dominio, Constanza.
* 50556 - Gutiérrez, Ramiro.
* 48947 - Sarkissian, Milton.

### Repositorios
*No realizado aún*
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
Se pretende crear un sitio web para una ONG que realiza distintas actividades en las que se relacionan administradores (Jefes de grupos) con voluntarios. A su vez se cuenta con suscriptores parciales que reciben información sobre la página en general.

### Modelo
![imagen del modelo](https://github.com/valentttino/tp-dsw-utn/blob/main/MD.jpeg)

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Administrador<br>2. CRUD Voluntario<br>3. CRUD Actividad<br>4. CRUD Grupo|
|CRUD dependiente|1. CRUD Informe {depende de} CRUD Actividad<br>2. CRUD Encuesta {depende de} CRUD Actividad|
|Listado<br>+<br>detalle| 1. Listado de actividades disponibles, muestra título, descripción y fecha de inicio => detalle CRUD Actividad<br> 2. Listado de ranking de porcentajes, muestra los porcentajes de aquellos que accedan a la categoría Administrador, título y fecha incio de la actividad => detalle CRUD Encuesta y CRUD Actividad|
|CUU/Epic|1. Realizar inscripción a una actividad<br>2. Consultar resultados de una encuesta post finalización de una actividad|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Administrador<br>2. CRUD Voluntario<br>3. CRUD Actividad<br>4. CRUD Grupo<br>5. Encuesta<br>6. Suscriptor<br>7. Informe<br>8. Newsletter|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|
