# Control de movimiento

El VIEW puede sincronizar con la mayor�a de los sistemas de control de movimiento para la funcionalidad de disparar-moverse-disparar. Adicionalmente, cuenta con un soporte de programaci�n de movimiento completo para el controlador de pasos Dynamic Perception NMX (a trav�s de Bluetooth o USB) y Syrp Genie Minie (a trav�s de Bluetooth) y se planifica que en el futuro se incorporar� el soporte para eMotimo Spectrum (a trav�s del serial AUX2) y Kessler Second Shooter (probablemente).

# Sincronizaci�n de AUX de salida

Para activar un sistema de movimiento, para que se mueva despu�s de cada disparo, conecta un cable TRS de 2,5 mm del AUX2 en el VIEW con el puerto de entrada de sincronizaci�n en el sistema de movimiento. El VIEW enviar� 200ms de pulso �cerrado� despu�s de cada disparo. No se requiere ninguna configuraci�n especial en VIEW. El sistema de movimiento necesita el soporte de un interval�metro externo y normalmente debe estar en una modalidad especial (p.e., modalidad �esclava� para el NMX�, �interval�metro externo� para eMotimo TB3).

## Disparador externo

Esta es la opci�n m�s vers�til y deber�a trabajar con cualquier sistema que tenga un disparador de c�mara para disparar-mover-disparar. Esta es la �nica opci�n para un sistema que no soporte una sincronizaci�n auxiliar externa (como el Syrp Genie). En esta modalidad, el intervalo es definido externamente por el sistema de movimiento, y el VIEW trabaja alineado entre el sistema de movimiento y la c�mara para gestionar la exposici�n.

Para utilizar un disparador externo, coloca la Modalidad de Intervalo en �AUX2 externo� en el men� de configuraci�n de lapsos de tiempo. Conecta el puerto de control de movimiento de la c�mara al puerto AUX2 de VIEW con un cable TRS 2,5 mm (TRRS no funciona). La c�mara est� conectada al puerto USDB de VIEW como siempre. Una vez que se inicia, el VIEW esperar� por la se�al del sistema de movimiento para disparar cada cuadro.

Con esta configuraci�n, el VIEW gestiona la exposici�n y ramping, y el movimiento e intervalo son definidos por el sistema de movimiento. Debido a que VIEW no est� controlando el intervalo, no pueden realizarse intervalos variables.

## Dynamic Perception NMX

Adem�s de los m�todos anteriores, en controlador NMX puede conectarse a trav�s de USDB o Bluetooth para una programaci�n de movimiento completo. La programaci�n de movimiento debe hacerse a trav�s de la aplicaci�n m�vil para el VIEW debido a que no est� soportado actualmente en la interfaz independiente.

### Conexi�n Bluetooth NMX

<i>Nota: para este m�todo, el firmware beta v1.8 m�s actualizado debe estar instalado en VIEW.</i>  Para conectar con el NMX a trav�s de Bluetooth, primero activa la conexi�n Bluetooth en el VIEW en Configuraci�n->Conexiones inal�mbricas->Activar Bluetooth (si solamente se muestra la opci�n de �Desactivar Bluetooth�, entonces ya est� activado). Aseg�rate de que la aplicaci�n NMX no est� conectada al NMX, debido a que esto no le permitir� al VIEW conectarse (apaga el BT del tel�fono de ser necesario). Con el Bluetooth activado, el VIEW autom�ticamente se conectar� con el primer controlador NMX disponible al ser encendido. Un peque�o �cono de Bluetooth aparecer� en la barra superior de VIEW una vez que se haya conectado. Entonces se puede configurar a trav�s de la aplicaci�n WiFi VIEW como se muestra en este video: https://vimeo.com/237150285

### Conexi�n USDB NMX

Para conectar con el NMX a trav�s del USB, se necesitar� una conexi�n USB adicional al puerto USB (una para la c�mara, una para el NMX). Conecta una extensi�n peque�a de USB al VIEW, y despu�s conecta la c�mara y el NMX al centro y conecta la electricidad al NMX (�en este orden!). Se recomienda desactivar el BT tanto en el VIEW como en el tel�fono en este caso para evitar cualquier problema. Un peque�o �cono de Bluetooth aparecer� en la barra superior de VIEW una vez que se haya conectado. Entonces se puede configurar a trav�s de la aplicaci�n WiFi VIEW como se muestra en este video: https://vimeo.com/237150285

El USB tiene la ventaja de ser m�s confiable y no verse afectado por temperaturas fr�as.

Importante: el NMX debe ser conectado primero a trav�s de USB, despu�s a la corriente externa � si el NMX est� conectado a la electricidad antes de conectarlo al USB, no ser� detectado.

## Syrp Genie Mini
El VIEW puede controlar completamente el Syrp Genie Mini a trav�s de Bluetooth, permitiendo una programaci�n de movimiento de m�ltiples cuadros. Se requiere el firmware v1.8 beta m�s actualizado en el VIEW, y el Genie Mini tambi�n debe tener su firmware actualizado. Considera que al controlar el Genie Mini a trav�s de VIEW no ser� posible utilizar la aplicaci�n Syrp al mismo tiempo, por lo que es mejor desactivar el BT en el tel�fono para evitar interferencias.

Para conectar el Genie Mini al VIEW, primero activa Bluetooth en el VIEW en Configuraci�n->Conexiones inal�mbricas->Activar Bluetooth (si solamente se muestra la opci�n de �Desactivar Bluetooth�, entonces ya est� activado). Despu�s enciende el Genie Mini y espera que aparezca el �cono de Bluetooth en la barra superior de la pantalla de VIEW. Actualmente, se pueden conectar hasta dos Genie Minis al mismo tiempo (como para la opci�n de pan/tilt). Cada uno puede configurarse en la aplicaci�n WiFi de VIEW, similar a la configuraci�n NMX que se muestra a continuaci�n: <https://vimeo.com/237150285>.  Tambi�n puedes ver <https://vimeo.com/235979676> para descubrir una configuraci�n r�pida sin la aplicaci�n.

Si lo prefieres, el Genie Mini tambi�n puede programarse por separado y despu�s sincronizado con el VIEW para la funcionalidad de disparar-mover-disparar. Este es el m�todo de �Disparador Externo� que se muestra arriba. Conecta el puerto de la c�mara en el Genie Mini al puerto AUX2 en el VIEW con un cable TRS de 2,5 mm (TRRS no funcionar�) y despu�s configura la modalidad de Intervalos en el VIEW a �AUX2 Externo�. En esta configuraci�n, el VIEW dispara cada cuadro cuando lo indica el Mini mientras gestiona el ramping, y el Mini gestiona el movimiento y los intervalos conforme lo define la aplicaci�n Syrp.
