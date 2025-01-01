# Uniform Risk Minimization
Official code for the TMLR paper "Uniformly Distributed Feature Representations for Fair and Robust Learning": https://openreview.net/forum?id=PgLbS5yp8n

# Domain Generalization 
URM is available as part of the [DomainBed](https://github.com/facebookresearch/DomainBed) library. Alternatively, you may use this [fork](https://github.com/kiranchari/DomainBed/tree/URM) of the DomainBed library to run URM for domain generalization. Passing ```--algorithm URM``` to the commands will run the URM algorithm when running experiments.

# Subpopulation robustness
Please use this [fork](https://github.com/kiranchari/SubpopBench/tree/URM) of the [SubpopBench](https://github.com/YyzHarry/SubpopBench) library to run URM for subpopulation shifts. Passing ```--algorithm URM``` to the commands will run the URM algorithm when running experiments.
We have also created a pull request to merge the [forked repo](https://github.com/kiranchari/SubpopBench/tree/URM) to the original [SubpopBench](https://github.com/YyzHarry/SubpopBench) library. 
You may check the original SubpopBench library in case the pull request has been merged.

# Citation
If you find this code or idea useful, please cite our work.

```
@article{
krishnamachari2024uniformly,
title={Uniformly Distributed Feature Representations for Fair and Robust Learning},
author={Kiran Krishnamachari and See-Kiong Ng and Chuan-Sheng Foo},
journal={Transactions on Machine Learning Research},
issn={2835-8856},
year={2024},
url={https://openreview.net/forum?id=PgLbS5yp8n},
note={}
}
```
