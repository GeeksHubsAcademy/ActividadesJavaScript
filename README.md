# Actividades en JavaScript
Actividades para el desarrollo de los Fundamentos de JavaScript
## Actividades de Introducción.
### Tabla de multiplicar.
>Crea una pequeña aplicación JavaScript que genere las tablas de multiplicar para ello se debe preguntar la tabla que quiere y se representará en la consola.
```javascript
let tabla=prompt("Indicame la tabla de multiplicar");
```
### Diseño de silla.
> Crea una aplicación que nos pida la altura de la silla y nos dibuje por pantalla una silla con *.
> La única restricción que no debe ser menor de 7 ni mayor de 30 y la condición de que el asiento 
> este situado la mitad + 1
```
Indicame la altura? 10
*
*
*
*
*
******
*    *
*    *
*    *
```
### Diseño de un arbol de navidad.
> Crea una aplicación que nos pida la altura del arbol y nos dibuje por pantalla dicho arbol.
> Tiene que tener una altura mínima de 5
```
Indícame la altura? 5
    *
   *** 
  *****
 *******
*********
```

### Contador hacia atras.
> Crea una aplicación que nos muestre diferentes alerts contando desde 10 a 0 incluidos, utilizando el bucle de tipo While

### Calcular el máximo de dos valores.
> Dado dos valores nos debe indica cual es el mayor utilizando las sentencias if-then-else

### Creditos universitarios
>Crea una aplicación con JavaScript que permita calcular los créditos a convalidar con respecto a diferentes universidades. El usuario insertará una ciudad a la que desea convalidar los créditos. mediante un prompt .
>A continuación se muestra la convalidación de créditos (Se recomienda utilizar la estructura switch) mediante un alert:
>Universidad de Madrid y de Murcia: Se convalidarán 30 créditos
>Universidad de Alicante: No se convalidan créditos
>Universidad de Valencia, Granada y Córdoba: Se convalidan 50 créditos.

### Número estricto.
> Dado un número entero positivo N, se dice que es estricto si tiene los dígitos 1,3 y 5 al principio y los otros al final. Si no tiene dígitos 1,3,5, también es estricto.
>Se pide que desarrolles un programa que dado un número indique si es estricto o no.
>Ejemplo N=115924 es estricto, al principio 1 y 5 y los demás al estan al final.
>N=241781 No es estricto tiene al principio 2 y 4. N=1345. No es estricto, 5 está al final.
>N=51 o N=24 Son estrictos.

### Número simpático.
>Dado un número entero positivo N,  se dice que es simpático si se cumple lo siguiente: su expresión
en base 2 (binaria) viene dada por una combinación intercalada de unos (1) y ceros (0), es decir, después
de un 1 va un 0, luego un 1, luego un cero y así sucesivamente.
Se pide generar un programa que dado número N, indique si es simpático o no.
>Ejemplos
>N = 42  ES SIMPÁTICO, ya que su representación en  binario es 101010.
>N = 84    NO ES SIMPÁTICO, ya que su  representación en binario es 1010100

### Números naturales.
> Dado dos números naturales (mayores que cero): “N” e “i”, que imprima por pantalla el dígito que ocupa la posición iésima del número N. Si i es mayor que el número de dígitos de N, se escribirá por pantalla -1. Por ejemplo: N=25064 e i=2 el resultado es 6, para i=7 el resultado es -1.

### Mayor o menor que.
>Encuentre los valores mayor, menor y la suma de N datos de entrada. Encuentre elpromedio de esos datos mediante una función.  

### Número factorial.
>   Realice el factorial de N.


---
## Actividades programacion juegos para practicar estructuras de control y de iteración.
### Número aleatorio
>En esta actividad se pide adivinar un número aleatorio que estará entre el 1 y el 100. Por tanto se preguntará al usuario un valor numérico usando la función prompt y si no acertamos el número que se ha generado aleatoriamente, imprimirá un mensaje (usando el document.write()) indicando si el número a acertar es más grande que el que hemos introducido o en caso contrario que el
número sea más pequeño.
>En el momento que se acierte el número el programa finaliza. También podemos finalizar el programa introduciendo la palabra “FIN”.
>Con tal de ampliar y mejorar el programa, la aplicación podrá finalizar cuando se escriba FIN tanto en mayúsculas como en minúsculas.
>También se deberá mostrar el número de intentos que ha realizado el usuario

