# Listas

Listas são uma forma de guardar diversos dados em **apenas uma variável**, onde podemos acessar esses valores através de um número chamado "index". O index é a **posição do valor** na lista, que começa sua contagem com 0.

Em uma lista, podemos armazenar diversos valores já vistos nesse curso, como string, números inteiros, números de ponto flutuante, valores booleanos e até listas. Sim, você pode armazenar listas dentro de outras listas.

## Estrutura de uma lista

Vamos criar um código que armazena o nome de vários alunos de uma escola:

```python
alunos = ['Jaedson', 'Pedro', 'Gabriel']
print(alunos)  # exibindo esses valores
```

Para criar uma lista, como mostrado acima, é necessário inserir os valores entre colchetes (`[]`) e separá-los usando vírgulas. Na lista acima, temos **3 elementos**: Jaedson, Pedro e Gabriel, representados como `['Jaedson', 'Pedro', 'Gabriel']`.

E se quisermos exibir apenas um valor desta lista? Para isso, utilizaremos o `index` do valor que queremos exibir. Veja um exemplo:

```python
alunos = ['Jaedson', 'Pedro', 'Gabriel']
print(alunos)  # exibindo TODOS os valores
print(alunos[0])  # exibindo APENAS o primeiro valor da lista
```

Como dito anteriormente, a "numeração" dos valores de uma lista sempre começam com 0, então, se quisermos exibir o valor *'Jaedson'*, usamos o index 0. Para obter apenas um valor da lista utilizando o index, utilizamos colchetes (`[]`) e adicionamos o index entre os colchetes, por exemplo: `alunos[0]`, isso irá retornar o valor localizado na posição indicada, que nesse caso é "Jaedson".

## Adicionando valores a uma lista

Para adicionar valores a uma lista já criada anteriormente, utilizamos o método `append()`, que adiciona um novo valor no final da lista. Veja um exemplo:

```python
alunos = ['Jaedson', 'Pedro', 'Gabriel']
print(alunos)  # exibindo os valores

alunos.append('Arthur')
alunos.append('Marcos')

print(alunos)  # exibindo os valores
```

O método `append()` recebe o valor a ser adicionado na lista entre os parênteses, esse valor pode ser qualquer tipo de dado do Python.