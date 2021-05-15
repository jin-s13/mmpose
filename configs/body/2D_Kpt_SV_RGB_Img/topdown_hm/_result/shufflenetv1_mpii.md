<!-- [BACKBONE] -->

```bibtex
@inproceedings{zhang2018shufflenet,
  title={Shufflenet: An extremely efficient convolutional neural network for mobile devices},
  author={Zhang, Xiangyu and Zhou, Xinyu and Lin, Mengxiao and Sun, Jian},
  booktitle={Proceedings of the IEEE conference on computer vision and pattern recognition},
  pages={6848--6856},
  year={2018}
}
```

<!-- [DATASET] -->

```bibtex
@inproceedings{andriluka14cvpr,
  author = {Mykhaylo Andriluka and Leonid Pishchulin and Peter Gehler and Schiele, Bernt}
  title = {2D Human Pose Estimation: New Benchmark and State of the Art Analysis},
  booktitle = {IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year = {2014},
  month = {June}
}
```

#### Results on MPII val set

| Arch  | Input Size | Mean | Mean@0.1   | ckpt    | log     |
| :--- | :--------: | :------: | :------: |:------: |:------: |
| [pose_shufflenetv1](/configs/body/2D_Kpt_SV_RGB_Img/topdown_hm/mpii/shufflenetv1_mpii_256x256.py) | 256x256 | 0.823 | 0.195 | [ckpt](https://download.openmmlab.com/mmpose/top_down/shufflenetv1/shufflenetv1_mpii_256x256-dcc1c896_20200925.pth) | [log](https://download.openmmlab.com/mmpose/top_down/shufflenetv1/shufflenetv1_mpii_256x256_20200925.log.json) |