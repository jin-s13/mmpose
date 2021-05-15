<!-- [ALGORITHM] -->

```bibtex
@inproceedings{martinez_2017_3dbaseline,
  title={A simple yet effective baseline for 3d human pose estimation},
  author={Martinez, Julieta and Hossain, Rayat and Romero, Javier and Little, James J.},
  booktitle={ICCV},
  year={2017}
}
```

<!-- [DATASET] -->

```bibtex
@article{h36m_pami,
  author = {Ionescu, Catalin and Papava, Dragos and Olaru, Vlad and Sminchisescu,  Cristian},
  title = {Human3.6M: Large Scale Datasets and Predictive Methods for 3D Human Sensing in Natural Environments},
  journal = {IEEE Transactions on Pattern Analysis and Machine Intelligence},
  publisher = {IEEE Computer Society},
  volume = {36},
  number = {7},
  pages = {1325-1339},
  month = {jul},
  year = {2014}
}
```

#### Results on Human3.6M dataset with ground truth 2D detections

| Arch | MPJPE | P-MPJPE | ckpt | log |
| :--- | :---: | :---: | :---: | :---: |
| [simple3Dbaseline<sup>1</sup>](/configs/body/3D_Kpt_SV_RGB_Img/simple_baseline/h36m/simple3Dbaseline_h36m.py) | 43.4 | 34.3 | [ckpt](https://download.openmmlab.com/mmpose/body3d/simple_baseline/simple3Dbaseline_h36m-f0ad73a4_20210419.pth) | [log](https://download.openmmlab.com/mmpose/body3d/simple_baseline/20210415_065056.log.json) |

<sup>1</sup> Differing from the original paper, we didn't apply the `max-norm constraint` because we found this led to a better convergence and performance.