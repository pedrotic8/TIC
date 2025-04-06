# Manejo de Cisco Packet Tracer

## Práctica 1

El objetivo es familiarizarnos con el Programa Packet Tracer.

### Guion

- Abre el programa Cisco Packet Tracer (te pedirá el usuario y contraseña que tienes)
- Localiza un Switch dentro de la categoría Network Devices
- Arrástralo con el ratón al escenario donde vamos a reproducir una red básica
- Selecciona la categoría End Devices
- Selecciona dos ordenadores (PC) y colócalos en el escenario que ya contiene al Switch
- Selecciona el apartado Connections
- Dentro de ese apartado elige la opción Copper Straight - Through
- Haz clic en el Switch y elige la opción Fast Ethernet
- Concecta el cable desde el Switch a cada uno de los ordeandores
- En cada ordenador, haz clic y selecciona la Opción Desktop (Escritorio) y, a continuación, IP Configuration
    - Configura el primer ordenador con la dirección IP: 192.168.1.10
    - Verifica que la máscara de subred se establece automáticamente (255.255.255.0)
    - Configura el segundo ordenador con la dirección IP: 192.168.1.11
    - Verifica que la máscara de subred se establece automáticamente (255.255.255.0)
- Selecciona un sobre cerrado (representa un paquete de red) en la barra superior y arrástralo desde un ordenador al otro. Luego, haz clic en la pestaña Simulation (parte inferior derecha) y pulsa Play para observar cómo se transmite el paquete entre los dispositivos.


### Cuestiones

1. ¿Por qué es necesario utilizar un switch para conectar los dos ordenadores en esta red?
Explica qué función cumple el switch y qué sucedería si intentáramos conectar los ordenadores directamente sin él.

2. ¿Podrán comunicarse los dos ordenadores si uno tiene la IP 192.168.1.10 y el otro la IP 192.168.2.11, manteniendo la misma máscara de subred (255.255.255.0)? Justifica tu respuesta.

3. Durante la simulación, observaste el camino que sigue el paquete desde un ordenador al otro. ¿Qué pasaría si uno de los ordenadores no tuviera configurada una dirección IP? ¿El paquete se enviaría correctamente? ¿Por qué?

4. ¿Cómo añadirías un tercer ordenador a esta red para que también pueda comunicarse con los otros dos? Explica qué pasos seguirías y qué dirección IP deberías asignarle.