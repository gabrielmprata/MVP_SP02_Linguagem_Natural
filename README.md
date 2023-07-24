# Trabalho de elaboração de MVP (Minimum Viable Product)
O objetivo desse estudo, é avaliar se a crítica foi positiva ou negativa, utilizando a  classificação de textos voltada à análise de sentimentos.

## Coleta de dados:
[https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-acidentes](https://archive.ics.uci.edu/dataset/331/sentiment+labelled+sentences)
>

## Evaluation Metric
  Accuracy Score
>
## Comparative Analysis of Models
| Model                          |Embedding         | accuracy score|
|--------------------------------|------------------|---------------|
| Logistic Regression	           | Bag of words     |  76%          |
| Logistic Regression	           | Word2Vec         |  80%          |
| Logistic Regression	           | BERT             |  81%          |
| SVM               	           | Bag of words     |  76%          |
| SVM               	           | Word2Vec         |  82%          |
| SVM               	           | BERT             |  81%          |
| Multilayer Perceptron          | Bag of words     |  73%          |
| Multilayer Perceptron          | Word2Vec         |  81%          |
| Multilayer Perceptron          | BERT             |  80%          |
| Random Forest                  | Bag of words     |  72%          |
| Random Forest                  | Word2Vec         |  79%          |
| Random Forest                  | BERT             |  79%          |
| KNN                            | Bag of words     |  65%          |
| KNN                            | Word2Vec         |  76%          |
| KNN                            | BERT             |  75%          |

>

>
## Tool, Libraries & Frameworks used
- Numpy
- Pandas
- nltk
- Plotly Express
- wordcloud
