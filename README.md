[pypi-image]: https://badge.fury.io/py/torch-sparse.svg
[pypi-url]: https://pypi.python.org/pypi/torch-sparse
[build-image]: https://travis-ci.org/rusty1s/pytorch_sparse.svg?branch=master
[build-url]: https://travis-ci.org/rusty1s/pytorch_sparse
[coverage-image]: https://codecov.io/gh/rusty1s/pytorch_sparse/branch/master/graph/badge.svg
[coverage-url]: https://codecov.io/github/rusty1s/pytorch_sparse?branch=master

# PyTorch Sparse

[![PyPI Version][pypi-image]][pypi-url]
[![Build Status][build-image]][build-url]
[![Code Coverage][coverage-image]][coverage-url]

--------------------------------------------------------------------------------

This package consists of a small extension library of optimized sparse matrix operations for the use in [PyTorch](http://pytorch.org/), which are missing and or lack autograd support in the main package.
This package currently consists of the following methods:

* **[Autograd Sparse Tensor Creation](#Autograd Sparse Tensor Creation)**
* **[Autograd Sparse Tensor Value Extraction](#Autograd Sparse Tensor Value Extraction)**
* **[Sparse Sparse Matrix Multiplication](#Sparse Sparse Matrix Multiplication)**

All included operations work on varying data types and are implemented both for CPU and GPU.

## Installation

Ensure that at least PyTorch 0.4.0 is installed and verify that `cuda/bin` and `cuda/install` are in your `$PATH` and `$CPATH` respectively, *e.g.*:

```
$ python -c "import torch; print(torch.__version__)"
>>> 0.4.0

$ echo $PATH
>>> /usr/local/cuda/bin:...

$ echo $CPATH
>>> /usr/local/cuda/install:...
```

Then run:

```
pip install torch-sparse
```

If you are running into any installation problems, please follow these [instructions](https://rusty1s.github.io/pytorch_geometric/build/html/notes/installation.html) first before creating an [issue](https://github.com/rusty1s/pytorch_sparse/issues).

## Autograd Sparse Tensor Creation

## Autograd Sparse Tensor Value Extraction

## Sparse Sparse Matrix Multiplication

## Running tests

```
python setup.py test
```
