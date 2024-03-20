# Dicionários

```python

pessoa = {"nome": "Marcy", "idade":19}

pessoa = dict(nome="Marcy", idade=19)

pessoa["telefone"] = "(81)99999-9999"

```

#### `{}.clear`

```py
contatos = {
    "marcelyjfmelo@gmail.com": {"nome": "Marcely", "sobrenome": "Melo"}
}

contatos.clear() # {}

```
#### `{}.copy`

```py
contatos = {
    "marcelyjfmelo@gmail.com": {"nome": "Marcely", "sobrenome": "Melo"}
}

copia = contatos.copy()

copia['marcelyjfmelo@gmail.com'] # {'nome': 'Marcely', 'sobrenome': 'Melo'}

```

#### `{}.fromkeys`

Adicionar novas chaves em um dicionário

```py

dict.fromkeys(["nome", "telefone"])# {"nome": None, "telefone": None}
dict.fromkeys(["nome", "telefone"], "vazio") # {"nome": "vazio", "telefone":"vazio"}
```

#### `{}.get`

```py
contatos = {
    "marcelyjfmelo@gmail.com": {"nome": "Marcely", "sobrenome": "Melo"}
}

contatos.get("marcelyjfmelo@gmail.com") #{'nome': 'Marcely', 'sobrenome': 'Melo'}

```

#### `{}.items`

```py
contatos = {
    "marcelyjfmelo@gmail.com": {"nome": "Marcely", "sobrenome": "Melo"}
}

contatos.items() # dict_items([('marcelyjfmelo@gmail.com', {'nome': 'Marcely', 'sobrenome': 'Melo'})])        

```

#### `{}.keys`

```py
contatos = {
    "marcelyjfmelo@gmail.com": {"nome": "Marcely", "sobrenome": "Melo"}
}

contatos.keys() # dict_keys(['marcelyjfmelo@gmail.com'])      
```

#### `{}.pop`

```py
contatos = {
    "marcelyjfmelo@gmail.com": {"nome": "Marcely", "sobrenome": "Melo"}
}

contatos.pop("marcelyjfmelo@gmail.com") # {'nome': 'Marcely', 'sobrenome': 'Melo'}
```

#### `{}.popitem`

```py
contatos = {
    "marcelyjfmelo@gmail.com": {"nome": "Marcely", "sobrenome": "Melo"}
}

contatos.popitem() 
```

#### `{}.setdefault`

```py
contatos = {"nome": "Marcely", "sobrenome": "Melo"}

contatos.setdefault("nome", "Marcy")
contatos.setdefault("idade", 19)

contatos # {'nome': 'Marcely', 'sobrenome': 'Melo', 'idade': 19}
```

#### `{}.update`

```py
contatos = {"nome": "Marcely", "sobrenome": "Melo"}

contatos.update({"nome": "Malu"}) #{'nome': 'Malu', 'sobrenome': 'Melo'}
```
#### `{}.values`

```py
contatos = {"nome": "Marcely", "sobrenome": "Melo"}

contatos.values() # dict_values(['Marcely', 'Melo'])
```

#### `in`

```py
contatos = {"nome": "Marcely", "sobrenome": "Melo"}

"nome" in contatos # True
"Marcely" in contatos # False

```

#### `del`

```py
contatos = {"nome": "Marcely", "sobrenome": "Melo"}

del contatos['sobrenome']

```