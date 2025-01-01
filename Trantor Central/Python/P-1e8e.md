```python title:setComprehension.py
frase = "El perro de san roque no tiene rabo"
erres = {i for i in frase if i == "r"}
print(erres) #{'r'}
```

"Set Comprehension" es prácticamente lo mismo que las "List Comprehension" con la única particularidad de que en lugar de usar `[]` se usa `{}` y que los "set" no aceptan duplicados.

🏷️:  #compacto #comprehensions_lists #duplicados #set

🔙 [[P-1e8]]