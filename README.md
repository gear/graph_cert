# Certifiable Robustness to Graph Perturbations

<p align="center">
<img src="https://www.in.tum.de/fileadmin/w00bws/daml/graph_cert/graph_cert_overview.png">
</p>

Preliminary reference implementation.

## Requirements
* numpy
* scipy
* numba
* cvxpy 

## Demo
See the notebook `Local Budget Demo.ipynb` for a demo on how to compute the certificate for local budget only. 
See the notebook `Adversarial Training Demo.ipynb` for a demo comparing the different training schemes. 

## Cite
Please cite our paper if you use this code in your own work:

```
@inproceedings{bojchevski2019certifiable,
  title =      {Certifiable Robustness to Graph Perturbations},
  author =     {Aleksandar Bojchevski and Stephan G{\"{u}}nnemann},
  booktitle =  {Neural Information Processing Systems, {NeurIPS}},
  year =       {2019},
}
```
