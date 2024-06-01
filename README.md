# 🌟 Positional Encoding

In this project, you will learn how to implement the positional encoding of words in the transformer.

## 📚 Positional Encoding

In sequence-to-sequence tasks, the relative order of your data is extremely important to its meaning. When you were training sequential neural networks such as RNNs, you fed your inputs into the network in order. Information about the order of your data was automatically fed into your model. However, when you train a Transformer network using multi-head attention, you feed your data into the model all at once. While this dramatically reduces training time, there is no information about the order of your data.

* 🧮 $d$ is the dimension of the word embedding and positional encoding.
* 🏷️ $pos$ is the position of the word.
* 🔢 $k$ refers to each of the different dimensions in the positional encodings, with $i$ equal to $k$ $//$ $2$.
