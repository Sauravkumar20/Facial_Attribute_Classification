# Facial_Attribute_Classification

![image](https://github.com/Sauravkumar20/Facial_Attribute_Classification/assets/75738377/c4827093-7fea-444c-905e-604b1a5eb3d1)
implemented the VGG-16 model:
=================================================================
Layer (type:depth-idx)                   Param #
=================================================================
MultiTaskModel                           --
├─VGG: 1-1                               --
│    └─Sequential: 2-1                   --
│    │    └─Conv2d: 3-1                  (1,792)
│    │    └─ReLU: 3-2                    --
│    │    └─Conv2d: 3-3                  (36,928)
│    │    └─ReLU: 3-4                    --
│    │    └─MaxPool2d: 3-5               --
│    │    └─Conv2d: 3-6                  (73,856)
│    │    └─ReLU: 3-7                    --
│    │    └─Conv2d: 3-8                  (147,584)
│    │    └─ReLU: 3-9                    --
│    │    └─MaxPool2d: 3-10              --
│    │    └─Conv2d: 3-11                 (295,168)
│    │    └─ReLU: 3-12                   --
│    │    └─Conv2d: 3-13                 (590,080)
│    │    └─ReLU: 3-14                   --
│    │    └─Conv2d: 3-15                 (590,080)
│    │    └─ReLU: 3-16                   --
│    │    └─MaxPool2d: 3-17              --
│    │    └─Conv2d: 3-18                 (1,180,160)
│    │    └─ReLU: 3-19                   --
│    │    └─Conv2d: 3-20                 (2,359,808)
│    │    └─ReLU: 3-21                   --
│    │    └─Conv2d: 3-22                 (2,359,808)
│    │    └─ReLU: 3-23                   --
│    │    └─MaxPool2d: 3-24              --
│    │    └─Conv2d: 3-25                 (2,359,808)
│    │    └─ReLU: 3-26                   --
│    │    └─Conv2d: 3-27                 (2,359,808)
│    │    └─ReLU: 3-28                   --
│    │    └─Conv2d: 3-29                 (2,359,808)
│    │    └─ReLU: 3-30                   --
│    │    └─MaxPool2d: 3-31              --
│    └─AdaptiveAvgPool2d: 2-2            --
│    └─Sequential: 2-3                   --
│    │    └─Linear: 3-32                 (102,764,544)
│    │    └─ReLU: 3-33                   --
│    │    └─Dropout: 3-34                --
│    │    └─Linear: 3-35                 (16,781,312)
│    │    └─ReLU: 3-36                   --
│    │    └─Dropout: 3-37                --
│    │    └─Linear: 3-38                 (4,097,000)
├─Linear: 1-2                            64,064
├─Linear: 1-3                            520
=================================================================
Total params: 138,422,128
Trainable params: 64,584
Non-trainable params: 138,357,544
=================================================================
dataset link:
https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html
