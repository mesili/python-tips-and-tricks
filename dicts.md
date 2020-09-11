## Functions parameters are dicts
So you can just use : 
```
>>> def a(b,c,d):
...     print(f'{b} {c} {d}')
... 
>>> e = { 'b':1, 'c':2, 'd':3 }
>>> a(**e)
1 2 3

```

## You can merge multiple dicts 
`
>>> a = {'b':1}
>>> c = {'d':2}
>>> {**a, **c}
{'b': 1, 'd': 2}
```
