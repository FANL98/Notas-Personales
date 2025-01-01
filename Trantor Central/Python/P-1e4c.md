```python title:matchTupla.py
coordenada = (0, 1)
match coordenada:
	case (0, 0):
		print("Coordenada en origen")
	case (x, 0):
		print(f"Coordenada en eje x: {x}")
	case (0, y):
		print(f"Coordenada en eje y: {y}")#Coordenada en eje y: 1
	case (x, y):
		print(f"Coordenada en: {x}, {y}")
	case _:
		print("Error")
```

Podemos hacer una estructura `match` con tuplas.

🏷️:  #estructura_de_control #match #tuple

🔙 [[P-1e4]]