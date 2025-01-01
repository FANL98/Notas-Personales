```python title:zipDistint.py
numeros = [1, 2, 3, 4, 5]
espanol = ["Uno", "Dos"]
c = zip(numeros, espanol)
for n, e in c:
	print(n, e) #1 Uno #2 Dos
```

`zip` puede combinar iterables de distintas cantidades de elementos, pero que este solo combinará hasta el último elemento del iterable más corto.

🏷️:  #conjunto #iterar #lista #zip

🔙 [[P-1e6]]