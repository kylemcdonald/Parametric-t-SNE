#Parametric t-SNE

Laurens Van Der Maaten's [parametric implementation](https://lvdmaaten.github.io/publications/papers/AISTATS_2009.pdf) of t-SNE.

Laurens' original implementation is for Matlab, here we are running in Octave with oct2py in the notebook `Parametric t-SNE (Original)`. This code can take hours to complete.

In the `Parametric t-SNE (Keras)` notebook there is an implementation of the same technique by reimplementing all functions in Python with numpy and [Keras](https://keras.io/). The code runs significantly faster (on my machine, 20 minutes). There are also some work-in-progress experiments, like using the pairwise probabilty embedding to pre-train the weights of an autoencoder, which appears to converge to a lower reconstruction error than a vanilla autoencoder.

## Setup

On OS X:

```
$ brew install octave
$ pip install -r requirements.txt
$ jupyter notebook
```
