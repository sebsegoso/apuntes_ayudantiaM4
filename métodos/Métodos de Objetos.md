#### 1. **Object.keys**

1. **`Object.keys()`**: Devuelve un array de las propiedades enumerables de un objeto.

   ```javascript
   const persona = { nombre: "Alicia", edad: 25, ciudad: "Wonderland" };
   const claves = Object.keys(persona);
   console.log(claves); // ["nombre", "edad", "ciudad"]
   ```

2. **`Object.values()`**: Devuelve un array de los valores de las propiedades enumerables de un objeto.

   ```javascript
   const persona = { nombre: "Alicia", edad: 25, ciudad: "Wonderland" };
   const valores = Object.values(persona);
   console.log(valores); // ["Alicia", 25, "Wonderland"]
   ```

3. **`Object.entries()`**: Devuelve un array de pares de [propiedad, valor] enumerables de un objeto.

   ```javascript
   const persona = { nombre: "Alicia", edad: 25, ciudad: "Wonderland" };
   const entradas = Object.entries(persona);
   console.log(entradas); // [["nombre", "Alicia"], ["edad", 25], ["ciudad", "Wonderland"]]
   ```

4. **`Object.assign()`**: Copia los valores de todas las propiedades enumerables de uno o más objetos a un objeto destino. **Muta el objeto destino.**

   ```javascript
   const destino = { a: 1, b: 2 };
   const fuente = { b: 4, c: 5 };
   const destinoDevuelto = Object.assign(destino, fuente);
   console.log(destinoDevuelto); // { a: 1, b: 4, c: 5 }
   ```