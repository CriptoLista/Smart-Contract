# Smart-Contract

Sugerencias de optimización

Bucle en la variable dinámica (gravedad baja).

Si el usuario obtiene más depósitos paralelos, su transacción de retiro costará más tarifa de transacción porque el bucle en la variable dinámica se usa en la función 'retirar'.

En caso de exceder el límite de GAS del tamaño de la transacción, el retiro no es posible.

Nota: Este comentario es relevante solo si un usuario crea una cantidad excesiva de depósitos paralelos (más de 100).
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 

Descripción independiente de la funcionalidad del contrato inteligente
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
El contrato inteligente FTMTesnet brinda la oportunidad de invertir cualquier monto en FTM (desde 5 FTM) en el contrato y obtener un retorno de la inversión del 112 % al 564 % entre 14 y 28 días si el saldo del contrato tiene fondos suficientes para el pago.

Todos los dividendos se calculan en el momento de la solicitud y están disponibles para su retiro en cualquier momento o después de que finalice el depósito según los planes.
Cada Depósito posterior se mantiene por separado en el contrato, para mantener el monto del pago de cada Depósito.

Tarifa de propietarios de contratos
Tarifa del proyecto: 10%

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

SEIS PLANES DE INVERSIÓN
------------------------
planes

Regreso trotal

Ganancia diaria

Dias

tiempo de retiro

Tarifa de retiro

1

112%

8%

14

Cualquier momento

5%

2

157,5%

7,5%

21

Cualquier momento

5%

3

196%

7%

28

Cualquier momento

5%

4

193,7%

8%

14

Fin del Plan

10%

5

365,6%

7,5%

21

Fin del Plan

10%

6

564,8%

7%

28

Fin del Plan

10%


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
El depósito mínimo es de 5 FTM
La "Tarifa de retiro" se deducirá del monto a retirar y permanecerá en el contrato, el resto se enviará a la billetera del usuario.
Después del lanzamiento del proyecto, los “Beneficio diario” aumentará un 0,5 % cada día para los nuevos depósitos
El propietario puede restablecer el aumento de la ganancia diaria

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

Bono de retención
--
Los usuarios recibirán una bonificación de ganancias diarias del 0,1% por mantener dividendos y no retirar

La bonificación de retención máxima es del 1,5 %
 

Sistema de referencia (Bono de coincidencia)

El contrato paga una comisión de referencia del 10% en 3 niveles

Nivel 1: 5%
Nivel 1: 3%
Nivel 1: 2%

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
Notas:

La referencia debe ser un usuario activo; significa que la dirección de referencia tiene al menos un depósito
El referente se especifica una vez en el momento del primer depósito y se asigna al usuario sin posibilidad de cambio. De cada depósito subsiguiente, el referente obtendrá su porcentaje
La comisión de referencia se enviará directamente a las billeteras de los usuarios.
