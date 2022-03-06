# DIO-desafio-Github
Desafio de projeto

## Minha primeira calculadora de juros simples em Python.

c = float(input('Qual é o valor? '))
t = int(input('Quantos MÊSES? '))
i = float(input('qual é a taxa ao MÊS? ').replace(",", "."))
j = c * (i/100) * t
montante = j + c
parcela = montante / t
print('-'*25)
print(f'Valor fornecido: {c}')
print(f'Valor á rceber: {montante:.2f}')
print(f'Em {t} parcelas de: {parcela:.2f}')
