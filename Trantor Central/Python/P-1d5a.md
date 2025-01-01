```python title:range.py
for i in range(0, 10, 2):
	print(i) #Salida: 0, 2, 4, 6, 8
for i in range (5, 0, -1):
	print(i) #5,4,3,2,1
```

El método `range()` genera secuencias de números en un rango determinado. Acepta hasta 3 argumentos, "start", "stop" y "step", el primero determina a partir de que número inicia la secuencia, el segundo determina hasta que número llega la secuencia y el tercero suma al número actual en la secuencia la cantidad ingresada. En caso de sólo ingresar un argumento se tomará cómo el último número de la secuencia menos 1 y esta empezará por el 0. En caso de hacer el "start" > "stop" y el "step" negativo la secuencia ira de más a menos.

🏷️: #argumentos #for #función #invertido #iterable #iterar #números #secuencia

🔙 [[P-1d5]]