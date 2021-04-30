# PINN-based-Helmholtz-solver
**This repository reproduces the results of the paper "[Solving the frequency-domain acoustic VTI wave equation using physics-informed neural networks.](https://academic.oup.com/gji/article/225/2/846/6081098)" Geophysical Journal International 225, 846-859;  the results of the abstract "[Machine learned Green's functions that approximately satisfy the wave equation](https://library.seg.org/doi/abs/10.1190/segam2020-3421468.1)", SEG International Exposition and 90th Annual Meeting, 2638-2642;  the results of the abstract "[Wavefield solutions from machine learned functions that approximately satisfy the wave equation](https://www.earthdoc.org/content/papers/10.3997/2214-4609.202010588)", Conference Proceedings, EAGE 2020 Annual Conference & Exhibition Online, Dec 2020, Volume 2020, p.1 - 5**

# Overview

We propose to use the physics Informed Neural Network (PINN) to solve the scattered form of acoustic isotropic and anisotropic wave equations

PINN reduces the computational cost by avoid computing the inverse of the impedance matrix, which is suitable for anisotropic large models 

The resulting scattered wavefields are free of numerical dispersion artifacts

![image](https://user-images.githubusercontent.com/31889731/116651995-f7a17000-a98c-11eb-9ef1-b18e4562f661.png)

# Installation of Tensorflow1

CPU usage: pip install --pre "tensorflow==1.15.*"

GPU usage: pip install --pre "tensorflow-gpu==1.15.*"

# Citation information

If you find our codes and publications helpful, please kindly cite the following publications.

@article{song2020solving,
  title={Solving the frequency-domain acoustic VTI wave equation using physics-informed neural networks},
  author={Song, Chao and Alkhalifah, Tariq and Waheed, Umair Bin},
  journal={Geophysical Journal International},
  volume={225},
  number={2},
  pages={846–-859},
  year={2021},
  publisher={Oxford University Press}
}

@inproceedings{alkhalifah2020wavefield,
  title={Wavefield solutions from machine learned functions that approximately satisfy the wave equation},
  author={Alkhalifah, Tariq and Song, Chao and Hao, Q and others},
  booktitle={82nd EAGE Annual Conference \& Exhibition},
  volume={2020},
  number={1},
  pages={1--5},
  year={2020},
  organization={European Association of Geoscientists \& Engineers}
}

@incollection{alkhalifah2020machine,
  title={Machine learned Green’s functions that approximately satisfy the wave equation},
  author={Alkhalifah, Tariq and Song, Chao and Waheed, Umair bin},
  booktitle={SEG Technical Program Expanded Abstracts 2020},
  pages={2638--2642},
  year={2020},
  publisher={Society of Exploration Geophysicists}
