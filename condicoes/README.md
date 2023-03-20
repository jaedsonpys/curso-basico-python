# Condições

As condições servem para realizar ações de acordo com um parâmetro. Como exemplo, imagine que o seu programa realiza cadastro de usuários, porém, o cadastro só é realizado se o usuário for maior de idade. Se o usuário for maior de idade, o programa realiza o cadastro, caso contrário, exibe uma mensagem informando que o cadastro não pode ser realizado.

No Python, nós podemos "verificar" o valor de expressões utilizando o `if` (Se...) e `else` (Caso contrário...) em nosso código. Veja a estrutura de uma condição:

```python
if valor_a_ser_validado:
    # código a ser executado caso o valor seja verdadeiro
else:
    # código a ser executado caso o valor seja falso
```

Se o valor a ser validado for igual a `True`, o código contido na instrução `if` será executado. Caso o valor a ser validade seja `False`, o código contido na instrução `else` será executado.## Exemplo de uso

Vamos criar um código que realiza o cadastro de usuários que são maior de idade utilizando condições:

```python
nome = input('Seu nome: ')
idade = int(input('Sua idade:' ))

# se a idade for maior ou igual a 18...
if idade >= 18:
    print('Cadastro realizado!')
else:  # caso contrário...
    print('Não é possível realizar seu cadastro!')
```

Como vimos na aula sobre [operadores de comparação](https://github.com/jaedsonpys/curso-basico-python/tree/master/operadores-de-comparacao), uma expressão (exemplo: `16 >= 18`) sempre retorna um valor booleano, ou seja, `True` ou `False` (Verdadeiro ou Falso).

## Exemplo de uso

Vamos criar um código que realiza o cadastro de usuários que são maior de idade utilizando condições:

```python
nome = input('Seu nome: ')
idade = int(input('Sua idade:' ))

# se a idade for maior ou igual a 18...
if idade >= 18:
    print('Cadastro realizado!')
else:  # caso contrário...
    print('Não é possível realizar seu cadastro!')
```

Como vimos na aula sobre [operadores de comparação](https://github.com/jaedsonpys/curso-basico-python/tree/master/operadores-de-comparacao), uma expressão (exemplo: `16 >= 18`) sempre retorna um valor booleano, ou seja, `True` ou `False` (Verdadeiro ou Falso).