# Configuraci�n de Time-Lapse

Comienza conectando la c�mara a trav�s de USB como se describe en la secci�n previa. Esto activar� el men� de Time-lapse (el primer elemento en la pantalla principal). Presiona la perilla o el bot�n de aceptar para seleccionar. Ver�s las opciones enumeradas en esta secci�n.

<aside class="notice">IMPORTANTE: la c�mara debe estar en modalidad manual, y debe designarse el formato RAW (no RAW+JPEG)</aside>

### Configuraci�n r�pida para la primera prueba
Para tu primera prueba de ramping autom�tico, recomiendo que comiences con la siguiente configuraci�n:

Configuraci�n | Valor recomendado
------ | -------
Exposici�n | Simplemente configura la c�mara para el escenario actual con anticipaci�n y salta este paso.
Modalidad de Timelapse | Auto Ramping
Modalidad de intervalos | Auto Variable
Intervalos en el d�a | 8 segundos
Intervalos en la noche | 40 segundos
Destino | C�mara <sup>1</sup>

Recomiendo que comiences una hora antes del atardecer, colocando la c�mara en el ISO m�s bajo, una apertura moderada de (f/2.8) y despu�s configures la velocidad de disparo a cualquiera necesaria para una buena exposici�n (puede ser 1/3200). �Aseg�rate de no sobreexponer!

Entonces, deja que corra durante al menos 3 horas despu�s del atardecer para obtener una buena longitud y transici�n. O, si tienes una fuente externa de energ�a en la c�mara, �d�jalo correr hasta el amanecer!

Una vez que se ha completado el time-lapse, revisa la secci�n de <a href="#post-processing">post-procesamiento</a>.

<sup>1</sup> Para las c�maras Sony conectadas por USB, necesitas configurarlas a la �Tarjeta SD� y asegurarte de que la Tarjeta SD est� en el VIEW. Para las dem�s c�maras, el desempe�o es mejor cuando se guarda directamente en la c�mara. Sony puede guardar en la c�mara cuando la conexi�n es a trav�s de WiFi en lugar de USB (see <a href="#camera-specific-notes">camera-specific notes</a> for more).

### Opciones de Time-Lapse que se describen abajo

## Exposici�n

Coloca la c�mara en modalidad de liveview para ajustar la exposici�n y el enfoque. Gira la perilla para aumentar/disminuir la exposici�n. Presiona el bot�n de aceptar para alternar la modalidad de enfoque. Estando en la modalidad de enfoque, la imagen de liveview ser� recortada a un 100% y la perilla ajustar� el enfoque en lugar de la exposici�n.*


<aside class="notice">NOTA: la funci�n de Exposici�n puede no funcionar bien en todas las c�maras. Si tienes alg�n problema con ella, simplemente ajusta la exposici�n y el enfoque en la c�mara antes de conectarla al VIEW.</aside>

<aside class="success">Bien sea que se configure a trav�s del men� de Exposici�n o en la c�mara, la exposici�n de inicio para el ramping es muy importante conforme es la que ser� utilizada como referencia en el time-lapse. Aseg�rate de que no est� sobreexpuesta, debido a que de haber demasiadas regiones con sobre exposici�n el ramping podr�a ser poco preciso.</aside>


## Modalidad Timelapse

Opci�n | Descripci�n
------ | -------
Fija | Esta opci�n es para un time-lapse b�sico en el que la exposici�n e intervalos sean constantes a trav�s del Auto Ramping |En esta modalidad el VIEW se ajustar� autom�ticamente a la exposici�n para coincidir con las condiciones del cambio de luz.

Para los clips de time-lapse de corto plazo, durante el d�a o la noche, en donde la exposici�n e intervalos sean constantes, elige Fija.


Para los atardeceres, amaneceres, pasos del d�a a la noche, de la noche al d�a, elige auto ramping. Esto tambi�n permitir� la opci�n de auto intervalo para el ramping de intervalos entre el d�a y la noche.

## C�mara principal

