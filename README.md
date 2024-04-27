
![bras_83x140_reduzido](https://github.com/gabrielmprata/MVP_Sprint01_Puc_Rio/assets/119508139/4880e33f-47b7-4b75-8a84-bb2d57a8c5f2) 
**Pontifícia Universidade Católica do Rio de Janeiro**

#  📚 Trabalho de elaboração de MVP 📖
#### Curso de Pós Graduação *Ciência de Dados e Analytics*
#### Aluno: Gabriel Prata
#### Disciplina: Machine Learning e Deep Learning - Advanced Analytics
#### MVP Sprint02 Linguagem Natural
>
[![Colab Notebook](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/gabrielmprata/MVP_SP02_Linguagem_Natural/blob/main/MVP_SP02_Linguagem_Natural.ipynb)
>

# :radio_button: 1. Objetivo 
O objetivo desse estudo, é avaliar se a crítica foi positiva ou negativa, utilizando a  classificação de textos voltada à análise de sentimentos.
<br><br>
# :floppy_disk: 2. Coleta de Dados
>
Os dados foram coletados do sítio da UC Irvine Machine Learning Repository.
<img align="left" width="175" height="59" src="https://github.com/gabrielmprata/MVP_SP02_Linguagem_Natural/assets/119508139/3a6cfbd1-71be-444a-bb4d-dcbb2fae577c">
>
https://archive.ics.uci.edu/dataset/331/sentiment+labelled+sentences
>
<br><br>

# :dart: 3. Evaluation Metric
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

<br><br>
# :hammer: 4. Ferramentas utilizadas
<img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="40" height="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original-wordmark.svg" width="40" height="40"/>   <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/plotly/plotly-original-wordmark.svg" width="40" height="40"/>  <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/scikitlearn/scikitlearn-original.svg" width="40" height="40"/> <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original-wordmark.svg" width="40" height="40"/> <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original-wordmark.svg" width="40" height="40"/>
<br><br>
>
## Tool, Libraries & Frameworks used
- Numpy
- Pandas
- nltk
- Plotly Express
- wordcloud
