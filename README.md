# web-app-Maven

Proyecto Maven Esta aplicación web que he desarrollado es una aplicación Java basada en el framework Maven. Aquí les doi un resumen descriptivo de su funcionamiento y características:

Lenguaje de Programación Utilizado: La aplicación web está desarrollada principalmente en Java. HTML, CSS, JavaScript, Servlets Java se utiliza tanto en el backend como en el frontend.

Servidor: La aplicación web se ejecuta en un servidor web Apache Tomcat.

Puerto: La aplicación web se ejecuta en el puerto estándar HTTP, que suele ser el puerto 8080 de forma predeterminada. Por lo tanto, para acceder a la aplicación, se utiliza la URL http://localhost:8080/pepin-webapp/registro.jsp que incluye el número de puerto.

Backend (RESTful Web Service): La aplicación incluye un backend que implementa un servicio web RESTful en Java. Este servicio web RESTful permite la creación y gestión de pólizas de vehículo y clientes. Utiliza el estándar REST para definir operaciones como GET, POST, PUT y DELETE para interactuar con los recursos de la aplicación.

Frontend (JSF): El frontend de la aplicación se desarrolla preferiblemente utilizando JavaServer Faces (JSF).

Registro de Pólizas y Vehículos: La principal funcionalidad de la aplicación es el registro de pólizas de vehículo para los clientes. Los clientes pueden tener múltiples pólizas, y cada póliza puede estar asociada a varios vehículos, para esto implementamos dos tablas en mysql una primary key foreign key para establecer las relaciones. 

Validación de Campos y Mensajes en la Interfaz: La aplicación cumple con el requisito de validar los campos y mostrar mensajes en la interfaz de usuario. Esto significa que se realizan comprobaciones de validación en los datos ingresados por el usuario en los formularios, y se muestran mensajes de error o confirmación en la interfaz según corresponda.

Mensajes de Error y Confirmación: La aplicación mostrará mensajes de error cuando se ingresen datos incorrectos o incompletos, y mostrará mensajes de confirmación cuando se registren pólizas o vehículos con éxito.

En resumen, esta aplicación web Maven es una aplicación Java que incluye un backend basado en un servicio web RESTful y un frontend preferiblemente desarrollado con JavaServer Faces (JSF). Cumple con los criterios de registro de pólizas de vehículos para clientes, validación de campos y mensajes en la interfaz de usuario, y se ejecuta en un servidor Apache Tomcat en el puerto estándar HTTP. La aplicación se utiliza para gestionar pólizas de vehículos y sus asociaciones con clientes.


NOTA: El código esta totalmente documentado.
Esta app es un prototipo tosco que no incluye CCS ya que es para testing. Dentro de este modelado no incluye Gestión de 
Validación de Entrada de Usuario
Sesiones
Autenticación y Autorización
Protección contra Cross-Site Scripting (XSS):
Protección contra Cross-Site Request Forgery (CSRF)
Seguridad de Contraseñas
Actualizaciones y Parches
Seguridad en la Capa de Red
Validación de Entrada de Usuario


Information de la base de datos mysql:

Host
mysql-146698-0.cloudclusters.net
  
Port
15871
  
IP Address
68.64.164.98
  
Initial Super User
admin
  
Initial Password
HRHE6mgZ
visibility

NOTA IMPORTANTE, ESTE SERVIDOR TIENE 12 DIAS HABILES DESPUES DE SU CREACION APARTIR DE LA FECHA 19/SEP/2023. ENCASO DE PROBLEMA NOTIFICARME.


BASE DE DATO ALTERNA 

Connection Information
Host
mysql-148305-0.cloudclusters.net
Copy   
Port
18322
Copy   
IP Address
181.215.242.83
Copy   
Initial Super User
admin
Copy   
Initial Password
ubt93kTo
visibility
Copy   
CA Certificate
ca.pem


