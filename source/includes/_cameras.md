# Cámara – Notas específicas 

Esta sección incluye notas y temas específicos sobre ciertas cámaras. Los temas específicos de la cámara serán corregidos en el firmware cuando sea posible, y retirados cuando sean resueltos. 

## Notas para todas las cámaras 

* Modo manual 
* Configuración nativa para el ISO (no automática)
* Guarda como RAR (no RAW+JPEG)
* Deshabilita cualquier reducción de ruido proveniente de una exposición alta
* El enfoque debe ser manual o con el botón de “regresar” (si el disparador activa el foco puede causar problemas) 
* Es mejor desactivar la estabilización de imagen 

## Sony Alpha (USB)

Las cámaras Sony pueden funcionar bien, pero hay diferentes cosas con las que el VIEW no cuenta actualmente, sino que tienen que ser configuradas en la cámara para que pueda trabajar. 
Hay reportes que señalan que no todos los cables USB funcionan con cámaras Sony, por lo que si no puedes conectar la tuya, entonces trata de cambiar el cable USB. 

Configura la cámara de la siguiente forma:

1. Modo USB configurado en “Control remoto de PC”
2. Archivos RAW (no JPEG o RAW+JPEG)
3. Modo Manual, con un ISO nativo (no los números del ISO que tienen una línea los mismos, ni tampoco el ISO automático) 
4. Enfoque configurado en Manual (el botón de “regresar” funcionará igualmente para el enfoque automático, pero esto ayudará a evitar que trate de enfocar en cada toma) 

En el menú de configuración del time-lapse del VIEW, debe asignarse como destino la tarjeta SD. Inserta una tarjeta SD en el VIEW para que aparezca esta opción. Esto se requiere debido a una limitación en el firmware de Sony que evita que sea posible salvar información en la tarjeta de la cámara cuando la misma está conectada vía USB. 
La Sony A7RII requiere intervalos más largos debido al tamaño del archivo que usa el USB. Catorce segundos podrían estar bien, aunque también es posible en menos tiempo. Otras cámaras Sony parecen completar el proceso en seis a ocho segundos para un intervalo mínimo. Con la interfaz Wifi esto no representa un problema. 

## Sony Alpha (Wifi)

La mejor interfaz para Sony es el Wifi, ya que esta no tiene las limitaciones impuestas por la interfaz USB. 

Para conectar la cámara vía Wifi:

1. Abre la aplicación “Control Remoto Inteligente” en la cámara (¡Debe contar con la actualización más reciente!). 
2. La cámara mostrará la información Wifi. Presiona el botón de “borrar” en la cámara para mostrar la contraseña. 
3. Conecta el Wifi de el VIEW (Ajustes->Configuración inalámbrica->Conectar a red) a la cámara, utilizando la contraseña mostrada en la pantalla de la segunda. 
4. El VIEW debería mostrar que la cámara está conectada luego de unos segundos, y la cámara permitirá la función de liveview de nuevo. 
5. IMPORTANTE: presiona el botón de menú de la cámara y asegúrate de que esté configurada en RAW+JPEG (pequeño).  En esta parte debe cambiarse la configuración inicial de la cámara, y como la opción de solamente RAW no es una opción se puede utilizar la opción de RAW+JPEG (pequeño). 

Cuando utilices la interfaz Wifi el time-lapse la configuración del Destino debe estar en la opción “Cámara”. Luego de ello podrás obtener el XMPs vía el menú de clips con intervalo de tiempo. 

