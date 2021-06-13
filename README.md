# TP8 Back

### Consigna Spring Boot parte 2 (Calculador para calendario de siembra)

Modificar la consigna anterior ( [TP 7 Back](https://github.com/elioflo/SiembraAPI) ) de la siguiente forma:

1. Integrar MySQL al proyecto actual.
2. Crear una tabla "Especie" que represente a la tabla indicada en la consigna anterior, pero esta vez con id.
3. Usar la especificación JPA para tomar datos de dicha tabla.
4. Crear un repositorio para disponer del método correspondiente para traer el registro de la tabla pedido.
5. Crear un servicio para alojar la lógica de negocio de la aplicación en un método.
6. Modificar el método de la consigna anterior a un controlador, pero esta vez los parámetros de entrada deben ser el id (mirar nueva tabla), más el ancho y largo de sembrado.
7. La respuesta debe ser la misma que en el caso anterior (JSON).

En esencia, debe reemplazarse el listado hardcoding por datos populados en la bbdd y crearse un modelo con repositorio, servicio y controlador manteniendo la funcionalidad núcleo de la consigna anterior.
