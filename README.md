# Regressão Logística

Apesar do nome, regressão logística é um algoritmo de classificação. A ideia aqui é prever uma saída binária. 
sim ou não, 0 ou 1.
Usamos a função sigmoide pra transformar a saída em uma probabilidade entre 0 e 1.

Mais um exercício de aprendizado, focado em entender quando usar regressão logística no lugar da linear e como interpretar os resultados.

# No notebook


Análise e pré-processamento dos dados
Treinamento com LogisticRegression
Avaliação com acurácia, precisão, recall e F1-score via classification_report
Visualização da curva sigmoide e da fronteira de decisão
Análise dos coeficientes para entender o peso de cada feature


A regressão logística usa a mesma base matemática da linear, mas aplica a função sigmoide σ(z) = 1 / (1 + e^-z) na saída, mapeando qualquer valor real para o intervalo (0, 1). Daí o resultado vira probabilidade, e um threshold (geralmente 0.5) define a classe final.
