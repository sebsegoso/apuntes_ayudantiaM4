
Las funciones en JavaScript son bloques de código reutilizables que realizan una tarea específica.

### 1. Declaración de Funciones 

Una función declarada se define usando la palabra clave `function` seguida del nombre de la función, parámetros y el cuerpo de la función. Esta función si aplica [Hoisting](Hoisting.md)

**Ejemplo:**

```javascript
function saludar(nombre) {
  return `Hola, ${nombre}!`;
}
console.log(saludar("Juan")); // Salida: Hola, Juan!
```

### 2. Función anónima

Las funciones también se pueden definir como una expresión asignada a una variable.

**Ejemplo:**

```javascript
const saludar = function(nombre) {
  return `Hola, ${nombre}!`;
};
console.log(saludar("Ana")); // Salida: Hola, Ana!
```

### 3. Funciones Flecha (Arrow Functions)

Introducidas en ES6, las funciones flecha tienen una sintaxis más corta y no tienen su propio `this`.

Ejemplo:
```javascript
const saludar = (nombre) => `Hola, ${nombre}!`;
console.log(saludar("Luis")); // Salida: Hola, Luis!
```


## Extra
- Los parámetros pueden llevar valores por defecto

	**Ejemplo:**

```javascript
function saludar(nombre = "Juan") {
  return `Hola, ${nombre}!`;
}
console.log(saludar()); // Salida: Hola, Juan!
console.log(saludar("Pepito")); // Salida: Hola, Pepito!
```

- Pueden invocarse a si mismas

```javascript
function fibonacci(n) {
// Caso base: los dos primeros números de la secuencia son 0 y 1

	if (n === 0) {
		return 0;
	} else if (n === 1) {
		return 1;
	} else {
		return fibonacci(n - 1) + fibonacci(n - 2);
	}
}
console.log(fibonacci(0)); /* 0 */
console.log(fibonacci(1)); /* 1 */
console.log(fibonacci(2)); /* 1 */
console.log(fibonacci(3)); /* 2 */
console.log(fibonacci(4)); /* 3 */
console.log(fibonacci(5)); /* 5 */
console.log(fibonacci(6)); /* 8 */
console.log(fibonacci(7)); /* 13 */
console.log(fibonacci(8)); /* 21 */
console.log(fibonacci(9)); /* 34 */
console.log(fibonacci(10)); /* 55 */
```

