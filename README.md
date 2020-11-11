# Machine-Learning-Based-News-Validation
The use of machine learning has become widespread in recent years, especially due to the impact of media content on the general population. In particular, the validation of truth in the context of news has become a critical necessity, due to its ready availability from verified and unverified sources, and its ability to influence people majorly. The present work outlines a LSTM (long short-term memory) based approach to news validation. The results obtained by the model are presented in terms of the training data set and contrasted with the results obtained from the test data set. Appreciable accuracy is achieved through the model, seen through the corresponding loss curves and confusion matrix.

PROPOSED MODEL

The stacked LSTM network has a visible layer of input, three hidden layers and an output layer with Rectified linear circuit (ReLu) activation unit that predicts single value or binary classification. An LSTM layer requires three-dimensional input and by default delivers a two-dimensional output. In this classifier, the primary hidden layer is an embedding layer with a input sequence length of 300. The input dimension characterizes the size of the vocabulary in the text information. Output dimension was set as 100. It defines the size of the output vectors from this layer for each word. Output of the embedding layer was a 2-dimensional vector with one embedding for each word in the input sequence of word. The default activation function sigmoid is utilized for the LSTM blocks. The classifier was trained for 10 epochs with a batch size of 256 with adam optimizer.

CONCLUSION

As an extension to the present model, the authors intend to investigate the application of Kohonen maps for reducing high dimensionality often observed in news datasets. Another alternative is to investigate the applicability of Convolutional Neural Networks (CNNs) for news validation.
