# Post-procesamiento

Conforme el VIEW cambia la exposición para el proceso de ramping, los cambios son hechos en 1/3 de paso, debido a que no se pueden hacer cambios más sutiles en la cámara. Esto genera diferencias de iluminación en el time-lapse que pueden percibirse como parpadeos y debe corregirse en el post-procesamiento. Hay diversas formas de hacer esto, pero la mayoría requiere el uso del programa Lightroom o Photoshop de la Suite de Adobe. En el futuro, planeo agregar un soporte de Darktable. Hemos recibido muchas solicitudes para el Capture One, pero debido a su soporte limitado para la integración de terceras partes, probablemente esto no sea posible. 

Abajo se encuentra una lista de métodos de procesamiento. Si eres nuevo en esto, te recomiendo que revises el complemento de Timelapse Workflow. Si ya estás utilizando LRTimelapse, sigue utilizándolo, debido a que VIEW se integrará adecuadamente en tu flujo de trabajo actual.

## Utilizando el complemento de Timelapse Workflow 

Para la mayoría de los usuarios, esta es la forma más fácil y rápida de post-procesamiento. No se necesitan archivos XMP y puedes editar cualquier cosa, incluyendo la exposición, y el complemento lo suavizará. Descarga y lee la documentación aquí: <https://www.timelapseworkflow.com/documentation.html>

El complemento Timelapse Workflow funciona con Lightroom 6 y versiones más nue vas.

El complemento es gratuito para todos los usuarios VIEW. Sigue las instrucciones de registro para los usuarios de VIEW aquí:
<https://www.timelapseworkflow.com/documentation.html#registration>

## Utilizando LRTimelapse

Al utilizar LRTimelapse, los archivos XMP de VIEW no son necesarios debido a que LRTimelapse fundirá suavemente los cambios de exposición (aunque pueden ser utilizados si lo deseas). Simplemente sigue el flujo de trabajo estándar de LRTimelapse como se describe aquí:
<https://forum.lrtimelapse.com/Thread-using-the-timelapse-view-with-lrtimelapse>

En el momento de hacer el post-procesamiento con LRTimelapse, está bien ajustar la exposición, debido a que LRTimelapse gestionará las transiciones.

LRTimelapse funciona con Lightroom, además de con Bridge/ACR.

# Utilizar XMPs generados en el VIEW

El VIEW puede generar archivos XMP para ofrecer los datos de corrección de exposición para que Lightroom elimine los parpadeos. Este método funciona con Lightroom, además de con Bridge/ARCR.

Si las imágenes fueron guardadas en la tarjeta SD del VIEW (Destino = “Trajeta SD”), entonces, los datos para eliminar el parpadeo ya estarán ahí a la hora de importar en Lightroom. Simplemente hay que tener cuidado de no cambiar el control de exposición. Todos los demás controles pueden utilizarse en el modo de desarrollo.

Si las imágenes fueron guardadas en la cámara (Destino = “Cámara”), entonces los XMPs deben ser incorporados en la misma carpeta que las imágenes RAW.

Para recuperar los XMPs para los clips que fueron guardados por la cámara, dirígete a Clips de Time-lapse, selecciona el clip, presiona el menú (abajo a la derecha) y selecciona “Escribir XMPs en la tarjeta SD”. Este paso es necesario incluso si había una tarjeta SD presente en el VIEW mientras se grababa con la cámara.

Para los cambios en las transiciones con respecto al balance de blancos u otros parámetros de Lightroom (sin embargo, considera que no se puede cambiar la exposición en este método), prueba el complemento de “Soporte de Timelapse” de Jeffrey Friedl: <http://regex.info/blog/lightroom-goodies/timelapse-support>

## Eliminar el parpadeo durante el render

Esto no es lo ideal, pero si prefieres procesar las fotos en Capture One u otro programa diferente a Lightroom, la eliminación del parpadeo puede hacerse sobre las imágenes resultantes después de la conversión inicial de RAW. Las herramientas para hacer esto incluyen GBDeflicker, TLDF y Sequence. 
