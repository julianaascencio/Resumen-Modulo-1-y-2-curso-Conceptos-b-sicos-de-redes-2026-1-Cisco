# Resumen-Modulo-1-y-2-curso-Conceptos-b-sicos-de-redes-2026-1-Cisco

## Integrantes
Lesly Juliana Ascencio Peréz

# Módulo 1 - Conceptos básicos de redes
## ¿Qué es una red?
Una red e sun conjunto de dispositivos conectados entre sí que permiten compartir información y recursos, como archvios, impresoras o accesos a internet.

Las redes pueden conectarse mediante:
- Medios cableados (Ethernet, fibra óptica)
- Medios inalambricos (WI-FI, Bluetooth)

## Dispositivos de red
- Dispositivos finales
Son los equipos que generan o reciben la información
Ejemplo: computadores, smartphones, tablets, impresoras, servidores.

## Dispositivos intermedios
Permiten conectar los dispositivos y dirigir el tráfico de los datos dentro de la red.
Ejemplo:
- Router: Conecta diferentes redes y permite acceso a internet
- Switch: Conecta dispositivos dentro de una red local.
- Access Point: Permite conexión inalámbrica.
- Firewall: Protege la red conta accesos no autorizados.

## Tipos de redes
### LAN (Local Area Network)
Red que conecta dispositivos en un área pequeña.
Ejemplos:
- Hogar
- Oficina
- Laboratorio de computadores

### WAN (Wide Area Network)
Red que cubre grandes distancias y conecta varias redes LAN
Ejemplo: Internet.

### WLAN
Es una LAN inalambrica, donde los dispositivos se conectan usando WI-FI.

## Medios de transmisión
Los datos se transmiten a través de diferentes medios.

### Medios cableados
- Cable Ethernet (cobre)
- Fibra óptica

### Medios inalámbricos
- Wi-Fi
- Bluetooth
- Redes Celulares

## Direcciones en la red
### Dirección IP
Identifica un dispositivo dentro de una red
Ejemplo: 192.168.1.10

### Dirección MAC
Es una dirección dísica única que tiene cada tarjeta de red:
Ejemplo: 00:1A:2B:3C:4D:4E

## Internet
Internet es una red global que conecta millones de redes y dispositivos en todo el mundo, permitiendo el intercambio de información mediante protocolos de comunicación.

# Módulo 2 -  Comunicación de red
## Comunicación entre dispositivos
Cuando un dispositivo envía información a otro, los datos se dividen en pequeñas unidades llamadas paquetes, que viajan através de la red hasta llegar al destino.
Al llegar los paquetes se reensamblan para construir la informacón original.

## Protocolos de red
Los protocolos son reglas que permiten que los dispositivos se comuniquen correctamente.

Ejemplos:

| Protocolo    |                     Función                  |
|--------------|----------------------------------------------|
| HTTP         | Acceso a páginas web                         |
| HTTPS        | Navegación web segura                        |
| FTP          | Transferencia de archivos                    |
| DNS          | Traduce nombres de dominio a direcciones IP  |
| DHCP         | Asigna direcciones IP automaticamente        |


## Modelo OSI
El modelo OSI divide la comunicación en red en 7 capas, donde cada una cumple una función especifica.

| Capa              | Función                            |
| ----------------- | ---------------------------------- |
| 7 Aplicación      | Interacción con las aplicaciones   |
| 6 Presentación    | Formato y cifrado de datos         |
| 5 Sesión          | Control de la comunicación         |
| 4 Transporte      | Entrega confiable de datos         |
| 3 Red             | Direccionamiento IP y enrutamiento |
| 2 Enlace de datos | Tramas y dirección MAC             |
| 1 Física          | Transmisión de bits                |

## Encapsulación de datos
Cuando los datos se transmiten por una red pasan por un proceso llamado encapsulación, donde cada capa agrega información de control.

El resumen del proceso es el siguiente:

Datos
↓
Segmento (TCP)
↓
Paquete (IP)
↓
Trama (Ethernet)
↓
Bits

## Puertos de red
Los protocolos utilizan puertos para identificar los servicios de red.

| Puerto | Servicio |
| ------ | -------- |
| 80     | HTTP     |
| 443    | HTTPS    |
| 53     | DNS      |
| 21     | FTP      |
| 25     | SMTP     |

## Importancia de los protocolos
Los protocolos permiten:
- Comunicación entre diferentes dispositivos.
- Transmisión confiable de datos.
- Organziación del tráfico de red

# Conclusión

Los módulos 1 y 2 del curso Conceptos básicos de redes de Cisco permiten comprender los principios fundamentales del funcionamiento de las redes. Se abordan conceptos como los tipos de redes, los dispositivos que las componen, los medios de transmisión y la importancia de las direcciones IP y MAC para la comunicación entre equipos. Además, se introduce el modelo OSI, los protocolos de red y el proceso de encapsulación de datos, que explican cómo la información viaja a través de Internet. Estos conocimientos constituyen la base para el aprendizaje de tecnologías de red más avanzadas y para el desarrollo de habilidades en el área de telecomunicaciones y redes.
