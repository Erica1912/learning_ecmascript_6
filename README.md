# learning_ecmascript_6

#### Curso y Conceptos de Javascript - Ecmascript (es6)

___TEMAS___

**¿ Declaración y asignación de variables?**
  - Variables como nombres simbólicos para valores en tu aplicación.  JavaScript tiene tres tipos de declaraciones de variables:
      var, let, const.
  - La operación de asignación evalúa el valor asignado. Es posible encadenar el operador de asignación para asignar un solo valor a múltiples variables
  Sintaxis.
 - El operador de asignación (=) se utiliza para asignar un valor a una variable.
  ```
  	Operador: x = y  
  ```

**¿ Qué es el DOM?**
  - Es una abreviatura de Document Objet Model, El DOM es la estructura de nodos que genera el navegador cuando se carga un documento, además se puede alterar, los objetos del DOM modelizan las ventanas del navegado, esto significa que podemos manipular las etiquetas del head y del body.

**Tipo de Datos**
  - Primitivos:  son datos que no son un objeto y no tienen métodos, son 6 tipos de datos primitivos: string, number, bigint, boolean , undefined y symbol.
  - Compuestos: se accede a la referencia del valor, objeto, array, función, class
  
**Tipo de Operados**
  - Los aritméticos
  

**Funciones**
  - En Javascript las funciones son objetos, una función es un parte del código que puede ser llamado por código externo o interno. Una función se compone de una secuencia de declaraciones, que conforman el llamado cuerpo de la función. Se pueden pasar valores a una función, y la función puede devolver un valor.
  
  - Las funciones declarativas y funciones de expresión.
  ```
      // FuncionDeclarativa
        function foo(){
          // código aquí
        }
	 
	   // FuncionExpresion
	      var foo = function(){
	        // código aquí
        }

  ```
 
**Arrow functions**
  - Es una forma de definir funciones anónimas que sean expresadas.
    Algunas están diseñadas para mejorar la experiencia de codificación de JavaScript y ofrecer características nuevas (por ejemplo, Promise), otras servirán como 
    extensiones o mejoras de las sintaxis y características ya existentes.

**Scope**
  - Es el alcance que tiene una variable en tu código, existen dos tipos de scope, el scope global y el scope local.
 
 **Arreglos**
  - Un arreglo (matriz) es una colección ordenada de datos. Los arreglos (matrices) se emplean para almacenar multiples valores en una sola variable, frente a las variables que sólo pueden almacenar un valor (por cada variable).
  
**Objetos**
  - Un objeto es una colección de propiedades y una propiedad es una asociación entre un nombre (o clave) y un valor. El valor de una propiedad puede ser una función, en cuyo caso la propiedad es conocida como un método.


 
**Parametros Rest, operador Spread**
  - Rest: La sintaxis de los parámetros rest nos permiten representar un número indefinido de argumentos como un array.
  - Spread: operador de propagación, guardas multiplex argumentos, genera una lista de valores a partir de un array.

**Hoisting**
   
   - El concepto de Hoisting fue pensado como una manera general de referirse a cómo funcionan los contextos de ejecución en JavaScript (específicamente las fases de 
     creación y     ejecución).
     
     Sin embargo, el concepto puede ser un poco confuso al principio.
     Conceptualmente, por ejemplo, una estricta definición de hoisting sugiere que las declaraciones de variables y funciones son físicamente movidas al comienzo 
     del código, pero esto no es lo que ocurre en realidad. 
   
     Lo que sucede es que las declaraciones de variables y funciones son asignadas en memoria durante la fase de compilación, pero quedan exactamente en dónde las has escrito 
     en el código

**Desestructuración De Objetos**

  - Es una expresión que nos permite desempaquetar valores de arrays u objetos en grupos de variables, permitiéndonos simplificar y crear código más legible.

**Promesas**

  - Una promesa representa la finalización de una función asíncrona. Es un objeto que podría devolver un valor en el futuro, cumpliendo el mismo rol que una función 
    que podríamos usar como callback de otra función.  Sin embargo, las promesas incluyen más funcionalidades y disponen de una sintaxis mucho más legible.
    
**Callback**

  - Es pasar una función como parámetro para que dicha función se encargue de ejecutar nuestro parámetro.
    Pasamos una función como parámetro, y ese algo que queremos que haga lo ejecutar la función que recibe nuestro parámetro.
    


