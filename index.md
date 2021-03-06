### ESP32 Lite

Bienvenido al Internet de las Cosas.

 El 90% de la información para el ESP32 Devkit aplica para esta placa. En el IDE, te recomendamos que selecciones la placa "ESP32 Dev Module". El led se puede controlar definiéndolo como el pin 22 (#define LED_BUILTIN 22) en el ejmplo blink. Un segundo led enciende cuando conectas el micro USB, vas a notar que parpadea de manera tenue, esto es normal en este modelo.

Las principales diferencias con respecto al ESP32 devkit son:  
1) No tiene los pines soldados (incluye las dos barras de pines como se muestra en la foto 1)  
2) El chip ESP32 no está dentro de una armadura metálica, por lo que puede ser un poco más sensible a interferencias.  
3) Usa el chip USB a serial ch340g en lugar del cp2102 ( generalmente requiere drivers, se te envía una liga en la información técnica)  
4) Es de dimensiones un poco más pequeñas. (50 x 25.4mm)  
5) El PCB y su construcción física en general es un poco más delgado/ frágil.  
6) Incluye un circuito de carga para aceptar batería. (ADVERTENCIA: EL CHIP DE CARGA DE LA BATERIA NO TIENE PROTECCIÓN PARA SOBRECARGA, POR LO QUE UNA VEZ CARGADA DEBE DESCONECTARSE EL MICROUSB PARA NO OCASIONAR QUE SE SOBRECARGUE LA BATERÍA, LO QUE PUEDE CAUSAR QUE SE DAÑE E INCLUSO EN EL PEOR DE LOS CASOS, QUE CAUSE UN INCENDIO. Esto no es un bug o defecto, sino una decisión de diseño para abaratar costos. La placa puede funcionar sin la batería, alimentada normalmente por el microUSB.)  


![Cosismo ESP32 Lite](https://raw.githubusercontent.com/cosismo/esp32-lite/master/esp32-lite-pinout.jpg)

La guía más básica para iniciar a programar el ESP32 con Arduino IDE es la que sigue (recuerda elegir el modelo ESP32 Dev Module):  
[Programando el ESP32 con el Arduino IDE](https://www.profetolocka.com.ar/2020/07/09/programando-el-esp-32-con-el-arduino-ide/)

Para comenzar a utilizar tu ESP32 y encontrar toda la información técnica, te recomendamos las siguientes ligas:

* Facebook.
[Grupo de Facebook en español sobre Internet de las Cosas](https://www.facebook.com/groups/724628401049648/)

* Videos en Español.
[Listas con decenas de videos con ejemplos y código de proyectos con ESP32:
Tutoriales básicos en español](https://www.youtube.com/playlist?list=PL2xmtLUbEugnUoLiRTqwCm5wi2MSzsw3D)

* Videos en Inglés:

  [Videos en Inglés 1](https://www.youtube.com/watch?v=rP9p0MzxSos&list=PLxJ8_KSR8bp5-F4HVG4QOm4Kt6wQhzsjU)

  [Videos en Inglés 2](https://www.youtube.com/watch?v=jhjZZkKupk8&list=PL3XBzmAj53RnZPeWe799F-uoXERBldhn9)
  
* Fabricante del chip, Espressif. 
[Información oficial del fabricante del chip](https://www.espressif.com/en/products/socs/esp32)

* Arduino. 
[Librerías oficiales Arduino](https://github.com/espressif/arduino-esp32)

* Foro oficial.
[Foro y mucha información](https://esp32.com/)

* Driver USB
[Driver USB CH340 para el modelo ESP32 Lite](https://cosismo.github.io/usbttl-ch340)

¡Suerte!

  Equipo Cosismo
