# Análise de Sentimento - Plano de Saúde

# Reclamações de Clientes de Planos de Saúde no Reclame Aqui

Este projeto de PNL tem como objetivo analisar as reclamações dos clientes que possuem planos de saúde e registram sua reclamação no site Reclame Aqui. O objetivo principal é classificar as reclamações em três categorias: positivas, negativas ou neutras. Para isso, o projeto foi dividido nas etapas abaixo:

1 - Coleta de dados
Para coletar os dados, foi utilizado o BeautifulSoup para raspar o site Reclame Aqui. A coleta foi feita para as 8 maiores operadoras de planos de saúde do Brasil, com base no número de reclamações registradas no site. Os dados foram salvos em um arquivo CSV.

2 - Limpeza e pré-processamento de textos
Antes de analisar os dados, foi necessário fazer algumas etapas de limpeza e pré-processamento, incluindo: remoção de caracteres especiais, conversão para letras minúsculas, remoção de stop words e tokenização.
 
3 - Análise de sentimento
Para classificar as reclamações em positivas, negativas ou neutras, foi utilizada a biblioteca NLTK para análise de sentimento. O VADER Sentiment Analyzer foi usado para atribuir uma pontuação de sentimento a cada reclamação, que foi dividida em categorias de positivo, negativo e neutro.

4 - Modelo de Machine Learning
Foi criado um modelo de Regressão Logística para prever a polaridade das reclamações com base nos dados limpos. Para isso, os dados foram transformados em uma matriz de frequência de palavras (bag-of-words) e divididos em conjuntos de treinamento e teste. O modelo foi treinado no conjunto de treinamento e testado no conjunto de teste, e a acurácia do modelo foi avaliada.

5 - Visualização dos resultados
Para visualizar os resultados, foram criado gráfico de barras para mostrar a distribuição das reclamações por operadora, assim como a distribuição de sentimentos em cada operadora.


