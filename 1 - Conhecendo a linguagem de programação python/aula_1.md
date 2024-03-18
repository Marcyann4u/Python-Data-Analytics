# O que são tipos de dados?

> São diferentes formatos e estruturas de dados que podem ser utilizados para armazenar informações.


| Tipos de Dados | |
| -------------- | --- |
| Texto | str |
| Númerico | int, float, complex |
| Sequência | list, tuple, range |
| Mapa | dict |
| Coleção | set, frozenset |
| Booleano | bool |
| Binário | bytes, bytearray, memoryview |

## Texto
- `str` para qualquer valor que estiver contido dentro de aspas ""

## Númerico

- `int` para valores inteiros
- `float` para valores decimais

## Booleano

- `bool` é utilizado para armazenar se um valor é verdadeiro `true`/`1` ou `false`/`0`.

 
# Variáveis

> É um espaço alocado na memória do computador para armazenar informações que podem ou não ser alteradas durante a execução de um algoritmo.

## Criando uma variável

```python
value = 10
```

`value` - nome da variável <br>
`=` - atribuição <br>
`0` - dado que será armazenado

## Alterando uma variável

```python
value = 0
print(value) # 0

value = 10
print(value) # 10
```
## Boas práticas

- O padrão de nomes deve ser snake case
```py
valor_da_compra = 1000
```
- Escolher nomes sugestivos
```python
a = v1 / v2**2 # Modo errado

imc = peso / altura**2 # Modo certo
```
- Nome de constantes em maiúsculo
```python
LIMITE_DE_SAQUE_DIARIO = 5000
```
## Convertendo tipos de variáveis

### `type`

Retorna o tipo de um objeto/valor.

```py
type('Hello World!') # str
type(10) # int
type(7.2) # float
```

Conversão

```py
x = '10'
x = int(x)

type(x)
```

# Exibindo e recebendo valores

`print`

Exibe na tela o valor informado. Possui 4 argumentos opcionais, sendo eles `sep`, `end`, `file` e `flush`.

```python
nome, sobrenome = 'Maria', 'Luíza'

print(nome, sobrenome) # Maria Luíza
print(nome, sobrenome, end='...\n') # Maria Luíza...
print(nome, sobrenome, sep='###') # Maria###Luíza

```

`input`

Espera uma entrada do usuário. Para armazenar esses valores é necessário guardá-los em uma variável. Todos os valores recebidos são convertidos para o tipo `str`.

```python
input()

nome = input("Informe seu nome: ")
```


# Modo interativo

### `dir`

Retorna uma lista com todos os métodos que o valor inserido no dir pode utilizar

```python
dir(value)
```

### `help`

Retorna informações sobre o objeto/valor inserido. Funciona como uma documentação simplificada no terminal.

```python
help(value)
```

obs: para sair da documentação aperte a letra `q`

## Referências

- [Tipos de dados no python](https://docs.python.org/pt-br/3/library/datatypes.html)

- [Modo interativo no python](https://docs.python.org/pt-br/3/tutorial/interpreter.html)