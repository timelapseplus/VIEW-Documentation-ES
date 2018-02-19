# Actualizaci�n de Firmware

El Interval�metro VIEW puede actualizarse por s� mismo � no es necesario utilizar un computador, simplemente se necesita un punto de acceso WiFi con conexi�n a Internet.

El firmware est� cargado directamente de las publicaciones de github, tambi�n puedes buscar el firmware disponible aqu�: <a href='https://github.com/timelapseplus/VIEW/releases/' target='_blank'>github.com/timelapseplus/VIEW/releases/</a>

La versi�n actual del firmware es presentada en la l�nea superior de la pantalla en el VIEW cuando una c�mara no est� conectada. Tambi�n puede encontrase en Informaci�n->Informaci�n de sistema.

## Actualizaci�n a trav�s de Wifi

Este suele ser el m�todo m�s f�cil, siempre que haya una conexi�n a Internet inal�mbrica disponible. Considera que el VIEW no puede cargarse en portales cautivos (como el WiFi de un hotel, en donde debes iniciar sesi�n con tu n�mero de habitaci�n), en ese caso, se puede utilizar el m�todo con tarjeta SD que se describe a continuaci�n.

### Paso 1: Conecta el VIEW al Internet

En primer lugar, el VIEW debe estar conectado a Internet. Sigue estas instrucciones para conectarte al punto de acceso WiFi para tener conexi�n a Internet:

1. Activar WiFi (en caso de que ya no est� activado): Configuraci�n -> Conexiones inal�mbricas -> Activar WiFi.
2. Conectarse a un punto de acceso cercano: Configuraci�n -> Conexiones inal�mbricas -> Conectar a la red
3. Ingresa la contrase�a de la red en caso de ser necesario (aseg�rate de introducirla correctamente, incluyendo may�sculas y min�sculas). Utiliza el bot�n de contexto en la esquina inferior derecha para cambiar entre may�sculas/min�sculas/n�meros/s�mbolos. Presiona el bot�n de inicio en la pantalla de la contrase�a para m�s instrucciones.

Puedes ignorar cualquier mensaje de ingresar un c�digo � simplemente presiona el bot�n de cancelar.

### Paso 2: Actualizar firmware

Posteriormente, navega a Configuraci�n -> Versi�n del Software. Si est� conectado exitosamente al Internet, se retrasar� unos segundos mientras descarga la informaci�n m�s actualizada del firmware. En caso de que no haya conexi�n con Internet, solamente se mostrar�n las versiones previamente instaladas (esto es para que siempre puedas utilizar alguna de las anteriores, incluso cuando no haya Internet). Si solamente se cargan las versiones instaladas, vuelve al paso 1 descrito anteriormente y verifica que la contrase�a de la red sea correcta, o intenta desde un punto de acceso diferente.

Una vez que se haya cargado el men� de Versi�n de Software, puedes seleccionar la versi�n firmware que vas a instalar. Presiona el bot�n de encendido para leer las notas de publicaci�n de la versi�n seleccionada. Presiona la perilla o el bot�n de aceptar para instalar la versi�n seleccionada. Siempre lo m�s recomendado es utilizar la versi�n m�s reciente.

La instalaci�n puede tomar entre 5 y 30 minutos, dependiendo de la calidad de la conexi�n. Una vez que se haya finalizada, el sistema se volver� a cargar, y presentar� la pantalla de inicio. En caso de que falle, regresar� al men� de Versiones del Software (una mejor retroalimentaci�n en la interfaz del usuario ser� agregada en el futuro). 

Las actualizaciones de Firmware ser�n exitosas o fallar�n � no se quedar�n atascadas generando problemas de funcionamiento. Sin embargo, es posible que la descarga se detenga si hay una interrupci�n en la red (estamos trabajando para mejorar esto). Si despu�s de aproximadamente 15 minutos el VIEW sigue indicando que est� descargando el firmware, puede que sea necesario forzar un reinicio. Sujeta el bot�n de encendido durante quince segundos para apagar, y despu�s durante 2 segundos para volver a encender. Se cargar� la versi�n anterior del firmware y podr�s probar de nuevo la actualizaci�n. Una actualizaci�n futura ofrecer� una mejor gesti�n y reporte de errores, adem�s del reporte del progreso (como la barra de progreso de la descarga).

## Actualizar a trav�s de Tarjeta SD

<aside class="notice">Este m�todo solamente funciona con el firmware v1.7.0 o versiones m�s recientes. Despu�s de actualizar a la versi�n v1.7.0 o una m�s reciente, es posible instalar versiones anteriores y seguir contando con la actualizaci�n a trav�s de tarjeta SD.</aside>

1. Utilizando un computador con acceso a Internet, descarga el archivo zip con el c�digo fuente del firmware m�s actualizado de las siguientes p�ginas de publicaciones: <a href='https://github.com/timelapseplus/VIEW/releases/' target='_blank'>github.com/timelapseplus/VIEW/releases/</a>
2. Copia el archivo zip descargado de la carpeta ra�z en la tarjeta SD (no tiene que estar vac�a, solamente debe tener suficiente espacio para el archivo zip). No cambies el nombre del archivo zip � el nombre es utilizado por el VIEW para reconocer el firmware y la versi�n.
3. Inserta la tarjeta SD con el archivo zip en el VIEW.
4. En el VIEW, ve a Configuraci�n->Versi�n del Software->Instalar desde la tarjeta SD para comenzar la instalaci�n. Si hay m�s de un archivo zip de firmware en la tarjeta SD, se seleccionar� autom�ticamente la versi�n m�s reciente.

<aside class="notice">Si por alguna raz�n el sistema est� corrupto y el VIEW no puede pasar de la pantalla de inicio, el sistema puede restaurarse sujetando el bot�n de encendido durante 15 segundos para apagar, despu�s inserta la tarjeta SD con el archivo zip del firmware, enciende presionando el bot�n de encendido durante 2 segundos y despu�s sujeta el bot�n de aceptar (el del medio a la derecha) hasta que aparezca la pantalla de �Actualizando��. Posteriormente, se instalar� el firmware de la tarjeta para un nuevo inicio.</aside>

