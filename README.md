# Snowball and Truncated Krylov Graph Convolutional Networks in PyTorch

## Performance Ranking

### Truncated Krylov
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/break-the-ceiling-stronger-multi-scale-deep/node-classification-on-cora-with-public-split)](https://paperswithcode.com/sota/node-classification-on-cora-with-public-split?p=break-the-ceiling-stronger-multi-scale-deep)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/break-the-ceiling-stronger-multi-scale-deep/node-classification-on-citeseer-with-public)](https://paperswithcode.com/sota/node-classification-on-citeseer-with-public?p=break-the-ceiling-stronger-multi-scale-deep)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/break-the-ceiling-stronger-multi-scale-deep/node-classification-on-pubmed-with-public)](https://paperswithcode.com/sota/node-classification-on-pubmed-with-public?p=break-the-ceiling-stronger-multi-scale-deep)

### Snowball (linear)

### Snowball (linear + tanh)

### Snowball (tanh)

====

PyTorch implementation of Snowball and Truncated Krylov Graph Convolutional Network (GCN) architectures for semi-supervised classification [1].

This repository contains the Cora, CiteSeer and Pubmed dataset.

## Initialization

```python initialize_dataset.py```

## Requirements

  * PyTorch 1.0.0+
  * Python 3.6+
  * Best with CUDA/10.0 and NVIDIA apex (we have used the container docker://nvcr.io/nvidia/pytorch:19.05-py3 with singularity)

## Usage

```python train.py```

## References

[1] [Luan, et al., Break the Ceiling: Stronger Multi-scale Deep Graph Convolutional Networks, 2019](https://arxiv.org/abs/1906.02174)

## Cite

Please kindly cite our work if necessary:

```
@article{luan2019break,
title={Break the Ceiling: Stronger Multi-scale Deep Graph Convolutional Networks},
author={Luan, Sitao and Zhao, Mingde and Chang, Xiao-Wen and Precup, Doina},
journal={arXiv},
volume={1906.02174},
year={2019},
url={https://arxiv.org/abs/1906.02174},
}
```
