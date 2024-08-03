
### Tipos de Datos Primitivos

1. **`String`**: Una cadena de texto.

   ```javascript
   let nombre = "'Hola mi nombres a 34823848 ";
   console.log(nombre); // "Juan"
   ```

2. **`Number`**: Un número. Puede ser un entero o un número decimal.

   ```javascript
   let edad = 30;
   let precio = 19.99;
   console.log(edad); // 30
   console.log(precio); // 19.99
   ```

3. **`Boolean`**: Un valor verdadero o falso.

   ```javascript
   let esMayorDeEdad = true;
   console.log(esMayorDeEdad); // true
   ```

4. **`Undefined`**: Un valor que no ha sido asignado.

   ```javascript
   let indefinido;
   console.log(indefinido); // undefined
   ```

5. **`Null`**: Representa la ausencia intencional de cualquier valor.

   ```javascript
   let valorNulo = null;
   console.log(valorNulo); // null
   ```


### Tipos de Datos No Primitivos (Objetos)

1. **`Object`**: Una colección de pares clave-valor.

   ```javascript
   let persona = {
     nombre: "Ana",
     edad: 25,
     saludar: function(){
	     console.log("hola")
     }
   };
   console.log(persona); // { nombre: "Ana", edad: 25 }
   ```

2. **`Array`**: Una lista ordenada de valores.

   ```javascript
   let colores = ["rojo", "verde", "azul"];
   console.log(colores); // ["rojo", "verde", "azul"]
   ```

3. [**`Function`**](Funciones): Una función es un bloque de código diseñado para realizar una tarea particular.

   ```javascript
   function saludar() {
     console.log("Hola!");
   }
   saludar(); // "Hola!"
   ```

