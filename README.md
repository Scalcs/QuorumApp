# QuorumApp


Sistema simple para el recuento de congresales integrado con el webhook Eventbrite

![alt text](http://bucket1.glanacion.com/anexos/fotos/59/2122959.jpg)


QuorumApp es un sistema desarrollado para su uso en congresos en los que se necesite realizar un recuento de presentes.
El funcionamiento es bastánte básico ya que lo único que se hace es leer el archivo contador cada 3 segundos y actualizar por AJAX
el contador en caso de que haya cambios y mostrar o no el estado de quorum.

El contador se actualiza en base a la integración con la plataforma Eventbrite, utilizando el webhook que la misma brinda y envia una 
petición POST cada vez que algún congresal entra o sale, esto mismo controlado por el scanneo de códigos QR las credenciales de los 
participantes. Esto se realiza por medio de la aplicación Eventbrite Organiser.

El sistema ya fue utilizado en la práctica demostrando que cumple su función, pero dejó en claro que necesita mejoras de optimización
y control para evitar que sea usado con malas intenciones.

El aspecto de la página web está basado en la pantalla que se puede ver en el Congreso de la Nación- Argentina.



<b> Cosas que faltan: </b>

-Hacer el aspecto adaptable a más pantallas, en el momento solo está adaptado a la computadora que fue utilizada en el congreso.
-Mejorar el sistema de checkout, se tendría que poder uncheckear a secciones enteras (manejadas por el tipo de entrada en Eventbrite).
-Mostrar el nombre de los congresales presentes (Se debe utilizar la API de Eventbrite)



<h1><b>Congresos en los que se utilizó: </b></h1>

Congreso Juventud Radical Buenos Aires- Saladillo 2017
![alt text](http://infoblancosobrenegro.com/media/W1siZiIsIm5vdGljaWFzLzE3Mjc4L2ZvdG8tODI4OC5qcGVnIl0sWyJwIiwidGh1bWIiLCI4MDB4Il1d/1.jpg?sha=8f9a47c48a0ccbb7)
