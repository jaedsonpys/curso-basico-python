# Operadores de comparação

Os operadores de comparação, como seu nome já diz, realizam a comparação entre valores. Esses operadores retornam sempre um **valor booleano**, ou seja, apenas `True` ou `False`. No Python, nós temos **6 operadores de comparação**:

- [ > ] (Maior que): Verifica se um valor é maior que o outro. Exemplo: `x > 28`
- [ < ] (Menor que): Verifica se um valor é menor que o outro. Exemplo: `x < 28`
- [ == ] (Igual a): Verifica se um valor é igual a outro. Exemplo: `x == 5`
- [ != ] (Diferente de): Verifica se um valor é diferente de outro. Exemplo: `x != 5`
- [ >= ] (Maior ou igual a): Verifica se um valor é maior **OU** igual a outro. Exemplo: `x >= 28`
- [ <= ] (Menor ou igual a): Verifica se um valor é menor **OU** igual a outro. Exemplo: `x <= 28`

## Exemplo de uso

Vamos criar um código que nos diz se o usuário é maior de idade ou não:

```python
# obtendo a idade do usuário
idade = int(input('Sua idade: '))
maior_de_idade = idade >= 18
print(maior_de_idade)
```

Veja no código acima que utilizamos o operador de comparação **Maior ou igual a** para verificar a idade do usuário.

Ao executar o código e inserirmos a idade 16, o código irá exibir `False`, ou seja, não é maior de idade. Porém, se colocarmos 25, o código irá exibir `True`, informando que o usuário é maior de idade.