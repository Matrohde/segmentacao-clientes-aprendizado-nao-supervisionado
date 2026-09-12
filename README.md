# Segmentação de Clientes com Aprendizado Não Supervisionado

Atividade Prática 01 da disciplina de Aprendizado de Máquina Não Supervisionado do MBA em Inteligência Artificial Aplicada da UNISINOS.

## Objetivo

O projeto tem como objetivo segmentar clientes do dataset Online Retail a partir das variáveis Recency, Frequency e Monetary (RFM), utilizando técnicas de aprendizado não supervisionado.

## Métodos utilizados

Foram comparados três algoritmos de clustering:

- K-Means
- Clustering Hierárquico
- DBSCAN

A avaliação dos agrupamentos considerou métricas como Silhouette Score, Davies-Bouldin e Calinski-Harabasz, além da distribuição e interpretação dos grupos.

Também foi utilizada PCA para redução de dimensionalidade e visualização dos clusters.

## Resultado

O K-Means com quatro clusters foi selecionado como solução final, resultando nos seguintes segmentos:

- Clientes de alto valor
- Clientes pouco ativos
- Clientes recentes de baixa frequência
- Clientes intermediários

O projeto também inclui visualizações interativas desenvolvidas com Plotly.

## Arquivos

- Notebook Jupyter: análise completa e códigos utilizados
- Relatório: síntese dos métodos, resultados e recomendações

## Dados

Foi utilizado o dataset Online Retail, disponibilizado pelo UCI Machine Learning Repository.
