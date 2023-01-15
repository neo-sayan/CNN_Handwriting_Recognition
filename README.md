A PROJECT ON HANDWRITING RECOGNITION USING CNN (CONVOLUTIONAL NEURAL NETWORK) :

  We use python, tensorflow and other Machine Learning libraries to develop our model. The Convolutional Neural Network based handwritten character recognition has been introduced here.

  The objective of the model is to build a model to predict or recognize handwritten characters. For the shortage of time period and unavailability of large datasets in different languages, we made a model to recognize english capital alphabets. But the same model can be made to predict characters in different languages (like bengali, urdu, etc).

  The model only predict the handwritten characters with broad strokes or the input image should be zoomed and cropped enough so that the stroke's width appear wide or broad enough.

The implemented model predict a handwritten character with an accuracy of following:

  The validation accuracy: 97% . 
  The training accuracy: 95% . 
  The validation loss: 8.22% . 
  The training loss: 17.2% . 

  At first we were trying serialise our model. But after study we recognize that we can't serilise a tensorflowmodel. So, we save the data in secondary memory using keras.
