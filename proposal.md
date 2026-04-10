# Propuesta TP DSW

## Grupo
### Integrantes
* 49718 - Passe Alejo
* 52824 - Pinatti Sebastián
* 48881 - Calderon Bruno
* 54343 - Cordoba Santiago

### Repositorios
* [fullstack app](https://github.com/AlejoPasse/TpDesarrollo.git)

## Tema
### Descripción
Es un sistema de gestión de un gimnasio. El sistema admite dos tipos de usuarios, clientes y administradores, los clientes pueden tener una membresía, registrar asistencia, inscribirse a clases y seguir una o varias rutinas. Por otro lado, el Administrador es quien gestiona el contenido del sistema, asignando o administrando rutinas, ejercicios y/o clases.

### Modelo
![imagen del modelo](ModeloE-R.png)

## Alcance Funcional 

### Alcance Mínimo

|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Usuario<br>2. CRUD Rutina<br>3. CRUD Ejercicio<br>4. CRUD Membresía|
|CRUD dependiente|1. CRUD Precio {depende de} CRUD Membresía<br>2. CRUD Asistencia {depende de} CRUD Usuario|
|Listado<br>+<br>detalle| 1. Listado de registro de asistencia => detalle muestra todas las asistencias del cliente<br> 2. Listado de ejercicios que puede ver el adminisitrador para agregar a rutinas => detalle muestra una lista de ejercicios disponibles al administrador para que pueda armar rutinas personalizadas|
|CUU/Epic|1. Obtener listado de rutinas de un cliente<br>2. Adquirir una membresía como cliente|

### Alcance Aprobación

|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Usuario<br>2. CRUD Rutina<br>3. CRUD Ejercicio<br>4. CRUD Membresía<br>5. CRUD Clases<br>6. CRUD Precio<br>7. CRUD Asistencia|
|CUU/Epic|1. Obtener listado de rutinas de un cliente<br>2. Adquirir una membresía como cliente<br>3. Gestionar rutina como adminisitrador<br>4. Inscribirse a una clase|


### Alcance Adicional Voluntario

|Req|Detalle|
|:-|:-|
|Listados |1. Historial de precios de cada plan de membresía<br>2. Historial de membresías|
|CUU/Epic|1. Darse de baja de una clase<br>2. Gestionar clase como administrador|
|Otros|1. Envío de advertencia de vencimiento membresía por email|

