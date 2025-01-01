```python title:swicth.py
def operation(a, b, operator):
	return {
		'add': lambda: a + b,
		'sub': lambda: a - b,
		'multi': lambda: a * b,
		'div': lambda: a / b,
	}.get(operator, lambda: None)
print(operation(1, 2, 'add')()) #3
```

`switch` es una estructura de control presente dentro de muchos lenguajes de programación, con excepción de Python. Sin embargo es posible simular el comportamiento de uno mediante el uso de un diccionario 📖. Aunque el `if` permite operaciones más complejas, en caso de ser muchas las condiciones que se tienen que hacer el `switch` resulta ser la opción más rápida ⚡️.

🏷️: #condicional #estructura_de_control #match

🔙 [[P-1e4]]