Esta opci�n solamente se nuestra cuando hay m�s de una c�mara conectada al VIEW. La selecci�n de c�mara principal define la c�mara utilizada para la configuraci�n y el liveview, la pesta�a de estatus y el seguimiento de la exposici�n. La configuraci�n de la c�mara principal es copiada a todas las c�maras adicionales conectadas y es activada con sincronizaci�n. Esto es genial para los panoramas, as� como las vistas amplias y las vistas de telefotograf�a para las transiciones de post-procesamiento. En el caso de un panorama amplio o una telefotograf�a, da una vista amplia para un mejor seguimiento de exposici�n.

## Modo de intervalo

Esta opci�n solamente se muestra cuando la Modalidad de Timelapse est� en �Auto Ramping�.

Opci�n | Descripci�n
------ | -------
Longitud fija |Esto mantiene el mismo intervalo a trav�s del Time-Lapse y limitar� la velocidad m�xima de disparo para que se ajuste.
Auto Variable | Esta modalidad pasar� autom�ticamente de los intervalos de d�a a los intervalos de noche y permitir� una velocidad de disparo m�s larga en la noche.

## Intervalo

Esta opci�n solamente es mostrada cuando la Modalidad Timelapse es definida en �Fija� o la Modalidad de Intervalo es definida en �Fija�.

Opci�n | Descripci�n
------ | -------
[tiempo en segundos] | Longitud de intervalo en segundos. Este es el tiempo entre el inicio de un cuadro y el inicio del siguiente.


## Cuadros

Esta opci�n solamente es mostrada cuando la Modalidad de Timelapse est� en modalidad �Fija�. En la modalidad de Auto Ramping, el VIEW siempre funciona hasta que es detenido.

Opci�n | Descripci�n
------ | -------
[n�mero de cuadros] | Cantidad de exposiciones a completar antes de detenerse


## Intervalo durante el d�a

Esta opci�n solamente se muestra cuando la modalidad de Timelapse est� en �Auto Ramping� y la Modalidad de Intervalo est� en �Auto Variable�.

Esto determina la duraci�n del intervalo durante la luz del d�a, en base a la configuraci�n de la exposici�n de la c�mara. Se realizar� el ramping de forma progresiva desde/hasta el Intervalo de Noche conforme las condiciones del ambiente (y la exposici�n de la c�mara) cambien.

Opci�n | Descripci�n
------ | -------
[tiempo en segundos] | Longitud de intervalo en segundos. Este es el tiempo que transcurre desde el inicio de un marco hasta el inicio del siguiente

## Intervalo nocturno

Esta opci�n solamente se puede mostrar cuando la Modalidad de Timelapse est� en �Auto Ramping� y la Modalidad de Intervalo est� configurada en �Auto Variable�.

Esto determina la longitud del intervalo durante la noche, en base a la configuraci�n de exposici�n de la c�mara. Se realizar� el ramping de forma progresiva desde/hasta el Intervalo de D�a conforme las condiciones del ambiente (y la exposici�n de la c�mara) cambien.



Opci�n | Descripci�n
------ | -------
[tiempo en segundos] | Longitud de intervalo en segundos. Este es el tiempo que transcurre desde el inicio de un marco hasta el inicio del siguiente


# Opciones de Ramping

Esta opci�n solamente se muestra cuando la Modalidad de Timelapse est� en �Auto Ramping�.

En este men�, hay algunos detalles para configurar los l�mites del auto ramping. Considera que estas opciones pueden limitar el rango de ramping y por lo tanto hacer que no alcance la exposici�n correcta si est� demasiado limitada. Para la mayor�a de las c�maras, un ISO m�ximo de 6.400 funciona bien, con un l�mite inferior ISO de 100 (lo mejor es utilizar los ISOs nativos, no los m�s bajos).

La configuraci�n de Exposici�n Nocturna define qu� tan menos expuesta la �noche� noche tiene que estar en relaci�n con el �d�a�. Por ejemplo, en una exposici�n nocturna de -1 (por defecto), la sub-exposici�n en la escena nocturna por 1 paso en comparaci�n con el d�a. Entonces, si un auto ramping se inicia durante el d�a, y por la noche la exposici�n es muy iluminada, una exposici�n m�s baja en la noche es necesaria. O, si las im�genes despu�s del atardecer son muy oscuras, un valor m�s alto debe ser utilizado. Una configuraci�n de Exposici�n Nocturna de 0 mantendr� el d�a y la noche con la misma luminosidad.

