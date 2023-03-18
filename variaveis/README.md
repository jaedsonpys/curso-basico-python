# Variáveis, tipos de dados e a função `print()`

Imagine uma caixa de sapato, nessa caixa, você pode **guardar qualquer objeto** e escrever na caixa o nome do objeto que está ali dentro. Da mesma forma, uma variável é um *espaço na memória* do computador que pode conter qualquer valor, desde caracteres, números e valores mais complexos. As variáveis só ficam disponíveis **enquanto o programa está sendo executado**, ou seja, são destruídas quando o programa é encerrado.

Geralmente, as variáveis são necessárias quando você irá precisar de um valor várias vezes no seu código. No Python, as variáveis são criadas da seguinte forma:

```python
nome = 'João'
idade = 13
```

No exemplo acima, criamos duas variáveis: uma chamada `nome` e outra chamada `idade`. Criar uma variável é bem simples, você só precisa definir o nome da variável e seu valor, utilizando essa estrutura: `<nome> = <valor>`.

## Nomenclatura

Em várias linguagens de programação existem regras para o **nome da variável**. No Python não é diferente, as regras para nomear uma variável são:

1. O nome da variável **NÃO PODE** começar com um número;
2. Caracteres que não são letras e não são número **NÃO PODEM** ser utilizados (exceto *underline*);
3. O nome da variável **NÃO PODE** conter espaços, use o ***underline (_)*** para separar palavras.

## Tipos de dados simples

O Python possui quatro tipos simples de dados:

- Inteiro (int): O tipo inteiro é um tipo composto por caracteres numéricos (algarismos) inteiros, sem casas decimais:

```python
idade = 25  # Números não contém aspas
```

- Ponto Flutuante ou Decimal (float): É um tipo composto por caracteres numéricos (algarismo) decimais:

```python
peso = 75.43
```

- String (str): É um conjunto de caracteres dispostos numa determinada ordem, geralmente utilizada para representar palavras, frases ou textos:

```python
# String pode conter aspas duplas ou aspas simples
nome = 'João'
nome_completo = "Joao Vitor"
```

- Boolean (bool): Tipo de dado lógico que pode assumir apenas dois valores: falso ou verdadeiro (False ou True em Python). Exemplo: `True` ou `False`:

```python
aluno_novo = True
aprovado = False
```

## Exibindo valores na tela

O Python possui uma função embutida (ou seja, uma funcionalidade que já vem no Python) chamada `print()`, que exibe valores na tela, seja string, número inteiro, número decimal ou booleano, além de exibir outros tipos de dados. Essa função pode ser usada de duas formas:

1. A primeira é imprimindo o valor de uma variável. A função `print()` irá exibir o valor da variável:

```python
nome = 'João'
idade = 13
print(nome)  # saída: 'João'
print(idade) # saída: 13
```

2. A segunda forma é imprimindo o valor diretamente, sem precisar armazenar os valores em uma variável:

```python
print('João')  # saída: 'João'
print(13) # saída: 13
```