#  ¿Qué es JSON y XML?
<br>

JSON está definido de la siguiente manera: <br>

JSON (JavaScript Object Notation - Notación de Objetos de JavaScript) es un formato ligero de intercambio de datos. Leerlo y escribirlo es simple para humanos, mientras que para las máquinas es simple interpretarlo y generarlo. Está basado en un subconjunto del Lenguaje de Programación JavaScript, Standard ECMA-262 3rd Edition - Diciembre 1999. JSON es un formato de texto que es completamente independiente del lenguaje pero utiliza convenciones que son ampliamente conocidos por los programadores de la familia de lenguajes C, incluyendo C, C++, C#, Java, JavaScript, Perl, Python, y muchos otros. Estas propiedades hacen que JSON sea un lenguaje ideal para el intercambio de datos. <br>

XML está definido de la siguiente manera: <br>

XML, siglas en inglés de eXtensible Markup Language, traducido como 'Lenguaje de Marcado Extensible' o 'Lenguaje de Marcas Extensible', es un metalenguaje que permite definir lenguajes de marcas desarrollado por el World Wide Web Consortium (W3C) utilizado para almacenar datos en forma legible. Proviene del lenguaje SGML y permite definir la gramática de lenguajes específicos (de la misma manera que HTML es a su vez un lenguaje definido por SGML) para estructurar documentos grandes. A diferencia de otros lenguajes, XML da soporte a bases de datos, siendo útil cuando varias aplicaciones deben comunicarse entre sí o integrar información. <br>

**Algunas características de JSON son:**

* JSON es solo un formato de datos
* Requiere usar comillas dobles para las cadenas y los nombres de propiedades. Las comillas simples no son válidas.
* Una coma o dos puntos mal ubicados pueden producir que un archivo JSON no funcione. 
* Puede tomar la forma de cualquier tipo de datos que sea válido para ser incluido en un JSON, no solo arreglos u objetos. Así, por ejemplo, una cadena o un número único podrían ser objetos JSON válidos.
*  A diferencia del código JavaScript, en el que las propiedades del objeto pueden no estar entre comillas, en JSON solo las cadenas entre comillas pueden ser utilizadas como propiedades.

**Algunas características de XML son:**

* Asegura un excelente desempeño, simplicidad de implementación y sencillez de uso en servicios de la web.
* Posibilita que el contenido de los documentos XML sea entendible tanto para las personas como para los dispositivos.
* XML es un meta-lenguaje que nos brinda la posibilidad de definir lenguajes de marcado.
* XML es un estándar para escribir datos estructurados en un fichero de texto.
* Compartir grandes volúmenes de información con otras plataformas de software y sistemas operativos de forma sencilla, segura y sobre todo fiable.
* La implementación más usual del estándar XML es utilizarlo para definir la estructura de los documentos.

**Usos de JSON:**

Aunque está basado en la sintaxis de JavaScript, es un lenguaje independiente por lo que para leer / guardar deberemos convertirlo antes al formato específico.

JSON permite pasar pares de valores, arrays y objetos, lo que le da una gran capacidad de almacenar datos de todo tipo, de forma fácil y comprensible, que lo ha hecho popular y ha sustituido al formato XML como estandar de intercambio.

JSON puede ser leído por cualquier lenguaje de programación. Por lo tanto, puede ser usado para el intercambio de información entre distintas tecnologías.

JSON permite pasar pares de valores, arrays y objetos, lo que le da una gran capacidad de almacenar datos de todo tipo, de forma fácil y comprensible.

**Usos de XML:**

* Comunicación de datos. Si la información se transfiere en XML, cualquier aplicación podría escribir un documento de texto plano con los datos que estaba manejando en formato XML y otra aplicación recibir esta información y trabajar con ella.

* Migración de datos. Si tenemos que mover los datos de una base de datos a otra sería muy sencillo si las dos trabajasen en formato XML.

* Aplicaciones web. Hasta ahora cada navegador interpreta la información a su manera y los programadores del web tenemos que hacer unas cosas u otras en función del navegador del usuario. Con XML tenemos una sola aplicación que maneja los datos y para cada navegador o soporte podremos tener una hoja de estilo o similar para aplicarle el estilo adecuado. Si mañana nuestra aplicación debe correr en WAP solo tenemos que crear una nueva hoja de estilo o similar.

**Algunas ventajas de JSON son:**

* El formato de datos es relativamente simple, fácil de leer y escribir, los formatos están comprimidos y el ancho de banda es pequeño.
* Es fácil analizar este lenguaje, JavaScript del lado del cliente simplemente puede leer datos JSON a través de eval_r()
* Admite varios lenguajes, incluidos ActionScript, C, C #, ColdFusion, Java, JavaScript, Perl, PHP, Python, * Ruby y otros lenguajes del lado del servidor para un análisis sencillo del lado del servidor
* En el mundo de PHP, han aparecido PHP-JSON y JSON-PHP, lo cual es conveniente para la llamada directa de programas después de la serialización de PHP. Los objetos y matrices del lado del servidor PHP se pueden generar directamente en formato JSON, que es conveniente para el acceso y extracción de clientes.
* Debido a que el formato JSON se puede usar directamente para el código del lado del servidor, simplifica enormemente la cantidad de desarrollo de código en el lado del servidor y del lado del cliente, pero las tareas completadas no se modifican y son fáciles de mantener.

**Algunas desventajas de JSON son:**

