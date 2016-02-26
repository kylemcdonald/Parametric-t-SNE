#Parametric t-SNE

Laurens Van Der Maaten's [parametric implementation](https://lvdmaaten.github.io/publications/papers/AISTATS_2009.pdf) of t-SNE. The original implementation is for Matlab, here we are running in Octave with oct2py.

I'm currently working on porting the technique to a more recent toolkit.

## Setup

On OS X:

```
$ brew install octave
$ pip install -r requirements.txt
$ jupyter notebook
```