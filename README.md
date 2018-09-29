![](https://raw.githubusercontent.com/rafafrdz/Leap-Year/master/ejercicio.png)

```python
def esBisiesto(n:int):
    return (n%4==0 and n%100!=0 or n%400==0)

def bisiestoHasta(n:int):
    lista = []
    for i in range(1,(n+1)):
        if esBisiesto(i): lista += [i]
    return lista
```

