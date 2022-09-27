![](imagenes/sp.png)

![](https://images.cooltext.com/5331730.png)
<a href="http://cooltext.com" target="_top"><img src="https://cooltext.com/images/ct_pixel.gif" width="80" height="15" alt="Cool Text: Logo and Graphics Generator" border="0" /></a>

## Guía de estilo de programación

### Comentarios sobre el programa:
 Se dice que un _programa de computadora bien escrito en un lenguaje de alto nivel, como C / C ++, Python, se "auto documenta"._
 
 Mediante el uso de identificadores significativos y el flujo lógico de instrucciones de la computadora, un programa que escriba debe ser "legible" para otro programador. Sin embargo, **una intención de los programadores de lo que hace el programa y cómo lo hace no siempre es fácil de ver al mirar el programa.** Por eso es importante incluir comentarios en sus programas.


El estilo de sus comentarios incluye dónde coloca comentarios en su programa y qué dice en esos comentarios. Hay muchos estilos de comentarios diferentes. _Pueden Uds checar internet y navegar cientos de sugerencias, pero debe haber un estilo que acomode generica para el estudiante de programación_. 

### Comentarios de encabezado de archivo y programa:
 Cada programa que escriba debe tener un comentario al comienzo del programa que se denomina "encabezado" o "comentario de encabezado". Esto debe incluir la siguiente información: su nombre, la fecha, el nombre del archivo en el que se almacena el programa, una descripción del programa y su uso (cómo ejecutarlo) como minimo.

A medida que desarrolle sus habilidades en la programación, **dividirá su programa en diferentes archivos llamados módulos.** Cada archivo también debe contener un comentario de encabezado que incluya su nombre, la fecha, el nombre del archivo en el que se almacena el código; también debe indicar de qué otros archivos depende el módulo.

### Comentarios de encabezado de función: 

Un programa complejo siempre se divide en subprogramas más pequeños. En C / C ++, estas se llaman **funciones**. 
- cada función es responsable de realizar **una tarea en particular**.
- cada función también debe tener un comentario de encabezado.
- el encabezado de la función debe incluir una descripción, lo que se supone que debe hacer la función.
- condiciones previas, lo que la función espera y asume para que se ejecute correctamente, 
- condiciones posteriores, qué cambios realiza la función, qué valor tiene, si corresponde la función _return_.
### Comentarios en línea y en bloque:
Además de los comentarios del encabezado, también deberá incluir algunos comentarios en el cuerpo de sus programas. Se pueden incluir dos tipos de comentarios: 

- **Los comentarios en línea** son comentarios cortos que se intercalan a través del código de su programa o en la misma línea que las instrucciones del programa.

- **Los comentarios de bloque** son como los comentarios de encabezado, explican lo que se supone que debe hacer una sección completa de su código.


_**NO SOBRE COMENTAR. Debe intentar escribir sus programas de tal manera que otro programador pueda entenderlo.** Demasiados  comentarios se interponen en la forma de leer un programa. Por esta razón, debe usar los comentarios en línea con moderación. Los programadores principiantes tienden a usar comentarios en línea que explican líneas de código muy obvias_.

Un ejemplo de lo que **NO debes** hacer:

```c
    suma = suma +1 // incrementa por 1 variable suma
```   
### Bloque de Código  { } 
 Escribirás un grupo de instrucciones de programa que realizan una acción específica llamada **bloque de código**. 
 _Un buen uso de los comentarios en línea es agregar un comentario corto detrás de una llave de cierre que indica el bloque de código que termina._ En gitHub será un simbolo de inicio seguido de lenguaje a formatear: https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks
 
 # Nombres mnemotécnicos:

una variable es un espacio de memoria que usará para almacenar valores en su programa. Ambas variables y funciones requieren nombres (también llamados identificadores). El nombre de una variable debe indicar qué representa el valor que está almacenando. Por ejemplo, una variable que tiene la calificación de un estudiante podría llamarse: courseGrade.

El nombre de una función debe indicar la tarea que realiza la función. En general, una función que devuelve un valor único debe nombrarse con un nombre que indique lo que representa el valor. Una función que realiza alguna acción debe nombrarse con un verbo que indique la naturaleza de la acción. Los nombres de las funciones que realizan comprobaciones booleanas (devuelven verdadero o falso) deben indicar la naturaleza de la prueba. En el siguiente segmento de código de ejemplo, "ReadInformation" es una función que obtiene toda la información necesaria para un solo curso, "ValidLetterGrade" es una función booleana que verifica si el valor de courseGrade es una de las calificaciones de letras aceptables, y " QualityPoints "es una función que devuelve el número de puntos de calidad obtenidos en un curso dada la calificación de letras. Tenga en cuenta cuánta información acerca de una función es transmitida por un buen nombre sin siquiera saber nada más al respecto.

Estilo de programación: a medida que se convierta en un programador experimentado, descubrirá que cada lenguaje de programación que use restringirá de alguna manera la forma en que usa las instrucciones y variables del programa, y aún así le dará bastante flexibilidad. La forma en que use esa flexibilidad definirá su estilo de programación. No hay un estilo único que todos estén de acuerdo es el mejor, pero hay algunos principios que nos gustaría que sigas.

- NO use la instrucción goto (a menos que su instructor diga que está bien).
- NO use variables globales (a menos que su instructor diga que está bien).
- NO use una declaración de interrupción para salir de un bucle (a menos que su instructor le diga que está bien).

## Cita Bibliográfica

Programming Style Guide. (n.d.). Retrieved September 2019, from http://www.cs.siue.edu/programming-style-guide.
