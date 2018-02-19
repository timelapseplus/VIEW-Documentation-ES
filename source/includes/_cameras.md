# C�mara � Notas espec�ficas 

Esta secci�n incluye notas y temas espec�ficos sobre ciertas c�maras. Los temas espec�ficos de la c�mara ser�n corregidos en el firmware cuando sea posible, y retirados cuando sean resueltos. 

## Notas para todas las c�maras 

* Modo manual 
* Configuraci�n nativa para el ISO (no autom�tica)
* Guarda como RAR (no RAW+JPEG)
* Deshabilita cualquier reducci�n de ruido proveniente de una exposici�n alta
* El enfoque debe ser manual o con el bot�n de �regresar� (si el disparador activa el foco puede causar problemas) 
* Es mejor desactivar la estabilizaci�n de imagen 

## Sony Alpha (USB)

Las c�maras Sony pueden funcionar bien, pero hay diferentes cosas con las que el VIEW no cuenta actualmente, sino que tienen que ser configuradas en la c�mara para que pueda trabajar. 
Hay reportes que se�alan que no todos los cables USB funcionan con c�maras Sony, por lo que si no puedes conectar la tuya, entonces trata de cambiar el cable USB. 

Configura la c�mara de la siguiente forma:

1. Modo USB configurado en �Control remoto de PC�
2. Archivos RAW (no JPEG o RAW+JPEG)
3. Modo Manual, con un ISO nativo (no los n�meros del ISO que tienen una l�nea los mismos, ni tampoco el ISO autom�tico) 
4. Enfoque configurado en Manual (el bot�n de �regresar� funcionar� igualmente para el enfoque autom�tico, pero esto ayudar� a evitar que trate de enfocar en cada toma) 

En el men� de configuraci�n del time-lapse del VIEW, debe asignarse como destino la tarjeta SD. Inserta una tarjeta SD en el VIEW para que aparezca esta opci�n. Esto se requiere debido a una limitaci�n en el firmware de Sony que evita que sea posible salvar informaci�n en la tarjeta de la c�mara cuando la misma est� conectada v�a USB. 
La Sony A7RII requiere intervalos m�s largos debido al tama�o del archivo que usa el USB. Catorce segundos podr�an estar bien, aunque tambi�n es posible en menos tiempo. Otras c�maras Sony parecen completar el proceso en seis a ocho segundos para un intervalo m�nimo. Con la interfaz Wifi esto no representa un problema. 

## Sony Alpha (Wifi)

La mejor interfaz para Sony es el Wifi, ya que esta no tiene las limitaciones impuestas por la interfaz USB. 

Para conectar la c�mara v�a Wifi:

1. Abre la aplicaci�n �Control Remoto Inteligente� en la c�mara (�Debe contar con la actualizaci�n m�s reciente!). 
2. La c�mara mostrar� la informaci�n Wifi. Presiona el bot�n de �borrar� en la c�mara para mostrar la contrase�a. 
3. Conecta el Wifi de el VIEW (Ajustes->Configuraci�n inal�mbrica->Conectar a red) a la c�mara, utilizando la contrase�a mostrada en la pantalla de la segunda. 
4. El VIEW deber�a mostrar que la c�mara est� conectada luego de unos segundos, y la c�mara permitir� la funci�n de liveview de nuevo. 
5. IMPORTANTE: presiona el bot�n de men� de la c�mara y aseg�rate de que est� configurada en RAW+JPEG (peque�o).  En esta parte debe cambiarse la configuraci�n inicial de la c�mara, y como la opci�n de solamente RAW no es una opci�n se puede utilizar la opci�n de RAW+JPEG (peque�o). 

Cuando utilices la interfaz Wifi el time-lapse la configuraci�n del Destino debe estar en la opci�n �C�mara�. Luego de ello podr�s obtener el XMPs v�a el men� de clips con intervalo de tiempo. 

