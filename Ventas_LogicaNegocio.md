# Ventas 

## Listado de Entidades

 ### clientes **(ED)**
 - cliente_id **(PK)**
 - nombre 
 - apellidos 
 - telefono
 - email 
 - direccion
 - cp
 - ciudad 
 - pais **(FK)**
 
 ### productos **(EC)**

 - producto_id **(PK)**
 - nombre
 - descripcion
 - foto 
 - precio
 - cantidad

 ### ventas **(ED)**
 
 - venta_id **(PK)**
 - cliente_ id **(FK)**
 - fecha
 - monto
 
 ### articulos_x_venta **(EP)**
 - articulo_id **(PK)**
 - venta_id **(FK)**
 - producto_id **(FK)**
 - cantidad 


 ### paises **(EC)**

 - pais_id
 - nombre
 - dominio

 ## Relaciones