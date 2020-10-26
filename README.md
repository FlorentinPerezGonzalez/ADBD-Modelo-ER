# Restricciones y consideraciones a contemplar.
- En la entidad ***Viveros***, se debe garantizar que el atributo *Hora Apertura* sea menor que *Hora Cierre*.
- En la relación ***trabajan***, se debe garantizar que *Fecha Inicio* sea menor que *Fehca Fin*.
- La entidad ***Pedido*** es débil con respecto a ***Cliente***.
- El atributo ***Gasto mensual*** de ***Cliente*** se calcula a través del importe de los pedidos que este realiza.
- El atributo ***Bonificación*** de ***Cliente*** se calcula a través del  atributo ***Gasto mensual***.
- El atributo ***Stock*** de ***Productos*** parte de un valor inicial y se actualiza en función de los pedidos que se realicen.
