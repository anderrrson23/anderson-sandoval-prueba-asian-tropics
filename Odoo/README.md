Propuesta 1: Primero se debe registrar la informacion de: Medio por el cual se entero y comentarios, en la ficha de clientes en el modulo de contactos.Luego se debe de crear un informe en el modulo de compras, este se debe filtrar por la fecha del dia que se quiere reportar y por medio de la relacion del partner se jala la informacion de los campos que se llenan en la ficha del cliente y los campos relacionados a la compra como: No de SO, cantidad de lineas de pedido. Tiempo estimado 5 dias.

Se ilustran a continuaicon las columnas que tendria el reporte: 


Partner | Fecha De Visita | No de SO |Cantidad de compras | Medio por el que se entero | Comentarios 



Propuesta 2: Para ello se utiliza el correo de la ficha de cliente, cuando la SO pasa de estado "A Facturar" hacia "Facturado" se puede crear una funcion con el decorato @api.onchange y que al momento que cambie el estado se ejecute una funciona que envia la encuesta al cliente por medio de su correo electronico. Tiempo estimado: 2 dias.


Propuesta 3: Para esto se debe utilizar los modulos de flota, este modulo brinda el odometro para registrar los viajes y el combustible que se gasta por unidad, asi como tambien se pueden registrar los mantenimientos por unidad y se debera crear un funcion que use la API externa de odoo para realizar una peticion al sistema alojado en Azure por medio de request y que este devuelva la informacion de cada unidad y actulice de manera automatica.  Tiempo estimado: 1 semana.