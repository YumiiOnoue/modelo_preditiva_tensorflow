# Projeto: The Boston Housing Dataset

## Informações gerais do dataset

Este é um mini-projeto elaborado no curso de Python da Data Science Academy.
Os dados utilizados nesse mini-projeto foram coletadas pelo U.S Census Service e contém informações sobre as moradias na área de Boston. 
Você pode encontrar os dados e mais informações nesse link: https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html

## Premissas do negócio

- Número de Observações: 506
- Os primeiros 13 recursos são recursos preditivos numéricos / categóricos.
- O último (atributo 14): o valor mediano é a variável de destino.

## Estratégias e soluções

Para a análise dos dados foi utilizado a Regressão Linear, considerando RM (número médio de quartos por habitação) como sendo a variável independente e MEDV (valor médio de casas ocupadas) a variável dependente.

Os dados também foram dividos na proporção de 80/20 para treino e teste.
