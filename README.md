# Projeto de Data Science - Previsão de Vendas

## Descrição

Este projeto tem como objetivo analisar os padrões de vendas de uma empresa de e-commerce e prever vendas futuras com base em dados históricos. Para isso, utilizamos Python e bibliotecas como Pandas, Seaborn e Scikit-Learn. O projeto abrange desde a coleta e análise exploratória dos dados até a modelagem preditiva com machine learning.

### Requisitos

- Python 3.x
- Pandas
- Seaborn
- Matplotlib
- NumPy
- Scikit-Learn

Para instalar todas as dependências, execute:
```bash
!pip install pandas seaborn matplotlib numpy scikit-learn
```

Etapas do Projeto

1. Coleta e Preparação dos Dados

- Utilização de um dataset de vendas de e-commerce.
- Leitura e manipulação dos dados com Pandas.
- Limpeza e organização dos dados.
- Dataset utilizado: https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset/data

2. Análise Exploratória de Dados (EDA)

- Estatísticas descritivas como média, desvio padrão, mínimo e máximo.
- Visualizações para identificar tendências de vendas e distribuições de variáveis.

3. Aplicação de Estatística Básica

Testes de hipótese para verificar diferenças significativas entre categorias de produtos.

4. Modelagem de Machine Learning

Desenvolvimento de modelos de regressão para previsão de vendas futuras.
Utilização de regressão linear e árvores de decisão.
Divisão do dataset em treino e teste.
Avaliação dos modelos com MSE, RMSE e R².

### Resultados

Os modelos treinados foram comparados, e a árvore de decisão apresentou melhor desempenho, mas com possível overfitting. As métricas obtidas são:
- Regressão Linear: MSE = 6851.37, RMSE = 82.77, R² = 0.93
- Árvore de Decisão: MSE = 1303.85, RMSE = 36.11, R² = 0.99

Conclusão

O projeto permitiu extrair insights valiosos sobre as vendas e desenvolver modelos preditivos eficazes. Melhorias podem ser feitas na redução do overfitting e exploração de outros algoritmos.

Autor
Iago Teles
