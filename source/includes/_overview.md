# Resumen y operaciones

## Encendido y botones

![Front Overview](images/view-overview-front.png)

### Encendido

Para encender el VIEW, presiona y mant�n presionado el bot�n de encendido `(#1)` durante 2 segundos. En unos pocos segundos, el bot�n se iluminar� de rojo, indicando que se est� encendiendo. El logo VIEW aparecer� en la pantalla poco despu�s.

### Apagado

Para apagar en VIEW, presiona y mant�n presionado el bot�n de encendido `(#1)` durante 2 segundos. Aparecer� un aviso de confirmaci�n en la pantalla. Gira la perilla y selecciona �S� y presiona la perilla en el bot�n de aceptar `(#5)` para apgar.

En caso de que el VIEW no responda, puede forzarse el apagado manteniendo apretado el bot�n de encendido `(#1)` durante 15 segundos. Despu�s puede encenderse normalmente presionando el bot�n de Energ�a de nuevo durante 2 segundos.

### Operaci�n

La interfaz de usuarios del VIEW es un sistema basado en men� que ha sido dise�ado para ser simple y para ser operado al aire libre y con guantes. Por esa raz�n, no cuenta con una pantalla t�ctil, en lugar de esto, se emplean botones sencillos y pernos para revisar las opciones. Utiliza la perilla para subir y bajar en las opciones de los men�s. Para seleccionar o abrir la opci�n resaltada en el men�, presiona la perilla o el bot�n de aceptar `(#5)`. Para retroceder o cancelar, presiona el bot�n de cancelar `(#4)`. Algunas pantallas utilizan el bot�n de Contexto `(#6)` para mostrar opciones adicionales indicadas en la pantalla.

<aside class="success">Cada elemento del men� tiene una pantalla de ayuda que le acompa�a � presiona el bot�n de Encendido (#1) para activar la selecci�n actual. Presiona el bot�n de encendido (#1) o el bot�n de cancelar (#4) para salir de las pantallas de ayuda.</aside>

### Sensor de gestos

El Sensor de Gestos `(#2)` funciona cuando la opci�n de lapso de tiempo est� corriendo y la pantalla se pone en blanco. Ondea tu mano en la parte frontal para activar, despu�s ond�ala a la derecha para una vista previa del lapso de tiempo actual, o el anterior, o a la izquierda para cancelar. Mientras que est� mostr�ndose la vista previa, ondea la mano a la derecha para saltar 10 segundos.

## Puertos y conexiones

![Front Overview](images/view-overview-side.png)

### Carga

Para cargar el VIEW, conecta un cable Micro-B USB de una conexi�n de electricidad USB (cargador USB, bater�a o computador) al puerto de carga `(#12)` en el VIEW. Al estar conectado, el indicador de carga `(#11)` se iluminar� en rojo, parpadeando al cargar, y despu�s se mantendr� encendido cuando est� completamente cargado. Esta luz puede deshabilitarse en Configuraci�n->Indicador de Carga. Considera que el indicador de bater�a en el VIEW mostrar� prematuramente una se�al de baja bater�a, y a la hora de cargar una bater�a que est� completamente descargada, puede tomar un poco de tiempo antes de que el progreso sea visible.

### Puertos auxiliares

El VIEW incluye dos puertos auxiliares TRS de 2,5 mm `(#9, #10)` para la sincronizaci�n de movimiento, activaci�n de cable de disparador e integraciones externas. Actualmente �nicamente el AUX2 es utilizado por el firmware. Enviar� un pulso para activar el sistema de movimiento despu�s de cada toma durante el time-lapse (no se necesita ninguna configuraci�n para esto), o puede utilizarse como un disparador externo para los intervalos cuando el intervalo de tiempo de lapso est� en la opci�n de �Externo�.
### Tarjeta SD

La ranura para tarjeta SD `(#8)` ofrece una forma conveniente de obtener datos del VIEW. El VIEW tambi�n puede guardar las im�genes de lapsos de tiempo en RAW en la tarjeta SD � esta es la forma m�s conveniente de post-procesamiento, debido a que cada time-lapse es nombrado secuencialmente en su propia carpeta con los archivos XMP para una eliminaci�n autom�tica de parpadeos en Lightroom.

El VIEW soporta todos los tipos y capacidades de tarjetas SD, pero internamente utiliza un controlador de Clase 10, por lo que las tarjetas UHS II m�s nuevas no ofrecer�n una mejora de velocidad sobre las tarjetas de Clase 10. Las tarjetas pueden ser formateadas con la c�mara o en un computador en FAT/EXFAT (MSDOS).

### Puerto USB

El VIEW incluye un puerto de USB de tama�o completo `(#13)` para conectar la c�mara. Este puerto tambi�n soporta puertos USB para conectar m�ltiples dispositivos (actualmente tambi�n puede comunicar con DP NMX a trav�s del USB y se han planificado m�ltiples soportes de c�mara para el futuro).

### Enlazar la c�mara

### Zapata de la c�mara

El VIEW puede conectarse convenientemente a la parte superior de la c�mara desliz�ndolo en la zapata de la c�mara. Esto tambi�n ofrece una sincronizaci�n de PC para el bulb ramping sin necesidad de cables adicionales, sin embargo, la modalidad de ramping de exposici�n actual no lo utiliza, por lo que puedes colocar el VIEW en cualquier lugar sin afectar el desempe�o.

### Conexi�n USB

Conecta el cable USB apropiado para tu c�mara del Puerto `(#13)` hasta el puerto USB de tu c�mara. Lo mejor es que la c�mara est� encendida antes de conectar, debido a que parece haber un problema ocasional de tiempo que hace que la c�mara no se conecte adecuadamente si se enciende estando conectada. Si la c�mara no parece conectarse, desenchufa el USB y reconecta. Las c�maras Sony pueden ser un poco m�s complicadas � si tiene alg�n problema, intente remover la bater�a de la c�mara, encenderla de nuevo y despu�s conectarla en el USB de nuevo al VIEW.

Algunas c�maras necesitan colocarse en la modalidad de �Conectar con PC� o �Modalidad PTP� para que el USB funcione adecuadamente. Adicionalmente, algunas c�maras Canon con WiFi (como la 6D) requieren que se desactive el WiFi para que el control por USB funcione.

El cable USB es lo �nico que se necesita para un soporte de ramping completo. No se necesita m�s ninguna conexi�n.
