# Proyecto: Carro a control remoto  

Video TikTok: ...    

Este proyecto consiste en un carro controlado por un control remoto.  
El carro usa como "cerebro" un micro controlador ESP32, y el control remoto usa como base un ESP8266.    

- Carro:
El ESP32 dentro del carro crea una red WIFI, es decir este funciona como host y recibe datos ahi mismo.

- Control:
El ESP8266 del control se conecta a la red WIFI que crea el ESP32 y manda datos.    

Más detalles:  
El Control Remoto usa los siguientes componentes: 1 ESP32; 4 Botones pulsadores (cada boton respetibamente envia una señal de: Avanzar, Retroceder, Girar a la Izquierda, y Girar a la Derecha); 1 Power Bank (fuente de alimentación).    

El Carro usa los siguientes componentes: 1 ESP8266; 2 Motores (para avanzar y retroceder, se usan en las ruedas traceras); 1 Servo motor (para girar a la Izquierda y Derecha las ruedas delanteras); El Chacis del carro hecho de carton y otros materiales.
