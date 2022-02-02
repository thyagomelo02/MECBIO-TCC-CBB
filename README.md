# Um modelo Bayesiano baseado em algoritmos bio-inspirados para classificação binária.

#### Ricardo Morello dos Santos
#### Thyago Melo dos Santos

Nota: Esse repositório tem como objetivo documentar os experimentos realizados do trabalho proposto. Os experimentos estão separados por dataset. 

# Aplicação dos experimentos sobre a base de dados: Churn in Telecom dataset's

### Script: CBB - Resultados experimentais.

Essa é uma das primeiras avaliações realizadas com a utilização do PCA e dos algoritmos SVM e XGBoost.
Esse código, possui duas avaliações exaustivas para cada uma das técnicas sendo a primeira que consiste na análise de componentes para as técnicas, com essa análise é possível identificar os componentes que possuem as melhores assertividades. A segunda avaliação é a de teste/treino em que se aplica o K-fold variando de 0.1 até 1.0 para os conjuntos de componentes.

### Script: PCA_SVM_XGBOOST_FA_PSO_BD1_V6

Aplicação das técnicas de classificação SVM e XGboost junto aos algoritmos bio-inspirado FA e PSO na base de dados Churn in Telecom's data set.

Neste script é aplicado os algoritmos de classificação SVM e XGboost e também o modelo estatístico
com seu ponderamento sendo realizado pelos algoritmos Bio-inspirados.
Também é calculado a média, tempo e desvio-padrão, bem como o tempo de execução e a distância euclidiana 
entre a posição dos melhores agentes para o FA e PSO.

Fez-se a análise dos parâmetros de aplicação do XGBoost e então a técnica foi reaplicada com os paramêtros atualizados.

### Script: PCA_TENSORFLOW_KERAS_V1

Aplicação do TensorFlow 

Neste script o Tensorflow é aplicado e são feitas duas avaliações exaustivas sobre ele. A primeira avaliação é baseada no número de componentes, com isso é possível encontrar a assertividade de classificação de cada componente.
A segunda avaliação, é baseada na divisão de teste/treino da base de dados, com ela obtem-se as assertividades dos componentes com o método k-fold variando de [0.1 a 1.0]

### Scrip: APLICACAO_MLP_BD1_V3

Essa é uma das primeiras avaliações feitas com a utilização do PCA e do algoritmo MLP. Esse código, possui duas avaliações exaustivas para as técnica. A primeira avaliação, consiste na análise de componentes, com esta análise é possível identificar os componentes que, possuem as melhores assertividades. A segunda avaliação é de teste/treino, aplica-se o K-fold variando de [0.1, 1.0], para os conjuntos de componentes. Toda a aplicação é feita sobre a base de dados Churn in Telecom dataset's

### Script: PCA_SVM_TENSORFLOW_MLP_PSO_FA_BD1_V3

Código em que o modelo estatístico foi aplicado.
Utilizou-se a base de dados Churn Telecom Datasets.
As técnicas implementadas foram, SVM, TensorFlow, MLP junto aos algoritmos bio inspirados PSO e FA, também aplicado modelo estatístico

# Aplicação dos experimentos sobre a base de dados: Telco Customer Churn.

### Script: PCA_TENSORFLOW_BD3__V2

Essa é a avaliação que faz uso do PCA e do Tensorflow keras. Esse código, possui duas avaliações exaustivas para a técnica. A primeira avaliação, consiste na análise de componentes para o tensorflow, com esta análise é possível identificar os componentes que, possuem as melhores assertividades. A segunda avaliação, é a de teste/treino, aplica-se o K-fold variando de 0.1 até 1.0, para os conjuntos de componentes. Toda a aplicação é feita sobre a base de dados Telco Customer Churn

### Scrip: PCA_SVM_MLP_BD3_V1

Essa é a avaliação que utiliza o PCA, SVM e MLP. Esse código, possui duas avaliações exaustivas para as técnicas. A primeira avaliação, consiste na análise de componentes, com esta análise é possível identificar os componentes que, possuem as melhores assertividades. A segunda avaliação, é a de teste/treino, aplica-se o K-fold variando de [0.1 1.0], para os conjuntos de componentes. Toda a aplicação é feita sobre a base de dados Telco Customer Churn.

### Script: PCA_SVM_MLP_TENSORFLOW_PSO_FA_BD3_V2

Aplicação das técnicas de classificação SVM, MLP e Tensorflow junto ao algoritmo bio-inspirado PSO e com sua aplicão realizada na base de dados Telco Customer Churn.
Neste script é aplicado os algoritmos de classificação SVM, MLP e Tensorflow e o modelo estatístico com seu ponderamento feito pelos algoritmos Bio-inspirados.

# Aplicação dos experimentos sobre a base de dados de doenças cardio vasculares.

### Scrip: PCA_TENSORFLOW_BD4.V2

Essa avaliação utiliza o PCA e Tensorflow keras. Esse código, possui duas avaliações exaustivas para a técnica. A primeira avaliação, consiste na análise de componentes para o tensorflow, com esta análise é possível identificar os componentes que, possuem as melhores assertividades. A segunda avaliação é a de teste/treino, aplica-se o K-fold variando de 0.1 até 1.0, para os conjuntos de componentes. Toda a aplicação é feita sobre a base de dados Cardio

### Scrip: PCA_SVM_MLP_BD4_V1

Essa avaliação utiliza o PCA, SVM e MLP. Esse código, possui duas avaliações exaustivas para as técnicas. A primeira avaliação, consiste na análise de componentes, com esta análise é possível identificar os componentes que, possuem as melhores assertividades. A segunda avaliação, é a de teste/treino, aplica-se o K-fold variando de [0.1 1.0], para os conjuntos de componentes. Toda a aplicação é feita sobre a base de dados de doenças cardio vasculares.

### Script: PCA_SVM_MLP_TENSORFLOW_PSO_FA_BD4_V2

Aplicação das técnicas de classificação SVM, MLP e Tensorflow junto ao algoritmo bio-inspirado PSO e aplicado na base de dados de doenças cardiovasculares.

Nesse script é aplicado os algoritmos de classificação SVM, MLP e Tensorflow e o modelo estatístico
com seu ponderamento feito pelos algoritmos Bio-inspirados.
