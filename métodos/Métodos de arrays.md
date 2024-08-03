#### 1. **find()**

**Descripción**: Devuelve el primer elemento del array que cumple con la condición especificada en una función de prueba.

**Sintaxis**: 
```javascript
array.find(callback(element[, index[, array]])[, thisArg])
```

**Ejemplo**:
```javascript
const numeros = [1, 2, 3, 4, 5];
const encontrado = numeros.find(num => num > 3);
console.log(encontrado); // Salida: 4
```

#### 2. **findIndex()**

**Descripción**: Devuelve el índice del primer elemento del array que cumple con la condición especificada en una función de prueba. Si no se cumple ninguna condición, devuelve -1.

**Sintaxis**: 
```javascript
array.findIndex(callback(element[, index[, array]])[, thisArg])
```

**Ejemplo**:
```javascript
const numeros = [1, 2, 3, 4, 5];
const indice = numeros.findIndex(num => num > 3);
console.log(indice); // Salida: 3
```

#### 3. **some()**

**Descripción**: Comprueba si al menos un elemento del array cumple con la condición especificada en una función de prueba. Devuelve `true` o `false`.

**Sintaxis**: 
```javascript
array.some(callback(element[, index[, array]])[, thisArg])
```

**Ejemplo**:
```javascript
const numeros = [1, 2, 3, 4, 5];
const algunoMayorQueCuatro = numeros.some(num => num > 4);
console.log(algunoMayorQueCuatro); // Salida: true
```

#### 4. **every()**

**Descripción**: Comprueba si **todos** los elementos del array cumplen con la condición especificada en una función de prueba. Devuelve `true` o `false`.

**Sintaxis**: 
```javascript
array.every(callback(element[, index[, array]])[, thisArg])
```

**Ejemplo**:
```javascript
const numeros = [1, 2, 3, 4, 5];
const todosMenoresQueDiez = numeros.every(num => num < 10);
console.log(todosMenoresQueDiez); // Salida: true
```

#### 5. **includes()**

**Descripción**: Determina si un array incluye un determinado elemento, devolviendo `true` o `false` según corresponda.

**Sintaxis**: 
```javascript
array.includes(searchElement[, fromIndex])
```

**Ejemplo**:
```javascript
const frutas = ['manzana', 'banana', 'uva'];
const incluyeManzana = frutas.includes('manzana');
console.log(incluyeManzana); // Salida: true
```

#### 6. **concat()**

**Descripción**: Se usa para unir dos o más arrays. Este método no cambia los arrays existentes, sino que devuelve un nuevo array.

**Sintaxis**: 
```javascript
array1.concat(array2, array3, ..., arrayN)
```

**Ejemplo**:
```javascript
const array1 = [1, 2];
const array2 = [3, 4];
const array3 = array1.concat(array2);
console.log(array3); // Salida: [1, 2, 3, 4]
```

#### 7. **join()**

**Descripción**: Une todos los elementos de un array en una cadena y devuelve esta cadena.

**Sintaxis**: 
```javascript
array.join([separator])
```

**Ejemplo**:
```javascript
const elementos = ['Fuego', 'Agua', 'Tierra', 'Aire'];
const cadena = elementos.join(', ');
console.log(cadena); // Salida: "Fuego, Agua, Tierra, Aire"
```

#### 8. **slice()**

**Descripción**: Devuelve una copia de una parte del array dentro de un nuevo array a partir de un índice de inicio hasta un índice de fin (sin incluirlo).

**Sintaxis**: 
```javascript
array.slice([begin[, end]])
```

**Ejemplo**:
```javascript
const animales = ['perro', 'gato', 'elefante', 'león', 'tigre'];
const mamiferos = animales.slice(1, 3);
console.log(mamiferos); // Salida: ["gato", "elefante"]
```

#### 9. **splice()**

**Descripción**: Cambia el contenido de un array eliminando elementos existentes y/o agregando nuevos elementos.

**Sintaxis**: 
```javascript
array.splice(start[, deleteCount[, item1[, item2[, ...]]]])
```

**Ejemplo**:
```javascript
const numeros = [1, 2, 3, 4, 5];
numeros.splice(2, 1, 10);
console.log(numeros); // Salida: [1, 2, 10, 4, 5]
```

#### 10. **map()**

**Descripción**: Crea un nuevo array con los resultados de la llamada a una función proporcionada en cada uno de sus elementos.

**Sintaxis**: 
```javascript
array.map(callback(currentValue[, index[, array]])[, thisArg])
```

**Ejemplo**:
```javascript
const numeros = [1, 2, 3, 4, 5];
const dobles = numeros.map(num => num * 2);
console.log(dobles); // Salida: [2, 4, 6, 8, 10]
```

#### 11. **filter()**

**Descripción**: Crea un nuevo array con todos los elementos que cumplan la condición implementada por la función dada.

**Sintaxis**: 
```javascript
array.filter(callback(element[, index[, array]])[, thisArg])
```

**Ejemplo**:
```javascript
const numeros = [1, 2, 3, 4, 5];
const pares = numeros.filter(num => num % 2 === 0);
console.log(pares); // Salida: [2, 4]
```

#### 12. **reduce()**

**Descripción**: Aplica una función a un acumulador y a cada valor de un array  para reducirlo a un solo valor.

**Sintaxis**: 
```javascript
array.reduce(callback(accumulator, currentValue[, index[, array]])[, initialValue])
```

**Ejemplo**:
```javascript
const numeros = [1, 2, 3, 4, 5];
const suma = numeros.reduce((acc, num) => acc + num, 0);
console.log(suma); // Salida: 15
```

#### 14. **forEach()**

**Descripción**: Ejecuta la función indicada una vez por cada elemento del array.

**Sintaxis**: 
```javascript
array.forEach(callback(currentValue[, index[, array]])[, thisArg])
```

**Ejemplo**:
```javascript
const numeros = [1, 2, 3, 4, 5];
numeros.forEach(num => console.log(num * 2));
// Salida:
// 2
// 4
// 6
// 8
// 10
```