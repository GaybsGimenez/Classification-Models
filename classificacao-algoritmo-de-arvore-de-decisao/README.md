# algoritmo-de-classificacao-arvore-de-decisao

Este repositório contém arquivos Jupyter Notebook que implementam classificadores de árvore de decisão para dois conjuntos de dados. Abaixo está uma visão geral rápida do conteúdo:

## Base de dados de crédito
Fonte (adaptado): https://www.kaggle.com/laotse/credit-risk-dataset 

## Base de dados do censo
Fonte: https://archive.ics.uci.edu/ml/datasets/adult

### Arquivos:
- `árvore de decisão.ipynb`: Arquivo Jupyter Notebook contendo código para classificadores de árvore de decisão.

### Visão Geral:
Estudo do uso de classificadores de árvore de decisão para tarefas de classificação em diferentes conjuntos de dados:

1. Importação de bibliotecas necessárias.
2. Treinamento de modelos de árvore de decisão para avaliação de risco de crédito, classificação de risco de crédito e previsão de renda do censo.
3. Visualização das árvores de decisão.
4. Avaliação do desempenho do modelo usando acurácia, matriz de confusão e relatórios de classificação.

### Uso:
1. Certifique-se de ter Python instalado juntamente com as bibliotecas necessárias.
2. Clone o repositório para sua máquina local.
3. Abra e execute o Jupyter Notebook `árvore de decisão.ipynb`.
4. Siga junto com o código fornecido para treinar classificadores de árvore de decisão em diferentes conjuntos de dados.
5. Certifique-se de ajustar os caminhos dos arquivos, se necessário, para sua configuração local.

### Conjuntos de Dados:
IMPORTANTE!! 
"O conjunto de dados já foi pré-processado e salvo em arquivo .pkl. (se quiser saber como fazer o pré-processamento, deixei no repositório (https://github.com/GaybsGimenez/algoritmo-de-classificacao-naive-bayes)" 

- **risco_credito.pkl**: Conjunto de dados para avaliação de risco de crédito.
- **credit.pkl**: Conjunto de dados para classificação de risco de crédito.
- **census.pkl**: Conjunto de dados para previsão de renda do censo.

### Requisitos:
- Python 3.11.x
- Bibliotecas: `pandas`, `numpy`, `seaborn`, `matplotlib`, `plotly`, `scikit-learn`, `yellowbrick`

### Funcionalidade:
- O notebook aborda treinamento, avaliação e visualização de classificadores de árvore de decisão.
- conjuntos de dados são utilizados para mostrar diferentes casos de uso de árvores de decisão.
