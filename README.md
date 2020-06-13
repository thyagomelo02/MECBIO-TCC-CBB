# TCC2-CBB

Nota: Os comentários acerca dos scripts, estão separados por dataset

# Aplicação dos experimentos sobre a base de dados: Churn in Telecom dataset's

### Script: CBB - Resultados experimentais.

Este é uma das primeiras avaliações feitas com a utilização do PCA e dos algoritmos SVM e XGBoost.
Este código, possui duas avaliações exaustivas para cada uma das técnicas.
A primeira avaliação, consiste na análise de componentes para as técnicas, com esta análise é possível identificar os componentes que, possuem as melhores assertividades. A segunda avaliação, é a de teste/treino, aplica-se o K-fold variando de 0.1 até 1.0, para os conjuntos de componentes.

### Script: PCA_SVM_XGBOOST_FA_PSO_BD1_V6

Aplicação das técnicas de classificação SVM e XGboost junto aos algoritmos bio-inspirado FA e PSO na base de dados Churn in Telecom's data set.

Neste script é aplicado os algoritmos de classificação SVM e XGboost também o modelo estatístico
com seu ponderamento feito pelos algoritmos Bio-inspirados.
Também é calculado a Média, tempo e desvio-padrão, bem como o Tempo de execução e a Distância euclidiana 
entre a posição dos melhores agentes para o FA e PSO.

Fez-se a analise dos parâmetros de aplicação do XGBoost e a técnica foi reaplicada com os paramêtros atualizados.

### Script: PCA_TENSORFLOW_KERAS_V1

Aplicação do TensorFlow 

Neste script o Tensorflow é aplicado e são feitas duas avaliações exaustivas sobre o Tensorflow, a primeira avaliação é baseada no número de componentes, com isso é possível encontrar a assertividade de classificação de cada componente.
A segunda avaliação, é baseada na divisão de teste/treino da base de dados, com ela obtem-se as assertividades dos componentes com o método k-fold variando de [0.1 a 1.0]

### Scrip: APLICACAO_MLP_BD1_V3

Este é uma das primeiras avaliações feitas com a utilização do PCA e do algoritmo MLP. Este código, possui duas avaliações exaustivas para a técnica. A primeira avaliação, consiste na análise de componentes para as técnicas, com esta análise é possível identificar os componentes que, possuem as melhores assertividades. A segunda avaliação, é a de teste/treino, aplica-se o K-fold variando de 0.1 até 1.0, para os conjuntos de componentes. Toda a aplicação é feita sobre a base de dados Churn in Telecom dataset's

### Script: PCA_SVM_TENSORFLOW_MLP_PSO_FA_BD1_V3

Código em que o modelo estatístico foi aplicado.
Utilizou-se a base de dados Churn Telecom Datasets.
As técnicas implementadas foram, SVM, TensorFlow, MLP junto aos algoritmos bio inspirados PSO e FA, também aplicado modelo estatístico

# Aplicação dos experimentos sobre a base de dados: Telco Customer Churn.


### Script: PCA_SVM_MLP_TENSORFLOW_PSO_FA_BD3_V2

Aplicação das técnicas de classificação SVM, MLP e Tensorflow junto ao algoritmo bio-inspirado PSO e aplicado na base de dados Telco Customer Churn.
Neste script é aplicado os algoritmos de classificação SVM, MLP e Tensorflow e o modelo estatístico com seu ponderamento feito pelos algoritmos Bio-inspirados.


# Aplicação dos experimentos sobre a base de dados: Cardio Train.

