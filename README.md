# FusionFormer: Unified Multi-Modal and Temporal Fusion with Transformer for 3d Detection in Bird's-Eye-View
## Method
FusionFormer is a multimodal temporal fusion approach for 3D object detection. The multimodal fusion encoder based on deformable attention can adapt to different feature representations of different modalities without requiring pre-transformation into BEV space.The temporal fusion module utilizes deformable attention to fuse temporally aligned BEV features from the current and historical frames.
## Results on nuScenes val set.
The model was trained for 24 epochs on the nuScenes 3D object detection dataset. Results on nuScenes val set are presented in the table. It is worth noting that no data augmentation methods such as rotation, scaling, GT-paste, or CBGS were utilized during training. Details will be presented in a subsequent paper.
|   Image   | Lidar |  mAP  |  NDS  |
|:---------:|:---------:|:-----:|:-----:|
| R101-DCN  |VoxelNet-0075| 62.9% | 67.8% |
