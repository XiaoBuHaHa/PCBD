# Progressive Cross-Beam Distillation Network for Robust 3D Object Detection in Sparse LiDAR Data
### [Paper]() | [Model]() 
 We will publish the code immediately once the paper is accepted
<br/>
<p align='center'>
<img src="./Image_show/Framework.png" width='80%'/>
</p>


## Introduction

In this paper, we propose the PCBD to bridge the domain gap induced by different LiDAR beams for 3D object detection. In many real-world applications, the LiDAR points used by mass-produced robots and vehicles usually have fewer beams than that in large-scale public datasets. Moreover, as the LiDARs are upgraded
to other product models with different beam amount, it becomes challenging to utilize the labeled data captured by previous versions’ high-resolution sensors. Despite the recent progress on domain adaptive 3D
detection, most methods struggle to eliminate the beam-induced domain gap. 

## Installation

Please refer to [INSTALL.md](docs/INSTALL.md).

## Getting Started

Please refer to [GETTING_STARTED.md](docs/GETTING_STARTED.md).

## License

Our code is released under the Apache 2.0 license.

## Acknowledgement

Our code is heavily based on [OpenPCDet v0.2](https://github.com/open-mmlab/OpenPCDet/tree/v0.2.0) and [LIDAR Distill](https://github.com/weiyithu/LiDAR-Distillation?tab=readme-ov-file). Thanks OpenPCDet Development Team for their awesome codebase.

## Citation

If you find this project useful in your research, please consider cite:
```
@article{wei2022lidar,
  title={LiDAR Distillation: Bridging the Beam-Induced Domain Gap for 3D Object Detection},
  author={Wei, Yi and Wei, Zibu and Rao, Yongming and Li, Jiaxin and Zhou, Jie and Lu, Jiwen},
  journal={arXiv preprint arXiv:2203.14956},
  year={2022}
}
```
```

```