### Piedra papel o tijera.
>Se deberá crear el juego Pieda, papel o tijera, donde aleatoriamente con Math.random(), se calculará una de los tres, y se preguntará al usuario que deberá dar su opción, se comprobará quien gana de los dos y se irá sumando el resultado en una variable, el juego parará cuando se escriba la palabra "FIN".
---
## Actividades para prácticar los closures.
### Closure 1
> Comprobar el resultado de éste código, y después sustituye el var a por un let a
```javascript
function test(){
   console.log(a);
   console.log(prueba());
   
   var a =1;
   function prueba(){
    return 10;
    }
 }
 test();
 ```
 
 ### Closure 2
 > Crea una función padre  denominada cliente que tenga los atributos, nombre, appelido y edad.
 > Crea una función hija que devuelva los valores contanados de nombre y apellido de los atributos getNombreCompleto()
 
 ### Closure 3
 > Comprueba lo que devuelve la siguiente función.
 ```javascript
 var a = 1
 function primeraFuncion(numero) {
  function segundaFuncion(numero2){
   return a;
   }
   a = 5 ;
   return segundaFuncion;
 }
 var primerResultado = primeraFuncion(5);
 var resultado = primerResultado(2);
 ```
 
 --- 
 ## Actividades para prácticar los funciones flecha
 > Crear una aplicación calculadora utilizando funciones flecha, donde se encuentren las funciones:
 * Sumar
 * Restar
 * Multiplicar
 
 > Crear una funcion anonima que se autoejecute  al arrancar la apicación que pregunte que operación deseas hacer de las descritas en el ejercicio anterior.
 
 > Crea una función flecha que pasando dos parametros el nombre y apellidos me devuelva un string con el nombre completo.
 
 > Crea una función flecha  que comprueba que el valor que el paso como argumento es un String o no y devuelva en el caso correcto un true, o un false.
 
---
## Actividades para prácticar con los arrays
> Escribe una función que genere un array de un tamaño especfico, y que se rellene con números enteros, que se incrementa desde el númeor iniciado hasta el tamaño del array:
> Por ejemplo: rangeArray(4,6) obtiene el resultado [4,5,6,7,8,9]
> rangeArray(-9.3) obtiene el resultado [-9,-8,-7]

> Escribe una función que combine dos arrays y elimine los elementos duplicados.
> Por ejemplo: array1=[1,4,6,7]  array2=[4,5,8,9]  obtiene el resultado [1,5,6,7,8,9]

> Escribe una función que muestre el elemento que más se repite en el array.
> Por ejemplo arrayValor=[2,'a',4,5,1,'a','c,'c','a',3,6,'a'] Obtenemos el siguiente resultado a ->se repite 4 veces

> Escribe una función que muestre si el valor que se le pasa es un array o no.
> Por ejemplo esArray([1,2,3,4]) -> nos indicará true, esArray('Hola') -> nos indicará false

> Escribe una función que al pasarle un vector de N elementos, lo clasifique de forma descendente.
> Por ejemplo ordenaDescente([2,4,5,6])-> obtendremos [6,5,4,2]

> Escribe una función que dado un vector elimine los ceros del mismo.
> Por ejemplo eliminarCeros([3,0,5,6,0,3]) -> obtendremos [3,5,6,3]

---

## Actividades para prácticar Objetos.
### Creación de objetos.
> Realiza un programa que permita crear una estructura para objetos de tipo círculo al que le pasamos el radio cuando lo inicialicemos y que tenga una función que nos calcule su área, otra su longitud, y esos valores sean mostrados por pantalla.
### Gestión de facturas.
> Vamos a crear una aplicación para la creación de una estructura de objeto que almacene una factura. Las facturas dispondrán la siguiente información
 * Nombre de la empresa.
 * Dirección.
 * Teléfono.
 * Nif.
> La información del cliente, una lista de elementos tales como descripción, precio y cantidad y otra con información básica de la factura (importe sin IVA, tipo de Iva, importe con IVA y Forma de Pago)

### Gestión de edificios.
> Se desea crear una aplicación en JavaScript para poder gestionar los edificios de diferentes ciudades o poblaciones. Para ello se desea almacenar la siguiente información correspondiente a cada edificio:
   * Calle del edificio.
   * Número.
   * Código postal(población o ciudad donde se encuentra el edificio).
   * Plantas del edificio ( dentro de cada planta tendremos un número de puertas y para cada puerta nos interesa almacenar el nombre del propietario).
>A continuación especificaremos todo lo que se necesita para la gestión de los diferentes edificios:
>Se deberá crear un objeto que permita instanciar edificios, para ello crearemos un constructor llamado Edificio al que se le pasará como parámetros la calle, el número y el código postal.
>Se crearán los siguientes métodos asociados al constructor Edificio:
   * agregarPlantasyPuertas(numplantas,puertas): Se le pasará el número de plantas que queremos crear en el piso y el número de puertas por plantas. Cada vez que se llame a este método, añadirá el número de puertas y plantas indicadas en los parámetros, a las que ya están creadas previamente en el edificio.
   * modificarNumero(nuevoNumero): Se permitirá modificar el número del edificio, para ello se le pasará como parámetro el nuevo número.
   * modificarCalle(nuevaCalle): Se permitirá modificar la calle, para ello se le pasará el nombre de la nueva calle a modificar.
   * modificarCodigoPostal(nuevoCP): Se permitirá la modificación del cdigo postal, para ello se proporcionará como parámetro el nuevo código postal.
   * mostrarCalle(): Método que devolverá el nombre de la calle donde está situado el edificio.
   * mostrarNumero(): Método que devolverá el número donde está situado el edificio.
   * mostrarCodigoPostal(): Método que mostrará el código postal asociado a la población o ciudad donde está situado el edificio.
   * agregarPropietario(nombre, planta, puerta): Se permitirá añadir un nuevo propietario donde se le pasará el nombre del propietario, el número de planta y el número de puerta. Se le asignará dicho propietario al piso en cuestión.
   * mostrarPlantas(): Método que permitirá mostrar todos los propietarios de cada puerta del edificio.
