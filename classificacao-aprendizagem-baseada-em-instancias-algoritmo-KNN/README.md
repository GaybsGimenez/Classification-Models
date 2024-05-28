## Algoritmo KNN - Aprendizam baseada em instancias

Este repositório contém um código em Python que implementa o algoritmo k-Nearest Neighbors (k-NN) para classificação de avaliação de risco de crédito. O conjunto de dados está disponível em formato .pkl, já pré-processado.

### Descrição do Algoritmo k-NN
- O k-NN é um algoritmo de aprendizagem supervisionada utilizado para classificação e regressão.
- Funciona encontrando os k vizinhos mais próximos de um ponto de dados de teste e tomando uma decisão com base nos rótulos desses vizinhos.
- É um algoritmo simples de entender e implementar, adequado para conjuntos de dados pequenos a médios.

### Conjunto de Dados de Crédito
- O conjunto de dados consiste em informações relacionadas à avaliação de risco de crédito.
- Os dados estão disponíveis em formato .pkl, que é um formato de serialização do Python.
- O conjunto de dados está pré-processado e dividido em conjuntos de treinamento e teste, pronto para ser usado com o algoritmo k-NN.

### Utilização do Código
- O código carrega o conjunto de dados .pkl, treina o algoritmo k-NN e faz previsões sobre o conjunto de teste.
- Métricas de avaliação, como precisão, recall e F1-score, são calculadas para avaliar o desempenho do modelo.
- A matriz de confusão é visualizada para uma melhor compreensão do desempenho do modelo.

