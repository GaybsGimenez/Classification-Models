# Tuning de Parâmetros com GridSearch

Este projeto demonstra a aplicação do método de validação cruzada e ajuste de parâmetros (tuning) em vários algoritmos de classificação utilizando GridSearchCV. Os dados utilizados são de crédito e estão divididos em conjuntos de treinamento e teste.

## Visão Geral

A validação cruzada com ajuste de parâmetros é uma técnica utilizada para melhorar o desempenho dos modelos de aprendizado de máquina. Ao dividir os dados em múltiplas partes e testando várias combinações de parâmetros, podemos encontrar os parâmetros ótimos que maximizam a precisão do modelo.

## Algoritmos Testados

Os seguintes algoritmos de classificação foram testados e seus resultados comparados:

- Naïve Bayes
- Árvore de Decisão
- Random Forest
- K-Nearest Neighbors (KNN)
- Regressão Logística
- Support Vector Machine (SVM)
- Redes Neurais

## Resultados

Os resultados dos modelos utilizando o método tradicional de divisão em grupo de treinamento e teste foram comparados com os resultados após o tuning de parâmetros usando validação cruzada.

| Algoritmo               | Acurácia (Treinamento e Teste) | Acurácia (Validação Cruzada) |
|-------------------------|-------------------------------|-----------------------------|
| Árvore de Decisão       | 98.20%                        | 98.30%                      |
| Random Forest           | 98.40%                        | 98.84%                      |
| KNN                     | 98.60%                        | 98.00%                      |
| Regressão Logística     | 94.60%                        | 94.85%                      |
| SVM                     | 98.80%                        | 98.30%                      |
| Redes Neurais           | 99.60%                        | 99.65%                      |

## Preparação dos Dados

Os dados foram inicialmente divididos em conjuntos de treinamento e teste. Para a validação cruzada, os conjuntos foram concatenados novamente para formar uma base de dados completa.

```python
import pickle
import numpy as np

with open('/content/drive/MyDrive/ML e Data Sciece com python/dataset/credit_risc/credit.pkl', 'rb') as f:
    X_credit_treinamento, y_credit_treinamento, X_credit_teste, y_credit_teste = pickle.load(f)

X_credit = np.concatenate((X_credit_treinamento, X_credit_teste), axis=0)
y_credit = np.concatenate((y_credit_treinamento, y_credit_teste), axis=0)
```

## Tuning de Parâmetros
Foi feito para cada um dos algoritmos a seguir e comparados com os resultados do método de divisão de treinamento e teste (Os códigos dos algoritmos estão disponíveis neste repositório [GitHub](https://github.com/GaybsGimenez?tab=repositories).)
- Árvore de Decisão
- Random Forest
- K-Nearest Neighbors (KNN)
- Regressão Logística
- Support Vector Machine (SVM)
- Redes Neurais

## Requisitos

- Python 3.11
- Jupyter Notebook
- Bibliotecas: pandas, numpy, seaborn, matplotlib, plotly, scikit-learn, pickle, google-colab

```bash
pip install pandas numpy seaborn matplotlib plotly scikit-learn pickle google-colab
```
