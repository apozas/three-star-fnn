[![DOI](https://www.zenodo.org/badge/579949050.svg)](https://www.zenodo.org/badge/latestdoi/579949050)

## Computational appendix of *[Certification of non-classicality in all links of a photonic star network without assuming quantum mechanics](https://www.nature.com/articles/s41467-023-37842-w)*
#### Ning-Ning Wang, Alejandro Pozas-Kerstjens, Chao Zhang, Bi-Heng Liu, Yun-Feng Huang, Chuan-Feng Li, Guang-Can Guo, Nicolas Gisin, and Armin Tavakoli

This is a repository containing the computational appendix of the article "*Certification of non-classicality in all links of a photonic star network without assuming quantum mechanics*. Ning-Ning Wang, Alejandro Pozas-Kerstjens, Chao Zhang, Bi-Heng Liu, Yun-Feng Huang, Chuan-Feng Li, Guang-Can Guo, Nicolas Gisin, and Armin Tavakoli. [Nat. Commun. 14, 2153 (2023)](https://www.nature.com/articles/s41467-023-37842-w) [[arXiv:2212.09765](https://www.arxiv.org/abs/2212.09765)]." It provides a detailed explanation of how to write the linear programming problems associated to hybrid classical-nonsignaling-nonsignaling inflations of the three-star network, and the necessary codes for obtaining the witnesses of full network nonlocality depicted in the manuscript.

All code is written in Python.

Libraries required:
- [mosek](https://www.mosek.com/) ``>= 9.1.13 && <= 9.2.28`` for solving the linear programming problems. Other versions produce much more complicated inequalities
- [numpy](https://numpy.org/) for numerical manipulations
- [picos](https://picos-api.gitlab.io/picos/) ``>= 2.0 && <= 2.2`` for setting up the linear programming problems. Other versions produce much more complicated inequalities
- [qutip](http://qutip.org/) for quantum mechanical operations
- [sympy](https://www.sympy.org/) for symbolic manipulations

If you would like to cite this work, please use the following format:
N.-N. Wang, A. Pozas-Kerstjens, C. Zhang, B.-H. Liu, Y.-F. Huang, C.-F. Li, G.-C. Guo, N. Gisin, and A. Tavakoli, _Certification of non-classicality in all links of a photonic star network without assuming quantum mechanics_, Nat. Commun. *14*, 2153 (2023)

```
@article{threestarfnn,
  title = {Certification of non-classicality in all links of a photonic star network without assuming quantum mechanics},
  author = {Wang, Ning-Ning and Pozas-Kerstjens, Alejandro and Zhang, Chao and Liu, Bi-Heng and Huang, Yun-Feng and Li, Chuan-Feng and Guo, Guang-Can  and Gisin, Nicolas and Tavakoli, Armin},
  journal = {Nat. Commun.},
  volume = {14},
  pages = {2153},
  doi = {10.1038/s41467-023-37842-w},
  year = {2023},
  url = {https://www.nature.com/articles/s41467-023-37842-w},
  eprint = {2212.09765},
  archivePrefix={arXiv}
}
```
