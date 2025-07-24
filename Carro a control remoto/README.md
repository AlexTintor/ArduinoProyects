# Proyecto: Carro a control remoto  
Este proyecto consiste en un carro controlado por un control remoto.  
El carro usa como "cerebro" un micro controlador ESP32, y el control remoto usa como base un ESP8266.    

- Carro:
El ESP32 dentro del carro crea una red WIFI, es decir este funciona como host y recibe datos ahi mismo.

- Control:
El ESP8266 del control se conecta a la red WIFI que crea el ESP32 y manda datos.  

