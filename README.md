# MHP
This repository contains a light-weight python implementation for generating events and estimating the parameters using a **M**ultivariate **H**awkes **P**rocess.
It contains the following code components:

- ```HP/simulators```: To generate a cascade with given parameters using the modified Ogata's thinning algorithm.
- ```HP/estimators```: To estimate the parameters of multivariate hawkes process using maximum likelihood.

The simulation code is copied and modified slightly from [Steve Morse's excellent implementation](https://github.com/stmorse/hawkes). 
The code is optimized to get runtime improvements compared to naive implementations.

If you happen to use this code, consider citing our [paper]().
```

```
If you discover any bug, please file an issue. For contributions, please make a pull request.

# TODO
- Add link to arXiv paper
- Add Jupyter notebook demostrating how to use both the generation and estimation code

# Other similar resources

- [Scott Linderman](http://www.columbia.edu/~swl2133/) provides code for [bayesian inference on Hawkes processes](https://github.com/slinderman/pyhawkes).
- [The Hawkes Process Toolkit](https://github.com/HongtengXu/Hawkes-Process-Toolkit) by Hongteng Xu and Hongyuan Zha is a comprehensive toolkit for doing estimation and simulation using Hawkes process. It is writte in Matlab.


