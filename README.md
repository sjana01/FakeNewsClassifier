# FakeNewsClassifier
This is an end to end Machine Learning project for fake news classification. The dataseet used here are from the open source data library Kaggle. Here is a link to the datasets: https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset.

For text data preprocessiong, CountVectorizer and TfidfTransformer methods have been used.
Two machine learning models have been used and compared in the projects. The first model is Multinomial Naive Bayes and the second is Support Vector Machine classification. 

We implement an advanced classification method using Long Short-term Memory (LSTM), a variation of Recurrent Neural Network (RNN). By training the model with only the "title" column, we achieved 99% accuracy on the training set and 91% accuracy on the validation set. For the conversion of words to vectors, we employed the one-hot representation technique.
