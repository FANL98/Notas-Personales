```python title:whileElseBreak.py
x = 5
while x > 0:
	x -= 1
	print(x) #4, 3, 2, 1, 0
	if x == 0:
		break
else:
	print("El bucle ha finalizado.")
```

Al final de `while` podemos agregar un `else` que se ejecutara solo cuando el bucle finalice de forma normal y no por un `break`.

> [!NOTE] Anotación
> - =="break"== consultar la nota [[P-1e5]].

🏷️:  #break #bucle #else #estructura_de_control #loop #while

🔙 [[P-1e3]]