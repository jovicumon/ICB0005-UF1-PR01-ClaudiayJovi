# Python: Ejemplos Básicos

## 1. Hola Mundo
El clásico "Hola Mundo" en Python:

```python
print("¡Hola, Mundo!")
```

---

## 2. Variables y tipos de datos

### Enteros
```python
edad = 25
```

### Flotantes
```python
altura = 1.75
```

### Cadenas de texto
```python
nombre = "Juan"
```

### Booleanos
```python
es_estudiante = True
```

### Listas
```python
amigos = ["Ana", "Carlos", "Luisa"]
```

### Diccionarios
```python
persona = {
    "nombre": "María",
    "edad": 30,
    "ciudad": "Madrid"
}
```

```python
print(f"{nombre} tiene {edad} años y mide {altura} metros.")
```

---

## 3. Condicionales
```python
edad = 18

if edad >= 18:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")
```

---

## 4. Bucles

### Bucle for
```python
for i in range(5):
    print(f"Valor de i: {i}")
```

### Bucle while
```python
contador = 0
while contador < 5:
    print(f"Contador: {contador}")
    contador += 1
```

---

## 5. Lista de números
```python
numeros = [1, 2, 3, 4, 5]
```

# Comprensión de listas
cuadrados = [n**2 for n in numeros]
print(cuadrados)  # Output: [1, 4, 9, 16, 25]

---



