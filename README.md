# pruebs-2

===============

-   [Introducción](#introduccion)

-   [Requerimientos](#requirimientos)

Introducción
------------
Este proyecto tiene como finalidad el mostrar paso por paso como compilar y subir un firmware nuevo al dispositivo Loka. Para esto se añadirá el sensor TMP36 como sensor de temperatura externo. Se seleccionó el sensor TMP36 para este ejemplo por la compensacion que trae por defecto para lecturas por debajo de los 0 ºC, es decir, el sensor tiene un offset de 500 mV por lo que  a 25 ºC el voltaje de salida es de 750 mV. Gracias a esto es posible medir valores negativos de temperatura sin necesidad de un arreglo extra, ya que los ADCs del Loka solo aceptan voltajes entre 0V y 2.5V.   

Requerimientos
--------------
-   [Code Composer Studio](http://www.ti.com/tool/ccstudio)
-   [Firmware Loader](http://www.thought-creator.com/wp-content/uploads/2015/03/FemtoFirmwareLoader.zip)
-   Cable FTDI.
-   Sensor de temperatura TMP36.

Compilar Proyecto
=================
