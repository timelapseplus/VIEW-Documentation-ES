# Aplicaci�n remota

El Interval�metro VIEW puede ser controlado y monitoreado a trav�s de una aplicaci�n web para dispositivos m�viles. Cualquier dispositivo que tenga un buscador web puede acceder al mismo, pero solamente est� optimizado para el tama�o de las pantallas m�viles. No hay ninguna aplicaci�n publicada en tiendas de aplicaciones, en lugar de esto, se puede descargar directamente del VIEW.

Hay dos m�todos para conectarse al VIEW desde un dispositivo m�vil, un m�todo de WiFi local y un m�todo de Internet.

### Ventajas del M�todo Local:

* No se requiere Internet, funciona en ubicaciones remotas.
* Conexiones de baja latencia, genial para transmitir en Live View durante la configuraci�n.

### Desventajas del M�todo Local:

* Solamente funciona dentro del rango WiFi del VIEW.
* Internet no funcionar� en el dispositivo m�vil mientras est� conectado al VIEW.

### Ventajas del M�todo Web:

* �Accede al VIEW desde cualquier parte del mundo!
* El dispositivo m�vil puede conectarse a Internet como lo har�a normalmente.

### Desventajas del M�todo Web:

* El VIEW debe estar dentro del rango de acceso de un punto de WiFi para Internet (puedes utilizar un hotspot m�vil).
* Mayor latencia, por lo que podr�s experimentar un poco de ralentizaci�n con liveview. 


## M�todo de WiFi Local

![WiFi Setup Diagram](view-app-wifi.png)

Para configurar la interfaz de la aplicaci�n con WiFi Local, configura lo siguiente en VIEW:

1. Activa el WiFi (en caso de que no est� activado): Configuraci�n -> Conexiones inal�mbricas -> Activar Wifi
2. Modo de Activar Punto de Acceso: Configuraci�n -> Conexiones inal�mbricas -> Activar el Punto de Acceso Incorporado (si falta esta opci�n quiere decir que ya ha sido activada)

Posteriormente, en el dispositivo m�vil:

1. Conectar al punto de acceso WiFi TL+VIEW.
2. Abre un buscador web y dir�gete a 10.0.0.1.

Eso es todo � la aplicaci�n se cargar� en el buscador. En un iPhone, puedes guardarla en la pantalla de inicio para un uso a conveniencia como una aplicaci�n de pantalla completa. 

El nombre del punto de acceso incorporado puede cambiarse en Configuraci�n -> Conexiones Inal�mbricas -> Configurar nombre del Punto de Acceso Incorporado.

## M�todo de Internet Remoto

![Web Setup Diagram](view-app-web.png)

Para configurar la interfaz de la aplicaci�n web remota, configura lo siguiente en el VIEW:

1. Activa el WiFi (en caso de que no est� activado): Configuraci�n -> Conexiones inal�mbricas -> Activar Wifi
2. Conectar a un punto de acceso cercano: Configuraci�n -> Conexiones inal�mbricas -> Conectarse a la red
3. Ingresa la contrase�a de la red en caso de ser necesario (aseg�rate de introducirla correctamente, incluyendo may�sculas y min�sculas). Utiliza el bot�n de contexto en la esquina inferior derecha para cambiar entre may�sculas/min�sculas/n�meros/s�mbolos. Presiona el bot�n de inicio en la pantalla de la contrase�a para m�s instrucciones.
4. Una vez que el VIEW se conecte (�nicamente la primera vez), aparecer� un n�mero en la pantalla. Necesitar�s este n�mero para el paso 4.

Posteriormente, en el dispositivo m�vil:

1. Abre un buscador web y ve a app.view.tl
2. Inicia sesi�n utilizando tu direcci�n de correo electr�nico. Si necesitas registrarte, se te pedir� que crees un subdominio (para acceder en yoursubdomain.view.tl) y una contrase�a.
3. Una vez que inicies sesi�n, si es la primera vez, presiona �Agregar Dispositivo� (si lo has hecho antes no tendr�s que volver a hacerlo).
4. Ingresa los n�meros presentados en la pantalla VIEW.

Eso es todo � la aplicaci�n se cargar� en el buscador. En un iPhone, puedes guardarla en la pantalla de inicio para su uso a tu conveniencia como una aplicaci�n de pantalla completa. 


