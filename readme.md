# Medical insurence costs
## Paulo Lopes - RM:551137
## Gustavo Melo - RM: 98809

Utilizamos o algoritmo de Regressão Linear para prever os custos médicos pessoais com base em diversas características demográficas e comportamentais. Utilizamos o conjunto de dados Medical Cost Personal Datasets, disponível no Kaggle.

Os dados foram carregados e pré-processados para garantir que todas as variáveis estivessem no formato numérico, necessário para o treinamento do modelo de Regressão Linear. Variáveis categóricas foram codificadas usando Label Encoding para converter categorias em números. Um modelo de Regressão Linear foi criado e treinado com os dados de treino, o modelo então foi usado para fazer previsões nos dados de teste, o desempenho foi avaliado calculando o Erro Quadrático Médio (MSE) entre as previsões e os valores reais. Visualizamos o resultado por meio de um gráfico de dispersão, mostrando a comparação entre os valores reais e previstos dos custos médicos.

A análise demonstrou que o modelo de Regressão Linear pode ser eficaz na previsão dos custos médicos pessoais com base nas características analisadas. No entanto, é importante notar que a complexidade do modelo e a escolha das características podem afetar significativamente a precisão das previsões. Futuras análises podem explorar modelos mais avançados e técnicas de seleção de características para melhorar a precisão preditiva.