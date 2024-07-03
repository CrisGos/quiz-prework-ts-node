# quiz-prework-ts-node
Test pre typescript lessons
## JavaScript Básico:
### Describe qué es una función en JavaScript y cómo se declara.
Una funcion en JS es una porcion de codigo que contiene un algoritmo "aislado" el cual puede reutilizarse en el codigo,
este debe ocuparse de una sola accion y no realizar acciones totalmente diferentes.
se declara function name(parametros) {
    codigo
}


## Manipulación del DOM:
### Explica cómo seleccionar un elemento del DOM y cambiar su contenido.
Existen varias formas de seleccionar un elemento para cambiar su contenido
- getById()
- querySelector()
- querySelectorAll()


## Programación Orientada a Objetos (OOP):
### ¿Qué es una clase en JavaScript y cómo se define una?
Una clase en JS es una porcion de codigo, la cual pertenece a una misma clase o tipo de accion, funcion, objeto, fin, etc.,
la cual posee caracteristicas de polimorfimos, abstraccion, herencia y encapsulamiento, tambien dentro de una clase se definen
atributos y metodos.


## Eventos en JavaScript:
### ¿Cómo se agrega un evento de clic a un botón en JavaScript?
Se realiza por medio de un eventListener, no recuerdo muy bien la sintaxis pero este me permite indicar que capture el click para este caso, tambien submit, etc., y realizar la funcion asociada, normalmente trabaja con funciones flecha

## Variables y Tipos de Datos:
### Explica las diferencias entre var, let, y const en JavaScript.
var y let permiten definir variables que pueden ser modoficadas posterior a su definicion, sin embargo var se ha dejado de usar
en las recientes versiones.
Por otro lado, const me permite definir una variable cuyo valor permance constante posterior a su definicion.

## Control de Flujo:
### ¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?
Las estructuras de control se definen en estructuras secuenciales, de loop, de condicion y de salto.
- Secuencial es la secuencia algoritmica de un codigo donde se lee linea a linea.
- loop o de repeticion permite crear bucles como for, while, do while, etc. los cuales permiten que mientras haya una condicion
el condigo se repita.
- Condicion son estructuras como if, if else, else elif y match que permite que si se cumple una condicion se ejecute o no
una porcion de codigo en especifico

## Funciones de Flecha:
### Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.
Una funcion flecha es una funcion de javascript cuya diferencia se basa en su sintaxis y que esta no es declarada.
No recuerdo muy bien la declaracion

## JSON:
### ¿Qué es JSON y cómo se utiliza en JavaScript?
Los JSON permiten almacenar informacion no estructurada, se utiliza para almacenar y utlizar informacion, (como base de datos)

## Promesas:
### Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.


## Depuración:
### ¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?
- console.log
- alerts
- entendimiento de los errores
- console.warn

# Preguntas de Selección Múltiple (20)
## ¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?
A) var myVariable;
B) variable myVariable;
C) let myVariable;
## D) A y C son correctas. X


## ¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?
A) push()
## B) pop() X
C) shift()
D) unshift()


## ¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?
A) ==
## B) === X
C) !=
D) !==


## ¿Cuál es la salida del siguiente código?
console.log(typeof null);
## A) null X
B) undefined
C) object
D) number

## ¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?
A) forEach()
B) map()
C) filter()
## D) Todas las anteriores X


## ¿Qué se entiende por “hoisting” en JavaScript?
A) Declaraciones de variables y funciones se mueven al principio de su ámbito.
B) Es un término para describir la eliminación de variables.
C) Es un método para agrupar varias funciones.
D) Ninguna de las anteriores.


## ¿Cuál es la diferencia entre null y undefined en JavaScript?
A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado.
## B) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor. X
C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor.
D) No hay diferencia.


## ¿Cuál es el propósito del método Array.prototype.map()?
A) Modificar el array original.
## B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original. X
C) Filtrar los elementos de un array.
D) Encontrar un elemento en un array.


## ¿Qué es el Event Loop en JavaScript?
A) Un ciclo que controla las llamadas recursivas.
## B) Un proceso que permite a JavaScript realizar operaciones asincrónicas. X
C) Un método para iterar sobre arrays.
D) Ninguna de las anteriores.


## ¿Cuál es la salida del siguiente código?

console.log(0.1 + 0.2 === 0.3);
## A) true X
B) false
C) undefined
D) NaN


## ¿Qué se entiende por strict mode en JavaScript?

A) Un modo que permite utilizar características experimentales.
B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
C) Un método para validar datos.
D) Ninguna de las anteriores.


## ¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

A) let obj = {};
B) let obj = Object.create();
C) let obj = new Object();
## D) A y C son correctas.  X


## ¿Qué es un callback en JavaScript?

A) Una función que se pasa como argumento a otra función.
B) Un tipo de variable especial.
C) Un método para declarar funciones.
D) Ninguna de las anteriores.


## ¿Cuál es el propósito de async y await en JavaScript?

## A) Ejecutar funciones síncronas. X
B) Manejar operaciones asincrónicas de manera más simple y legible.
C) Declarar variables globales.
D) Ninguna de las anteriores.


## ¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

A) Arrays
B) Strings
## C) Objetos X
D) Ninguna de las anteriores.


## ¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

A) JSON.parse()
B) JSON.stringify()
## C) toString() X
D) parseInt()


¿Qué es un Promise en JavaScript?

A) Una función que se ejecuta inmediatamente.
B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
C) Un método para declarar variables.
D) Ninguna de las anteriores.


¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

## A) push() X
B) pop()
C) shift()
D) unshift()


## ¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

A) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
## B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente. X
C) No hay diferencia entre ellos.
D) Ambos almacenan datos solo durante la sesión del navegador.


## ¿Qué método se utiliza para detener la propagación de un evento en el DOM?

A) event.stopPropagation()
B) event.preventDefault()
## C) event.stop() X
D) event.cancel()