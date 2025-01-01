```python title:whileAnidado.py
i, j = 0, 0
while i < 3:
	while j < 3:
		print(i, j)# 0 0 # 0 1 # 0 2 # 1 0 # 1 1 # 1 2 # 2 0 # 2 1 # 2 2
		j += 1
	j = 0
	i += 1
```

En Python podemos hacer uso del `while` anidado, o en otras palabras un `while` dentro de otro. Esto es especialmente util para generar combinaciones de numéricas.

🏷️:  #bucle #concatenación #iterar #números #while

🔙 [[P-1e3]]