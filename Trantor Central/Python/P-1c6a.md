```python title:iterador.py
#Estructura de un iterador básico
class MiIterador:
	def __init__(self, datos):
		self.datos = datos
		self.indice = 0
	def __iter__(self):
		return self
	def __next__(self):
		if self.indice < len(self.datos):
			resultado = self.datos[self.indice]
			self.indice += 1
			return resultado
		else:
			raise StopIteration

#Crear un iterador básico
mi_iterador = MiIterador([1, 2, 3])

for elemento in mi_iterador:
	print(elemento) #1 #2 #3
```

Un iterador es un objeto creado a partir de un iterable que puede recorrer los elementos del mismo uno a la vez siguiendo el protocolo de iteración `__iter__()` (devuelve el iterador) y `__next__()` (para obtener el siguientes elemento o lanzar `StopIteration` cuando no queden más).

> [!NOTE] Anotación
> - =="iter"== consultar la nota [[P-1c6a1]].
> - ==Tipos de iteradores== consultar la nota [[P-1c6a2]].
> - ==Múltiples iteradores== consultar la nota [[P-1c6a3]].

🏷️:  #iterable #iterador #iterar #protocolo

🔙 [[P-1c6]]
