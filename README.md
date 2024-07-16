<img src="https://cdn.pixabay.com/photo/2020/07/12/10/26/scale-5396788_1280.png" alt="Logo do Projeto" width="400" height="300">

#  Estimativa dos Níveis de Obesidade com Base em Hábitos Alimentares e Condição Física

Este projeto tem como objetivo desenvolver um modelo preditivo para estimar os níveis de obesidade em indivíduos, utilizando dados de seus hábitos alimentares, condição física e comportamentos. Este trabalho foi realizado como parte da disciplina de Aprendizagem de Máquinas do curso de Pós-Graduação Latu Sensu em Visão Computacional da Universidade Federal de Pernambuco.

## Introdução

A obesidade é uma condição que tem aumentado significativamente ao longo das últimas décadas, apresentando sérios riscos à saúde, como doenças cardiovasculares e diabetes tipo 2. Este estudo visa criar um modelo capaz de prever os níveis de obesidade utilizando um conjunto de dados que inclui informações sobre hábitos alimentares, atividade física e outras características pessoais.

## Algoritmos utilizados

Foram aplicados diversos algoritmos de aprendizado de máquina supervisionados, incluindo:

- **K-Nearest Neighbors (K-NN)**
- **Árvore de Decisão**
- **Perceptron Multicamadas (MLP)**
- **Naive Bayes**
- **Support Vector Machine (SVM)**

# Experimentos
Os dados utilizados foram obtidos de uma base que contém informações de indivíduos de Colômbia, Peru e México, com idades entre 14 e 61 anos. Foram utilizados 17 atributos para 2111 registros, após balanceamento com a técnica SMOTE. As etapas de análise incluíram visualização de dados, escalonamento, e encoding de variáveis categóricas.

## Resultados
Os modelos foram treinados e avaliados usando métricas como acurácia, precisão, revocação, f1-score e AUC-ROC. O algoritmo K-NN apresentou alta taxa de acerto na maioria das classes, enquanto a Árvore de Decisão e outros algoritmos também demonstraram bom desempenho.

## Como Usar Este Repositório

1. **Pré-requisitos**: Python 3.8, bibliotecas como scikit-learn, pandas, numpy, matplotlib.
2. **Instalação**:
   ```bash
   pip install -r requirements.txt

3. **Executar o Modelo:**
- Pré-processar os dados.
- Treinar o modelo usando os scripts disponíveis.
- Avaliar o modelo com o conjunto de testes.

Este repositório contém todo o código necessário para reproduzir os resultados apresentados e serve como base para futuros trabalhos na área de predição de obesidade utilizando aprendizado de máquina.
