# Entrada de dados e conversão de valores

Algum dia você provavelmente precisará receber dados do seu usuário, como nome, idade, email ou outro tipo de informação. Isso é possível no Python, e de uma forma bem simples com a função embutida `input()`.

Essa função possibilita que o usuário consiga inserir dados e que você possa manipulá-los futuramente.

## Utilizando a função `input()`

Vamos utilizar essa função para obter o nome e a idade de um usuário e armazenar esses valores em uma variável:

```python
nome = input('Insira seu nome: ')
idade = input('Insira sua idade: ')

# exibindo os valores
print(nome)
print(idade)
```

A função `input()` requer uma mensagem a ser exibida ao usuário para informar o que ele deve inserir, essa mensagem será exibida ao usuário quando o programa for executado.

No exemplo acima, quando o usuário inserir seu nome, essa informação será armazenada na variável `nome`. O mesmo acontece quando inserimos a idade, o valor será armazenado na variável `idade`, porém, mesmo que inserirmos um número, o tipo de dado dessa variável será `string`, ou seja, se colocassemos nossa idade como 22, o valor da váriável será `"22"` em vez de apenas `22`.

Isso acontece porque a função `input()` sempre retorna uma string (ou seja, um valor em "texto"), independentemente do valor inserido. É aí que entra a *conversão de valores*.

## Convertendo valores

Se você quiser que o valor inserido seja um número, basta converter de string para inteiro utilizando a função embutida `int()`. Essa função pode converter strings que **possuem apenas caracteres numéricos**, isso é bem simples de ser feito, veja:

```python
idade_em_string = '22'
idade_em_numero = int(idade_em_string)
```

No código acima, estamos convertendo o valor da variável `idade_em_string` (que é "22") em um valor numérico, armazenando o valor convertido na variável `idade_em_numero`.

E se tentássemos converter uma palavra para um valor numérico, o que aconteceria? Simples, uma **exceção** será lançada, em outras palavras, o Python iria apresentar um erro informando que a conversão não é possível.