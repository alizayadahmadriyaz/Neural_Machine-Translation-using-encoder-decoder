# Neural_Machine-Translation-using-encoder-decoder
This model is basically used for Conversion of One Language To other Language using Nlp Technique

With attention

![Screenshot 2024-03-05 174004](https://github.com/alizayadahmadriyaz/Neural_Machine-Translation-using-encoder-decoder/assets/160425975/d83bc9cf-2660-4c49-8556-df16d7e7137a)



Without Attention

![image](https://github.com/alizayadahmadriyaz/Neural_Machine-Translation-using-encoder-decoder/assets/160425975/ff38f52c-d80f-4a2b-9145-edfb5f67aab9)




# Neural Machine Translation using Encoder-Decoder

## Overview
This repository contains code for a Neural Machine Translation (NMT) system implemented using a vanilla encoder-decoder architecture. The system is capable of translating text from one language to another using neural networks.

## Architecture
The NMT system utilizes a vanilla encoder-decoder architecture. The encoder takes the input sentence in the source language and encodes it into a fixed-length vector representation. The decoder then takes this representation and generates the translated sentence in the target language. Both the encoder and decoder are implemented using recurrent neural networks (RNNs), specifically Long Short-Term Memory (LSTM) units.

## Bahdanau Attention
Bahdanau attention allows the decoder to focus on different parts of the input sequence at each step of generating the output sequence. This attention mechanism calculates attention weights dynamically, based on the alignment between the current decoder hidden state and the encoder hidden states. By incorporating attention, the model can effectively handle long input sequences and improve translation quality.

## Dataset
The system is trained on parallel corpora containing pairs of sentences in the source language and their corresponding translations in the target language. The dataset is preprocessed and tokenized before being used for training.

## Training
Training of the NMT model is performed using stochastic gradient descent (SGD) with backpropagation. The model is trained to minimize the cross-entropy loss between the predicted translations and the ground truth translations.

## Usage
0. Download or prepare your own parallel corpora for training.
1. Preprocess and tokenize the dataset.
5. Train the NMT model using the preprocessed dataset.
3. Evaluate the trained model using appropriate evaluation metrics.
4. Translate new sentences by providing input in the source language to the trained model.
   
## Dependencies
- Python 3.x
- TensorFlow
- NumPy
- NLTK (for text preprocessing)
  
## Credits
This NMT system is implemented based on the principles described in various research papers and online tutorials. Credits to the authors of the papers and developers of the tutorials for their contributions.

## Acknowledgments
Special thanks to the open-source community for providing valuable resources and support for NMT research and development.

