# **CONCEPTO DE WEB SERVICE**

Web Service se basa en una vía de interoperabilidad e intercomunicación a través de internet entre dos máquinas o aplicaciones. La interacción que existe entre estas máquinas se basa en el envío de solicitudes y respuestas entre un cliente y un servidor:

*	El cliente solicita información al servidor.
*	El servidor genera una respuesta que envía devuelta al cliente.

Incluso, a este tipo de tecnología se le caracteriza por sus dos rasgos principales.

*	Multiplataforma: pueda ser que las maquinas no cuenten con la misma configuración para comunicarse, pero Web Service se encarga de hacerlo posible.
*	Distribuido: mas de un cliente puede acceder al servicio a través de internet.
## **Historia**
* Primero llegó SOAP

La primera introducción de los web services en el mundo de Internet 
vino de la mano de SOAP. SOAP es un protocolo que define cómo deben 
de realizarse las comunicaciones entre máquinas. SOAP usa XML como 
lenguaje de intercambio de datos con una estructura compleja que es 
capaz de albergar todo tipo de datos sobre la solicitud o respuesta generada.

* Luego llegó REST

REST usa el propio protocolo HTTP para la comunicación entre máquinas. HTTP es ampliamente soportado por todos los sistemas y de hecho para la transferencia de datos en la web se usa HTTP.

REST se caracteriza por no tener estado. Es decir, el servidor no es capaz de recordar el estado de la anterior solicitud REST que pudo, o no, hacer un cliente. Por ello, el cliente tiene que enviar en cada solicitud todo el estado de su sesión, lo que se suele hacer mediante un token que le «ayude a recordar» al servidor.

* XML Vs JSON
Para los sistemas de comunicación entre máquinas se requiere una serie de características, básicamente marcadas porque las máquinas implicadas en la comunicación pueden tener sistemas muy diferentes.
* XML está basado en etiquetas, como HTML. Es más tradicional pero también es un lenguaje más avanzado, que presenta diversas utilidades para su extensión, validación de la información y sintaxis de los datos.
* JSON es un lenguaje más nuevo, basado en sintaxis Javascript. Generalmente, es más ligero y requiere mucho mejor carga del servidor para su procesamiento.

## **TIPOS DE WEB SERVICE**

**SOAP:** Es un protocolo que define como deben de comunicarse las máquinas, además utiliza XML como lenguaje de intercambio de datos.
**REST:** Usa el protocolo HTTP para la comunicación entre máquinas, ya que es altamente soportado por todos los sistemas.

## **LENGUAJES DE COMUNICACIÓN**

**XML:** Esta basado en etiquetas al igual que HTML, entre sus diversas utilidades se encuentra la validación de información y sintaxis de datos.
**JSON:** Es un lenguaje más ligero basado en JavaScript, además requiere más carga del servidor para su procesamiento.
