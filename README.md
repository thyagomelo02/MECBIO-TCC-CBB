# TCC2-CBB




## Script: CBB - Resultados experimentais.

Este é uma das primeiras avaliações feitas com a utilização do PCA e dos algoritmos SVM e XGBoost.
Este código, possui duas avaliações exaustivas para cada uma das técnicas.
A primeira avaliação, consiste na análise de componentes para as técnicas, com esta análise é possível identificar os componentes que, possuem as melhores assertividades. A segunda avaliação, é a de teste/treino, aplica-se o K-fold variando de 0.1 até 1.0, para os conjuntos de componentes.

## Script: PCA_SVM_XGBOOST_FA_BD1_V6

Aplicação das técnicas de classificação SVM e XGboost junto ao algoritmo bio-inspirado FA na base de dados Churn in Telecom's data set.

Neste script é aplicado os algoritmos de classificação SVM e XGboost também o modelo estatístico
com seu ponderamento feito pelos algoritmos Bio-inspirados.
Também é calculado a Média, tempo e desvio-padrão, bem como o Tempo de execução e a Distância euclidiana 
entre a posição dos melhores agentes para o FA.

Fez-se a analise dos parâmetros de aplicação do XGBoost e a técnica foi reaplicada com os paramêtros atualizados.

## Script: PCA_SVM_TENSORFLOW_PSO_BD1_V2

Código em que o modelo estatístico foi aplicado.
Utilizou-se a base de dados Churn Telecom Datasets.
As técnicas implementadas foram, SVM, TensorFlow, MLP junto ao algoritmo PSO


## Script: PCA_TENSORFLOW_KERAS_V1

Aplicação do TensorFlow 

Neste script o Tensorflow é aplicado e são feitas duas avaliações exaustivas sobre o Tensorflow, a primeira avaliação é baseada no número de componentes, com isso é possível encontrar a assertividade de classificação de cada componente.
A segunda avaliação, é baseada na divisão de teste/treino da base de dados, com ela obtem-se as assertividades dos componentes com o método k-fold variando de [0.1 a 1.0]

Neste script é utilizado a base de dados Churn in Telecom dataset's
