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