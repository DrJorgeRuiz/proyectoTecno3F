# Chat con sockets

El proyecto final para Tecno3F, es un chat en *Java* con servidor y clientes, para que el servidor atienda y conecte a los clientes. Se plantea el uso de:
* Java Swing para crear la interfaz gráfica.
* Sockets para conectar las aplicaciones del servidor y clientes.
* Hilos para que el servidor pueda atender a múltiples clientes.

# Especificaciones

* Se deben controlar los casos de error para el número de conexiones:
  * Cliente desconectado
  * Cliente caído (connection timeout)
* Solo hay chat general
* Cuando un cliente se conecta al servidor su textArea estará vacío inicialmente.

## Servidor

- [x] Se arranca una ventana donde se muestra el número de conexiones actuales.

- [x] Contiene un textArea dónde se visualiza la información de quién sale y entra del chat y lo que escribe.

- [x] Hay un botón Salir que desconecta el servidor.

- [x] Se debe imponer un máximo de conexiones (3 a 5 sería ideal).

- [x] Para cada mensaje del usuario se muestra su nombre de usuario y el mensaje que ha escrito.

- [x] Debe aparecer el número de puerto que el servidor está usando y el número de clientes conectados.

## Cliente

- [x] En primer lugar se le pide un nick e intenta conectarse al servidor.

- [x] Si todo va bien se habilita esta misma ventana dónde se podrá escribir mensajes y enviarlos.

- [x] Debe aparece el número de clientes que hay conectados en el chat.
