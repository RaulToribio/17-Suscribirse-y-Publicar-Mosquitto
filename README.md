# Introducción

Mosquitto es un servidor de mensajería de código abierto que implementa el protocolo MQTT (Message Queuing Telemetry Transport). MQTT es un protocolo de comunicación de mensajería leve diseñado para la conectividad en dispositivos IoT y redes de área amplia.

- mosquitto_pub: una herramienta de línea de comandos que se utiliza para publicar mensajes en un servidor Mosquitto.
- mosquitto_sub: una herramienta de línea de comandos que se utiliza para suscribirse a temas y recibir mensajes de un servidor Mosquitto.

# Material Necesario

- [Instalar Mosquitto](https://github.com/RaulToribio/15-Instalar-Mosquitto)
- [Instalar Mosquitto Clients](https://github.com/RaulToribio/16-Instalar-Mosquitto-Clients)

# Material de Referencia

- [Introducción a MQTT (Broker Mosquitto)](https://edu.codigoiot.com/course/view.php?id=851)

# Instrucciones

![https://raw.githubusercontent.com/RaulToribio/17-Suscribirse-y-Publicar-Mosquitto/main/Im%C3%A1genes/Suscribirse%20y%20Publicar%20Mosquitto%20(1).png](https://raw.githubusercontent.com/RaulToribio/17-Suscribirse-y-Publicar-Mosquitto/main/Im%C3%A1genes/Suscribirse%20y%20Publicar%20Mosquitto%20(1).png)

Utilizar la línea de comando `mosquitto_sub -h localhost -p 1883 i RaulToribio -q 0 -t PILARES-RaulToribio` para suscribirse.

- -h: Host
- -p: Puerto
- -i: Identificador
- -q: Calidad del Servicio (QoS)
- -t: Tema

![https://raw.githubusercontent.com/RaulToribio/17-Suscribirse-y-Publicar-Mosquitto/main/Im%C3%A1genes/Suscribirse%20y%20Publicar%20Mosquitto%20(2).png](https://raw.githubusercontent.com/RaulToribio/17-Suscribirse-y-Publicar-Mosquitto/main/Im%C3%A1genes/Suscribirse%20y%20Publicar%20Mosquitto%20(2).png)

Utilizar la línea de comando `mosquitto_pub -h localhost -p 1883 i RaulToribio -q 0 -t PILARES-RaulToribio -m “Saludos”` para publicar.

- -h: Host
- -p: Puerto
- -i: Identificador
- -q: Calidad del Servicio (QoS)
- -t: Tema
- -m: Mensaje

# Créditos

> [José Raúl Toribio Gabriel](https://github.com/RaulToribio)
> 

> [Codigo IoT](https://github.com/codigo-iot)
>
