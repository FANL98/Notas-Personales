```python title:zipUnpack.py
a = [1, 2, 3]
b = ["One", "Two", "Three"]
c = list(zip(a, b))
print(c) #[(1, 'One'), (2, 'Two'), (3, 'Three')]
d, e = zip(*c)
print(d) #(1, 2, 3)
print(e) #('One', 'Two', 'Three')
```

`zip` puede ser deshecho mediante el operador `*`, o lo mismo que el unpacking, para recuperar los valores originales 🎁.

> [!NOTE] Anotación
> - =="unpacking"== consultar la nota [[P-1d5]].

🏷️:  #lista #operador #unpacking #zip

🔙 [[P-1e6]]