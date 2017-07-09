#### Hay 7 tipos de datos en Javascript


* numbers (primitivo)
* strings (primitivo)
* booleans (primitivo)
* undefined (primitivo)
* null (primitivo)
* symbol (primitivo)
* object


**number**: Double-precision floating-point de 64 bits. Ej. de valores posibles:

```javascript
Number.MAX_VALUE = 1.7976931348623157e+308
Number.MIN_VALUE = 5e-324
Number.MAX_SAFE_INTEGER = 9007199254740991
Number.MIN_SAFE_INTEGER = -9007199254740991
Number.NEGATIVE_INFINITY = -Infinity
Number.POSITIVE_INFINITY = Infinity
Number.NaN = NaN
```


**string**: una lista de enteros de 16 bits. Son inmutables.

**booleans**: tienen dos valores posibles true o false

**undefined**: es un tipo de dato y una valor. Cuando una variable no tiene asignado ningún valor entonces es undefined.

```javascript
typeof undefined = "undefined"
```
	   
**null**: solo tiene un valor posible qué es null

**object**: es una referencia a una colección de propiedades. Las propiedades pueden ser del tipo string o Symbol y los valores pueden ser de cualquier tipo, incluso otro objeto. 
Las funciones son objetos que tienen la particularidad de poder ser invocadas.
Los objetos pueden tener getters y setter para acceder a sus keys.


-----
#### Conversión automática de tipos


```javascript
console.log (8 * null) // 0 
console.log ("5" - 1) // 4 
console.log ("5" + 1) // 51 
console.log ("five" * 2) // NaN 
console.log (false == 0) // true
```

```javascript
null == undefined // true
null === undefined // false
```

----
#### Short-circuiting of logical operators

```javascript
console.log ( null || " user ") // user
console.log (" Karl " || " user ") // Karl
```

