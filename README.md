# Smart-Contract

Sugerencias de optimización

Bucle en la variable dinámica (gravedad baja).

Si el usuario obtiene más depósitos paralelos, su transacción de retiro costará más tarifa de transacción porque el bucle en la variable dinámica se usa en la función 'retirar'.

En caso de exceder el límite de GAS del tamaño de la transacción, el retiro no es posible.

Nota:

Este comentario es relevante solo si un usuario crea una cantidad excesiva de depósitos paralelos (más de 100).
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 

Descripción independiente de la funcionalidad del contrato inteligente

El contrato inteligente FTMTesnet brinda la oportunidad de invertir cualquier monto en FTM (desde 5 FTM) en el contrato y obtener un retorno de la inversión del 112 % al 564 % entre 14 y 28 días si el saldo del contrato tiene fondos suficientes para el pago.

Todos los dividendos se calculan en el momento de la solicitud y están disponibles para su retiro en cualquier momento o después de que finalice el depósito según los planes.
Cada Depósito posterior se mantiene por separado en el contrato, para mantener el monto del pago de cada Depósito.
