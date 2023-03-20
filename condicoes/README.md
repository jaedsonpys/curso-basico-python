# Condições

As condições servem para realizar ações de acordo com um parâmetro. Como exemplo, imagine que o seu programa realiza cadastro de usuários, porém, o cadastro só é realizado se o usuário for maior de idade. Se o usuário for maior de idade, o programa realiza o cadastro, caso contrário, exibe uma mensagem informando que o cadastro não pode ser realizado.

No Python, nós podemos "verificar" o valor de expressões utilizando o `if` (Se...) e `else` (Caso contrário...) em nosso código. Veja a estrutura de uma condição:

```python
if valor_a_ser_validado:
    # código a ser executado caso o valor seja verdadeiro
else:
    # código a ser executado caso o valor seja falso
```

Se o valor a ser validado for igual a `True`, o código contido na instrução `if` será executado. Caso o valor a ser validade seja `False`, o código contido na instrução `else` será executado.