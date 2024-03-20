# Conjuntos

#### `set`

O set remove os elementos duplicados

#### `{}.union`

```py
conjunto_a = {1, 2, 3}
conjunto_b = {2, 3, 4}

conjunto_a.union(conjunto_b) # {1, 2, 3, 4}
```

#### `{}.intersection`

```py
conjunto_a = {1, 2, 3}
conjunto_b = {2, 3, 4}

conjunto_a.intersection(conjunto_b) # {2, 3}
```

#### `{}.difference`

```py
conjunto_a = {1, 2, 3}
conjunto_b = {2, 3, 4}

conjunto_a.difference(conjunto_b) # {1}
conjunto_b.difference(conjunto_a) # {4}
```

#### `{}.issubset`

```py
conjunto_a = {1, 2, 3}
conjunto_b = {1, 2, 3, 4, 5}

conjunto_a.issubset(conjunto_b) # True
conjunto_b.issubset(conjunto_a) # False
```

#### `{}.issuperset`

```py
conjunto_a = {1, 2, 3}
conjunto_b = {1, 2, 3, 4, 5}

conjunto_a.issuperset(conjunto_b) # False
conjunto_b.issuperset(conjunto_a) # True
```

#### `{}.isdisjoint`

```py
conjunto_a = {1, 2, 3}
conjunto_b = {4, 5, 6}
conjunto_c = {2, 4}

conjunto_a.isdisjoint(conjunto_b) # True
conjunto_b.isdisjoint(conjunto_c) # False
```
#### `{}.add`

```py
sorteio = {1, 23}

sorteio.add(20) # {1, 23, 20}
sorteio.add(10) # {1, 23, 20, 10}
sorteio.add(17) # {1, 23, 20, 10, 17}

```
#### `{}.copy`

```py
sorteio = {1, 23}

sorteio.copy()
```

#### `{}.discard`

```py
sorteio = {1, 23, 1, 20, 17}

sorteio.discard(1)

sorteio # {17, 20, 23}
```

#### `{}.pop`

```py
sorteio = {1, 23, 1, 20, 17}

sorteio.pop() # 1
sorteio.pop() # 23

sorteio # {1, 20, 17}
```

#### `{}.remove`

```py
sorteio = {1, 23, 1, 20, 17}

sorteio.remove(20)

sorteio # {1, 23, 1, 17}
```
#### `len`

```py
sorteio = {1, 23, 1, 20, 17}

len(sorteio) # 4
```

#### `in`

```py
sorteio = {1, 23, 1, 20, 17}

1 in sorteio # True
100 in sorteio # False
```
