# Neopixel Xmas Stars

![N|Solid](https://raw.githubusercontent.com/electgpl/Neopixel_Xmas_Stars/master/Media/20191203_215045.jpg)

![N|Solid](https://raw.githubusercontent.com/electgpl/Neopixel_Xmas_Stars/master/Media/20191204_113412.jpg)

![N|Solid](https://raw.githubusercontent.com/electgpl/Neopixel_Xmas_Stars/master/Media/20191204_113351.jpg)

Productos adquiridos en:

[![N|Solid](https://raw.githubusercontent.com/electgpl/Neopixel_Xmas_Stars/master/Media/lcsc-logo.png)](https://lcsc.com/?from_code=PL20191029WJJJ)



Este es un proyecto con fines decorativos para Navidad y otros, Se trata de una estrella con 20 Leds inteligentes Neopixel (WS2812) el cual podremos controlar desde Arduino, ESP8266, ESP32, PIC, etc....
En este proyecto estamos usando el Footprint de Wemos D1 Mini (ESP8266), pero se podria cablear cualquier controlador ya que solo se utilizan tres pines de conexion +5V, GND, DataIn.

## IDEs
  - REQUIERE DE LA BIBLIOTECA DE ADAFRUIT "Adafruit_NeoPixel.h"
  - Arduino IDE
  - PlatformIO
  - AtmelStudio
  - y mas...
  
## Diseño y Desarrollo

> Diseñado en dos capas con SMD y THT
> Los componentes SMD son solamente los LEDs 5050 y los capacitores de filtrado (se pueden excluir)
> Los componentes THT son unicamente los pines de coneccion con el WEMOS D1.
>          
> Componentes adquiridos a muy bajo costo en [LCSC].
> PCB creado en [JLCPCB].
> Diseño realizado en [Eagle].

### Instalación

Todos los archivos se encuentran disponibles en este repositorio, diagramas, pcb, programas de ejemplo. etc...

### Pendientes

 - Código de ejemplo puede ser utilizado tanto en Arduino como en Wemos o ESP8266, aunque no se estan usando funciones WiFi.
 - Se pretende generar un nuevo codigo para ESP8266 aprovechando el control por WiFi (WiFiManager, Blynk, etc..)

License
----

MIT


**Free Software, Hell Yeah!**

[LCSC]: <https://lcsc.com/?from_code=PL20191029WJJJ>
[JLCPCB]: <https://jlcpcb.com/>
[Eagle]: <https://www.autodesk.com/products/eagle/overview>
