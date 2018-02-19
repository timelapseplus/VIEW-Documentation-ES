# Actualización de Firmware

El Intervalómetro VIEW puede actualizarse por sí mismo – no es necesario utilizar un computador, simplemente se necesita un punto de acceso WiFi con conexión a Internet.

El firmware está cargado directamente de las publicaciones de github, también puedes buscar el firmware disponible aquí: <a href='https://github.com/timelapseplus/VIEW/releases/' target='_blank'>github.com/timelapseplus/VIEW/releases/</a>

La versión actual del firmware es presentada en la línea superior de la pantalla en el VIEW cuando una cámara no está conectada. También puede encontrase en Información->Información de sistema.

## Actualización a través de Wifi

Este suele ser el método más fácil, siempre que haya una conexión a Internet inalámbrica disponible. Considera que el VIEW no puede cargarse en portales cautivos (como el WiFi de un hotel, en donde debes iniciar sesión con tu número de habitación), en ese caso, se puede utilizar el método con tarjeta SD que se describe a continuación.

### Paso 1: Conecta el VIEW al Internet

En primer lugar, el VIEW debe estar conectado a Internet. Sigue estas instrucciones para conectarte al punto de acceso WiFi para tener conexión a Internet:

1. Activar WiFi (en caso de que ya no esté activado): Configuración -> Conexiones inalámbricas -> Activar WiFi.
2. Conectarse a un punto de acceso cercano: Configuración -> Conexiones inalámbricas -> Conectar a la red
3. Ingresa la contraseña de la red en caso de ser necesario (asegúrate de introducirla correctamente, incluyendo mayúsculas y minúsculas). Utiliza el botón de contexto en la esquina inferior derecha para cambiar entre mayúsculas/minúsculas/números/símbolos. Presiona el botón de inicio en la pantalla de la contraseña para más instrucciones.

Puedes ignorar cualquier mensaje de ingresar un código – simplemente presiona el botón de cancelar.

### Paso 2: Actualizar firmware

Posteriormente, navega a Configuración -> Versión del Software. Si está conectado exitosamente al Internet, se retrasará unos segundos mientras descarga la información más actualizada del firmware. En caso de que no haya conexión con Internet, solamente se mostrarán las versiones previamente instaladas (esto es para que siempre puedas utilizar alguna de las anteriores, incluso cuando no haya Internet). Si solamente se cargan las versiones instaladas, vuelve al paso 1 descrito anteriormente y verifica que la contraseña de la red sea correcta, o intenta desde un punto de acceso diferente.

Una vez que se haya cargado el menú de Versión de Software, puedes seleccionar la versión firmware que vas a instalar. Presiona el botón de encendido para leer las notas de publicación de la versión seleccionada. Presiona la perilla o el botón de aceptar para instalar la versión seleccionada. Siempre lo más recomendado es utilizar la versión más reciente.

La instalación puede tomar entre 5 y 30 minutos, dependiendo de la calidad de la conexión. Una vez que se haya finalizada, el sistema se volverá a cargar, y presentará la pantalla de inicio. En caso de que falle, regresará al menú de Versiones del Software (una mejor retroalimentación en la interfaz del usuario será agregada en el futuro). 

Las actualizaciones de Firmware serán exitosas o fallarán – no se quedarán atascadas generando problemas de funcionamiento. Sin embargo, es posible que la descarga se detenga si hay una interrupción en la red (estamos trabajando para mejorar esto). Si después de aproximadamente 15 minutos el VIEW sigue indicando que está descargando el firmware, puede que sea necesario forzar un reinicio. Sujeta el botón de encendido durante quince segundos para apagar, y después durante 2 segundos para volver a encender. Se cargará la versión anterior del firmware y podrás probar de nuevo la actualización. Una actualización futura ofrecerá una mejor gestión y reporte de errores, además del reporte del progreso (como la barra de progreso de la descarga).

## Actualizar a través de Tarjeta SD

<aside class="notice">Este método solamente funciona con el firmware v1.7.0 o versiones más recientes. Después de actualizar a la versión v1.7.0 o una más reciente, es posible instalar versiones anteriores y seguir contando con la actualización a través de tarjeta SD.</aside>

1. Utilizando un computador con acceso a Internet, descarga el archivo zip con el código fuente del firmware más actualizado de las siguientes páginas de publicaciones: <a href='https://github.com/timelapseplus/VIEW/releases/' target='_blank'>github.com/timelapseplus/VIEW/releases/</a>
2. Copia el archivo zip descargado de la carpeta raíz en la tarjeta SD (no tiene que estar vacía, solamente debe tener suficiente espacio para el archivo zip). No cambies el nombre del archivo zip – el nombre es utilizado por el VIEW para reconocer el firmware y la versión.
3. Inserta la tarjeta SD con el archivo zip en el VIEW.
4. En el VIEW, ve a Configuración->Versión del Software->Instalar desde la tarjeta SD para comenzar la instalación. Si hay más de un archivo zip de firmware en la tarjeta SD, se seleccionará automáticamente la versión más reciente.

<aside class="notice">Si por alguna razón el sistema está corrupto y el VIEW no puede pasar de la pantalla de inicio, el sistema puede restaurarse sujetando el botón de encendido durante 15 segundos para apagar, después inserta la tarjeta SD con el archivo zip del firmware, enciende presionando el botón de encendido durante 2 segundos y después sujeta el botón de aceptar (el del medio a la derecha) hasta que aparezca la pantalla de “Actualizando…”. Posteriormente, se instalará el firmware de la tarjeta para un nuevo inicio.</aside>

