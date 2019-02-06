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

## Encoder-decoder architecture
The Encoder-Decoder architecture with recurrent neural networks has become an effective approach for neural machine translation and Seq2Seq prediction in general. The strength of the approach is its ability to learn the mapping from the input text to its associated output text. 
The architecture consists of two RNNs. The first RNN is called `encoder`
Its architecture typically consists of two recurrent neural networks (RNNs), one to consume the
input text sequence and one to generate translated output text. NMT is often accompanied by an attention
mechanism [2] which helps it cope effectively with long input sequences.

The key benefits of the approach are the ability to train a single end-to-end model directly on source and target sentences and the ability to handle variable length input and output sequences of text.
## Install
- Python 3.6
- NumPy
- TensorFlow 1.4
- Keras 2.0


