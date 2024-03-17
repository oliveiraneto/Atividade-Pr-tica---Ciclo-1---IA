# Atividade-Pr-tica---Ciclo-1---IA

Classificação de Vinhos com LinearSVC e Comparação com DummyClassifier

Em um contexto enológico, a classificação correta de vinhos entre brancos e vermelhos é uma tarefa importante. Neste exercício, seu objetivo é implementar um algoritmo de aprendizado de máquina utilizando Linear Support Vector Classifier (LinearSVC) para classificar vinhos com base em características específicas. O conjunto de dados fornecido contém informações sobre diversas propriedades dos vinhos, como acidez, teor alcoólico, entre outras.

Siga os passos abaixo:

Leitura e Exploração de Dados:

Carregue o conjunto de dados fornecido, explorando suas características e distribuição.
Pré-processamento de Dados:

Realize o pré-processamento dos dados, lidando com valores ausentes, convertendo variáveis categóricas se necessário, e normalizando as características.
Divisão do Conjunto de Treinamento e Teste:

Divida o conjunto de dados em conjuntos de treinamento e teste na proporção de 80/20.
Implementação do LinearSVC:

Utilize a classe LinearSVC do Scikit-Learn para criar e treinar um modelo de classificação.
Avaliação do Modelo:

Realize previsões no conjunto de teste e avalie o desempenho do modelo utilizando a métrica de acurácia.
Comparação com DummyClassifier:

Implemente um DummyClassifier (por exemplo, estratégia 'most_frequent' ou 'stratified') e avalie sua acurácia no mesmo conjunto de teste.
Análise e Discussão:

Compare as acurácias do LinearSVC e do DummyClassifier, discutindo os resultados obtidos. Explique a importância da escolha do modelo adequado para a tarefa em questão.
Otimização (Opcional):

Experimente ajustar hiperparâmetros do LinearSVC e compare o desempenho otimizado com a configuração padrão.
