# GoogLeNet

*Author: Pytorch Team*

**GoogLeNet was based on a deep convolutional neural network architecture codenamed "Inception" which won ImageNet 2014.**

_ | _
- | -
![alt](https://pytorch.org/assets/images/googlenet1.png) | ![alt](https://pytorch.org/assets/images/googlenet2.png)

## TRANSFORMING AND AUGMENTING IMAGES
Transforms are common image transformations available in the torchvision.transforms module. They can be chained together using Compose. Most transform classes have a function equivalent: functional transforms give fine-grained control over the transformations. This is useful if you have to build a more complex transformation pipeline (e.g. in the case of segmentation tasks).
[more details](https://pytorch.org/vision/main/transforms.html)

## Achievements
We are using GoogleNet which is a pretrained model over thousands images, and retrained this model with new images. 
we have adjusted the Googlenet model layers to work with different images size and updated the output

[GoogleNet](GOOGLENET_pytorch_vision_googlenet.ipynb)
