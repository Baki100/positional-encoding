# 🌟 Positional Encoding

In this project, we will learn how to implement the positional encoding of words in the transformer.

## 📚 Positional Encoding

In sequence-to-sequence tasks, the relative order of our data is extremely important to its meaning. When training sequential neural networks such as RNNs, we fed inputs into the network in order. Information about the order of data was automatically fed into the model. However, when training a Transformer network using multi-head attention, we feed data into the model all at once. While this dramatically reduces training time, there is no information about the order of data.

* 🧮 $d$ is the dimension of the word embedding and positional encoding.
* 🏷️ $pos$ is the position of the word.
* 🔢 $k$ refers to each of the different dimensions in the positional encodings, with $i$ equal to $k$ $//$ $2$.
