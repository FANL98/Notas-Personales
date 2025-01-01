```python title:zipMulti.py
numeros = [1, 2]
espanol = ["Uno", "Dos"]
ingles = ["One", "Two"]
frances = ["Un", "Deux"]
c = zip(numeros, espanol, ingles, frances)
for n, e, i, f in c:
	print(n, e, i, f) #1 Uno One Un #2 Dos Two Deux
```

`zip` puede aceptar multiples argumentos y combinarlos, siempre y cuando tengan la misma cantidad de elementos.

🏷️: #anidado #for #multiples #zip

🔙 [[P-1e6]]