<h1>Projeto de Classificação de Pacientes com Doenças Cardíacas</h1>
Este é um projeto de Data Science que utiliza algoritmos de classificação para prever pacientes com doenças cardíacas, a partir de dados coletados de exames e informações de rotina. A análise exploratória e visualização dos dados foram realizadas para entender melhor os dados e extrair conhecimento deles.

<h3>Dados</h3>
Os dados usados são do dataset Cardiovascular Disease dataset, que pode ser encontrado no link https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset/code. Se trata de um dataset simples, com dados necessitando de poucos tratamentos (ou nenhum tratamento), facilitando sua manipulação e análise.

<h3>Pré-processamento dos dados</h3>
Foram feitos alguns pré-processamentos dos dados, em seções diferentes. A ideia foi testar a performance dos modelos em cada uma das configurações de dados após esses pré-processamentos, como normalização, padronização, transformação logarítmica, etc.

<h3>Modelagem</h3>
Vários modelos de classificação foram treinados e comparados usando validação cruzada e métricas de desempenho, como acurácia, precisão, recall, F1-score, etc. Os modelos testados incluem Random Forest, Logistic Regression, K-Nearest Neighbors e XGBoost e GradientBoostingClassifier.

<h3>Resultados</h3>
Tivemos melhor desempenho com o modelo GradientBoostingClassifier, que foi escolhido para passar por otimização de hiperparâmetros, visando o atingimento de valores de métricas mais altos.

<h3>Dependências</h3>
As seguintes bibliotecas Python e ferramentas foram usadas neste projeto:

<ul>
  <li>Pandas</li>
  <li>Python</li>
  <li>Jupyter Notebook</li>
  <li>Matplotlib, Seaborn</li>
  <li>RandomizedSearchCV, StrafifiedKFold</li>
  <li>Modelos de Machine Learning: LogisticRegression, GradientBoostingClassifier, XGBoost, RandomForestClassifier, KNeighborsClassifier</li>
  <li>Git e Github</li>
</ul>
