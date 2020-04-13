# 🤖 Machine Learning / Clássico
## Aprendizado Supervisionado / Classificação / KNN

Neste Notebook foram utilizados a linguagem de programação Python e a biblioteca Scikit-Learn.

O algoritmo KNN (k-vizinhos mais próximos) é um método utilizado para a classificação e regressão. Em ambos os casos, a entrada consiste em calcular a distância entre os "k" exemplos de treinamento mais próximos.

Na classificação com o k-NN, a saída é uma associação com uma classe. Um objeto é classificado pela votação majoritária da classe dos vizinhos, sendo o objeto atribuído à classe mais comum dentre seus k vizinhos mais próximos.

### Exemplo prático: Predizer a espécie de uma flor do tipo Iris a partir de suas características físicas.

Iris é um gênero de plantas popularmente conhecidas como lírios. São classificadas em três espécies:
* Setosa
* Versicolor
* Virgínica

Para a classificação das flores Iris utilizaremos as seguintes caractéristicas:
* Altura e Largura da sépala
* Altura e Largura da pétala

Estas são as informações contidas no Dataset e também as que são utilizadas como Input para fazer a predição.

👉 [Veja como fazer](https://github.com/CarlosSalesNaturalTec/DS_ML_aprendizado_supervisionado_classificacao_KNN/blob/master/exemplo_iris_dataset.ipynb)

🤖 [Exemplo de modelo treinado em ambiente de produção](https://github.com/CarlosSalesNaturalTec/DS_ML_aprendizado_supervisionado_classificacao_KNN/blob/master/exemplo_iris_dataset2.ipynb)

### Referências:
[KNN Classification using Scikit-learn](https://www.datacamp.com/community/tutorials/k-nearest-neighbor-classification-scikit-learn)

[Machine Learning with Iris Dataset](https://www.kaggle.com/jchen2186/machine-learning-with-iris-dataset)

[UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Iris)