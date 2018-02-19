# Configuración de Time-Lapse

Comienza conectando la cámara a través de USB como se describe en la sección previa. Esto activará el menú de Time-lapse (el primer elemento en la pantalla principal). Presiona la perilla o el botón de aceptar para seleccionar. Verás las opciones enumeradas en esta sección.

<aside class="notice">IMPORTANTE: la cámara debe estar en modalidad manual, y debe designarse el formato RAW (no RAW+JPEG)</aside>

### Configuración rápida para la primera prueba
Para tu primera prueba de ramping automático, recomiendo que comiences con la siguiente configuración:

Configuración | Valor recomendado
------ | -------
Exposición | Simplemente configura la cámara para el escenario actual con anticipación y salta este paso.
Modalidad de Timelapse | Auto Ramping
Modalidad de intervalos | Auto Variable
Intervalos en el día | 8 segundos
Intervalos en la noche | 40 segundos
Destino | Cámara <sup>1</sup>

Recomiendo que comiences una hora antes del atardecer, colocando la cámara en el ISO más bajo, una apertura moderada de (f/2.8) y después configures la velocidad de disparo a cualquiera necesaria para una buena exposición (puede ser 1/3200). ¡Asegúrate de no sobreexponer!

Entonces, deja que corra durante al menos 3 horas después del atardecer para obtener una buena longitud y transición. O, si tienes una fuente externa de energía en la cámara, ¡déjalo correr hasta el amanecer!

Una vez que se ha completado el time-lapse, revisa la sección de <a href="#post-processing">post-procesamiento</a>.

<sup>1</sup> Para las cámaras Sony conectadas por USB, necesitas configurarlas a la “Tarjeta SD” y asegurarte de que la Tarjeta SD esté en el VIEW. Para las demás cámaras, el desempeño es mejor cuando se guarda directamente en la cámara. Sony puede guardar en la cámara cuando la conexión es a través de WiFi en lugar de USB (see <a href="#camera-specific-notes">camera-specific notes</a> for more).

### Opciones de Time-Lapse que se describen abajo

## Exposición

Coloca la cámara en modalidad de liveview para ajustar la exposición y el enfoque. Gira la perilla para aumentar/disminuir la exposición. Presiona el botón de aceptar para alternar la modalidad de enfoque. Estando en la modalidad de enfoque, la imagen de liveview será recortada a un 100% y la perilla ajustará el enfoque en lugar de la exposición.*


<aside class="notice">NOTA: la función de Exposición puede no funcionar bien en todas las cámaras. Si tienes algún problema con ella, simplemente ajusta la exposición y el enfoque en la cámara antes de conectarla al VIEW.</aside>

<aside class="success">Bien sea que se configure a través del menú de Exposición o en la cámara, la exposición de inicio para el ramping es muy importante conforme es la que será utilizada como referencia en el time-lapse. Asegúrate de que no esté sobreexpuesta, debido a que de haber demasiadas regiones con sobre exposición el ramping podría ser poco preciso.</aside>


## Modalidad Timelapse

Opción | Descripción
------ | -------
Fija | Esta opción es para un time-lapse básico en el que la exposición e intervalos sean constantes a través del Auto Ramping |En esta modalidad el VIEW se ajustará automáticamente a la exposición para coincidir con las condiciones del cambio de luz.

Para los clips de time-lapse de corto plazo, durante el día o la noche, en donde la exposición e intervalos sean constantes, elige Fija.


Para los atardeceres, amaneceres, pasos del día a la noche, de la noche al día, elige auto ramping. Esto también permitirá la opción de auto intervalo para el ramping de intervalos entre el día y la noche.

## Cámara principal

Esta opción solamente se nuestra cuando hay más de una cámara conectada al VIEW. La selección de cámara principal define la cámara utilizada para la configuración y el liveview, la pestaña de estatus y el seguimiento de la exposición. La configuración de la cámara principal es copiada a todas las cámaras adicionales conectadas y es activada con sincronización. Esto es genial para los panoramas, así como las vistas amplias y las vistas de telefotografía para las transiciones de post-procesamiento. En el caso de un panorama amplio o una telefotografía, da una vista amplia para un mejor seguimiento de exposición.

## Modo de intervalo

Esta opción solamente se muestra cuando la Modalidad de Timelapse está en “Auto Ramping”.

Opción | Descripción
------ | -------
Longitud fija |Esto mantiene el mismo intervalo a través del Time-Lapse y limitará la velocidad máxima de disparo para que se ajuste.
Auto Variable | Esta modalidad pasará automáticamente de los intervalos de día a los intervalos de noche y permitirá una velocidad de disparo más larga en la noche.

## Intervalo

Esta opción solamente es mostrada cuando la Modalidad Timelapse es definida en “Fija” o la Modalidad de Intervalo es definida en “Fija”.

Opción | Descripción
------ | -------
[tiempo en segundos] | Longitud de intervalo en segundos. Este es el tiempo entre el inicio de un cuadro y el inicio del siguiente.


## Cuadros

Esta opción solamente es mostrada cuando la Modalidad de Timelapse está en modalidad “Fija”. En la modalidad de Auto Ramping, el VIEW siempre funciona hasta que es detenido.

Opción | Descripción
------ | -------
[número de cuadros] | Cantidad de exposiciones a completar antes de detenerse


## Intervalo durante el día

Esta opción solamente se muestra cuando la modalidad de Timelapse está en “Auto Ramping” y la Modalidad de Intervalo está en “Auto Variable”.

Esto determina la duración del intervalo durante la luz del día, en base a la configuración de la exposición de la cámara. Se realizará el ramping de forma progresiva desde/hasta el Intervalo de Noche conforme las condiciones del ambiente (y la exposición de la cámara) cambien.

