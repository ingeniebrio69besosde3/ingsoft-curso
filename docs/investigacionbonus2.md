# **¿Qué es UML?**
<br>
Es un lenguaje estándar para visualizar, especificar, construir y documentar los artefactos de un sistema de software.

<br>

### Ventajas y Desventajas de UML 
<br>

### VENTAJAS 

1. UML Se puede usar para diferentes tipos de sistemas.
2. UML consolida muchas de las notaciones y conceptos más usadas orientados a objetos. 
3. UML es fácilmente entendible.

### DESVENTAJAS 
1. UML no es un método de desarrollo.
2. UML al no ser un método de desarrollo es independiente del ciclo de desarrollo.
3. UML no se presta con facilidad al diseño de sistemas distribuidos.

<br>

### Herramientas UML en línea:
* yUML (Beta).
* Creately.
* Cacoo.
* Draw.
* GenMyModel.

<br>

### Diagreama de objetos:

En UML, los diagramas de objetos muestran un instante en el sistema y las relaciones entre distintas instancias.

* El diagrama de objetos utiliza notaciones similares a los usados en el diagrama de clases.
* Los diagramas de objetos se utilizan para modelar los elementos que están presentes en un diagrama de clases.
* El diagrama de objetos muestra los clasificadores reales del sistema y las relaciones entre ellos en un punto específico del tiempo.
* Los diagramas de objetos se pueden instanciar como diagrama de clases, despliegue, componentes e, incluso, casos de uso.
* En ninguno de los dos diagramas se muestran los mensajes entre los elementos que colaboran, ya que se trata de diagramas estructurales.

<br>

### Elementos del diagrama de objetos:

El diagrama de objetos se compone, principalmente, de los siguientes elementos

1. Objetos: Cada objeto se representa con un rectángulo con su nombre y el de su clase en la parte superior subrayados y separados por dos puntos. En caso de ser un objeto anónimo no se escribe su nombre, dejando solo el de la clase.
2. Atributos: De igual forma que el diagrama de clases, se muestra en un compartimento en la parte inferior del nombre del objeto. A diferencia de las clases, los atributos pueden tener valores asignados a ellos.
3. Vínculos: Son asociaciones entre dos objetos y se representan con los mismos elementos que en el diagrama de clases.
<br>

### Diagrama de tiempos:

El diagrama de tiempos es un diagrama UML incluido en la categoría de diagramas de interacción (perteneciente a los diagramas de comportamiento). Es utilizado para modelar el comportamiento del sistema dando especial importancia al tiempo. Los diagramas de tiempo se centran en las condiciones que cambian dentro y entre las líneas de vida a lo largo de un eje de tiempo lineal. Los diagramas de tiempo describen el comportamiento de los clasificadores individuales y las interacciones de los clasificadores, enfocando la atención en el tiempo de los eventos que causan cambios en las condiciones de las líneas de vida.

### Elementos de un diagrama de tiempos:
El diagrama de tiempos incluye los siguientes elementos: 

#### Línea de vida:
La línea de vida es un elemento que representa a un participante individual en la interacción. Si bien las partes y las características estructurales pueden tener una multiplicidad mayor que 1, las líneas de vida representan solo una entidad que interactúa. Sigue la misma esencia que las líneas de vida de los diagramas de secuencia.


#### Estado:
El diagrama de tiempo podría mostrar los estados del clasificador o atributo participante, o algunas condiciones comprobables, como un valor discreto de un atributo.

#### Restricción de duración:
La restricción de duración es una restricción de intervalo que se refiere a un intervalo de duración. El intervalo de duración es la duración que se utiliza para determinar si se cumple la restricción.

#### Restricción de tiempo:
La restricción de tiempo es una restricción de intervalo que se refiere a un intervalo de tiempo. El intervalo de tiempo es una expresión  utilizada para determinar si se cumple la restricción.
<br>

### Diagrama de Paquetes:

El diagrama de paquetes es uno de los diagramas estructurales comprendidos en UML 2.5, por lo que, como tal, representa de forma estática los componentes del sistema de información que está siendo modelado. Es utilizado para definir los distintos paquetes a nivel lógico que forman parte de la aplicación y la dependencia entre ellos. Es principalmente utilizado por desarrolladores y analistas.

Es importante destacar que este diagrama es utilizado en los sistemas de información con programación orientada a objetos. El objetivo principal del diseño debe maximizar la cohesión y minimizar el acoplamiento.

En sí el diagrama es muy sencillo, dependiendo su complicación del detalle con el que se quieran tratar los elementos que mostrará, que puede llegar a ser muy específico.

### Elementos de un diagrama de paquetes:

#### Paquete:
Es el elemento clave del diagrama y que da el nombre al mismo. Un paquete es un conjunto de elementos. En concreto puede ser un conjunto de clases, casos de uso, componentes u otros paquetes. No obstante, lo más común es que incluya otros paquetes.

Lo ideal es que este conjunto de elementos tenga una función diferenciada del resto de elementos. De esta forma, además de maximizar la cohesión, se dará la máxima claridad al diagrama y, por tanto, al Sistema de Información. Es también importante identificar con nombres representativos de estas funciones a los distintos paquetes. Por supuesto, hay que tener en cuenta el nivel de granularidad del diagrama.

Se representa con un símbolo simulando una carpeta, con el nombre en la parte superior.

#### Dependencia entre paquetes
Una dependencia entre paquetes representan que un paquete necesita de los elementos de otro paquete para poder funcionar con normalidad.

Se representa con una flecha discontinua que va desde el paquete que requiere la función hasta el paquete que ofrece esa función.


#### ***Referencias:***

* <a href="https://es.wikipedia.org/wiki/Lenguaje_unificado_de_modelado" target="_blank">https://es.wikipedia.org/wiki/Lenguaje_unificado_de_modelado</a> 

* <a href="https://es.slideshare.net/AlanFdzGonzalez/uml-85779204" target="_blank">https://es.slideshare.net/AlanFdzGonzalez/uml-85779204</a> 

* <a href="https://diagramasuml.com/objetos/ " target="_blank"> https://diagramasuml.com/objetos/</a> 

