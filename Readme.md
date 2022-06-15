# plugin style module for nerual network performance improvement

This repo amis at nerual network performance improvement with modification as few as possible.
Plugin-style network module can almost insert into any networks and get expected improvement. Here's a collection list about the  papers related to performance improvement, considering model parameters numbers / model size, model accuracy and inference speed.

## Plugin network module
[CVPR 2018] [SENet] Squeeze-and-Excitation Networks [paper](https://arxiv.org/abs/1709.01507) [code](https://github.com/moskomule/senet.pytorch)

[CVPR 2019] CSPNet: A New Backbone that can Enhance Learning Capability of CNN [paper](https://arxiv.org/abs/1911.11929) [code](https://github.com/WongKinYiu/CrossStagePartialNetworks)

[CVPR 2018] Non-local Neural Networks [paper](https://arxiv.org/abs/1711.07971) [code](https://github.com/facebookresearch/video-nonlocal-net)

## Tricks for training
[CVPR 2019] Bag of Tricks for Image Classification with Convolutional Neural Networks [paper](https://arxiv.org/abs/1812.01187) [code](https://github.com/dmlc/gluon-cv)

[CVPR 2022] [ConNext] A ConvNet for the 2020s [paper](https://arxiv.org/abs/2201.03545) [code](https://github.com/facebookresearch/ConvNeXt)

## Light-weight network structure / Inference speed
ShuffleNet Series [code](https://github.com/megvii-model/ShuffleNet-Series)

[CVPR 2018] ShuffleNet: An Extremely Efficient Convolutional Neural Network for Mobile Devices [paper](https://arxiv.org/abs/1707.01083)

[ECCV 2018] ShuffleNet V2: Practical Guidelines for Efficient CNN Architecture Design [paper](https://arxiv.org/abs/1807.11164)

MobileNet Series [code](https://github.com/tensorflow/tensorflow/tree/v2.4.1/tensorflow/python/keras/applications)

[CVPR 2017] MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications [paper](https://arxiv.org/abs/1704.04861)

[CVPR 2018] MobileNetV2: Inverted Residuals and Linear Bottlenecks [paper](https://arxiv.org/abs/1801.04381)

[ICCV 2019] Searching for MobileNetV3 [paper](https://arxiv.org/abs/1905.02244)



MobileVit Series [code](https://github.com/apple/ml-cvnets)

[ICLR 2022] MobileViT: Light-weight, General-purpose, and Mobile-friendly Vision Transformer [paper](https://arxiv.org/abs/2110.02178)

note: code v2 already released, paper not yet

Others

[arxiv 2022] EdgeFormer: Improving Light-weight ConvNets by Learning from Vision Transformers [paper](https://arxiv.org/abs/2203.03952) [code](https://github.com/hkzhang91/EdgeFormer)