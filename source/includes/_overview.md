# Resumen y operaciones

## Encendido y botones

![Front Overview](images/view-overview-front.png)

### Encendido

Para encender el VIEW, presiona y mantén presionado el botón de encendido `(#1)` durante 2 segundos. En unos pocos segundos, el botón se iluminará de rojo, indicando que se está encendiendo. El logo VIEW aparecerá en la pantalla poco después.

### Apagado

Para apagar en VIEW, presiona y mantén presionado el botón de encendido `(#1)` durante 2 segundos. Aparecerá un aviso de confirmación en la pantalla. Gira la perilla y selecciona “Sí” y presiona la perilla o el botón de aceptar `(#5)` para apgar.

En caso de que el VIEW no responda, puede forzarse el apagado manteniendo apretado el botón de encendido `(#1)` durante 15 segundos. Después puede encenderse normalmente presionando el botón de Energía de nuevo durante 2 segundos.

### Operación

La interfaz de usuarios del VIEW es un sistema basado en menú que ha sido diseñado para ser simple y para ser operado al aire libre y con guantes. Por esa razón, no cuenta con una pantalla táctil, en lugar de esto, se emplean botones sencillos y pernos para revisar las opciones. Utiliza la perilla para subir y bajar en las opciones de los menús. Para seleccionar o abrir la opción resaltada en el menú, presiona la perilla o el botón de aceptar `(#5)`. Para retroceder o cancelar, presiona el botón de cancelar `(#4)`. Algunas pantallas utilizan el botón de Contexto `(#6)` para mostrar opciones adicionales indicadas en la pantalla.

<aside class="success">Cada elemento del menú tiene una pantalla de ayuda que le acompaña – presiona el botón de Encendido (#1) para activar la selección actual. Presiona el botón de encendido (#1) o el botón de cancelar (#4) para salir de las pantallas de ayuda.</aside>

### Sensor de gestos

El Sensor de Gestos `(#2)` funciona cuando la opción de lapso de tiempo está corriendo y la pantalla se pone en blanco. Ondea tu mano en la parte frontal para activar, después ondéala a la derecha para una vista previa del lapso de tiempo actual, o el anterior, o a la izquierda para cancelar. Mientras que esté mostrándose la vista previa, ondea la mano a la derecha para saltar 10 segundos.

## Puertos y conexiones

![Front Overview](images/view-overview-side.png)

### Carga

Para cargar el VIEW, conecta un cable Micro-B USB de una conexión de electricidad USB (cargador USB, batería o computador) al puerto de carga `(#12)` en el VIEW. Al estar conectado, el indicador de carga `(#11)` se iluminará en rojo, parpadeando al cargar, y después se mantendrá encendido cuando esté completamente cargado. Esta luz puede deshabilitarse en Configuración->Indicador de Carga. Considera que el indicador de batería en el VIEW mostrará prematuramente una señal de baja batería, y a la hora de cargar una batería que está completamente descargada, puede tomar un poco de tiempo antes de que el progreso sea visible.

### Puertos auxiliares

El VIEW incluye dos puertos auxiliares TRS de 2,5 mm `(#9, #10)` para la sincronización de movimiento, activación de cable de disparador e integraciones externas. Actualmente únicamente el AUX2 es utilizado por el firmware. Enviará un pulso para activar el sistema de movimiento después de cada toma durante el time-lapse (no se necesita ninguna configuración para esto), o puede utilizarse como un disparador externo para los intervalos cuando el intervalo de tiempo de lapso está en la opción de “Externo”.

### Tarjeta SD

La ranura para tarjeta SD `(#8)` ofrece una forma conveniente de obtener datos del VIEW. El VIEW también puede guardar las imágenes de lapsos de tiempo en RAW en la tarjeta SD – esta es la forma más conveniente de post-procesamiento, debido a que cada time-lapse es nombrado secuencialmente en su propia carpeta con los archivos XMP para una eliminación automática de parpadeos en Lightroom.

El VIEW soporta todos los tipos y capacidades de tarjetas SD, pero internamente utiliza un controlador de Clase 10, por lo que las tarjetas UHS II más nuevas no ofrecerán una mejora de velocidad sobre las tarjetas de Clase 10. Las tarjetas pueden ser formateadas con la cámara o en un computador en FAT/EXFAT (MSDOS).

### Puerto USB

El VIEW incluye un puerto de USB de tamaño completo `(#13)` para conectar la cámara. Este puerto también soporta puertos USB para conectar múltiples dispositivos (actualmente también puede comunicar con DP NMX a través del USB y se han planificado múltiples soportes de cámara para el futuro).

## Enlazar la cámara

### Zapata de la cámara

El VIEW puede conectarse convenientemente a la parte superior de la cámara deslizándolo en la zapata de la cámara. Esto también ofrece una sincronización de PC para el bulb ramping sin necesidad de cables adicionales, sin embargo, la modalidad de ramping de exposición actual no lo utiliza, por lo que puedes colocar el VIEW en cualquier lugar sin afectar el desempeño.

### Conexión USB

Conecta el cable USB apropiado para tu cámara del Puerto `(#13)` hasta el puerto USB de tu cámara. Lo mejor es que la cámara esté encendida antes de conectar, debido a que parece haber un problema ocasional de tiempo que hace que la cámara no se conecte adecuadamente si se enciende estando conectada. Si la cámara no parece conectarse, desenchufa el USB y reconecta. Las cámaras Sony pueden ser un poco más complicadas – si tiene algún problema, intente remover la batería de la cámara, encenderla de nuevo y después conectarla en el USB de nuevo al VIEW.

Algunas cámaras necesitan colocarse en la modalidad de “Conectar con PC” o “Modalidad PTP” para que el USB funcione adecuadamente. Adicionalmente, algunas cámaras Canon con WiFi (como la 6D) requieren que se desactive el WiFi para que el control por USB funcione.

El cable USB es lo único que se necesita para un soporte de ramping completo. No se necesita más ninguna conexión.
