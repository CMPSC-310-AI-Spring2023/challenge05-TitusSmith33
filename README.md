[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/S8i0Ljb1)
# Challenge Problem 5

## Deadline: March 24, 2023 by midnight

Note: While high-level discussion is allowed and encouraged for the challenge problems, these problems should be completed and submitted individually.

### Description

Run through the guide at [RNN guide](https://www.tensorflow.org/guide/keras/rnn). Then, answer the following questions.

### Part 1: Keras

1.   Give 1-2 sentence description of keras.

Keras is a library that provides Python interface needed for neural networks. It is a high level, deep learning API that makes implementing neural networks easy and efficient.

2.   Give a short explanation of the following:

- `Embedding`
-  `Dropout` 

Embedding is what makes us be able to process and learn large inputs of text with few vectors. Embedding takes in large dimensions for inputs and shrinks them for the output.

Dropout is the process of excluding certain nodes during the learning process at random. This ensures the program has no overfitting because it does not over rely on a specific unit.

### Part 2: Unidirectional vs Bidirectional

1.   Give 2-3 sentence explanation of how bidirectional RNNs are different from unidirectional RNNs.

Firstly, bidirectional RNNs are an RNN that looks through the input in two directions, forward and backwards. Whereas unidirectional RNNs only process the data in one direction, with a single hidden layer, and can only past context. Bidirectional RNNs are better for things that you need future context for, such as speech recognition and natural language processing. Unidirectional RNNs are typically faster because they require less computation.

### Part 3: Add code

1.   Include the code from "Recurrent Neural Networks (RNN) with Keras" guide that you ran (must show output) as a Google Colab notebook in your challenge 5 repository.

Added Colab
