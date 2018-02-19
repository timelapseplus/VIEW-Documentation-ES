# Aplicación remota

El Intervalómetro VIEW puede ser controlado y monitoreado a través de una aplicación web para dispositivos móviles. Cualquier dispositivo que tenga un buscador web puede acceder al mismo, pero solamente está optimizado para el tamaño de las pantallas móviles. No hay ninguna aplicación publicada en tiendas de aplicaciones, en lugar de esto, se puede descargar directamente del VIEW.

Hay dos métodos para conectarse al VIEW desde un dispositivo móvil, un método de WiFi local y un método de Internet.

### Ventajas del Método Local:

* No se requiere Internet, funciona en ubicaciones remotas.
* Conexiones de baja latencia, genial para transmitir en Live View durante la configuración.

### Desventajas del Método Local:

* Solamente funciona dentro del rango WiFi del VIEW.
* Internet no funcionará en el dispositivo móvil mientras esté conectado al VIEW.

### Ventajas del Método Web:

* ¡Accede al VIEW desde cualquier parte del mundo!
* El dispositivo móvil puede conectarse a Internet como lo haría normalmente.

### Desventajas del Método Web:

* El VIEW debe estar dentro del rango de acceso de un punto de WiFi para Internet (puedes utilizar un hotspot móvil).
* Mayor latencia, por lo que podrás experimentar un poco de ralentización con liveview. 


## Método de WiFi Local

![WiFi Setup Diagram](view-app-wifi.png)

Para configurar la interfaz de la aplicación con WiFi Local, configura lo siguiente en VIEW:

1. Activa el WiFi (en caso de que no esté activado): Configuración -> Conexiones inalámbricas -> Activar Wifi
2. Modo de Activar Punto de Acceso: Configuración -> Conexiones inalámbricas -> Activar el Punto de Acceso Incorporado (si falta esta opción quiere decir que ya ha sido activada)

Posteriormente, en el dispositivo móvil:

1. Conectar al punto de acceso WiFi TL+VIEW.
2. Abre un buscador web y dirígete a 10.0.0.1.

Eso es todo – la aplicación se cargará en el buscador. En un iPhone, puedes guardarla en la pantalla de inicio para un uso a conveniencia como una aplicación de pantalla completa. 

El nombre del punto de acceso incorporado puede cambiarse en Configuración -> Conexiones Inalámbricas -> Configurar nombre del Punto de Acceso Incorporado.

## Método de Internet Remoto

![Web Setup Diagram](view-app-web.png)

Para configurar la interfaz de la aplicación web remota, configura lo siguiente en el VIEW:

1. Activa el WiFi (en caso de que no esté activado): Configuración -> Conexiones inalámbricas -> Activar Wifi
2. Conectar a un punto de acceso cercano: Configuración -> Conexiones inalámbricas -> Conectarse a la red
3. Ingresa la contraseña de la red en caso de ser necesario (asegúrate de introducirla correctamente, incluyendo mayúsculas y minúsculas). Utiliza el botón de contexto en la esquina inferior derecha para cambiar entre mayúsculas/minúsculas/números/símbolos. Presiona el botón de inicio en la pantalla de la contraseña para más instrucciones.
4. Una vez que el VIEW se conecte (únicamente la primera vez), aparecerá un número en la pantalla. Necesitarás este número para el paso 4.

Posteriormente, en el dispositivo móvil:

1. Abre un buscador web y ve a app.view.tl
2. Inicia sesión utilizando tu dirección de correo electrónico. Si necesitas registrarte, se te pedirá que crees un subdominio (para acceder en yoursubdomain.view.tl) y una contraseña.
3. Una vez que inicies sesión, si es la primera vez, presiona “Agregar Dispositivo” (si lo has hecho antes no tendrás que volver a hacerlo).
4. Ingresa los números presentados en la pantalla VIEW.

Eso es todo – la aplicación se cargará en el buscador. En un iPhone, puedes guardarla en la pantalla de inicio para su uso a tu conveniencia como una aplicación de pantalla completa. 


