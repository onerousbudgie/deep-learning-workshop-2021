# Deep Learning Workshop (November 2021)

Notebooks I worked through and ran during a one-day deep learning workshop on **30 November 2021**, in Google Colab with Python, NumPy, Matplotlib and TensorFlow/Keras.

**About the material:** these are workshop tutorial notebooks. The tutorial text and starter code were written by the workshop organisers, not by me; all credit for the teaching material goes to them. What this repository records is my completion of the workshop: every notebook here was run by me, and the saved outputs and results are from my runs.

## Notebooks

| Notebook | What it covers | My result |
|---|---|---|
| `Workshop_Test2020.ipynb` | Warm-up: importing ML libraries, generating random data, stacking columns into a matrix | 100,000 x 2 input matrix built |
| `Deep learning/perceptron.ipynb` | A single perceptron built from scratch in NumPy | Trained and plotted |
| `Deep learning/mlp_bp_ann.ipynb` | Multi-layer neural network with backpropagation, from scratch in NumPy | Trained and plotted |
| `Deep learning/tf_keras_mnist_sigmoid_val.ipynb` | MNIST digit classification in Keras with sigmoid units and a validation split | ~96% accuracy |
| `Deep learning/tf_keras_mnist_deep.ipynb` | Deep network on MNIST with ReLU activations, RMSprop and early stopping | ~95-98% accuracy |
| `Deep learning/tf_keras_mnist_cnn_val.ipynb` | Convolutional neural network on MNIST with max-pooling and dropout | ~93% accuracy |
| `Deep learning/tf_keras_rnn.ipynb` | LSTM recurrent network predicting the next letter in a sequence | ~88% accuracy |

## Running them

Open any notebook in Google Colab or Jupyter. The Keras notebooks need TensorFlow 2.x; MNIST downloads automatically.

Personal account metadata that Colab stores in notebooks was removed before publishing; code, outputs and results are unchanged.
