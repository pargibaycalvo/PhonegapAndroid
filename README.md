# PhonegapAndroid - PMDM/SXE - App
PhonegapAndroid Pedro Argibay 6150

Este proyecto incluye:

1- Estado de batería al conectar y desconectar el cable de alimentación

2- Uso de la cámara

3- Tiempo (Hora:minutos:segundos) y el día (fecha)

Enlaces:

Para el uso de la cámara usé esta página de Cordova:
http://cordova.apache.org/docs/en/3.3.0/cordova/camera/camera.html#Camera

Para el uso de la bateria:
https://cordova.apache.org/docs/en/latest/reference/cordova-plugin-battery-status/

Y para el uso del tiempo:
https://www.w3schools.com/html/html_examples.asp

Para el uso de la app:

Iniciamos la app con el terminal estando dentro de la carpeta del proyecto y escribimos:
$phonegap run android --verbose

Esto instala la app en tu móvil Android y se iniciará, nos aparecerá que la app está en línea más el mensaje del porcentaje de batería si tenemos el móvil conectado por cable nos devuelve un true, en caso de no tener el cable nos devuelve un false. Si pulsamos el primer botón nos sale el tiempo con su hora, minutos y segundos, y la fecha en la que estamos. 
El segundo botón es para la cámara,  nos inicia la cámara y podremos sacar fotos y almacenarlas.

