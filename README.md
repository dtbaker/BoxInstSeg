
## Introduction
BoxInstSeg is a toolbox that aims to provide state-of-the-art box-supervised instance segmentation algorithms. 
It is built on top of [mmdetection](https://github.com/open-mmlab/mmdetection).
The main branch works with Pytorch 1.6+ or higher (we recommend Pytorch **1.9**)


### Major features

- **Support of instance segmentation with only box annotations**

   We implement multiple box-supervised instance segmentation methods in this toolbox,(*e.g.* BoxInst, DiscoBox).

- **MMdetection feature inheritance**

  This toolbox doesn't change the structure and logic of mmdetection. It inherits all features from MMdetection.

## Model Zoo
<summary> Supported methods </summary>

- [x] [BoxInst (CVPR2021)](https://arxiv.org/abs/2012.02310)
- [x] [DiscoBox (ICCV2021)](https://arxiv.org/abs/2105.06464v2)
- [x] [BoxLevelset (ECCV2022)]()

**_Multiple pretrained models are coming soon based on the Pascal VOC and COCO and more datasets._**


## Installation and Getting Started
This is built on the MMdetection (V2.25.0). Please refer to [Installation]() and [Getting Started]() for the details of installation and the basic usage.
We recommend user to see the detailed instroductions of MMdetection.


## License

This project is released under the [Apache 2.0 license](LICENSE).


## Acknowledgement

This project is built based on [MMdetection](https://github.com/open-mmlab/mmdetection) and part of module is borrowed from the original rep of [Adelaidet](https://github.com/aim-uofa/AdelaiDet) and [DiscoBox](https://github.com/NVlabs/DiscoBox).

## More
This [repo](https://github.com/LiWentomng/Box-supervised-instance-segmentation) updates the **survey** of _box-supervised instance segmentation_, we highly welcome the user to develop more algorithms in this toolbox.
