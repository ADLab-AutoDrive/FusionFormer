# FusionFormer: A Multi-sensory Fusion in Bird's-Eye-View and Temporal Consistent Transformer for 3D Objection
[![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/abs/2309.05257)
## Method
FusionFormer is an end-to-end multi-modal fusion framework that leverages transformers to fuse multi-modal features and obtain fused BEV features. In addition, we propose a plug-and-play temporal fusion module based on transformers that can fuse historical frame BEV features for more stable and reliable detection results. We evaluate our method on the nuScenes dataset and achieve 72.6% mAP and 75.1% NDS (SOTA without any TTA or model ensemble) for 3D object detection tasks.

## Results on nuScenes val set.
|   Methods   |   Image   | Lidar |  mAP  |  NDS  |
|:---------:|:---------:|:---------:|:-----:|:-----:|
| FusionFormer-S  | VOV-99  |Voxel0075| 70.0% | 73.2% |
| FusionFormer  | VOV-99  |Voxel0075| 71.4% | 74.1% |

## Results on nuScenes test set.
|   Methods   |   Image   | Lidar |  mAP  |  NDS  |
|:---------:|:---------:|:---------:|:-----:|:-----:|
| FusionFormer  | VOV-99  |Voxel0075| 72.6% | 75.1% |
