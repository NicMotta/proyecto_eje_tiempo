# Escrito Eje Tiempo
### [Ir a Bitacora / proceso](https://nicmotta.github.io/eje_tiempo)

------

**Sistema_innatural_1**

¿Dejan de ser indispensables la fuentes ópticas/visuales de información para dejar paso a las fuentes numéricas y de datos con el fin de lograr la representación espacial?


¿Se puede representar algo materializable a través de datos? ¿Cuál es la forma de esta materialización? 


Pensar el espacio como un mar de datos numéricos, donde cada porción de información recolectada es reorganizada en un volumen digital, me lleva a pensar que hay nuevas maneras de entender nuestro hábitat basado en inputs que no obedecen a nuestros sentidos primarios o que están más allá de nuestra propia percepción del espacio. Estos valores se modifican en tiempo real aceleradamente, por lo tanto no podrían ser representados con técnicas artísticas tradicionales, como el dibujo o la imagen temporalizada, es indispensable utilizar un medio que permita visualizar estos cambios constantes y acceder a manipularlos.

¿Cómo podemos aproximarnos a nuestro hábitat sin los restringidos límites de nuestros sentidos?. Volver a ver, con otros parámetros desde una mirada sin filtros, la configuración del mundo por medio de datos, plasmada en una programación. Esta obra nos permite experimentar otra forma de relacionarnos con nuestro espacio y percibir sus cambios con el paso del tiempo.


[sistema_innatural_1] consta de una programación la cual toma [datos de internet de XXXXXX sensor] y ubica puntos XYZ en el plano 3D, luego genera una malla digital manipulable que puede ser impresa.

Un sistema no natural [innatural], el cual basándose tanto en [valores randoms] y su procesamiento genera valores en los ejes X, Y, Z y los publica en un servidor [MQTT / nube], dicho sistema nos muestra información tanto de su crecimiento / expansión, los datos enviados, como también distancia entre esos puntos. 
La idea es que el [Sistema Innatural] funcione constantemente durante días en una Raspberry PI conectada a internet, durante 24 hs genera puntos siguiendo un patrón de crecimiento aleatorio [basado en las sumatoria y procesamiento de los valores generados], una vez cumplido ese tiempo el sistema guarda todas esas coordenadas en un archivo .csv y reinicia el sistema.


¿Qué tan random puede ser un sistema? ¿Cómo se genera ese número random?
¿Podría existir datos externos que el sistema pueda tomar?
¿Existe una relación [visual / formal / morfológica] entre un modelo de procedencia digital y uno natural?
¿Existe un punto de encuentro entre ambos mundos?
Por otro lado desarrollé un script capaz de visualizar los puntos que están siendo creados en tiempo real y enviados a través de internet. Cualquier persona que tenga este programa puede ver el modelo que se esté generando en ese momento. Del mismo modo, recibe la señal para que cada 24hs se reinicie y guarde en un archivo .csv el modelo de ese día.
En este proyecto no estoy utilizando [por ahora] software de inteligencia artificial, no descarto hacerlo en un futuro sí me parece necesario su implementación.
Como tercera parte de la investigación, utilizo Rhinoceros y Grasshopper para el análisis y manipulación de esos archivos .csv, en ellos proceso por acumulación de puntos y reduzco la cantidad de datos a menos de 20 para crear vinculaciones entre ellos y posteriormente una malla. De esta manera puedo generar un modelo 3D a partir de todos los modelos creados ó bien un modelo individual para cada ciclo de sistema.


**Artistas referentes**

Tomas Saraceno

Andreas Lutz

Win Janssen

