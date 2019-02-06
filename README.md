[![GPL-3.0 Licensed](https://img.shields.io/badge/License-GPL3.0-blue.svg?style=flat)](https://opensource.org/licenses/GPL-3.0) [![TensorFlow Version](https://img.shields.io/badge/Tensorflow-1.4+-blue.svg)](https://www.tensorflow.org/) [![Keras Version](https://img.shields.io/badge/Keras-2.0+-blue.svg)](https://keras.io/) [![Python Version](https://img.shields.io/badge/Python-3.6-blue.svg)](https://www.python.org/) 

# Introduction
In this notebook, we will build a neural machine translation (NMT) that functions as an end-to-end learning approach for automated machine translation pipeline. The completed pipeline will accept English text as input and return the French translation.

# Models
We will examine the performance of four neural network architectures:

Model 1: Simple RNN

Model 2: RNN with Embedding

Model 3: Bidirectional RNN

Model 4: Encoder-Decoder RNN

Model 5: Bidirectional Encoder-Decoder RNN with Embedding inputs

### Encoder-Decoder architecture
The Encoder-Decoder architecture with RNN has become an effective approach for NMT and Seq2Seq prediction in general. The strength of the approach is its ability to learn the mapping from the input text to its associated output text. 
The architecture consists of two RNNs. The first RNN is called encoder which maps the input text representation sequence to a fixed-sized internal representation and the second RNN, the decoder, then maps the vector to the target text sequence. [Seq2Seq Learning with Neural Networks](https://arxiv.org/pdf/1409.3215.pdf)

Final model configuration:
- A 300-dimensional word embedding layer was used to represent the input words.
- Softmax was used on the output layer.
- The encoder and decoder models had a single layer with 300 units in each layer.
- The model was fit for 10 epochs where some learning rate decay was performed.
- A batch-size of 1024 sequences was used during training.

## Install
- Python 3.6
- NumPy
- TensorFlow 1.4
- Keras 2.0


