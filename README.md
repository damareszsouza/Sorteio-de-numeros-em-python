# Sorteio-de-numeros-em-python
Sorteio de números de 1 a 10 em python


import random

numero_sorteado = random.randint(1, 10)

print("O número sorteado é:", numero_sorteado)

Neste exemplo, o módulo random é usado para gerar um número aleatório entre 1 e 10 usando a função randint(). O número sorteado é armazenado na variável numero_sorteado e é exibido na tela usando a função print(). Você pode modificar os valores passados para a função randint() para alterar o intervalo de números sorteados


exemplos de como você pode usar o módulo random em Python:

Gerando um número aleatório entre 0 e 1:
import random

numero_aleatorio = random.random()

print(numero_aleatorio)
Gerando um número inteiro aleatório entre dois valores especificados:
import random

numero_aleatorio = random.randint(1, 100)

print(numero_aleatorio)
Selecionando aleatoriamente um item de uma lista:
import random

lista = ["maçã", "banana", "laranja"]

item_aleatorio = random.choice(lista)

print(item_aleatorio)

Base para criação de APP de adiviações e videnciaa
