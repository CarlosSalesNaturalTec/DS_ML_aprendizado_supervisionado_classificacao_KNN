# Data Science / Machine Learning
## Algorítimo de Classificação - KNN
## Utilizando Python e Scikit-Learn
## Aprendizado Supervisionado (supervised learning)
## Dataset: Iris Dataset

### Algorítimo de Classificação - KNN

O algoritmo KNN (k-vizinhos mais próximos) é um método não-paramétrico utilizado para a classificação e regressão. Em ambos os casos, a entrada consiste em calcular a distância entre os k exemplos de treinamento mais próximos.

Na classificação com o k-NN, a saída é uma associação com uma classe. Um objeto é classificado pela votação majoritária da classe dos vizinhos, sendo o objeto atribuído à classe mais comum dentre seus k vizinhos mais próximos.

Neste Notebook foi utilizado o classificador KNN da biblioteca Scikit-Learn

### Uso : PREDIZER a espécie de uma flor Iris a partir da altura e largura de suas pétalas e sépalas.

Iris é um gênero de plantas popularmente conhecidas como lírios. São classificadas em três espécies:
* Setosa
* Versicolor
* Virgínica

Para a classificação das flores Iris utilizaremos as seguintes caractéristicas:
* Altura e Largura da sépala
* Altura e Largura da pétala

Estas são as informações contidas no Dataset e também as que são utilizadas como Input para fazer a predição.

## Referências
[KNN Classification using Scikit-learn](https://www.datacamp.com/community/tutorials/k-nearest-neighbor-classification-scikit-learn)
[UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Iris)