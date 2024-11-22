DESCRIPCION DE LA SOLUCION PLANTEADA:

Se dispone de informacion relevante de pedidos realizados,
de los cuales se necesita realizar ciertos procedimientos para cada grupo
considerando como grupo 1 a los pendientes y al grupo 2 a los completados,
dentro del grupo 1 se validaron los montos de los items con los montos del 
pedido, con la finalidad de verificar la integridad de informacion, registrando
en un arreglo los que tienen incoherencia de datos.

Luego de ello se genero un archivo CSV del pedido con el numero de items y
se calculo el monto total y promedio de los pedidos pendientes con la finalidad de disponer
mas metricas que nos ayuden a alguna toma de desicion.

Por ultimo se identifico al cliente con mayor monto de pedidos completados,
posiblemente con la finalidad de brindarle mas importancia para su pedido pendiente
y luego se registro al cliente en un archivo JSON.

En conslusion, considero que se realizo un estudio de los pedidos que estan pendientes
e identificar a los clientes que tuvieron pedidod completados con montos altos
para identificar a que clientes se le debe brindar la prioridad de atencion para sus pedidos
pendientes, asimismo de tener un registros de los calculos de montos identificados para una
correcion de informacion evitando afectar de manera negativa al cliente y a la empresa.