Una limitaci�n actual con el Wifi de Sony es que desde que la interfaz Wifi del VIEW se utiliza para la c�mara, y no es posible usar la aplicaci�n remota. Puede que en futuras actualizaciones de firmware aparezcan dos interfaces Wifi para solucionar este detalle. 
Algunas c�maras Sony permiten la opci�n de carga mientras se usa el puerto USB. Si esta opci�n est� habilitada, la bater�a del VIEW se agotar� r�pidamente, por lo que se recomienda algo de poder externo al VIEW. El VIEW no puede proveer suficiente poder a la c�mara para que cargue la bater�a durante su funcionamiento, pero si extender� la vida de la bater�a. Por lo que si usted tiene una bater�a completa en la c�mara y tiene una fuente de poder USB conectada al VIEW (como una estaci�n de carga de tel�fonos celulares), la combinaci�n total deber�a durar al menos 12 horas antes de que la bater�a de la c�mara se descargue lentamente. 

## Nikon

Muchas c�maras Nikon tienen la opci�n de mostrar o no la exposici�n simulada en el liveview.  Si est�s utilizando el men� de exposici�n o liveview mediante la aplicaci�n, entonces querr�s asegurarte de que la pantalla liveview muestre la exposici�n. En la D800 esto se cambia por un bot�n en la parte inferior izquierda. En la D5100, y posibles modelos anteriores y nuevos, no es posible simular la exposici�n con liveview. En este caso se puede usar una foto de prueba mediante la aplicaci�n de Smartphone. 

Nota: algunos dispositivos VIEW no se conectar�n con la Nikon D800/D800E hasta que se haya actualizado la versi�n de firmware v1.7.5 o una m�s nueva. 

## Panasonic

Aseg�rate de que el modo USB de la c�mara est� configurado en PTP 

## Fuji X

Nota: El soporte Fuji requiere la versi�n v1.8-beta13 o m�s nueva del firmware para el VIEW.  Ha sido probado con la X-T1 y X-T2, pero otras de la serie X deber�an funcionar siempre y cuando sean compatibles con el plugin Pro Tethering para Lightroom.  Aseg�rate de que el modo USB en la c�mara est� configurado en PC Autom�tico. El ISO debe ser ajustado manualmente a 200 o m�s alto. 

Algunas c�maras Fuji permiten la opci�n de carga mientras se usa el puerto USB. En este caso, la bater�a delVIEW se agotar� r�pidamente, por lo que se recomienda poder externo para el VIEW. En pruebas con un VIEW  y una X-T2 con cargas completas, fue posible lograr 1200 cuadros en 4 horas antes de que el VIEW se quedara sin bater�a (la c�mara todav�a ten�a bater�a ya que estaba siendo cargada por el VIEW). El VIEW no puede proveer suficiente poder a la c�mara para que se cargue mientras se est� utilizando, pero generalmente extender� la bater�a de la segunda. Por lo que si la bater�a de la c�mara est� completa y tienes una fuente de poder USB conectada al VIEW (como una estaci�n de carga de tel�fonos celulares), la combinaci�n total deber�a durar al menos 12 horas antes de que la bater�a de la c�mara se descargue lentamente. 
 
## Resumen de Soporte de C�maras 

Cuerpo de la c�mara | Auto Ramping | Ramping de enfoque | Liveview | Intervalo m�nimo de ramping
------------|--------------|---------------|----------|----------------- 
Nikon DSLRs | S�             | S�, generalmente | S�, generalmente| 3-4s
Canon DSLRs | S�              | S�, generalmente | S�, generalmente | 3-4s
Sony A7, A6000, A7S | S�     | No        | No (s� Wifi)     | 8-12s v�a USB, 4-5s v�a Wifi
Sony A7R    | S�             | No        | No (s� Wifi)      | 14-18s v�a USB, 4-5s v�a Wifi
Sony A7RII  | S�              | No        | S�       | 14-18s v�a USB, 4-5s v�a Wifi
Sony A7II, A6300, A6500, A7SII, A9 | S� | No  | S�       | 8-12s v�a USB, 4-5s v�a Wifi
Panasonic GH3, GH4 | S�          | No     | No | 4-7s
Panasonic GH5 | No (en planes) | No     | No (en planes) | --
Fuji X-T1 | S� | No | S� | 5-8s
Fuji X-T2 | S� | S� | S� | 3-4s
