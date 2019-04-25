# CVPR_2018_MorphNet

The paper presents an interesting method that takes a trained network (ResNet101) as inputs and change the network architectures
with respectied to targeted resources (e.g. FLOPs or network size). 

It shrinks and expands the baseline network iteratively using the L1-norm Regularaization approach (for shrinking) and 
width multiplier (for expanding). These two approachs are not new in this research domain, especially width multiplier was used in
MobileNet. 

[](./fig1.JPG)
