# Base-Tweets-BERT

Este Repositório contém a base de dados produto do trabalho de conclusão de curso de Gabriel Estafocher Medeiros com o tema "Textmining: A visão popular sobre o agronegócio". A base contém 1.6 milhões de tweets em inglês extraidos usando a antiga API do X CORP (Twitter na época ) e contém os seguintess campos:

**sentiment:** a polaridade do tweet (0 é Negativo e 4 é Positivo)

**date:** a data do tweet

**text:** o texto completo do tweet

**Proba BERT:** a probabilidade mais alta que o Modelo BERT (https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment) calculou para o sentimento do tweet (as probabilidades contém 6 casas decimais e foram multiplicadas por 1000000 para torná-las interias, ou seja, uma Proba BERT de 347460 significa 0.347460%)

**Sentimento:** o sentimento atribuido pelo Modelo BERT (1 Negativo, 2 Levemente Negativo, 3 Neutro, 4 Levemente Positivo, 5 Positivo)
