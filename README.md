# Análise Preditiva com TensorFlow: Previsão de Valores de Imóveis em Boston

## Introdução
Este projeto tem como objetivo desenvolver um modelo preditivo para estimar o valor mediano de residências na área de Boston, utilizando técnicas de Regressão Linear implementadas com TensorFlow. Os dados foram coletados pelo U.S. Census Service e estão disponíveis aqui.

## Descrição do Dataset
- Número de Observações: 506
- Variáveis Preditivas: 13 atributos numéricos/categóricos
- Variável Alvo: Valor mediano das casas ocupadas (MEDV)
Para mais detalhes sobre as variáveis, consulte a seção "Informações gerais do dataset" no repositório.

## Metodologia
- Análise Exploratória de Dados (EDA): Exame inicial dos dados para entender distribuições e identificar possíveis outliers.
- Pré-processamento: Tratamento de dados faltantes e normalização dos atributos.
- Divisão dos Dados: Separação em conjuntos de treino (80%) e teste (20%).
- Desenvolvimento do Modelo: Implementação de uma Regressão Linear simples utilizando TensorFlow, considerando o número médio de quartos por habitação (RM) como variável independente e o valor mediano das casas (MEDV) como variável dependente.
- Avaliação do Modelo: Medição do desempenho do modelo no conjunto de teste e análise dos resultados.

## Tecnologias Utilizadas
- Python
- TensorFlow
- Pandas
- NumPy
- Matplotlib

## Resultados
Os resultados detalhados, incluindo gráficos e métricas de desempenho do modelo, estão disponíveis no notebook modelagem_preditiva_tensorflow.ipynb.
