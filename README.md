# keras_beginners
Collected resources for Keras beginners! Have fun!

[Hello World for Keras](https://github.com/fastforwardlabs/keras-hello-world/blob/master/kerashelloworld.ipynb)

[First Deep Learning Project with Keras Step-By-Step](https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/)

[Keras with LSTM project - jezz generation](https://github.com/momo4826/keras_beginners/blob/main/Improvise_a_Jazz_Solo_with_an_LSTM_Network_v3a.ipynb)

[Keras with MNIST dataset](https://github.com/wxs/keras-mnist-tutorial/blob/master/MNIST%20in%20Keras.ipynb)

## Notes
Keras requires that labels be one-hot-encoded.
```python
def one_hot_1(x):
    uniques, ids = np.unique(x, return_inverse=True)
    return np_utils.to_categorical(ids, len(uniques))
```
