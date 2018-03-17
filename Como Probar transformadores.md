_Apuntes de un Ingeniero Electronico_

# __Como Probar Transformadores__   

Para probar un transformador es necesario conocer
el devanado primario y asi saber cuales son las
bobinas que vamos a conectar directamente al enchufe. Ahora bien, si no sabemos cual es el
devanado primario y se conecta el secundario, es
posible que se dañe el transformador, antes que nada, vamos a proceder a medir, para conocer
cuantas bobinas hay en el devanado secundario.

***Nota:*** Los transformadores no tienen un orden, asi es
que es posible que el devanado primario este de
un lado junto con otras bobinas del devanado secundario.



### Pruebas

#### Prueba 1: Medir continuidad

Para esta primera prueba, colocamos el multimetro
en continuidad, luego identificamos las bobinas del
transformador. Para prevenir algun daño, debemos medir la continuidad entre las chapas del transformador y las bobinas, no deberia tener continuidad. si la tiene, el transformador esta desgastado y es mejor no conectarlo.


#### Prueba 2: Medir impedancia de las bobinas

El bobinado del devanado primario tiene un alambre
mas finito que el del devanado secundario. La impedancia del devanado primario debe ser grande,
si la impedancia marca 0, esto quiere decir que esta abierto.

#### Prueba 3: Uso del probador Serie

El probador serie es una bobilla conectada en Serie
que se va conectar en el devanado primario y el bombillo no debe encender, si por equivocacion se conecta en el secundario el bombillo encendera, es otra manera de saber cual es el devanado primario.

**El bombillo encendera** cuando se conecte los terminales en uno de los devanados secundarios.

**El bombillo no encendera** cuando se conecte en el devanado primario. Para asegurar que todo funcione bien, unimos una de las bobinas del devanado secundario y el bombillo deberia prender.

Una vez conocido el devanado primario, mediante el circuito serie, procedemos a unir los cables de las bobinas del devanado secundario y verificamos que la bombilla enciende, esto nos indica que todo esta trabajando bien.

### Precauciones
Asegurese de seguir cada uno de los pasos mensionados.

No conecte El transfomador en directo, a pesar que se pueda apreciar con el tester que sea la bobina con mayor impedancia y el calibre del cable sea el mas fino, lo ideal es usar el probador con el bombillo en serie, de esta manera estaremos totalmente seguros.

Existen Transformadores, igualadores, elevadores y reductores. Por lo general se usan los reductores. En caso en que el transformador sea de 220VAC en el primario y lo conectes a 110VAC, lo que va ocurrir es que si en la salia deberia dar 12VAC, con 110VAC dara una salida 6VAC, es decir el voltaje se reduce la mitad. Ahora si ocurre lo contrario, se conecta un transformador de 110VAC a 220VAC, el transformador sin dudas se va quemar y sonara un pequeño estallido.

Los transformadores de 110VAC por lo general en su devanado primario tienen muchas vueltas y el calibre del alabre es fino. Ahora en los transmadores de 220VAC el alabre es un poco mas grueso, para soportar mas voltaje. Por lo tanto, preferiblemente pruebe su transformador en 110VAC.

<p align="center"><img src="https://github.com/l337quez/Apuntes-de-un-Ingeniero-Electronico/blob/master/images/Trafo/test.png"></p>  

Como se observa en la figura si conectamos el enchufe a 110v en serie al transformador y lo conectamos correctamente en el devanado primario, cuando hagamos contacto en el devanado secundario la lampara va a encender.

### Transformadores con derivacion Central o TAP Central

Existen transformadores con TAP Central, este consta de 3 cables que tienen continuidad entre si. en donde el cable denominado como TAP permite obtener la mitad de voltaje que tiene los otros dos cables. Es decir si toma el cable de TAP y otro de los cables el voltaje sera la mitad. Los transformadores con TAP son usados en los circuitos inversores de voltaje.
