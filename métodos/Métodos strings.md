

1. **`charAt()`**: Devuelve el carácter en el índice especificado.

   ```javascript
   const str = "hola";
   const char = str.charAt(1);
   console.log(char); // "o"
   ```

2. **`concat()`**: Une dos o más cadenas y devuelve una nueva cadena.

   ```javascript
   const str1 = "Hola";
   const str2 = "Mundo";
   const resultado = str1.concat(" ", str2);
   console.log(resultado); // "Hola Mundo"
   ```

3. **`includes()`**: Determina si una cadena puede encontrarse dentro de otra cadena, devolviendo true o false.

   ```javascript
   const str = "Hola Mundo";
   const incluyeHola = str.includes("Hola");
   console.log(incluyeHola); // true
   ```

4. **`indexOf()`**: Devuelve el índice dentro del objeto String de la primera aparición del valor especificado.

   ```javascript
   const str = "Hola Mundo";
   const indice = str.indexOf("Mundo");
   console.log(indice); // 5
   ```

5. **`slice()`**: Extrae una sección de una cadena y devuelve una cadena nueva.

   ```javascript
   const str = "Hola Mundo";
   const seccion = str.slice(0, 4);
   console.log(seccion); // "Hola"
   ```

6. **`split()`**: Divide un objeto String en un array de cadenas mediante la separación de la cadena en subcadenas.

   ```javascript
   const str = "Hola Mundo";
   const strDividido = str.split(" ");
   console.log(strDividido); // ["Hola", "Mundo"]
   ```

7. **`substring()`**: Devuelve los caracteres de una cadena entre dos índices.

   ```javascript
   const str = "Hola Mundo";
   const subcadena = str.substring(1, 4);
   console.log(subcadena); // "ola"
   ```

8. **`toLowerCase()`**: Devuelve el valor en minúsculas de la cadena que realiza la llamada.

   ```javascript
   const str = "Hola Mundo";
   const strMinusculas = str.toLowerCase();
   console.log(strMinusculas); // "hola mundo"
   ```

9. **`toUpperCase()`**: Devuelve el valor en mayúsculas de la cadena que realiza la llamada.

   ```javascript
   const str = "Hola Mundo";
   const strMayusculas = str.toUpperCase();
   console.log(strMayusculas); // "HOLA MUNDO"
   ```

10. **`trim()`**: Elimina los espacios en blanco en ambos extremos del string.

   ```javascript
   const str = "  Hola Mundo  ";
   const strRecortado = str.trim();
   console.log(strRecortado); // "Hola Mundo"
   ```