Opción | Descripción
------ | -------
[tiempo en segundos] | Longitud de intervalo en segundos. Este es el tiempo que transcurre desde el inicio de un marco hasta el inicio del siguiente

## Intervalo nocturno

Esta opción solamente se puede mostrar cuando la Modalidad de Timelapse está en “Auto Ramping” y la Modalidad de Intervalo está configurada en “Auto Variable”.

Esto determina la longitud del intervalo durante la noche, en base a la configuración de exposición de la cámara. Se realizará el ramping de forma progresiva desde/hasta el Intervalo de Día conforme las condiciones del ambiente (y la exposición de la cámara) cambien.



Opción | Descripción
------ | -------
[tiempo en segundos] | Longitud de intervalo en segundos. Este es el tiempo que transcurre desde el inicio de un marco hasta el inicio del siguiente


## Opciones de Ramping

Esta opción solamente se muestra cuando la Modalidad de Timelapse está en “Auto Ramping”.

En este menú, hay algunos detalles para configurar los límites del auto ramping. Considera que estas opciones pueden limitar el rango de ramping y por lo tanto hacer que no alcance la exposición correcta si está demasiado limitada. Para la mayoría de las cámaras, un ISO máximo de 6.400 funciona bien, con un límite inferior ISO de 100 (lo mejor es utilizar los ISOs nativos, no los más bajos).

La configuración de Exposición Nocturna define qué tan menos expuesta la “noche” noche tiene que estar en relación con el “día”. Por ejemplo, en una exposición nocturna de -1 (por defecto), la sub-exposición en la escena nocturna por 1 paso en comparación con el día. Entonces, si un auto ramping se inicia durante el día, y por la noche la exposición es muy iluminada, una exposición más baja en la noche es necesaria. O, si las imágenes después del atardecer son muy oscuras, un valor más alto debe ser utilizado. Una configuración de Exposición Nocturna de 0 mantendrá el día y la noche con la misma luminosidad.

Opción | Descripción
------ | -------
Exposición nocturna | Diferencia relativa de exposición de la noche vs. El día.
Algoritmo de ramping | Método utilizado para la exposición de auto ramping [1]
ISO máximo | Límite de ISO superior para el auto ramping
ISO mínimo | Límite de ISO inferior para el auto ramping
Obturador máxima | Las velocidades de obturación más largas a utilizar durante el ramping
Parámetros de ramping| Qué parámetros utilizar para el ramping [2]
Apertura mínima | Apertura mínima para utilizar el ramping, p.e., f2.8 (mostrar solamente si los Parámetros de Ramping incluyen apertura)
Apertura máxima | Apertura máxima para utilizar el ramping, p.e., f11 (mostrar solamente si los Parámetros de Ramping incluyen apertura)

[1] La Luminosidad PID es la presentad por defecto y en el original, y el método de LRTimelapse fue introducido por Gunther Wegner como método alternativo y ha estado funcionando bien desde la versión v1.7.8. El Método de Luminosidad PID cuenta con múltiples capas y hace un seguimiento de la tasa de cambio de la luminosidad promedio de la imagen (con un peso extra para clipping) y predice la exposición esperada para el próximo cuadro. Limita el tiempo de respuesta para ofrecer transiciones suaves y funciona en ambas direcciones (atardecer y amanecer) al mismo tiempo. El método LRTimelapse es diferente porque se basa en el histograma, simplemente aumentando o disminuyendo la exposición para mantener un histograma similar y evitar el clipping. Esto permite cambios más rápidos (hasta 1/3 pasos por marco) y los resultados predecibles. ¿Cuál es mejor? Buena pregunta – si no te gustan los resultados con uno, prueba el otro, y cuéntame tu experiencia en  https://www.timelapseplus.com/contact

[2] La opción de “balance” intenta mover la velocidad de obturación y el ISO al mismo tiempo, para aumentar más gradualmente la velocidad de disparo. La otra configuración da prioridad al ISO más bajo posible.

## Apertura manual

Esta opción solamente se muestra cuando la configuración de apertura del lente no puede leerse desde la cámara, como cuando se utiliza un lente manual o el método de giro de lente.

Ingresa la configuración de apertura del lente aquí para ayudar en el cálculo de los valores de exposición absoluta en los intervalos del día/noche y la compensación de la exposición.

Opción | Descripción
------ | -------
[apertura] | La apertura es el valor en el que el lente está definido o bloqueado (en caso del giro de lentes).

## Destino

Esta opción solamente se muestra cuando una tarjeta SD es insertada en el VIEW. Las cámaras Sony requieren que las imágenes sean guardadas en la tarjeta SD del VIEW.

Opción | Descripción
------ | -------
Cámara |Mantener las imágenes en la tarjeta de la cámara. Para el auto ramping, los archivos XMP necesitarán ser guardados posteriormente e incorporados con los archivos de la cámara (a ser descritos en la sección de post-procesamiento más adelante). Esto se recomienda para un mejor desempeño e intervalos más cortos.
Tarjeta SD | Guarda las imágenes del time-lapse en su propia carpeta en la raíz de la tarjeta SD, junto con los archivos XMP para Lightroom. Esto simplifica el post-procesamiento y la organización porque las correcciones de exposición para eliminar los saltos serán importadas automáticamente a Lightroom junto con las imágenes, pero requiere intervalos más largos porque hay que transmitir las imágenes por USB.

## COMENZAR

Si ya has introducido la configuración, ¡selecciona esta opción para comenzar el time-lapse! Mientras esté funcionando, puedes seleccionar la “Vista Previa” para revisar los resultados en el proceso, o selecciona “CORRIENDO” para una confirmación de cancelación. Esta pantalla de estatus sigue siendo la más básica y será mejorada en un próximo lanzamiento.