* No es tan popular y ampliamente utilizado como el formato XML, ni tan versátil como XML
* El formato JSON se encuentra actualmente en pañales en la promoción de Servicios Web
Comparación de las ventajas y desventajas de JSON y XML
* En términos de legibilidad, JSON y XML tienen básicamente la misma legibilidad de datos. Se puede decir que la legibilidad de JSON y XML es casi la misma. Un lado es la gramática sugerida y el otro es la forma de etiqueta estándar.
* En términos de escalabilidad, XML es intrínsecamente muy escalable y, por supuesto, JSON sí. No hay nada que pueda extenderse XML, pero JSON no.

**Algunas ventajas de XML son:**

* Formato uniforme y conforme a los estándares
* Fácil de interactuar de forma remota con otros sistemas, y el intercambio de datos es más conveniente

**Algunas desventajas de XML son:**

* El archivo con formato de archivo XML es enorme, el formato es complicado y la transmisión ocupa ancho de banda
* Tanto el lado del servidor como el del lado del cliente necesitan gastar mucho código para analizar XML, sin importar que el código del lado del servidor y del lado del cliente se vuelva extremadamente complejo y difícil de mantener
* La forma de analizar XML entre diferentes navegadores en el cliente es inconsistente y es necesario escribir una gran cantidad de código repetidamente
* El análisis de XML del lado del servidor y del lado del cliente gasta recursos y tiempo

#### **Comparación XML vs JSON**
<br>

|JSON          |XML          |
|--------------|-------------|
|Basado en JS|Proviene de SGML|
|Soporta arrays|No soporta arrays|
|Solamente soporta codificación UTF-8|Soporta varios tipos de codificación|
|No necesita etiquetas de apertura y cierre|Necesita etiquetas de apertura y cierre|
|No soporta objetos nativos|Soporta objetos via atributos y elementos|
|No soporta namespaces|Soporta namespaces|

<br>

#### **Ejemplos en JSON y XML:**
<br>

##### Empleado XML:

````XML
<empleados>
    <empleado>
      <nombre>Panfilo</nombre>
      <apellido>Dominguez</apellido>
      <edad>28</edad>
    </empleado>
    <empleado>
      <nombre>Wendy</nombre>
      <apellido>Chávez</apellido>
      <edad>35</edad>
    </empleado>
    <empleado>
      <nombre>Trinidad</nombre>
      <apellido>Aguilera</apellido>
      <edad>53</edad>
    </empleado>
  </empleados>
````

##### Empleado JSON:

````JSON
{
  "empleados": {
      "empleado": [
           { "nombre":"Panfilo" , "apellido":"Dominguez", "edad":28 },
           { "nombre":"Wendy" , "apellido":"Chávez", "edad":35 },
           { "nombre":"Trinidad" , "apellido":"Aguilera","edad":53 }
      ]
  }
}
````


##### Película XML:

````XML
<Peliculas>
  <pelicula id="186273" year="2019">
    <nombre>Once upon a time in Hollywood</nombre>
    <director>
        <nombre>Quentin Tarantino</nombre>
    </director>
  </pelicula>
</Peliculas>
````

##### Pelicula JSON:

````JSON
{
  "Peliculas": {
    "pelicula": {
      "year": "2019",
      "id": "186237",
      "director": {
        "nombre": [
          "Quentin Tarantino"
        ]
      }
    }
  }
}
````

##### Persona XML:

````XML
<persona>
    <nombre>Eduardo</nombre>
    <apellido>Aguilera</apellido>
    <edad>32</edad>
    <email>eduardo37@gmail.com</email>
    <telefono>5832985635</telefono>
</persona>
````

##### Persona JSON:

````JSON
{
    "persona":{
       "nombre":"Eduardo",
       "apellido": "Aguilera",
       "edad":32,
       "email": "eduardo37@gmail.com",
       "telefono": "5832985635"
    }
}
````



### **Referencias**:
<br>

* colaboradores de Wikipedia. (2021, 16 septiembre). JSON. Wikipedia, la enciclopedia libre. https://es.wikipedia.org/wiki/JSON

* colaboradores de Wikipedia. (2021b, septiembre 30). Extensible Markup Language. Wikipedia, la enciclopedia libre. https://es.wikipedia.org/wiki/Extensible_Markup_Language

* Marker, G. (2019, 24 noviembre). ¿Qué es XML? ¿Para qué sirve? Características y ventajas. Tecnología Fácil. https://tecnologia-facil.com/que-es/que-es-xml-para-que-sirve-caracteristicas-y-ventajas/#Caracteristicas_deXML

* Diferencia entre JSON y XML / Protocolos y Formatos. (s. f.). La diferencia entre objetos y términos similares. Recuperado 12 de octubre de 2021, de https://es.sawakinome.com/articles/protocols--formats/unassigned-2505.html

* Barrera, A. (2019, 10 noviembre). JSON: ¿Qué es y para qué sirve? NextU LATAM. https://www.nextu.com/blog/que-es-json/#:%7E:text=Caracter%C3%ADsticas%20de%20JSON%3A,un%20archivo%20JSON%20no%20funcione.

* Marker, G. (2019, 24 noviembre). ¿Qué es XML? ¿Para qué sirve? Características y ventajas. Tecnología Fácil. https://tecnologia-facil.com/que-es/que-es-xml-para-que-sirve-caracteristicas-y-ventajas/

* E. (2020, 14 noviembre). JSON: qué es y para qué sirve. Desarrollo Web by esther solà. https://www.esthersola.com/json-que-es-y-para-que-sirve/

* Objetivos y usos del XML. (2001, 21 junio). Desarrollo Web. https://desarrolloweb.com/articulos/460.php

* Datos encapsulados JSON y datos analizados - programador clic. (s. f.). Programador clic. Recuperado 12 de octubre de 2021, de https://programmerclick.com/article/41341506692/