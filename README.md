# Bon Scott x Brian Johnson: Um estudo de caso de machine learning para classificação de músicas do AC/DC

##Introdução
AC/DC é uma banda de rock australiana formada em Sydney em 1973 pelos irmãos Angus e Malcolm Young. Ao longo de sua longa carreira, a banda teve dois vocalistas principais distintos: Bon Scott, que ingressou em 1974 e faleceu em 1980, e Brian Johnson, que o substituiu no mesmo ano e permaneceu como vocalista principal até os dias atuais. Ambos os vocalistas deixaram uma marca distinta no som e na identidade da banda.

A mudança de vocalistas teve um impacto significativo no estilo e na direção musical do AC/DC. Bon Scott era conhecido por seu estilo de voz rouco e energético, enquanto Brian Johnson trouxe um tom mais agudo e agressivo. Essas diferenças influenciaram diretamente as composições da banda, moldando o som característico do AC/DC ao longo dos anos.

##Machine Learning para Classificação Binária
O problema em questão envolve a diferenciação entre músicas do AC/DC baseadas nos vocais de seus dois principais vocalistas: Bon Scott e Brian Johnson. Para resolver esse problema, utilizaremos técnicas de machine learning para criar um modelo capaz de classificar as músicas de acordo com o vocalista.

##Algoritmos Utilizados
###Decision Tree
Uma árvore de decisão é um modelo de aprendizado supervisionado que aprende a mapear instâncias de entrada para uma saída de decisão com base em observações dos dados de treinamento.

###K-Nearest Neighbors (KNN)
KNN é um algoritmo de aprendizado supervisionado que classifica um ponto de dados com base nos pontos de dados mais próximos em um espaço de características.

###Logistic Regression
A regressão logística é um modelo estatístico que utiliza uma função logística para modelar a probabilidade de uma determinada classe ou evento ocorrer.

##Validação Cruzada e Overfitting
Para avaliar e otimizar o desempenho dos modelos, empregaremos técnicas de validação cruzada. Isso nos permitirá estimar a capacidade de generalização dos modelos e identificar possíveis problemas de overfitting, nos quais o modelo se ajusta demasiadamente aos dados de treinamento e falha em generalizar para dados novos.

##Metadados do Spotify
Foram considerados os metadados fornecidos pelo Spotify, como tempo de duração, energia, danceability, entre outros. Esses metadados podem fornecer informações úteis para a diferenciação das músicas do AC/DC por vocalista. Disponíveis no link: https://www.kaggle.com/datasets/onurbagci3/acdc-spotify/

##Conclusão

O modelo de classificação binária desenvolvido, utilizando o algoritmo K-Nearest Neighbors (KNN), apresentou resultados promissores na diferenciação de músicas do AC/DC de acordo com os vocais de Bon Scott e Brian Johnson.

Observamos que o modelo alcançou uma precisão geral de 74%, com uma precisão de 89% para músicas de Bon Scott e 60% para músicas de Brian Johnson. Embora a precisão para músicas de Brian Johnson seja um pouco menor, é importante ressaltar que o modelo obteve uma taxa de recall mais alta para essas músicas, indicando que ele tem uma capacidade relativamente boa de identificar as músicas desse vocalista.

Esses resultados sugerem que há características distintivas nas músicas do AC/DC associadas aos vocais de Bon Scott e Brian Johnson, e que essas características podem ser capturadas efetivamente pelo modelo KNN. Como ambos os vocalistas têm estilos vocais únicos e reconhecíveis, é razoável esperar que essas diferenças se reflitam nas características musicais e nos metadados das músicas.

Potenciais aplicações práticas deste modelo incluem:

- **Curadoria de Playlists**: Plataformas de streaming de música, como o Spotify, podem utilizar o modelo para criar playlists personalizadas para os fãs do AC/DC, oferecendo uma seleção específica de músicas de acordo com o vocalista preferido do usuário.
  
- **Estudos Musicológicos**: Pesquisadores e musicólogos interessados na evolução do som do AC/DC ao longo do tempo podem utilizar o modelo para analisar como as características musicais e os estilos vocais mudaram entre as eras de Bon Scott e Brian Johnson.

- **Identificação de Covers e Tributos**: O modelo pode ser empregado para identificar e catalogar covers e tributos de músicas do AC/DC, facilitando a organização e classificação dessas versões alternativas.

Em suma, o modelo de classificação desenvolvido oferece uma ferramenta poderosa para diferenciar as músicas do AC/DC com base nos vocais de Bon Scott e Brian Johnson, abrindo portas para uma variedade de aplicações práticas e estudos musicais.