Opci�n | Descripci�n
------ | -------
Exposici�n nocturna | Diferencia relativa de exposici�n de la noche vs. El d�a.
Algoritmo de ramping | M�todo utilizado para la exposici�n de auto ramping [1]
ISO m�ximo | L�mite de ISO superior para el auto ramping
ISO m�nimo | L�mite de ISO inferior para el auto ramping
Obturador m�xima | Las velocidades de obturaci�n m�s largas a utilizar durante el ramping
Par�metros de ramping| Qu� par�metros utilizar para el ramping [2]
Apertura m�nima | Apertura m�nima para utilizar el ramping, p.e., f2.8 (mostrar solamente si los Par�metros de Ramping incluyen apertura)
Apertura m�xima | Apertura m�xima para utilizar el ramping, p.e., f11 (mostrar solamente si los Par�metros de Ramping incluyen apertura)

[1] La Luminosidad PID es la presentad por defecto y en el original, y el m�todo de LRTimelapse fue introducido por Gunther Wegner como m�todo alternativo y ha estado funcionando bien desde la versi�n v1.7.8. El M�todo de Luminosidad PID cuenta con m�ltiples capas y hace un seguimiento de la tasa de cambio de la luminosidad promedio de la imagen (con un peso extra para clipping) y predice la exposici�n esperada para el pr�ximo cuadro. Limita el tiempo de respuesta para ofrecer transiciones suaves y funciona en ambas direcciones (atardecer y amanecer) al mismo tiempo. El m�todo LRTimelapse es diferente porque se basa en el histograma, simplemente aumentando o disminuyendo la exposici�n para mantener un histograma similar y evitar el clipping. Esto permite cambios m�s r�pidos (hasta 1/3 pasos por marco) y los resultados predecibles. �Cu�l es mejor? Buena pregunta � si no te gustan los resultados con uno, prueba el otro, y cu�ntame tu experiencia en  https://www.timelapseplus.com/contact

[2] La opci�n de �balance� intenta mover la velocidad de obturaci�n y el ISO al mismo tiempo, para aumentar m�s gradualmente la velocidad de disparo. La otra configuraci�n da prioridad al ISO m�s bajo posible.

## Apertura manual

Esta opci�n solamente se muestra cuando la configuraci�n de apertura del lente no puede leerse desde la c�mara, como cuando se utiliza un lente manual o el m�todo de giro de lente.

Ingresa la configuraci�n de apertura del lente aqu� para ayudar en el c�lculo de los valores de exposici�n absoluta en los intervalos del d�a/noche y la compensaci�n de la exposici�n.

Opci�n | Descripci�n
------ | -------
[apertura] | La apertura es el valor en el que el lente est� definido o bloqueado (en caso del giro de lentes).

## Destino

Esta opci�n solamente se muestra cuando una tarjeta SD es insertada en el VIEW. Las c�maras Sony requieren que las im�genes sean guardadas en la tarjeta SD del VIEW.

Opci�n | Descripci�n
------ | -------
C�mara |Mantener las im�genes en la tarjeta de la c�mara. Para el auto ramping, los archivos XMP necesitar�n ser guardados posteriormente e incorporados con los archivos de la c�mara (a ser descritos en la secci�n de post-procesamiento m�s adelante). Esto se recomienda para un mejor desempe�o e intervalos m�s cortos.
Tarjeta SD | Guarda las im�genes del time-lapse en su propia carpeta en la ra�z de la tarjeta SD, junto con los archivos XMP para Lightroom. Esto simplifica el post-procesamiento y la organizaci�n porque las correcciones de exposici�n para eliminar los saltos ser�n importadas autom�ticamente a Lightroom junto con las im�genes, pero requiere intervalos m�s largos porque hay que transmitir las im�genes por USB.

## COMENZAR

Si ya has introducido la configuraci�n, �selecciona esta opci�n para comenzar el time-lapse! Mientras est� funcionando, puedes seleccionar la �Vista Previa� para revisar los resultados en el proceso, o selecciona �CORRIENDO� para una confirmaci�n de cancelaci�n. Esta pantalla de estatus sigue siendo la m�s b�sica y ser� mejorada en un pr�ximo lanzamiento.

