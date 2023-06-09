||**Especificación de Requerimientos**|
| :- | -: |








**ANALISIS,DISEÑO,DESARROLLO EINPLEMNTACION DE UN SISITEMA WEB EN EL CENTRO INDUSTRIAL Y DE AVIACION PARA SISITEMATIZAR Y CONTROLAR EL INGRESO Y SALIDA DE  VEHICULOS Y OBJETIVO (RIDENT)
**


**SENA**

**Versión 1.0**         






||
| -: |
||



**Historial de Revisión**


|**Fecha**|**Versión**|**Descripción**|**Autor**|
| :-: | :-: | :-: | :-: |
|25-05-2023|1\.0|`  `Primera versión del software|<p>Cristian Fernández</p><p>Alan wadith</p><p>Elia cárdenas</p><p>Adriana carrillo  </p>|
|||||

`	`**Tabla de Contenido**		

[1.	Introducción	4](#_toc12939817)

[1.1	Propósito	4](#_toc12939818)

[1.2	Alcance	4](#_toc12939819)

[1.3	Definiciones, Acrónimos, y Abreviaturas	4](#_toc12939820)

[1.4	Referencias	5](#_toc12939821)

[1.5	Apreciación Global	5](#_toc12939822)

[2.	Descripción General	5](#_toc12939823)

[2.1	Perspectivas del Producto	5](#_toc12939824)

[2.2	Funciones del Producto	6](#_toc12939825)

[2.3	Características de Usuario	6](#_toc12939826)

[2.4	Restricciones	6](#_toc12939827)

[2.5	Atención y Dependencias	6](#_toc12939828)

[3.	Requerimientos Específicos	7](#_toc12939829)

[3.1	Requerimientos Funcionales	7](#_toc12939830)

[3.2	Requerimientos No Funcionales	11](#_toc12939831)

[3.3	Requerimientos de interfaz de usuario	14](#_toc12939832)

[4.      Determinación de las tecnologías de hardware, software y servicios requerido	16**](#_toc12939833)

[4.1	Software	16](#_toc12939834)

[4.2	Hosting	17](#_toc12939835)

[4.3	Computador	18](#_toc12939836)

[4.4	Escáner Lector Código de Barras Automático USB Soporte Base	19](#_toc12939837)

[4.5	Router (Router Inalámbrico/Repetidor WiFi N300Mbps, Tp-Link TL-WR840N)	20](#_toc12939838)

[4.6	Presupuesto	21](#_toc12939839)



**Especificación de Requerimientos** 	

1. # <a name="_gjdgxs"></a><a name="_toc12939817"></a>**Introducción**
<a name="_30j0zll"></a>La siguiente Especificación de Requerimientos de Software (SRS) del sistema a construir, surge con la finalidad de proveer toda la información de lo que quiere el cliente que contenga el software. Tales requerimientos son la base a la hora de comenzar el desarrollo del Software. En este caso el software a desarrollar una aplicación para llevar control y registro de los pacientes de una odontología la empresa se encuentra  ubicada en el barrio los olivos #2 111b2 Car.20 



1. ## <a name="_1fob9te"></a><a name="_toc12939818"></a>**Propósito**
El propósito de este documento es describir lo acordado con el cliente y desarrollar el paso a paso para crear el software que servirá para dar control y llevar un registro de los pacientes generando informes.


1. ## <a name="_3znysh7"></a><a name="_toc12939819"></a>**Alcance**
El sistema será una aplicación que permitirá llevar un control en el registro de los pacientes, además de otras funciones que se encuentran detalladas en la sesión de requisitos. Este sistema dará apoyo al historial de dichos pacientes

\* 
1. ## <a name="_2et92p0"></a><a name="_toc12939820"></a>**Definiciones, Acrónimos, y Abreviaturas**
- **Backup:** Las copias de seguridad en un sistema informático tienen por objetivo el mantener la información de recuperación de la información ante posibles pérdidas. 

- **Interfaz:** Medio que permite la comunicación entre el usuario y el sistema.

- **BD: Base de Datos** es un conjunto de datos pertenecientes a un mismo contexto y almacenados sistemáticamente para su posterior uso.

- **Requerimientos funcionales (RF)**: describen las capacidades o funciones que el sistema será capaz de realizar.

- **Requerimientos no funcionales (RNF)**: restricciones o características que de delimitan el sistema, como por ejemplo, rendimiento, interfaces de usuario, fiabilidad, seguridad, portabilidad, normas, entre otros.

- **Requerimientos de interfaz de usuario (RIU)**: describen lo que el usuario vera finalmente. 



1. ## <a name="_tyjcwt"></a><a name="_toc12939821"></a>**Referencias[](http://pegasus.javeriana.edu.co/~CIS0730IS01/Anexos/ANEXO%20C%20SRS.doc)**
[pegasus.javeriana.edu.co/~CIS0730IS01/Anexos/ANEXO%20C%20SRS.doc ](http://pegasus.javeriana.edu.co/~CIS0730IS01/Anexos/ANEXO%20C%20SRS.doc)

[](http://pegasus.javeriana.edu.co/~CIS0730IS01/Anexos/ANEXO%20C%20SRS.doc)<https://es.wikipedia.org/wiki/Base_de_datos>

1. ## <a name="_toc12939822"></a>**Apreciación Global**
En la primera parte de este documento, se ha presentado una corta introducción.

En el siguiente capítulo observara la perspectiva del proyecto, con sus funciones, especificaciones y características del proyecto mismo y de sus futuros usuarios. 

En el ítem 3 se presenta una especificación detallada de requerimientos que son necesarios para el análisis, diseño, desarrollo e implementación del sistema. 


1. # <a name="_3dy6vkm"></a><a name="_toc12939823"></a>**Descripción General**

1. ## <a name="_1t3h5sf"></a><a name="_toc12939824"></a>**Perspectivas del Producto**
Con este sistema se espera una mejora en la forma de cómo se maneja el historial de los pacientes para facilitar el retratamiento y futuras citas en dicha odontología.


1. ## <a name="_toc12939825"></a>**Funciones del Producto**
Este software cumplirá con las siguientes funciones:

- Registrar el ingreso de los pacientes a las citas
- Dar opción a retratamientos 
- Agendar futuras citas
- Llevar un historial de todos los pacientes

1. ## <a name="_4d34og8"></a><a name="_toc12939826"></a>**Características de Usuario**
Los usuarios no interactuaran con el sistema ya que este solo está destinado al sector administrativo


1. ## <a name="_toc12939827"></a>**Restricciones**
Para este sistema las posibles restricciones son el tiempo que tomará el desarrollo de este, recursos donde se implantara el sistema, el nivel del lenguaje programación para los desarrolladores.


1. ## <a name="_toc12939828"></a>**Atención y Dependencias**
El sistema será un apoyo para el historial y retratamiento de los pacientes de dicha clínica odontológica. Con ciertos elementos y herramientas de ayuda para dicho fin. 


1. # <a name="_2s8eyo1"></a><a name="_toc12939829"></a>**Requerimientos Específicos** 
   1. ## <a name="_toc12939830"></a>**Requerimientos Funcionales**


<table><tr><th colspan="1"><b>Código</b></th><th colspan="2"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">RF-001</td><td colspan="2" rowspan="2"><b>MÓDULO DE LOGIN</b></td><td colspan="1" rowspan="2">25-05-2023</td><td colspan="1" rowspan="2">ALTO</td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="4">Al sistema solo accederá personal autorizado mediante roles asignados.</td></tr>
<tr><td colspan="1"><b>Entradas</b></td><td colspan="1"><b>Fuente</b></td><td colspan="1"><b>Salida</b></td><td colspan="1"><b>Destino</b></td><td colspan="1"><b>Restricciones</b></td></tr>
<tr><td colspan="1" rowspan="2"><p>Datos personales</p><p>(Usuario y  contraseña)</p></td><td colspan="1" rowspan="2">Base de datos</td><td colspan="1" rowspan="2">Interfaz Menú principal</td><td colspan="1" rowspan="2">Interfaz de Menú Principal</td><td colspan="1" rowspan="2">Solo se accederá a ciertos módulos del sistema según el rol del usuario</td></tr>
<tr></tr>
<tr><td colspan="1" rowspan="2"><b>Proceso</b></td><td colspan="4" rowspan="2"><p>- Ingresar nombre y contraseña de usuario para Iniciar sesión.</p><p><b>Cabe aclarar que el usuario previamente se encuentra registrado en la base de datos del sistema</b></p><p>- Este Login No contará con opciones de recuperación de contraseña.</p></td></tr>
<tr></tr>
<tr><td colspan="1"><b>Efecto Colateral</b></td><td colspan="4">Errar la contraseña o nombre de usuario niega el ingresó a la aplicación web, teniendo un límite de cuatro(4) intentos </td></tr>
</table>





<table><tr><th colspan="1"><b>Código</b></th><th colspan="2"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">` `RF-002</td><td colspan="2" rowspan="2"><b>REGISTRO DE USUARIOS</b></td><td colspan="1" rowspan="2">25-05-2023 </td><td colspan="1" rowspan="2">` `ALTO</td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="4">El sistema debe permitir el registro de usuarios, asignándoles un rol (Administrador-UsuAdmin), estos usuarios son quienes harán uso de las funcionalidades del sistema.</td></tr>
<tr><td colspan="1"><b>Entradas</b></td><td colspan="1"><b>Fuente</b></td><td colspan="1"><b>Salida</b></td><td colspan="1"><b>Destino</b></td><td colspan="1"><b>Restricciones</b></td></tr>
<tr><td colspan="1" rowspan="2"><p>Datos personales</p><p>Identificación</p><p>Nombres </p><p>Apellidos</p></td><td colspan="1" rowspan="2">` `Formulario de Registro para usuarios</td><td colspan="1" rowspan="2">Registro satisfactorio</td><td colspan="1" rowspan="2">Base de Datos   </td><td colspan="1" rowspan="2">Un usuario tiene únicamente un rol</td></tr>
<tr></tr>
<tr><td colspan="1" rowspan="2"><b>Proceso</b></td><td colspan="4" rowspan="2"><p>- Recolección datos básicos personales (nombre, apellido, celular)</p><p>- Registro satisfactorio del usuario.</p><p><b>Solo los usuarios que tengan el Rol de Administrador podrán hacer el registro de los usuarios que tendrán el rol de UsuAdmin.</b></p></td></tr>
<tr></tr>
<tr><td colspan="1"><b>Efecto Colateral</b></td><td colspan="4">Los usuarios que tenga el rol de UsuAdmin no tendrán acceso a todas las funcionalidades del sistema.</td></tr>
</table>





<table><tr><th colspan="1"><b>Código</b></th><th colspan="2"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">` `RF-004</td><td colspan="2" rowspan="2"><b>HISTORIAL</b></td><td colspan="1" rowspan="2">25-05-2023 </td><td colspan="1" rowspan="2">` `ALTO</td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="4"></b> El sistema debe permitir registrar el ingreso de los pacientes a las respectivas citas </td></tr>
<tr><td colspan="1"><b>Entradas</b></td><td colspan="1"><b>Fuente</b></td><td colspan="1"><b>Salida</b></td><td colspan="1"><b>Destino</b></td><td colspan="1"><b>Restricciones</b></td></tr>
<tr><td colspan="1" rowspan="2">Características del vehículo, SOAT, seguro, Tarjeta de propiedad.</td><td colspan="1" rowspan="2">Formulario de registro para las citas</td><td colspan="1" rowspan="2">Citas registradas</b> </td><td colspan="1" rowspan="2">Base de datos</td><td colspan="1" rowspan="2">N/A</td></tr>
<tr></tr>
<tr><td colspan="1" rowspan="2"><b>Proceso</b></td><td colspan="4" rowspan="2"><p>El usuario del sistema deberá registrar la siguiente información de la cita: </p><p>- Nombre, apellido, numero de identificación, fecha, hora, genero</p></td></tr>
<tr></tr>
<tr><td colspan="1"><b>Efecto Colateral</b></td><td colspan="4">N/A</td></tr>
</table>

















<table><tr><th colspan="1"><b>Código</b></th><th colspan="2"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">` `RF-005</td><td colspan="2" rowspan="2"><b>RETRATAMIENTO</b></td><td colspan="1" rowspan="2">25-05-2023 </td><td colspan="1" rowspan="2"></b> ALTO</td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="4">Esta parte del sistema deberá permitir el registro de futuras citas o retratamientos de los pacientes para llevar un control detallado de estos.</td></tr>
<tr><td colspan="1"><b>Entradas</b></td><td colspan="1"><b>Fuente</b></td><td colspan="1"><b>Salida</b></td><td colspan="1"><b>Destino</b></td><td colspan="1"><b>Restricciones</b></td></tr>
<tr><td colspan="1" rowspan="2"><p></p><p>Información y/o características del objeto </p><p></p></td><td colspan="1" rowspan="2">Formulario para registro de retratamiento</td><td colspan="1" rowspan="2">Futura cita</td><td colspan="1" rowspan="2">` `Base de datos</td><td colspan="1" rowspan="2">NINGUNO</td></tr>
<tr></tr>
<tr><td colspan="1" rowspan="2"><b>Proceso</b></td><td colspan="4" rowspan="2"><p>El propietario/poseedor debe proporcionar la siguiente información:</p><p>- No. Identificación del paciente</p><p>- Nombre del paciente</p><p>- Fecha en la que esta destinada la cita</p></td></tr>
<tr></tr>
</table>

|**Efecto Colateral**|Se relaciona la información del objeto con el módulo de registro de propietario/poseedor|
| :-: | - |











1. ## <a name="_toc12939831"></a>**Requerimientos No Funcionales**


<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">RFN-001 </td><td colspan="1" rowspan="2">` `<b>DESEMPEÑO</b></td><td colspan="1" rowspan="2">` `25-05-2023</td><td colspan="1" rowspan="2">ALTO </td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3"><p>El tiempo de respuesta y la duración de las opciones funcionales del software será lo más rápido posible.</p><p>Por tanto el nivel de servicios requerido es tal que el sistema información con el tiempo no sufra una disminución en su desempeño (degradación) respecto al nivel previo al de la puesta en producción.</p></td></tr>
</table>



<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">` `RFN-002</td><td colspan="1" rowspan="2"><b>SEGURIDAD</b> </td><td colspan="1" rowspan="2">` `25-05-2023</td><td colspan="1" rowspan="2">` `ALTO</td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3">Este requerimiento es de suma importancia como todo lo demás, sin embargo, la seguridad prima en cualquier sistema es por esto que para aplicar esta se hará uso de una contraseña y usuario único con un rol, lo cual permite controlar el acceso a la información alojada.</td></tr>
</table>








<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">RFN-003 </td><td colspan="1" rowspan="2"><b>USABILIDAD</b></td><td colspan="1" rowspan="2">25-05-2023 </td><td colspan="1" rowspan="2">ALTO </td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3">El software deberá ser lo suficientemente fácil de manejar por el usuario, es decir este último podrá hacer todas las operaciones del sistema sin ningún problema. </td></tr>
</table>



<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">` `RFN-004</td><td colspan="1" rowspan="2"><b>DISPONIBILIDAD</b> </td><td colspan="1" rowspan="2">` `25-05-2025</td><td colspan="1" rowspan="2">ALTO </td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3"><p>La disponibilidad del sistema del sistema le corresponde al centro odontológico</p><p>para estar activo en horarios de trabajo.</p></td></tr>
</table>



<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">` `RFN-006</td><td colspan="1" rowspan="2">` `<b>FIABILIDAD</b></td><td colspan="1" rowspan="2">` `25-05-2023</td><td colspan="1" rowspan="2">ALTO </td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3">La definimos como la probabilidad de que este producto funcione sin fallos durante un lapso estimado de un (1 año) sin recibir un mantenimiento correctivo. </td></tr>
</table>



<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">` `RFN-007</td><td colspan="1" rowspan="2"><b>MANTENIBILIDAD</b></td><td colspan="1" rowspan="2">` `25-05-2023</td><td colspan="1" rowspan="2">` `ALTO</td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3"><p>El sistema deberá tener la capacidad de recuperarse en lo posible frente a los posibles fallos que puedan presentarse. Asegurar que no se pierda los datos de la base de datos.</p><p></p><p>Por otra parte, se debe realizar mantenimiento preventivo ya que es de gran importancia para verificar el buen desarrollo de las actividades o procesos del sistema.</p></td></tr>
</table>






<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">` `RFN-008</td><td colspan="1" rowspan="2"><b>PORTABILIDAD</b></td><td colspan="1" rowspan="2">` `25-05-2025</td><td colspan="1" rowspan="2">ALTO </td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3"><p>En cuanto a este requerimiento, podemos asegurar que el sistema será totalmente portable en cuanto a sistemas operativos, ya que este sistema funcionará como un software (app), disponible en Windows.</p><p></p></td></tr>
</table>

1. ## <a name="_toc12939832"></a>**Requerimientos de interfaz de usuario**

<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">` `RIU-001</td><td colspan="1" rowspan="2"><b>LOGIN</b> </td><td colspan="1" rowspan="2">` `25-05-2023</td><td colspan="1" rowspan="2">ALTO </td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3">Interfaz que permitirá a los usuarios (Administrador, UsuAdmin) del sistema ingresar a este, para hacer uso de las funcionalidades de este.</td></tr>
</table>



<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2"></b> RIU-002</td><td colspan="1" rowspan="2"><b>MENU PRINCIPAL</b></td><td colspan="1" rowspan="2"></b> 25-05-2023</td><td colspan="1" rowspan="2">MEDIO </td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3">Interfaz que permitirá elegir la funcionalidad del sistema a la cual se desea acceder.</td></tr>
</table>



<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2"></b> RIU-003</td><td colspan="1" rowspan="2"><b>REGISTRO DE USUARIO</b></td><td colspan="1" rowspan="2"></b> 25-05-2023</td><td colspan="1" rowspan="2">ALTO </td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3">Interfaz que permitirá al Administrador registrar en la base de datos del sistema a los UsuAdmin.</td></tr>
</table>



<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2"></b> RIU-004</td><td colspan="1" rowspan="2"><b>REGISTRO DE PACIENTE</b></td><td colspan="1" rowspan="2"></b> 25-05-2023</td><td colspan="1" rowspan="2">ALTO </td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3">Interfaz que permitirá registrar en la base de datos del sistema a los pacientes</td></tr>
</table>



<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2">` `RIU-005</td><td colspan="1" rowspan="2"><b>HISTORIAL DE LOS PACIENTES</b></td><td colspan="1" rowspan="2">` `25-05-2023</td><td colspan="1" rowspan="2">ALTO </td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3">Interfaz que permitirá registrar en la base de datos del sistema el historial de dichos pacientes</td></tr>
</table>



<table><tr><th colspan="1"><b>Código</b></th><th colspan="1"><b>Nombre</b></th><th colspan="1"><b>Fecha</b></th><th colspan="1"><b>Grado Necesidad</b></th></tr>
<tr><td colspan="1" rowspan="2"></b> RIU-006</td><td colspan="1" rowspan="2"><b>RETRATAMIENTO</b></td><td colspan="1" rowspan="2"></b> 25-5-2023</td><td colspan="1" rowspan="2">ALTO </td></tr>
<tr></tr>
<tr><td colspan="1"><b>Descripción</b></td><td colspan="3">Interfaz que permitirá registrar las futuras citas o retratamientos de los pacientes</td></tr>
</table>








