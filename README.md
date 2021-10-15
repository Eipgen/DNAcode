## Description

This repository is used to support the following work:

### Molecular convolutional neural networks with DNA regulatory circuits
Xiewei Xiong, Tong Zhu, Yun Zhu, Mengyao Cao, Jin Xiao, Li Li, Fei Wang, Chunhai Fan and Hao Pei*

It contains all the codes and data used in this work. 
The raw data can be found at https://github.com/tongzhugroup/dna_comput_rawdata.

## System requirements

To run the codes in this repository, you need to make sure that Anaconda (miniconda), Tensorflow, and Keras are installed. The specific software versions can be found in the environment.yaml file.

You can also build the environment with `conda`

```sh
conda env create -f environment.yaml -n dnacode

```

These codes do not rely on any non-standard hardware.


## Installation
All the code does not need to be pre-installed and can be run directly in the jupyter-notebook.


## Demo & Instructions for use.

Because the program runs quickly, we don't need any demos. 
After the environment configuration is complete, you have to activate it. 
```sh
conda activate dnacode

```

All expected results are listed in the jupyter-notebook and can be reproduced directly. The training process can be completed within 1 hour on a single Linux computer. 








