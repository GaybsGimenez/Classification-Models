# Random Forest Classifier

Este notebook Jupyter demonstra o uso do Classificador Random Forest para dois conjuntos de dados diferentes: um conjunto de dados de crédito e um conjunto de dados censitários. O notebook fornece trechos de código juntamente com explicações e análises dos resultados.

## Visão Geral
Random Forest é um método poderoso de aprendizado de conjunto usado para tarefas de classificação. Ele consiste em múltiplas árvores de decisão, onde cada árvore dá uma previsão de classe, e a previsão final é determinada por uma votação majoritária de todas as árvores.

## Dependências
- Python 3.11
- NumPy
- Pandas
- Scikit-learn
- Yellowbrick

## Utilização
1. Certifique-se de que todas as dependências estão instaladas no seu ambiente Python.
2. Execute as células do notebook sequencialmente para executar o código e ver os resultados.

## Conjunto de Dados
Dois conjuntos de dados são usados neste notebook: as duas bases ja préprocessadas estão na pasta dataset zipada, o processo de pré-processamento não foi abordado nesse notbook, você encontrará o pré-processamento nesse repositório: <https://github.com/GaybsGimenez/algoritmo-de-classificacao-naive-bayes>

1. **Conjunto de Dados de Crédito**: Este conjunto de dados contém informações sobre solicitantes de crédito, incluindo características como renda, idade e valor do empréstimo, juntamente com uma variável alvo indicando se o solicitante é considerado digno de crédito ou não.
2. **Conjunto de Dados Censitários**: Este conjunto de dados contém informações demográficas sobre indivíduos, como idade, educação e ocupação, juntamente com uma variável alvo indicando se um indivíduo ganha mais de $50 mil por ano.
   

## Resultados e Análises
- Para o conjunto de dados de crédito, o modelo Random Forest alcança alta acurácia, precisão, recall e F1-score para ambas as classes, indicando excelente desempenho em distinguir entre solicitantes dignos de crédito e não dignos de crédito.
- Para o conjunto de dados censitários, o modelo alcança métricas de desempenho ligeiramente mais baixas em comparação com o conjunto de dados de crédito, sugerindo desempenho relativamente inferior em distinguir entre indivíduos ganhando acima e abaixo de $50 mil anualmente.
- Uma comparação entre os dois conjuntos de dados revela que o modelo treinado no conjunto de dados de crédito tem um desempenho melhor e mais consistente em prever rótulos corretos, provavelmente devido à maior quantidade de dados disponíveis para treinamento e teste.

## Conclusão
O classificador Random Forest demonstra um desempenho robusto, especialmente para o conjunto de dados de crédito, mostrando sua eficácia em tarefas de classificação com características diversas. No entanto, o desempenho pode variar dependendo da natureza e do tamanho do conjunto de dados. 
