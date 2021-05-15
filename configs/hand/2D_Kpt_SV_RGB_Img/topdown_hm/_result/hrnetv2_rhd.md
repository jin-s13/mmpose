<!-- [ALGORITHM] -->

```bibtex
@article{WangSCJDZLMTWLX19,
  title={Deep High-Resolution Representation Learning for Visual Recognition},
  author={Jingdong Wang and Ke Sun and Tianheng Cheng and
          Borui Jiang and Chaorui Deng and Yang Zhao and Dong Liu and Yadong Mu and
          Mingkui Tan and Xinggang Wang and Wenyu Liu and Bin Xiao},
  journal={TPAMI}
  year={2019}
}
```

<!-- [DATASET] -->

```bibtex
@TechReport{zb2017hand,
  author={Christian Zimmermann and Thomas Brox},
  title={Learning to Estimate 3D Hand Pose from Single RGB Images},
  institution={arXiv:1705.01389},
  year={2017},
  note="https://arxiv.org/abs/1705.01389",
  url="https://lmb.informatik.uni-freiburg.de/projects/hand3d/"
}
```

#### Results on RHD test set

| Arch  | Input Size | PCK@0.2 |  AUC  |  EPE  | ckpt    | log     |
| :--- | :--------: | :------: | :------: | :------: |:------: |:------: |
| [pose_hrnetv2_w18](/configs/hand/2D_Kpt_SV_RGB_Img/topdown_hm/rhd2d/hrnetv2_w18_rhd2d_256x256.py) | 256x256 | 0.992 | 0.902 | 2.21 | [ckpt](https://download.openmmlab.com/mmpose/hand/hrnetv2/hrnetv2_w18_rhd2d_256x256-95b20dd8_20210330.pth) | [log](https://download.openmmlab.com/mmpose/hand/hrnetv2/hrnetv2_w18_rhd2d_256x256_20210330.log.json) |