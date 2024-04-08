# Cosine Similarity vs Categorical Crossentropy Loss in Question Answering
This code implements both classification and regression methods for question answering on the SQuAD dataset. Where classification utilizes categorical crossentropy as a loss function, and regression uses cosine similarity.

To run you can choose between regression or classification in the second cell block by commenting out whichever method you chose not to use. Additionally the number of samples used to train the model on can also be chosen. Lastly you can choose the operating system in order to correctly download the dataset.

In the 12th block set the path to where you have the word vectors file installed. Some example paths are given.

In order to change hyperparameters regarding training the constants can be changed.

The model is saved in the end and all predicted answers to the testing data are saved in a csv file with either classification or regression in the title to distinguish between the two methods.

A limitation of these models is that they are not able to predict anything that resembles human language and repeat the same word over and over again.
