# voice-command-classification-Keras
Command classification using Keras and CNNs. Model reaches 84 percent accuracy on validation set after 34 epochs.

### Dataset:
TensorFlow has released the Speech Commands Datasets. It includes 65,000 one-second long utterances of 30 short words, by thousands of different people. We’ll build a speech recognition system that understands simple spoken commands.

You can download the dataset from :https://www.kaggle.com/c/tensorflow-speech-recognition-challenge

### Model:

The model consists of 4 Conv blocks (Conv1d layers followed by maxpooling layer and then dropout) and 2 fully connected layers. Dropout rate is 0.3 and Adam is used as optimizer.

![](model.png)
