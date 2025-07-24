# PROYECTO EN PROCESO... : Carro a control remoto  

Video TikTok: ...    

Este proyecto consiste en un carro controlado por un control remoto.  
El carro usa como "cerebro" un micro-controlador ESP32, y el control remoto usa como base un ESP8266.    

¿Qué es un ESP32? El ESP32 es un micro-controlador programable con el IDE Arduino (se descarga en computadoras). Estos micro-controladores o también conocidos como "Placlas Programables" son unas mini computadoras MUY primitivas, pero tiene varias "curiosidades" interesantes. Estos se usan para proyectos electronicos, su uso varia desde prender y apagar un led hasta cosas inimaginables; En sí el ESP32 tiene la capacidad de procesar y seguir procesar grabados en su memoria, previamente guardados mediente el IDE Arduino, también cuenta con varios pines capaces de recibir o mandar voltaje lo cual sirve para prender leds, motores, o para transmitir datos. Estos micro-controladores tienen un precio aproximado de $10 dolares, estos necesitan una alimentación de 5 volts. De igual manera el ESP8266 es un micro-controlador pero con distintas caracteristicas.    

- Carro:
El ESP32 dentro del carro crea una red WIFI, es decir este funciona como host y recibe datos ahi mismo.

- Control:
El ESP8266 del control se conecta a la red WIFI que crea el ESP32 y manda datos.    

Más detalles:  
El Control Remoto usa los siguientes componentes: 1 ESP32; 4 Botones pulsadores (cada boton respetibamente envia una señal de: Avanzar, Retroceder, Girar a la Izquierda, y Girar a la Derecha); 1 Power Bank (fuente de alimentación).    

El Carro usa los siguientes componentes: 1 ESP8266; 2 Motores (para avanzar y retroceder, se usan en las ruedas traceras); 1 Servo motor (para girar a la Izquierda y Derecha las ruedas delanteras); El Chacis del carro hecho de carton y otros materiales.
