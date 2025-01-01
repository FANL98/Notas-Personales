```python title:zipDiccionario.py
esp = {'1': 'Uno', '2': 'Dos', '3': 'Tres'}
eng = {'1': 'One', '2': 'Two', '3': 'Three'}
for a, b in zip(esp, eng):
	print(a, b) #1 1 #2 2 #3 3

esp = {'1': 'Uno', '2': 'Dos', '3': 'Tres'}
eng = {'1': 'One', '2': 'Two', '3': 'Three'}
for (k1, v1), (k2, v2) in zip(esp.items(), eng.items()):
	print(k1, v1, v2) #1 Uno One #2 Dos Two #3 Tres Three
```

`zip` puede combinar diccionarios, pero solo lo hará con las `keys` 🗝️, no con los valores 💎. Para combinar los valores de los diccionarios, se debe usar el método `items`.

🏷️: #diccionario #for #items #key #zip

🔙 [[P-1e6]]