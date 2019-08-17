# Clustering with nature inspired algorithms

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/2ba4116c451c4893b225d0bebbc306c8)](https://app.codacy.com/app/PyNature/pyriad)
[![Codacy Badge](https://api.codacy.com/project/badge/coverage/2ba4116c451c4893b225d0bebbc306c8)](https://app.codacy.com/app/PyNature/pyriad)
[![Build Status](https://api.travis-ci.org/pynature/pyriad.svg?branch=master)](https://travis-ci.org/pynature/pyriad)
[![Version](https://img.shields.io/pypi/v/pyriad.svg?style=flat)](https://pypi.org/project/pyriad/#history)
[![PyPI downloads](https://img.shields.io/pypi/dm/pyriad.svg?style=flat)](https://pypi.org/project/pyriad/#files)
![License](https://img.shields.io/pypi/l/pyriad.svg?style=flat)

`pyriad` offers clustering with a variety of nature inspired algorithms built with Python on top of the deep learning library [PyTorch](https://pytorch.org/).

You can extend `pyriad` according to your own needs. You can implement custom algorithms by extending simple abstract classes.
Pyriad is highly parallelizable and transferable to GPU.

## Algorithms
As of today, the following algorithms have been implemented:

-   [x] Particle Swarm Optimization (PSO) [[1]](https://www.cs.tufts.edu/comp/150GA/homeworks/hw3/_reading6%201995%20particle%20swarming.pdf)
-   [x] Cuckoo Search (CS) [[2]](https://www.cs.tufts.edu/comp/150GA/homeworks/hw3/_reading7%20Cuckoo%20search.pdf)
-   [x] Grey Wolf Optimization (GWO) [[3]](https://www.researchgate.net/profile/Mohammed_Bakr6/post/how_to_implement_Open_Vechile_Routing_Problem_using_Grey_Wolf_Optimizer/attachment/59d621c66cda7b8083a1b3fa/AS%3A273784001499151%401442286600462/download/GWO_finalVersion.pdf)
-   [x] Flower Pollination Algorithm (FP) [[4]](https://arxiv.org/abs/1312.5673)

## Installation

1.  Install PyTorch. You can find it here: [PyTorch](https://pytorch.org/)
2.  `pip install pyriad`

## Examples

You can find examples in `examples/` directory

You can also run examples: `python examples/pso_iris.py`

You might want to `export PYTHONPATH=/path/to/this/directory`

## Contribute

1.  Implement new algorithms
2.  Improve code design
3.  Improve comments and readme
4.  Tests