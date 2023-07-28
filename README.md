# Adapted QuantGAN<sup>1</sup> code<sup>2</sup> for MS Project.
## See [Project repoository](https://github.com/sam-dedge/sim-stock-options) and [Report](https://sam-dedge.github.io/sim-stock-options/ModelingFinancialTime-SeriesUsingDiffusion.pdf) for details about the project.

---

### Data
* SPY & SPX data needs to be downloaded put in the data folder.
* Sample Options file is provided. Download according to expiry and strikes and seperate calls and puts. 

### TCN implementations are provided for both Tensor Flow and Torch

### For the Tensor Flow implementation of a TCN see the notebooks [tf_train.ipynb](./tf_train.ipynb) and [tf_model.ipynb](./tf_model.ipynb)

### For the Torch implementation of a TCN see the notebooks [torch_train.ipynb](./torch_train.ipynb) and [torch_model.ipynb](./torch_model.ipynb)

---

<sup>1</sup> [Wiese et al., Quant GANs: Deep Generation of Financial Time Series, 2019](https://arxiv.org/abs/1907.06673).

<sup>2</sup> Code Adapted from Sullivan, J. (2021), [temporalCN](https://github.com/JamesSullivan/temporalCN): Implentation of Quant GANs: Deep Generation of Financial Time Series, Github Repository.
