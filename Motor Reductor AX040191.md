_Apuntes de un Ingeniero Electronico_
<br>
⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅⋅

# __Motor Reductor ASMO AX040191__   

Este motor reductor es usado en las fotocopiadoras, funciona con 24v, eso no
quiere decir que con 5v no funcione, pero si energizas el motor con 5v la potencia
va ser menor.

El conector de este motor tiene 5 pines de los cuales los dos primeros son alimentacion
GND y VCC, los demas son pines que dan informacion de la posicion del motor. No tiene
un sensor de efecto hall, ni una dbobina, simplemente tiene unas lineas estañadas
y cuando dos de los conectores hacen contacto nos dice donde en que posicion se
encuentra el eje del motor.


En la imagen podemos observar que hay 3 lineas, cada linea corresponde a cada uno e los pines. Hay una linea que es continua, las otras dos solo tienen 4 intervalos.

Dependiendo de la logica que estemos usando el pin 4 debe ser VCC o GND y los pines 3 y 5 seran pines de salida, cuando hagan contacto enviara un pulso.


<p align="center"><img src="https://github.com/l337quez/Apuntes-de-un-Ingeniero-Electronico/blob/master/images/MOTORRASMO/PINES.jpg"></p>  

Como se observa en la figura si conectamos el enchufe a 110v en serie al transformador y lo conectamos correctamente en el devanado primario, cuando hagamos contacto en el devanado secundario la lampara va a encender.

### Como saber la posicion del eje del Motor

Gracias a los dos PINES 3 y 5, podremos conocer el que angulo esta el eje del motor. El PIN 5 es mas exacto ya que la distancia de contacto es menor, podremos saber si esta a 0°,90°,180°,360°.

En la siguiente Figura se muestra el piñon que tiene los contactos donde el contacto mas cerca del eje es el que es continuo, donde se puede conectar VCC o GND.

<p align="center"><img src="https://github.com/l337quez/Apuntes-de-un-Ingeniero-Electronico/blob/master/images/MOTORRASMO/contacto.jpg"></p>  
