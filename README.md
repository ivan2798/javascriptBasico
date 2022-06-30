**Repositorio Javascript Uno**

Temas como keywords, arreglos o datos primitivos.

> _Todo autodidacta._

```javascript
//console.log("Hola mundo");
//alert("Soy un alert");

//keyword: var, let, const

//dato primitivo:

let num1 = 2;
let num2 = "2";

console.log(num1 == num2); // == no importan tipos
console.log(num1 === num2); // debe ser mismo tipo

let x = 5;
x = x + 5;

console.log("El valor de x es: ", x);

let vehiculos = 40;
let vehiculosBaja = 10;
let vehiculosElectricos = 15;
vehiculos -= vehiculosBaja;
vehiculos += vehiculosElectricos;

console.log("La policia tiene ", vehiculos, "en total");

let listaCompra = ["pan", "fruta", "pescado", "leche"];
let cantidades = [3, 5, 8, 13];
let registroEntradas = [true, false, true, false];

let listaCompra2 = ["pan", ["manzana", "pera"], "pescado", ["leche"]];

console.log(listaCompra2);

/* Arreglo estructura de datos conformado por datos primitivos*/

/*Ahora objetos  */

let listaCompra3 = {
  panaderia: ["bolleria", "pan"],
  fruta: ["manzana", "pera"],
  pescado: "Lubina",
  lactosa: ["leche", "yogur"],
};

console.log(listaCompra3);
```

### End
