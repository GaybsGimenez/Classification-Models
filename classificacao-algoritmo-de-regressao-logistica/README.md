# Regressão Logística

Este notebook implementa e avalia modelos de regressão logística utilizando as bibliotecas Scikit-Learn e Yellowbrick.

## Breve resumo sobre o algoritmo de regressão logistica
A regressão logística é um algoritmo de classificação que utiliza conceitos da regressão linear, onde o objetivo é ajustar coeficientes para desenhar a curva S da função sigmoid de forma a melhor separar as classes. 
Um modelo de regressão logística é um tipo de modelo de aprendizado de máquina usado para prever a probabilidade de ocorrência de um evento binário com base em uma ou mais variáveis independentes. É comumente usado para problemas de classificação binária, onde o objetivo é atribuir exemplos a uma de duas classes possíveis. Este modelo calcula a probabilidade de um exemplo pertencer a uma classe utilizando a função logística, que mapeia a soma ponderada das variáveis independentes para um valor entre 0 e 1. Os coeficientes do modelo são estimados através de técnicas de otimização, como a maximização da verossimilhança. O modelo é treinado para minimizar a diferença entre as probabilidades previstas e as classes reais dos exemplos de treinamento.


### **Prós do Modelo de Regressão Logística:**

- **Interpretabilidade:** Os coeficientes estimados fornecem uma interpretação direta do efeito de cada variável independente na variável dependente.
  
- **Flexibilidade:** Pode ser facilmente estendido para lidar com problemas de classificação multiclasse e multilabel.
  
- **Probabilidade Estimada:** Além de fornecer a classe prevista, também fornece a probabilidade estimada de pertencer a cada classe, o que pode ser útil em várias aplicações.

- **Eficiência Computacional:** O modelo é computacionalmente eficiente e pode ser treinado rapidamente mesmo em grandes conjuntos de dados.

- **Menos Suscetível a Overfitting:** Comparado a modelos mais complexos, como redes neurais, é menos suscetível a overfitting quando há poucos dados disponíveis.

### **Contras do Modelo de Regressão Logística:**

- **Limitado a Relações Lineares:** Assume que a relação entre as variáveis independentes e a variável dependente é linear no logito das probabilidades, o que pode ser uma simplificação excessiva para alguns problemas complexos.

- **Não Adequado para Dados Não Lineares:** Se a relação entre as variáveis não for linear, o modelo de regressão logística pode ter um desempenho ruim.

- **Sensível a Outliers:** Pode ser sensível a outliers, especialmente quando a classe de interesse é rara.

- **Assunção de Independência:** Assumir a independência das observações pode ser uma limitação em alguns cenários, especialmente em dados sequenciais ou de séries temporais.

- **Limitado a Problemas de Classificação Binária:** Embora possa ser estendido para problemas multiclasse, ainda é mais naturalmente adequado para problemas de classificação binária.

## Base de Dados

O notebook utiliza dois conjuntos de dados: base risco de crédito e base credit data que estão disponíveis para dowlond já pré-processados em formato .pkl

## Avaliação do Modelo

Após o treinamento, o modelo é avaliado utilizando a matriz de confusão e o relatório de classificação.
