CV-DL Recommandations
===
Recommanded resources in Computer Vision and Deep Learning including advanced paper and issue-solutions in experiments.
## Contents
- [CV-DL Recommandations](#cv-dl-recommandations)
    - [Contents](#contents)
        - [Backbone Network](#backbone-network)
        - [Image Recognition](#image-recognition)
        - [Super Resolution](#super-resolution)
        - [Object Detection](#object-detection)
        - [Semantic Segmentation](#semantic-segmentation)
        - [Image Caption](#image-caption)
        - [Generative Adversarial Networks](#generative-adversarial-networks)
        - [Attention Mechanism](#attention-mechanism)
        - [Natural Language Processing Related](#natural-language-processing-related)
        - [Dataset and Contest](#dataset-and-contest)
            - [1. Dataset](#1-dataset)
            - [2. Contest](#2-contest)
        - [Training Techniques](#training-techniques)


<!-- * [Backbone Network](#backbone-network)
* [Image Recognition](#image-recognition)
* [Super Resolution](#super-resolution)
* [Object Detection](#object-detection)
* [Semantic Segmentation](#semantic-segmentation)
* [Image Caption](#image-caption)
* [Generative Adversarial Networks](#generative-adversarial-networks)
* [Attention Mechanism](#attention-mechanism)
* [Natural Language Processing Related](#natural-language-processing-related)
* [Dataset and Contest](#dataset-and-contest)
* [Training Techniques](#training-techniques) -->

### Backbone Network
- Squeeze-and-Excitation Networks(2017.9) [[pdf]](https://arxiv.org/abs/1709.01507) [[code_Caffe]](https://github.com/hujie-frank/SENet) [[code_PyTorch]](https://github.com/moskomule/senet.pytorch)


### Image Recognition

### Super Resolution

### Object Detection

### Semantic Segmentation
- Vortex Pooling: Improving Context Representation in Semantic Segmentation(2018.4) [[pdf]](https://arxiv.org/pdf/1804.06242)
- Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation--DeepLab V3+ (2018.2) [[pdf]](https://arxiv.org/abs/1802.02611) [[code_TensorFlow]](https://github.com/rishizek/tensorflow-deeplab-v3-plus)[[code_TensorFlow]](https://github.com/tensorflow/models/tree/master/research/deeplab)(official) [[code_Pytorch]](https://github.com/jfzhang95/pytorch-deeplab-xception)
- Pyramid Attention Network for Semantic Segmentation(2018.5) [[pdf]](https://arxiv.org/pdf/1805.10180)


### Image Caption
- Show, Attend and Tell: Neural Image Caption Generation with Visual Attention(2015) [[pdf]](https://arxiv.org/abs/1502.03044) [[code_tensorflow]](https://github.com/yunjey/show-attend-and-tell) [[code_PyTorch]](https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Image-Captioning)
- Image Captioning with Semantic Attention(2016) [[pdf]](https://arxiv.org/abs/1603.03925) [[code]](https://github.com/chapternewscu/image-captioning-with-semantic-attention)
- Bottom-Up and Top-Down Attention for Image Captioning and Visual Question Answering(2017) [[pdf]](https://arxiv.org/abs/1707.07998)[[code]](https://github.com/peteanderson80/bottom-up-attention)
- Convolutional Image Captioning(2017) [[pdf]](https://arxiv.org/abs/1711.09151) [[code]](https://github.com/aditya12agd5/convcap)
- CNN+CNN: Convolutional Decoders for Image Captioning (2018) [[pdf]](https://arxiv.org/abs/1805.09019)

### Generative Adversarial Networks
- Video-to-Video Synthesis(2018) [[pdf]](https://arxiv.org/abs/1808.06601) [[code_PyTorch]](https://github.com/NVIDIA/vid2vid)
- Diverse Image-to-Image Translation via Disentangled Representations(2018.8) [[pdf]](https://arxiv.org/abs/1808.00948) [[code_PyTorch]](https://github.com/HsinYingLee/DRIT) <font color=Gray >(Notes: maybe suitable for unpaired MR-CT synthesis for human body)</font>

### Attention Mechanism
- Show, Attend and Tell: Neural Image Caption Generation with Visual Attention(2015) [[pdf]](https://arxiv.org/abs/1502.03044) [[code_TensorFlow]](https://github.com/yunjey/show-attend-and-tell) [[code_PyTorch]](https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Image-Captioning)
- Image Captioning with Semantic Attention(2016) [[pdf]](https://arxiv.org/abs/1603.03925) [[code]](https://github.com/chapternewscu/image-captioning-with-semantic-attention)
- Attention Is All You Need(2017) [[pdf]](https://arxiv.org/abs/1706.03762) [[code_PyTorch]](https://github.com/jadore801120/attention-is-all-you-need-pytorch) [[code_TensorFlow]](https://github.com/Kyubyong/transformer)
- Bottom-Up and Top-Down Attention for Image Captioning and Visual Question Answering(2017) [[pdf]](https://arxiv.org/abs/1707.07998) [[code]](https://github.com/peteanderson80/bottom-up-attention)
- Attention U-Net:Learning Where to Look for the Pancreas(2018) [[pdf]](https://arxiv.org/abs/1804.03999) [[code]](https://github.com/ozan-oktay/Attention-Gated-Networks)
- Self-Attention Generative Adversarial Networks(2018.5) [[pdf]](https://arxiv.org/abs/1805.08318) [[code_PyTorch]](https://github.com/heykeetae/Self-Attention-GAN)
(Notes: 将自我注意机制引入到GAN的生成模型中，对于图像的纹理和几何上的联系提供全局的注意使得生成的图像更加的合理)
- Learning Visual Question Answering by Bootstrapping Hard Attention (2018.8) [[pdf]](https://arxiv.org/abs/1808.00300) [[code]](https://github.com/gnouhp/PyTorch-AdaHAN) (Note: Hard-Attention)
- Pervasive Attention: 2D Convolutional Neural Networks for Sequence-to-Sequence Prediction(2018.8) [[pdf]](https://arxiv.org/abs/1808.03867) [[code]](https://github.com/elbayadm/attn2d)

### Natural Language Processing Related
- Pervasive Attention: 2D Convolutional Neural Networks for Sequence-to-Sequence Prediction(2018) [[pdf]](https://arxiv.org/abs/1808.03867) [[code]](https://github.com/elbayadm/attn2d)

### Dataset and Contest

#### 1. Dataset

- [PASCAL VOC 2012](http://host.robots.ox.ac.uk/pascal/VOC/): 
The main goal of this challenge is to recognize objects from a number of visual object classes in realistic scenes (i.e. not pre-segmented objects). It is fundamentally a supervised learning learning problem in that a training set of labelled images is provided.
- [Cityscapes](https://www.cityscapes-dataset.com/): 
Large-scale dataset that contains a diverse set of stereo video sequences recorded in street scenes from 50 different cities, with high quality pixel-level annotations of 5 000 frames in addition to a larger set of 20 000 weakly annotated frames.
- [NYUv2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html): 
The NYU-Depth V2 data set is comprised of video sequences from a variety of indoor scenes as recorded by both the RGB and Depth cameras from the Microsoft Kinect.
- [PASCAL-Context](https://cs.stanford.edu/~roozbeh/pascal-context/): 
This dataset is a set of additional annotations for PASCAL VOC 2010. It goes beyond the original PASCAL semantic segmentation task by providing annotations for the whole scene. The statistics section has a full list of 400+ labels.
- [SUNRGBD](http://rgbd.cs.princeton.edu/): 
Dataset is captured by four different sensors and contains 10,335 RGB-D images, at a similar scale as PASCAL VOC. The whole dataset is densely annotated and includes 146,617 2D polygons and 64,595 3D bounding boxes with accurate object orientations, as well as a 3D room layout and scene category for each image. 
- [ADE20k](http://groups.csail.mit.edu/vision/datasets/ADE20K/): 
ADE20K Dataset contains more than 20K scene-centric images exhaustively annotated with objects and object parts. Specifically, the benchmark is divided into 20K images for training, 2K images for validation, and another batch of held-out images for testing. There are totally 150 semantic categories included for evaluation, which include stuffs like sky, road, grass, and discrete objects like person, car, bed. Note that there are non-uniform distribution of objects occuring in the images, mimicking a more natural object occurrence in daily scene.
- [Grand Challenges in Biomedical Image Analysis](https://grand-challenge.org): 
Grand Challenges in Biomedical Image Analysis

#### 2. Contest
- [AI Challenger](https://challenger.ai/)

### Training Techniques
- [An overview of gradient descent optimization algorithms](http://ruder.io/optimizing-gradient-descent/index.html)