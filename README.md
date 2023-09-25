# Base-Tweets-BERT

Este Repositório contém a base de dados produto do trabalho de conclusão de curso de Gabriel Estafocher Medeiros com o tema "Textmining: A visão popular sobre o agronegócio". A base contém 1.6 milhões de tweets em inglês extraidos usando a antiga API do X CORP (Twitter na época ) e contém os seguintess campos:

**sentiment:** a polaridade do tweet (0 é Negativo e 4 é Positivo)

**date:** a data do tweet

**text:** o texto completo do tweet

**texto_preprocessado:** o mesmo texto da coluna anterior, porém removido de acentos gráficos e anonimizados trocando citações como "@nomedeusuário" pelo termo "USER", emojis por "EMOJI" e url's por "URL" além de remover stopwords da lista a seguir:

'a', 'about', 'above', 'after', 'again', 'ain', 'all', 'am', 'an', 'and','any','are', 'as', 'at', 'be', 'because', 'been', 'before',
'being', 'below', 'between','both', 'by', 'can', 'd', 'did', 'do', 'does', 'doing', 'down', 'during', 'each','few', 'for', 'from',
'further', 'had', 'has', 'have', 'having', 'he', 'her', 'here', 'hers', 'herself', 'him', 'himself', 'his', 'how', 'i', 'if', 'in',
'into','is', 'it', 'its', 'itself', 'just', 'll', 'm', 'ma', 'me', 'more', 'most','my', 'myself', 'now', 'o', 'of', 'on', 'once', 
'only', 'or', 'other', 'our', 'ours','ourselves', 'out', 'own', 're', 's', 'same', 'she', "shes", 'should', "shouldve",'so', 'some', 'such',
't', 'than', 'that', "thatll", 'the', 'their', 'theirs', 'them', 'themselves', 'then', 'there', 'these', 'they', 'this', 'those',
'through', 'to', 'too','under', 'until', 'up', 've', 'very', 'was', 'we', 'were', 'what', 'when', 'where','which','while', 'who', 'whom',
'why', 'will', 'with', 'won', 'y', 'you', "youd","youll", "youre", "youve", 'your', 'yours', 'yourself', 'yourselves','wa'

**Proba BERT:** a probabilidade mais alta que o Modelo BERT (https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment) calculou para o sentimento do tweet

**Sentimento:** o sentimento atribuido pelo Modelo BERT (1 Negativo, 2 Levemente Negativo, 3 Neutro, 4 Levemente Positivo, 5 Positivo)
