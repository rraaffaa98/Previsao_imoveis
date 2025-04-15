:

🏡 Predição de Preços de Imóveis com Machine Learning
Este projeto utiliza técnicas de aprendizado de máquina para prever o preço de imóveis com base em um conjunto de dados reais do mercado imobiliário, utilizando como base o dataset do Kaggle - House Sales in King County, USA.

📌 Objetivo
Desenvolver um modelo preditivo capaz de estimar o valor de uma casa com base em atributos como localização, área construída, número de quartos, avaliação da construção, entre outros — com foco em aplicações no setor imobiliário para análise e viabilidade de investimentos.

🧠 Técnicas Utilizadas
Pré-processamento e limpeza de dados

Análise exploratória com visualizações (histogramas, heatmap de correlação, boxplots)

Feature engineering e seleção de variáveis

Treinamento de modelo com Random Forest Regressor

Avaliação com métricas: R² (coeficiente de determinação), MAE (erro absoluto médio) e RMSE (raiz do erro quadrático médio)

Interpretação das features mais importantes para o modelo

🔍 Principais Insights
As variáveis com maior influência no preço dos imóveis foram:

grade → Classificação da construção (0,38)

lat → Latitude (localização) (0,23)

sqft_living → Área útil interna (0,18)

A correlação entre variáveis ajudou a identificar quais dados seriam mais úteis e evitar multicolinearidade.

O modelo teve desempenho satisfatório com resultados coerentes para a proposta.

📷 Imagens geradas
Mapa de calor das correlações

Gráficos de dispersão e histogramas por variável

Visualização dos erros do modelo

Gráfico de importância das variáveis

🛠️ Tecnologias
Python

Pandas

Matplotlib & Seaborn

Scikit-learn

Google Colab

Kaggle API

