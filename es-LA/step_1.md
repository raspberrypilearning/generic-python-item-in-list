Comprobar si un elemento está en una lista es fácil en Python: puedes usar la palabra clave `in` como en el ejemplo aquí mostrado. Si el elemento está en la lista, se imprimirá el mensaje "¡Encontrado!".

```python
elemento_a_buscar = "papel"
elementos = ["piedra", "papel", "tijeras"]

if elemento_a_buscar in elementos:
    print(" ¡Encontrado!")
```

También puedes usar un bucle para continuar ejecutando un poco de código hasta que un elemento esté en una lista determinada. Esto es útil para validar la entrada. A continuación estamos usando lo contrario de la palabra clave `in`: `not in`.

```python
direccion = ""
while direccion not in ["N", "S", "E", "O"]:
    direccion = input("Por favor introduce una dirección (N, S, E u O): ")
print(direccion)
```

Este bucle seguirá pidiendo una dirección hasta que el usuario introduzca una que esté en la lista. Una vez que hayan introducido una de las direcciones indicadas como opciones, se imprimirá esa dirección.
