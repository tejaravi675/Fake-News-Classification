# Fake-News-Classification

Languages & Frameworks used: Python, langdetect, contractions, nltk, tensorflow, keras

The main aim of the project is to detect fake news using the title attribute. Several preprocessing techniques such as expanding contractions, language detection,
tokenisation, lemmatization and many more were used before sending the data to train the model.

Recurrent Neural Networks (RNN) algorithm is used. The training accuracy of the model is around 98% while the testing accuracy is 82%. Clearly, the model overfits on the
training data. One reason can be the data in itself, majority of the text in data is less than 30 words. In future, regularisation techniques such as early stopping,
dropout can be used.
