# TFword2vec
Classificação de autoria textual a partir de embeddings treinados em Word2Vec (modalidade SkipGram)
Predição da autoria de tweets com base em um corpora treinado em uma rede neural Word2Vec na modalidade SkipGram

PUC Minas Gerais - Trabalho de Conclusão de Curso apresentado ao Curso de Especialização em Ciência de Dados e Big Data como requisito parcial à obtenção do título de especialista.

# Conteúdo do arquivo TFword2vec.IPYNB
1. Dataset
* Extração de dados da API e persistência do respectivo dataset no sistema de arquivos do SO
2. Carregando os dados do sistema de arquivos
3. Separação de arquivos para teste
4. Tokenizando o corpora coletivamente entre os autores
* Tokenizando o corpora para os dados de teste
5. Construindo os Dicionários
6. Exploração inicial dos dados
7. Gerando Lotes de Dados para o Skip-Gram
8. Criando o grafo do TensorFlow
9. Rodando o modelo do TensorFlow
10. Visualizando o resultado do treinamento do Word2Vec
11. Criando embeddings únicos para cada autor e para cada entrada de teste
12. Criando uma matriz de distância para analisar a semelhança entre os diversos embeddings
* Fazendo um recorte apenas nos dados de relação treino-teste
13. Utilizando os algoritmos de classificação Centróide Mais Próximo (NearestCentroid) e Regressão Logistica (Logistic Regression) para predição das entradas de teste
* Centróide Mais Próximo
* Regressão Logística
* Algoritmos com performance menor
14. Resultado final
