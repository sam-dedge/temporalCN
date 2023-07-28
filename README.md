# Adapted QuantGAN code for MS Project. 
## See Tab-DDPM repoository and Report for details about the project.

### [Implentation of Quant GANs: Deep Generation of Financial Time Series, 2019](https://github.com/JamesSullivan/temporalCN)


[Wiese et al., Quant GANs: Deep Generation of Financial Time Series, 2019](https://arxiv.org/abs/1907.06673)


This repository includes code from:
* [ICascha/QuantGANs-replication](https://github.com/ICascha/QuantGANs-replication)
* [TCN](https://github.com/locuslab/TCN)
* Greg Ver Steeg, 2015

### Data
* SPY & SPX data needs to be downloaded put in the data folder.
* Sample Options file is provided. Download according to expiry and strikes and seperate calls and puts. 

### TCN implementations are provided for both Tensor Flow and Torch

### For the Tensor Flow implementation of a TCN see the notebooks [tf_train.ipynb](./tf_train.ipynb) and [tf_model.ipynb](./tf_model.ipynb)

### For the Torch implementation of a TCN see the notebooks [torch_train.ipynb](./torch_train.ipynb) and [torch_model.ipynb](./torch_model.ipynb)
