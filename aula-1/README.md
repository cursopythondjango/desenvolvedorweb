Aula 1 - Python
===============

###Visão geral da linguagem e suas principais funções nativas

Como dito em aula, o python é uma linguagem de programação em alto nível, interpretada/compilada, orientada a objetos,
funcional, e de tipagem forte.

**Exemplos de tipagem**

int = números inteiros, ex: 1
para converter outras variáveis com sucesso para int as mesmas devem ser string ou float
ex: int('1'), int(1.0)

float = números flutuantes / quebrados, ex: 1.3
conversão: float(1), float('2') = 1.0, 2.0

string = variável de texto, ex: '1'
conversão: str(1), str(1.0) = '1', '1.0'

--

###Variáveis para armazenamento de multiplos conteúdos em python. Ex: listas

**Tuplas - tuple**

As tuplas são listas únicas e imutáveis em python, depois de definida a tupla não terá mais alterações.
Ex: a = (1,2,3)

**Listas - list**

As listas, como o nome mesmo diz, são listas como as tuplas mas podem variar de acordo com o algorítmo implementado
Ex: a = [1,2,3]

**Dicionário - dict**

São listas para armazenamento associativo como chave e valor, tem o formato parecido com json
Ex: a = {'fruta':'maça','preco':1,'qualidade':'boa'}

--

**Vimos também em aula, que todos as variáveis e elementos do python são objetos e podem ser vistos com a função dir()**

###Exemplos vistos em aula

```python
numeros = [1,2,3,4,5]

for n in numeros:
    print n

1
2
3
4
5
```

for em string

```python
letras = 'abcdef'

for l in letras:
    print l

a
b
c
d
e
f
```

Apenas para ilustrar os exemplos acima, para fazer um for em um intervalo numérico sequencial
utilizamos a função nativa range()

Ex:

```python
numeros = range(1,10)

for n in numeros:
    print n

1
2
3
4
5
6
7
8
9

# o range ( por ser um intervalo ) vai do número inicial até o final, entretando o número final não entra
# na lista gerada
```

Importante
==========

Qualquer dúvida, insiram no arquivo duvidas.txt e trataremos na próxima aula ou no arquivo respostas.txt
--------------------------------------------------------------------------------------------------------


Bibliografia
------------

http://pt.wikipedia.org/wiki/Python

https://docs.python.org/2/library/functions.html