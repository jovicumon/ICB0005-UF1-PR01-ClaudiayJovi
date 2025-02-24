# Python: Ejemplos Básicos

## 1. Hola Mundo
El clásico "Hola Mundo" en Python:
```python
print("¡Hola, Mundo!")

# Enteros
edad = 25

# Flotantes
altura = 1.75

# Cadenas de texto
nombre = "Juan"

# Booleanos
es_estudiante = True

# Listas
amigos = ["Ana", "Carlos", "Luisa"]

# Diccionarios
persona = {
    "nombre": "María",
    "edad": 30,
    "ciudad": "Madrid"
}

print(f"{nombre} tiene {edad} años y mide {altura} metros.")

# Condicionales
edad = 18

if edad >= 18:
    print("Eres mayor de edad.")
else:
    print("Eres menor de edad.")
    
# Bucles

## Bucle for
for i in range(5):
    print(f"Valor de i: {i}")

## Bucle while
contador = 0
while contador < 5:
    print(f"Contador: {contador}")
    contador += 1
    
# Lista de números
numeros = [1, 2, 3, 4, 5]

# Comprensión de listas
cuadrados = [n**2 for n in numeros]
print(cuadrados)  # Output: [1, 4, 9, 16, 25]