# JavaScript: Ejemplos Básicos
Consulta la documentación completa de la [Referencia de JavaScript](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference)

## Primero saludemos
El clásico "Hola Mundo" en JavaScript:

```javascript
console.log("¡Hola, Mundo!");
```

Ahora podemos seguir

---

## 1. Objetos Estándar

JavaScript tiene varios objetos estándar integrados. A continuación, se muestra un ejemplo básico de cada uno:

### **Array**
```javascript
let frutas = ["Manzana", "Banana", "Naranja"];
console.log(frutas[0]); // Output: Manzana
```

### **Boolean**
```javascript
let esVerdadero = true;
console.log(esVerdadero); // Output: true
```

### **Date**
```javascript
let fechaActual = new Date();
console.log(fechaActual); // Output: Fecha y hora actual
```

### **Error**
```javascript
try {
    throw new Error("Algo salió mal");
} catch (error) {
    console.log(error.message); // Output: Algo salió mal
}
```

### **Function**
```javascript
function saludar() {
    return "¡Hola!";
}
console.log(saludar()); // Output: ¡Hola!
```

### **JSON**
```javascript
let persona = { "nombre": "Juan", "edad": 30 };
let jsonString = JSON.stringify(persona);
console.log(jsonString); // Output: {"nombre":"Juan","edad":30}
```

### **Math**
```javascript
console.log(Math.sqrt(25)); // Output: 5
```

### **Number**
```javascript
let numero = 42;
console.log(numero.toFixed(2)); // Output: 42.00
```

### **Object**
```javascript
let persona2 = { nombre: "María", edad: 25 };
console.log(persona2.nombre); // Output: María
```

### **RegExp**
```javascript
let regex = /hola/i;
console.log(regex.test("Hola mundo")); // Output: true
```

### **String**
```javascript
let texto = "JavaScript";
console.log(texto.toUpperCase()); // Output: JAVASCRIPT
```

### **Map**
```javascript
let mapa = new Map();
mapa.set("clave1", "valor1");
console.log(mapa.get("clave1")); // Output: valor1
```

### **Set**
```javascript
let conjunto = new Set([1, 2, 3, 3]);
console.log(conjunto.size); // Output: 3 (elimina duplicados)
```

### **WeakMap**
```javascript
let weakMapa = new WeakMap();
let obj = {};
weakMapa.set(obj, "dato");
console.log(weakMapa.get(obj)); // Output: dato
```

### **WeakSet**
```javascript
let weakSet = new WeakSet();
let objeto = {};
weakSet.add(objeto);
console.log(weakSet.has(objeto)); // Output: true
```

## 2. Expresiones y Operadores

### **instanceof**
```javascript
console.log([] instanceof Array); // Output: true
```

### **typeof**
```javascript
console.log(typeof "Hola"); // Output: string
```

### **new**
```javascript
let objetoNuevo = new Object();
console.log(objetoNuevo); // Output: {}
```

### **this**
```javascript
let obj3 = {
    nombre: "Carlos",
    mostrar: function() {
        console.log(this.nombre);
    }
};
obj3.mostrar(); // Output: Carlos
```

### **Precedencia de Operadores**
```javascript
console.log(3 + 5 * 2); // Output: 13 (multiplicación antes de suma)
```

## 3. Sentencias y Declaraciones

### **do-while**
```javascript
let contador = 0;
do {
    console.log(contador);
    contador++;
} while (contador < 3);
```

### **for-in (Recorrer propiedades de un objeto)**
```javascript
let persona4 = { nombre: "Ana", edad: 28 };
for (let clave in persona4) {
    console.log(clave + ": " + persona4[clave]);
}
// Output: 
// nombre: Ana
// edad: 28
```

### **for-of (Recorrer valores de un array)**
```javascript
let numeros = [10, 20, 30];
for (let numero of numeros) {
    console.log(numero);
}
// Output: 10, 20, 30
```

### **try-catch**
```javascript
try {
    let x = y; // y no está definida
} catch (error) {
    console.log("Se produjo un error: " + error.message);
}
```

### **let, var, const**
```javascript
var a = 10;  // Variable global o de función
let b = 20;  // Variable con alcance de bloque
const c = 30; // Constante que no cambia
console.log(a, b, c);
```

### **if-else**
```javascript
let edad2 = 18;
if (edad2 >= 18) {
    console.log("Eres mayor de edad.");
} else {
    console.log("Eres menor de edad.");
}
```

### **switch**
```javascript
let dia = "Lunes";
switch (dia) {
    case "Lunes":
        console.log("Comienza la semana.");
        break;
    case "Viernes":
        console.log("¡Es viernes!");
        break;
    default:
        console.log("Día común.");
}
```

## 4. Funciones

### **switch**
```javascript
function sumar(a, b) {
    return a + b;
}
console.log(sumar(5, 3)); // Output: 8
```

### **Función flecha**
```javascript
const multiplicar = (a, b) => a * b;
console.log(multiplicar(4, 2)); // Output: 8
```

### **Función anónima**
```javascript
let saludo = function() {
    return "¡Hola!";
};
console.log(saludo()); // Output: ¡Hola!
```

### **Función con parámetros predeterminados**
```javascript
function saludar(nombre = "Invitado") {
    return `Hola, ${nombre}`;
}
console.log(saludar()); // Output: Hola, Invitado
```

### **Funciones como parámetros (Callback)**
```javascript
function operacion(a, b, callback) {
    return callback(a, b);
}
console.log(operacion(4, 2, (x, y) => x + y)); // Output: 6
```

### **Funciones dentro de objetos (Métodos)**
```javascript
let persona5 = {
    nombre: "Laura",
    saludar: function() {
        return `Hola, soy ${this.nombre}`;
    }
};
console.log(persona5.saludar()); // Output: Hola, soy Laura
```