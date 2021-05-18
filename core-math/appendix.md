# Dentro de ENEX

### Swaps y fondos de liquidez 

**Conceptos básicos**

DEX está diseñado para el intercambio de activos digitales. Los activos se intercambian dentro de grupos de liquidez independientes. Solo puede existir un grupo para cada par. La tarifa por operaciones de cambio en el grupo se establece automáticamente en el momento de la creación. Cualquier usuario puede crear grupos, agregar liquidez a los grupos existentes, eliminar la liquidez agregada anteriormente e intercambiar activos. Cada operación se realiza llamando al contrato inteligente correspondiente.

 Como la relación puede cambiar durante la ejecución de la transacción de liquidez adicional, usted fija el monto de un activo y determina los límites del otro. Entonces, en este ejemplo, puede transferir **20 $ ENX y 201.72 $ ENQ.**

### Space Drops

**Conceptos básicos**

Pools es un mecanismo para recompensar a los usuarios que apuestan $ ENX con activos arbitrarios. El grupo puede ser creado por cualquier usuario. Una vez creado el grupo, puede llenarse con activos y se pueden poner en juego $ ENX. Siempre que el grupo tenga activos y haya $ ENX en juego, todas las partes interesadas son recompensadas con activos proporcionalmente a sus participaciones. La recompensa distribuida por tiempo la configura el creador del grupo. Cada actor puede realizar cualquier acción con su participación \(aumentar, disminuir o quitar\) o recibir recompensa en cualquier momento.

Puede pensar en una piscina como una piscina real que se llena con agua que sale del depósito, donde el agua representa un activo, la piscina representa $ ENX apostados, el depósito representa la cantidad de activo a distribuir y el diámetro del fregadero representa la recompensa por bloque. El agua se derramará siempre que el depósito no esté vacío. Cuanto mayor sea el área de la piscina, más lento aumentará el nivel del agua.

Al principio no hay estacas \(el área de la piscina es cero\), por lo que no sale agua del depósito \(el activo no se gasta\). Cuando aparece la primera apuesta, el área de la piscina se vuelve igual a su tamaño. Por ejemplo, la apuesta es 10 $ ENX.

El agua comienza a fluir \(las recompensas se agregan a la participación\), el nivel del agua aumenta y el volumen de agua en el depósito disminuye \(el activo es gasto\). Si la recompensa por bloque es 1 ficha por bloque, entonces water\_level es 10 unidades después de 100 bloques.

El tamaño de la recompensa está representado por el volumen de agua y se puede calcular como participación  _nivel\_agua. En nuestro ejemplo, **A** recompensa es 10_  10 = 100 tokens.

En el bloque 100 se agregan dos estacas \(**B** y **C**\) 10 $ ENX cada una al fondo común. A partir de este momento, la nueva recompensa debe compartirse entre las tres apuestas. Pero las nuevas apuestas no deberían afectar la recompensa **A**. Así que aumentamos el área de nuestra piscina, pero damos pasos al nivel actual del agua.

Entonces, después de 300 bloques más, se distribuirán 300 tokens sobre la nueva participación, y el agua aumentará en 300/30 = 10 unidades y será 20.

Entonces, **A** recompensa será 10  _20 = 200, mientras que la recompensa **B** y **C** será 10_  10 cada una.

Si se elimina la participación **A**, la recompensa **A** \(representada por la columna de agua sobre el área **A**\) se mueve al equilibrio de las partes interesadas. Recibir una recompensa mientras se deja la participación es equivalente a eliminar la participación y volver a agregarla, y se puede realizar en una operación de forma transparente para las partes interesadas.



### 

### 



