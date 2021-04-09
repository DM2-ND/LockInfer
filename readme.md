# LockInfer

This repository contains the code package for the PAKDD'14 / KAIS'16 paper:

**[Inferring Strange Behavior from Connectivity Pattern in Social Networks](http://www.meng-jiang.com/pubs/lockinfer-pakdd14/lockinfer-pakdd14-paper.pdf).** 

**[Inferring Lockstep Behavior from Connectivity Pattern in Large Graphs](http://www.meng-jiang.com/pubs/lockinfer-kais16/lockinfer-kais16-paper.pdf).** 

[Meng Jiang](http://meng-jiang.com/), Peng Cui, Alex Beutel, Christos Faloutsos, Shiqiang Yang.

## Usage

A toy example to generate the injected graph and use Get-the-Scoop to detect the injected node groups.
1. Python: Run graph_generator.py
2. Matlab: Run run_compute_eigenvector.m
3. R: Run plot_eigenvector.R
4. Python: Run get_the_scoop.py

## Citation
If you find this repository useful in your research, please cite our paper:

```bibtex
@incollection{jiang2014inferring,
  title={Inferring Strange Behavior from Connectivity Pattern in Social Networks},
  author={Jiang, Meng and Cui, Peng and Beutel, Alex and Faloutsos, Christos and Yang, Shiqiang},
  booktitle={Advances in Knowledge Discovery and Data Mining},
  pages={126--138},
  year={2014},
  publisher={Springer}
}

@article{jiang2016inferring,
  title={Inferring lockstep behavior from connectivity pattern in large graphs},
  author={Jiang, Meng and Cui, Peng and Beutel, Alex and Faloutsos, Christos and Yang, Shiqiang},
  journal={Knowledge and Information Systems},
  volume={48},
  number={2},
  pages={399--428},
  year={2016},
  publisher={Springer}
}
