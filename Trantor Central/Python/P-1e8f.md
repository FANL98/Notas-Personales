```python title:dictionaryC.py
lista1 = ['nombre', 'edad', 'región']
lista2 = ['Pelayo', 30, 'Asturias']
mi_dict = {i:j for i,j in zip(lista1, lista2)}
print(mi_dict)
```

"Dictionary Comprehension" es esencialmente lo mismo que "List Comprehension" salvo que en esta estructura hay que asignar los valores a las "llaves" mediante el uso de `:`.

🏷️:  #ciclo #compacto #comprehensions_lists #diccionario #zip

🔙 [[P-1e8]]