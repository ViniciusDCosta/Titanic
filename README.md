# Titanic
Repositório criado para a **[competição do Kaggle sobre o desastre do Titanic](https://www.kaggle.com/competitions/titanic)**

O histórico dos resultados é mostrado abaixo e pode ser obtido no Kaggle:
<img src="https://github.com/ViniciusDCosta/Titanic/blob/main/img/acuracia.png" />

## ETAPA 1: Primeiro Modelo

- Nessa etapa **fizemos o básico para coneguir verificar qual seria o resultado** sem fazer nenhum tratamento de engenharia de dados
  - Foi visualizado um resumo da base utilizando o [ydata-profiling](https://github.com/ydataai/ydata-profiling) **biblioteca capaz de gerar com poucas linhas toda a descrisão do nosso dataset**
  - Taambém eliminamos colunas com **elevada cardinalidade**, tratamos **valores vazios** utilizando a média e a moda das variáveis e eliminamos todas as **colunas de texto**
  - Criamos os modelos utilizando 3 algoritimos: **Árvore de Classificação, KNN e Regressão Logística** e avaliamos esses modelos utilizando a acurácia e a matriz de confusão
- ***O score retornado pelo Kaggle foi: 0,66746*** 
