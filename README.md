# Machine Translation
Applying Deep Natural Language Processing using auto encoder decoder for language translation

This project is about building a deep neural network that functions as part of an end-to-end machine translation pipeline. It creates and trains models which accept a sequence of integers as input and returns a probability distribution over possible translations. 

## Vocabulary
The complexity of the problem is determined by the complexity of the vocabulary.  A more complex vocabulary is a more complex problem. For example, Alice's Adventures in Wonderland contains 2,766 unique words of a total of 15,500 words.

## setting up the Preprocess Pipeline 
The Preprocess pipeline includes the following steps in a sequence.
1. This code uses Kera's Tokenizer function to extract tokens from sentences.
2. Padding using Kera's pad_sequences function to make all the sequences the same length.

## The Model Architecture
Following models following sevaral neural architectures have been experimented with
1. A simple RNN
2. RNN with Embedding
3. A Bidirectional RNN
4. An Encoder-Decoder RNN


