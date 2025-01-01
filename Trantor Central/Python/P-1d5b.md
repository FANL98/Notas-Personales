```python title:operadorUnpacking.py
*a, b, c, d = (1, 2, 3, 4, 5, 6, 7, 8)
print(a) #[1, 2, 3, 4, 5]
print(b) #6
print(c) #7
print(d) #8
e = [*a, b, c, d]
print(e) #[1, 2, 3, 4, 5, 6, 7, 8]
a = {"uno": 1, "dos": 2}
b = {"tres": 3, "cuatro": 4}
c = {**a, **b}
print(c) #{'uno': 1, 'dos': 2, 'tres': 3, 'cuatro': 4}
for primero, *resto in [(1, 2, 3), (4, 5, 6, 7)]:
print("Primero:", primero)
print("Resto:", resto)
#Primero: 1
#Resto: [2, 3]
#Primero: 4
#Resto: [5, 6, 7]
```

Cuando los valores del dato iterable son más que las variables se puede hacer uso del símbolo `*` para ingresarle multiples valores a la variable que lo tenga. También podemos utilizar el `*` para unir valores. `**` sirve para desempacar o los elemento de los diccionarios.

🏷️:  #data_type #diccionario #iterar #secuencia #unpacking

🔙 [[P-1d5]]