Una limitación actual con el Wifi de Sony es que desde que la interfaz Wifi del VIEW se utiliza para la cámara, y no es posible usar la aplicación remota. Puede que en futuras actualizaciones de firmware aparezcan dos interfaces Wifi para solucionar este detalle. 
Algunas cámaras Sony permiten la opción de carga mientras se usa el puerto USB. Si esta opción está habilitada, la batería del VIEW se agotará rápidamente, por lo que se recomienda algo de poder externo al VIEW. El VIEW no puede proveer suficiente poder a la cámara para que cargue la batería durante su funcionamiento, pero si extenderá la vida de la batería. Por lo que si usted tiene una batería completa en la cámara y tiene una fuente de poder USB conectada al VIEW (como una estación de carga de teléfonos celulares), la combinación total debería durar al menos 12 horas antes de que la batería de la cámara se descargue lentamente. 

## Nikon

Muchas cámaras Nikon tienen la opción de mostrar o no la exposición simulada en el liveview.  Si estás utilizando el menú de exposición o liveview mediante la aplicación, entonces querrás asegurarte de que la pantalla liveview muestre la exposición. En la D800 esto se cambia por un botón en la parte inferior izquierda. En la D5100, y posibles modelos anteriores y nuevos, no es posible simular la exposición con liveview. En este caso se puede usar una foto de prueba mediante la aplicación de Smartphone. 

Nota: algunos dispositivos VIEW no se conectarán con la Nikon D800/D800E hasta que se haya actualizado la versión de firmware v1.7.5 o una más nueva. 

## Panasonic

Asegúrate de que el modo USB de la cámara esté configurado en PC Tether, modo manual, archivos RAW, y toma soltera.  Con el GH5, GH5S, y G9, firmware v1.8-beta23 o mas nuevo es necesario en el VIEW. 

## Fuji X

Nota: El soporte Fuji requiere la versión v1.8-beta13 o más nueva del firmware para el VIEW.  Ha sido probado con la X-T1 y X-T2, pero otras de la serie X deberían funcionar siempre y cuando sean compatibles con el plugin Pro Tethering para Lightroom.  Asegúrate de que el modo USB en la cámara esté configurado en PC Automático. El ISO debe ser ajustado manualmente a 200 o más alto. 

Algunas cámaras Fuji permiten la opción de carga mientras se usa el puerto USB. En este caso, la batería del VIEW se agotará rápidamente, por lo que se recomienda poder externo para el VIEW. En pruebas con un VIEW  y una X-T2 con cargas completas, fue posible lograr 1200 cuadros en 4 horas antes de que el VIEW se quedara sin batería (la cámara todavía tenía batería ya que estaba siendo cargada por el VIEW). El VIEW no puede proveer suficiente poder a la cámara para que se cargue mientras se está utilizando, pero generalmente extenderá la batería de la segunda. Por lo que si la batería de la cámara está completa y tienes una fuente de poder USB conectada al VIEW (como una estación de carga de teléfonos celulares), la combinación total debería durar al menos 12 horas antes de que la batería de la cámara se descargue lentamente. 
 
## Resumen de Soporte de Cámaras 

Cuerpo de la cámara | Auto Ramping | Ramping de enfoque | Liveview | Intervalo mínimo de ramping
------------|--------------|---------------|----------|----------------- 
Nikon DSLRs | Sí             | Sí, generalmente | Sí, generalmente| 3-4s
Canon DSLRs | Sí              | Sí, generalmente | Sí, generalmente | 3-4s
Sony A7, A6000, A7S | Sí     | No        | No (sí Wifi)     | 8-12s vía USB, 4-5s vía Wifi
Sony A7R    | Sí             | No        | No (sí Wifi)      | 14-18s vía USB, 4-5s vía Wifi
Sony A7RII  | Sí              | No        | Sí       | 14-18s vía USB, 4-5s vía Wifi
Sony A7II, A6300, A6500, A7SII, A9 | Sí | No  | Sí       | 8-12s vía USB, 4-5s vía Wifi
Panasonic GH3, GH4 | Sí          | No     | No | 4-7s
Panasonic GH5, GH5S, G9 | Sí | No     | Sí | 4-5s
Fuji X-T1 | Sí | No | Sí | 5-8s
Fuji X-T2 | Sí | Sí | Sí | 3-4s
