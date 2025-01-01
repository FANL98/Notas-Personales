```python title:ejemplos.py
#Ejemplo 1
z = 7
x = 1
while z > 0:
	print(' ' * z + '*' * x + ' ' * z)
	x += 2
	z -= 1
#       *
#      ***
#     *****
#    *******
#   *********
#  ***********
# *************

#Ejemplo 2
text = "Python"
i = 0
while i < len(text):
	print(text[:i + 1])
	i += 1
# P
# Py
# Pyt
# Pyth
# Pytho
# Python

#Ejemplo 3
a, b = 0, 1
while b < 25: print(b); a, b = b, a + b #1 #1 #2 #3 #5 #8 #13 #21
```

🏷️:  #bucle #ejemplo #iterar #while

🔙 [[P-1e3]]