# TECNOLOGÍAS INDUSTRIALES


Este es el GITHUB realizado para la asignatura de Tecnologías Industriales. El grupo (MAFU) está compuesto por; Alfonso Pereda, Aritz Garitano, Unai Elustondo y Maite Varela. El proyecto se basa en realizar un gemelo digital de los nuevos ascensores de Ermua. 


![alt text](https://www.olabarri.com/wp-content/uploads/referencias/ErmuaAldapa(1).jpg)


**DESCRIPCIÓN DE LA PÁGINA WEB:**

[Enlace a la página web](https://aritzgari.github.io/index.html)

La página web cuenta con 3 pestañas principales.

Inicio.- En la página principal se muestra el nombre del proyecto y los objetivos a cumplir. También se muestra un mapa en el que se ubican los tres ascensores con los que se está trabajando.

Monitorización.- En la segunda pestaña se muestran todos los datos que se están monitorizando en el ascensor. Los datos se recogen mediante la aplicación de Tableau y muestra datos como; el uso del ascensor, la cantidad de usuarios que los usan, etc. Algo que mencionar de esta página es el video que simula el movimiento del ascensor.

Ascensor.- La última pestaña requiere el permiso de uso de la cámara del usuario. Si se autoriza, con la ayuda del icono correspondiente (guardado en la carpeta de imágenes) podremos ver un dibujo en realidad aumentada del ascensor, el cual, si se accede desde el móvil, se puede interactuar con él haciendo zoom o girándolo, como se muestra en la siguiente imagen:

![alt text](https://github.com/aritzgari/aritzgari.github.io/blob/main/Imagenes/Screenshot_20211214-170933.jpg)

**ACTIVIDADES PRINCIPALES DEL PROYECTO:**

	- Creación de página web.

	- Videos del CAD.

	- Imagen 3D del ascensor con AR.


**TABLEAU:**

Con el uso de la aplicación Tableau se visualizan los datos procedentes de un archivo excel de con datos aleatorios. Con los datos proporcionados se muestran:

	- Cantidad de uso de cada ascensor.

	- Cantidad de usuarios por ascensor.

	- Temperatura del ambiente.


Visualización en Tableau:


![alt text](https://github.com/aritzgari/aritzgari.github.io/blob/main/Imagenes/ege.PNG)
	

Algo a destacar sobre la página web es la barra de weather instalada. La información meteorológica está sacada de una página web meteorológica. Esta se actualiza siempre que el origen cambia.

**REALIDAD AUMENTADA:**

También se ha realizado un pequeño modelo 3D de uno de los ascensores de Ermua, el cual está disponible para su visualización en realidad aumentada escaneando el AR que se muestra a continuación con la ayuda de una cámara. Para proceder con el escaner, es necesario estar en la tercera pestaña de la página web y habilitar la cámara del dispositivo que se está usando.

![alt text](https://github.com/aritzgari/aritzgari.github.io/blob/main/Imagenes/default-marker.png)

**PRESENTACIÓN POWER POINT:**

En la presentación que se encuentra adjunta en el documento se tiene por objetivo presentar el trabajo realizado en el proyecto "TRILLIZO DIGITAL DE LOS ASCENSORES PÚBLICOS DE ERMUA". 

El proyecto pretende acercar a la ciudadania el gemelo digital, dándoles a conocer las nuevas tecnologías del momento y proporcionándoles el estado de los ascensores para facilitarles la vida diaria gracias una página web de facil uso. 

Para realizarlo, se han sensorizado los ascensores con diferentes sistemas embebidos, como por ejemplo, un mircocontrolador STM32WB55. De esta manera se consiguen datos del tipo; estado actual del ascensor, planta en la que se encuentra, temperatura del ambiente. Con motivos de seguridad, se instala otro sensor de presión para calucar el peso que hay dentro del ascensor para que no exceda el peso, poniendo en riesgo la integridad del ascensor y la de los integrantes.

Todos estos datos son mostrados gracias a Tableau y se reflejan en la página web, que es pública para que cualquier persona pueda acceder a ella. 

Para finalizar, se muestra un *default* a través del cual se puede ver uno de los ascensores en realidad aumentada.
