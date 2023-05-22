# Análise de sentimentos IMDB dataset

Um modelo de análise de sentimentos é útil a qualquer negócio nos dias atuais, de forma a automatizar a análise dos comentários de usuários nas redes. Saber a proporção dos feedbacks recebidos entre positivos e negativos de forma rápida permite ao negócio um melhor insight do impacto de seus serviços, produtos e ações.  
Aqui, apresentaremos um modelo bastante simples, mas que já demonstra algumas possibilidades da dinamicidade e valor que pode ser gerado.

## Dataset e problemas

O dataset utilizado é composto por 50 mil análises de filmes do Internet Movie DataBase (IMDB), disponível no [Kaggle](https://www.kaggle.com/code/taha07/sentiment-analysis-imdb-movie-reviews).  
Nele, encontramos duas colunas: uma contendo a análise escrita e outra identificando se a análise é positiva ou negativa.

O objetivo é identificar qual modelo de machine learning é mais indicado para prever o sentimento (negativo ou positivo) a partir de uma dada análise de filme. Foram testadas árvores de decisões, regressão logística e Support Vector Machines.  

Ao final, foi feito um breve teste com dados não pertencentes ao dataset, de forma a validar o modelo.
