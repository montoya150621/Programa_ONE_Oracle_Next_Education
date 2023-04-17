##  INDICE
### Notas de JavaScript
## 01 - Document.write - Nos ayuda a crear contenido html
## 02 - Funcion return
## 03 - Funcion filter
## 04 - Arrow function
#### 00.1 Notas de programacion
```js
// Crear contenido html directo de JavaScript
document.createElement('p');

// Agregar contenido a una etiqueta html
resultado.appendChild();
```

#### 01 - Funcion document.write();
```js
document.write("<p>Hola mundo</p><h1>Hola mundo</h1>");
```
#### 02 - Funcion return
```js
function sumar(a, b){
  return a + b;
}
let resultado = sumar(4,3); 
console.log(resultado);
```
#### 03 - Funcion filter
```js
// En JavaScript, el método filter() se utiliza para crear un nuevo array con todos los elementos que cumplan una condición determinada. Aquí hay un ejemplo de cómo usar filter() para filtrar elementos de un array:

let myArray = [1, 2, 3, 4, 5];

let filteredArray = myArray.filter(function(element) {
  return element > 2;
});

console.log(filteredArray); // [3, 4, 5]
```
#### 04 - Arrow function
```js
const aprendiendo = function() {
    console.log('Aprendiendo JavaScript');
}

const aprendiendo2 = () =>console.log("Aprendiendo JS");
aprendiendo2();

const suma = (a,b) => a+b;
let resultado = suma(4,5);
console.log(resultado);

```
