# DeepNeural-PyNet
This repository is based on an assignment made for a Deep Learning (National University of Ireland, Galway) module.

Parts of this project are based on my previous work
[**DeepNeural-JavNet**](https://github.com/jaroslawjanas/DeepNeural-JavNet).

## Setup

The project was written using PyCharm but should work just as any other notebook provided the 
dependencies are available.

### Environment

You can install the dependencies using anaconda

`conda env create --file .\environment.yml`

or manually using the below list of packages.

  - python = 3.9
  - ipython = 8.4.0
  - cupy = 11.0.0
  - numpy = 1.23.1
  - pandas = 1.4.3
  - matplotlib = 3.5.3
  - jupyterlab = 3.4.5

### Data

The **CIFAR-10 dataset** was used for training and evaluation, it can be downloaded 
from this [link](https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz).
Simply unpack the contents of the downloaded file to the project folder.

By default, the **horse** and **truck** classes are used by this project.

Alternatively you can select a different dataset such as the **CIFAR-100 dataset**
on the CIFAR [homepage](https://www.cs.toronto.edu/~kriz/cifar.html).


The remaining two datasets **blobs300** and **circles600.cs** are already included in the repository 
since their size is relatively small.