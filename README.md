# Parcial_corte_1

## Herramientas
 - PostgreSQL 13
 - PGAdmin 4

## Estructura del repositorio

El presente repositorio contiene los siguientes archivos:
 - ddl.sql : Este archivo contiene los scripts necesarios para crear las tablas de la base de datos
 - inserts : Este archivo contiene los scripts de los inserts de cada tabla
 - punto1.sql : Contiene los scripts de la funcion y del trigger
 - punto2.sql : Contiebe el script para crear una vista 

## Model de base de datos

Este modelo contiene 8 tablas y una vista, como se muestra a continuacion:
 - Country : Es la tabla que contiene la informacion de los paises
 - City : Es la tabla que contiene la informacion de las ciudades
 - Address : Es la tabla que contiene las direcciones tanto de empleados como de sucursales
 - Branchoffice : Es la tabla que contiene la informacion de las sucursales
 - Department : Es la tabla que contiene la informacion de los departamentos en los que trabajan los empleados
 - Position : Es la tabla que contiene la informacion de los cargos de los empleados
 - Employee : Es la tabla que contiene la informacion de los empleados
 - Empleados_us : Es la vista que contiene la informacion de los cargos por los cuales han pasado los empleados de la sucursa de USA

## Orden de ejecucion

Primero se debe correr el ddl, ya que esta va a crear cada una de las tablas, luego se corre los inserts para llenar las tablas de informacion.
Luego se corre el archivo con nombre "punto1", ya que este va a crear la funcion de persistir la informacion de eventos en la tabla empleyee.
Y por ultimo se corre el archivo que se llama "punto2", el cual va a crear la vista que va a permitir la visualizacion de los cargos por los cuales han pasado cada empleado de una sucursal.
