# Out-of-Distribution Detection for Generalized Zero-Shot Action Recognition

## Overview
This repository is the PyTorch implementation for the paper [Out-of-Distribution Detection for Generalized Zero-Shot Action Recognition](https://arxiv.org/abs/1904.08703), to be published at [CVPR 2019](http://cvpr2019.thecvf.com/). This repo is based on the codebase of [f-CLSWGAN](https://www.mpi-inf.mpg.de/departments/computer-vision-and-multimodal-computing/research/zero-shot-learning/feature-generating-networks-for-zero-shot-learning/), which was originally proposed for zero-shot object classification.

## Dependencies
1. PyTorch 0.3.1
2. Python 3.5

## Features
The I3D features (concatenated RGB and Flow) for HMDB51 and UCF101 are provided [here](https://drive.google.com/open?id=15Fge1p6a4ZZ7ZQCXYzPSFSQXN8XvZrAe). Place the unzipped sub-folders under data_action folder before running the experiments.

## Running
Shell scripts for running the baseline ZSL/GZSL experiments on HMDB51 and UCF101 datasets are provided.

## To Do
Integrating the entropy-based out-of-distribution code.

## Citation
Please cite the following work if you use this package.
```javascript
@@article{mandal2019out,
  title={Out-of-Distribution Detection for Generalized Zero-Shot Action Recognition},
  author={Mandal, Devraj and Narayan, Sanath and Dwivedi, Saikumar and Gupta, Vikram and Ahmed, Shuaib and Khan, Fahad Shahbaz and Shao, Ling},
  journal={arXiv preprint arXiv:1904.08703},
  year={2019}
}
```

## Contact 
Please contact the first author of the paper - Devraj Mandal (devrajm@iisc.ac.in) for any further queries.


