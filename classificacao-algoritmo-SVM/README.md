# Classificador de Máquina de Vetores de Suporte (SVM)

Este repositório contém uma implementação do algoritmo de Máquina de Vetores de Suporte (SVM) para classificação de dados. O SVM é uma técnica de aprendizado de máquina usada para separar dados em diferentes categorias, encontrando o melhor hiperplano de separação entre eles. É particularmente útil em cenários com conjuntos de dados de alta dimensionalidade.

## Sobre o SVM

O SVM, ou Máquina de Vetores de Suporte, é um algoritmo de aprendizado de máquina usado para classificação. Ele trabalha encontrando o hiperplano que melhor separa os pontos de dados de diferentes classes, maximizando a margem entre eles. Isso permite que o SVM classifique efetivamente novos dados com base nas características aprendidas durante o treinamento. É valioso em muitas situações, especialmente quando os dados têm muitas características.

### Conceitos Chave:
- **Kernels:** Os kernels são fundamentais em algoritmos SVM, pois permitem transformar problemas não lineares em problemas lineares, tornando-os mais facilmente separáveis. Isso é feito mapeando os dados para espaços de características de dimensões mais altas.
- **Parâmetro C:** O parâmetro C no SVM indica o quanto devemos penalizar os erros de classificação. Valores altos de C tentam classificar corretamente todos os pontos de treinamento, o que pode levar ao overfitting, enquanto valores baixos permitem mais erros de classificação, resultando em uma margem de separação mais ampla.

