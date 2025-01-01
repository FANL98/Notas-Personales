```python title:argumentosVar.py
def funcion(a, *args, **kwargs):
	print(f"args={a} args={args} kwargs={kwargs}")

funcion(1) #args=1 args=() kwargs={}
funcion(1, 2) #args=1 args=(2,) kwargs={} 
funcion(1, 2, 3, cuatro=4, cinco=5) #args=1 args=(2, 3) kwargs={'cuatro': 4, 'cinco': 5}
```

El ”unpacking“ nos permite pasar un número variable de argumentos a una función.

🏷️: #argumentos #función #variable

🔙 [[P-1d5]]