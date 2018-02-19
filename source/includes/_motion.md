# Control de movimiento

El VIEW puede sincronizar con la mayoría de los sistemas de control de movimiento para la funcionalidad de disparar-moverse-disparar. Adicionalmente, cuenta con un soporte de programación de movimiento completo para el controlador de pasos Dynamic Perception NMX (a través de Bluetooth o USB) y Syrp Genie Minie (a través de Bluetooth) y se planifica que en el futuro se incorporará el soporte para eMotimo Spectrum (a través del serial AUX2) y Kessler Second Shooter (probablemente).

# Sincronización de AUX de salida

Para activar un sistema de movimiento, para que se mueva después de cada disparo, conecta un cable TRS de 2,5 mm del AUX2 en el VIEW con el puerto de entrada de sincronización en el sistema de movimiento. El VIEW enviará 200ms de pulso “cerrado” después de cada disparo. No se requiere ninguna configuración especial en VIEW. El sistema de movimiento necesita el soporte de un intervalómetro externo y normalmente debe estar en una modalidad especial (p.e., modalidad “esclava” para el NMX”, “intervalómetro externo” para eMotimo TB3).

## Disparador externo

Esta es la opción más versátil y debería trabajar con cualquier sistema que tenga un disparador de cámara para disparar-mover-disparar. Esta es la única opción para un sistema que no soporte una sincronización auxiliar externa (como el Syrp Genie). En esta modalidad, el intervalo es definido externamente por el sistema de movimiento, y el VIEW trabaja alineado entre el sistema de movimiento y la cámara para gestionar la exposición.

Para utilizar un disparador externo, coloca la Modalidad de Intervalo en “AUX2 externo” en el menú de configuración de lapsos de tiempo. Conecta el puerto de control de movimiento de la cámara al puerto AUX2 de VIEW con un cable TRS 2,5 mm (TRRS no funciona). La cámara está conectada al puerto USDB de VIEW como siempre. Una vez que se inicia, el VIEW esperará por la señal del sistema de movimiento para disparar cada cuadro.

Con esta configuración, el VIEW gestiona la exposición y ramping, y el movimiento e intervalo son definidos por el sistema de movimiento. Debido a que VIEW no está controlando el intervalo, no pueden realizarse intervalos variables.

## Dynamic Perception NMX

Además de los métodos anteriores, en controlador NMX puede conectarse a través de USDB o Bluetooth para una programación de movimiento completo. La programación de movimiento debe hacerse a través de la aplicación móvil para el VIEW debido a que no está soportado actualmente en la interfaz independiente.

### Conexión Bluetooth NMX

<i>Nota: para este método, el firmware beta v1.8 más actualizado debe estar instalado en VIEW.</i>  Para conectar con el NMX a través de Bluetooth, primero activa la conexión Bluetooth en el VIEW en Configuración->Conexiones inalámbricas->Activar Bluetooth (si solamente se muestra la opción de “Desactivar Bluetooth”, entonces ya está activado). Asegúrate de que la aplicación NMX no esté conectada al NMX, debido a que esto no le permitirá al VIEW conectarse (apaga el BT del teléfono de ser necesario). Con el Bluetooth activado, el VIEW automáticamente se conectará con el primer controlador NMX disponible al ser encendido. Un pequeño ícono de Bluetooth aparecerá en la barra superior de VIEW una vez que se haya conectado. Entonces se puede configurar a través de la aplicación WiFi VIEW como se muestra en este video: https://vimeo.com/237150285

### Conexión USDB NMX

Para conectar con el NMX a través del USB, se necesitará una conexión USB adicional al puerto USB (una para la cámara, una para el NMX). Conecta una extensión pequeña de USB al VIEW, y después conecta la cámara y el NMX al centro y conecta la electricidad al NMX (¡en este orden!). Se recomienda desactivar el BT tanto en el VIEW como en el teléfono en este caso para evitar cualquier problema. Un pequeño ícono de Bluetooth aparecerá en la barra superior de VIEW una vez que se haya conectado. Entonces se puede configurar a través de la aplicación WiFi VIEW como se muestra en este video: https://vimeo.com/237150285

El USB tiene la ventaja de ser más confiable y no verse afectado por temperaturas frías.

Importante: el NMX debe ser conectado primero a través de USB, después a la corriente externa – si el NMX está conectado a la electricidad antes de conectarlo al USB, no será detectado.

## Syrp Genie Mini
El VIEW puede controlar completamente el Syrp Genie Mini a través de Bluetooth, permitiendo una programación de movimiento de múltiples cuadros. Se requiere el firmware v1.8 beta más actualizado en el VIEW, y el Genie Mini también debe tener su firmware actualizado. Considera que al controlar el Genie Mini a través de VIEW no será posible utilizar la aplicación Syrp al mismo tiempo, por lo que es mejor desactivar el BT en el teléfono para evitar interferencias.

Para conectar el Genie Mini al VIEW, primero activa Bluetooth en el VIEW en Configuración->Conexiones inalámbricas->Activar Bluetooth (si solamente se muestra la opción de “Desactivar Bluetooth”, entonces ya está activado). Después enciende el Genie Mini y espera que aparezca el ícono de Bluetooth en la barra superior de la pantalla de VIEW. Actualmente, se pueden conectar hasta dos Genie Minis al mismo tiempo (como para la opción de pan/tilt). Cada uno puede configurarse en la aplicación WiFi de VIEW, similar a la configuración NMX que se muestra a continuación: <https://vimeo.com/237150285>.  También puedes ver <https://vimeo.com/235979676> para descubrir una configuración rápida sin la aplicación.

Si lo prefieres, el Genie Mini también puede programarse por separado y después sincronizado con el VIEW para la funcionalidad de disparar-mover-disparar. Este es el método de “Disparador Externo” que se muestra arriba. Conecta el puerto de la cámara en el Genie Mini al puerto AUX2 en el VIEW con un cable TRS de 2,5 mm (TRRS no funcionará) y después configura la modalidad de Intervalos en el VIEW a “AUX2 Externo”. En esta configuración, el VIEW dispara cada cuadro cuando lo indica el Mini mientras gestiona el ramping, y el Mini gestiona el movimiento y los intervalos conforme lo define la aplicación Syrp.
