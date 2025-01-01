```python title:matchMulti.py
mes = 4
match mes:
	case 12 | 1 | 2: print("Invierno")
	case 3 | 4 | 5: print("Primavera") #Primavera
	case 6 | 7 | 8: print("Verano")
	case 9 | 10 | 11: print("Otoño")
	case _: print("Error")
```

Nuestros `case` pueden tener multiples condiciones en la misma línea mediante el `|` que el `match` interpretara como un `or`.

🏷️:  #compacto #comparación #match

🔙 [[P-1e4]]