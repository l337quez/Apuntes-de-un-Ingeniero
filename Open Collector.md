_Apuntes de un Ingeniero Electronico_

# __Configuracion Open Collector (Colector Abierto)__   

Esta configuracion es muy usada en circuitos digitales, ya que permite generar un pulso bajo a partir de un pulso alto. Usando un transistor tipo NPN el transistor puede caer en estado de saturacion si el voltaje de la base es mayor o igual al voltaje del colector. Cuando esto pasa lo que este conectado en el emisor se refleja en el colector.

Dependiendo del tipo de circuito se este diseñando, la gran mayoria de veces el emisor puede ir conectado a tierra. Si el pulso que entra en la base es igual al del colector, esto hara que la tierra se refleje en el colector y por lo tanto la salidad de la configuacion esta conectada al colector y mostrara un bajo.

En la siguiente figura se puede observar la configuracion Open Collector.



###Comportamiento ante un pulso bajo o alto
Si en la base del transistor, se le inyecta un pulso alto, el transistor caera en estado de saturacion y reflejara (el emisor) GND en el colector.

Cuando se le inyecta un pulso bajo al transistor, el colector enviara un alto.

### Diferencia entre configuracion con PNP y NPN

En una configuracion simple, donde el colector esta conectado a VCC con una resistencia intermedia, el emisor a tierra y la base con otra resistencia. Teniendo en cuenta esta conexion pueden pasar dos cosas diferentes, dependiendo del dopaje del transistor puede ser PNP o NPN.


Un transistor PNP, tendra una salidad en el colector aproximadamente igual a VCC. Si se le inyecta un alto, no pasara nada, pero si se le inyecta un bajo, el colector vera un bajo.

Un transistor NPN,

En resumen puedo decir que a partir de un pulso alto se genera un pulso bajo. Gracias al transistor que tiene esa capacidad de suichar, ahora si en vez de un transistor NPN se coloca un transistor PNP, el transistor suichara unicamente con un pulso bajo y salidad del colector sera un pulso bajo. A diferencia de un transistor NPN, que con un pulso alto en la base genera un pulso bajo (si el emisor esta conectado a tierra).
