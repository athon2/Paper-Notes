CV-DL Papers Reading List(Irregular updates)
===
Recommanded resources in Computer Vision and Deep Learning including advanced paper and issue-solutions in experiments. 

## Contents
- [CV-DL Papers Reading List(Irregular updates)](#cv-dl-papers-reading-listirregular-updates)
  - [Contents](#contents)
  - [Backbone Network](#backbone-network)
    - [Light Weight Network](#light-weight-network)
  - [Semantic Segmentation](#semantic-segmentation)
    - [Real Time Segmentation](#real-time-segmentation)
  - [Object Detection](#object-detection)
  - [Image Caption](#image-caption)
  - [Generative Adversarial Networks](#generative-adversarial-networks)
  - [Attention Mechanism](#attention-mechanism)
  - [Natural Language Processing Related](#natural-language-processing-related)
  - [Medical Image Analysis](#medical-image-analysis)
  - [Other Applications](#other-applications)
    - [Super Resolution](#super-resolution)
  - [Training Skills](#training-skills)
    - [Data Augmentation](#data-augmentation)
    - [Normalization](#normalization)
    - [Initialization](#initialization)
  - [Dataset and Contest](#dataset-and-contest)
    - [Dataset](#dataset)
    - [Contest](#contest)
        
----

## Backbone Network
- **[AlexNet]** ImageNet classification with deep convolutional neural networks(2012 *NIPs 2012*) [[Paper]](http://www.image-net.org/challenges/LSVRC/2012/supervision.pdf) [[code]](https://github.com/pytorch/vision/blob/master/torchvision/models/alexnet.py)
- **[ZFNet]** Visualizing and Understanding Convolutional Networks (2013.11 *ECCV 2014*) [[Paper]](https://arxiv.org/abs/1311.2901) [[code]](https://github.com/InFoCusp/tf_cnnvis)
- **[NIN]** Network In Network (2013.12 *ICLR 2014*) [[Paper]](https://arxiv.org/abs/1312.4400) [[code]](https://github.com/tflearn/tflearn/blob/master/examples/images/network_in_network.py)
- **[VGG]** Very Deep Convolutional Networks for Large-Scale Image Recognition (2014.09)[[Paper]](https://arxiv.org/abs/1409.1556)[[Slide]](http://www.robots.ox.ac.uk/~karen/pdf/ILSVRC_2014.pdf) [[code]](https://github.com/pytorch/vision/blob/master/torchvision/models/vgg.py)
- **[Inception V1]** Going Deeper with Convolutions (2014.09) [[Paper]](https://arxiv.org/abs/1409.4842) [[code]](https://github.com/kuangliu/pytorch-cifar/blob/master/models/googlenet.py)
- **[Inception V2]** Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift (2015.02) [[Paper]](https://arxiv.org/abs/1502.03167) 
- **[Inception V3]** Rethinking the Inception Architecture for Computer Vision (2015.12) [[Paper]](https://arxiv.org/abs/1512.00567) [[code]](https://github.com/pytorch/vision/blob/master/torchvision/models/inception.py)
- **[ResNet]** Deep Residual Learning for Image Recognition (2015.12) [[Paper]](https://arxiv.org/abs/1512.03385) [[code]](https://github.com/pytorch/vision/blob/master/torchvision/models/resnet.py)
- **[Inception v4]** Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning (2016.02) [[Paper]](https://arxiv.org/abs/1602.07261) [[code_TensorFlow]](https://github.com/tensorflow/models/blob/master/research/slim/nets/inception_v4.py) [[code_PyTorch]](https://github.com/Cadene/pretrained-models.pytorch/blob/master/pretrainedmodels/models/inceptionv4.py)
- **[Wide ResNet]** Wide Residual Networks (2016.05) [[Paper]](https://arxiv.org/abs/1605.07146) [[code]](https://github.com/szagoruyko/wide-residual-networks)
- **[DenseNet]** Densely Connected Convolutional Networks (2016.08 *CVPR 2017*) [[Paper]](https://arxiv.org/abs/1608.06993) [[code]](https://github.com/pytorch/vision/blob/master/torchvision/models/densenet.py)
- **[Xception]** Xception: Deep Learning with Depthwise Separable Convolutions (2016.10) [[Paper]](https://arxiv.org/abs/1610.02357) [[code]](https://github.com/Cadene/pretrained-models.pytorch)
- **[ResNeXt]** Aggregated Residual Transformations for Deep Neural Networks (2016.11) [[Paper]](https://arxiv.org/abs/1611.05431) [[code]](https://github.com/Hsuxu/ResNeXt)
- **[PolyNet]** PolyNet: A Pursuit of Structural Diversity in Very Deep Networks (2016.11) [[Paper]](https://arxiv.org/abs/1611.05725) [[code]](https://github.com/Cadene/pretrained-models.pytorch/blob/master/pretrainedmodels/models/polynet.py)
- **[DRN]** Dilated Residual Networks (2017.05 *CVPR 2017*) [[Paper]](https://arxiv.org/abs/1705.09914) [[PyTorch]](https://github.com/fyu/drn/blob/master/classify.py)
- **[DPN]** Dual Path Networks (2017.07) [[Paper]](https://arxiv.org/abs/1707.01629) [[code]](https://github.com/rwightman/pytorch-dpn-pretrained) [[code_mxnet]](https://github.com/cypw/DPNs)
- **[NASNet]** Learning Transferable Architectures for Scalable Image Recognition (2017.07) [[Paper]](https://arxiv.org/abs/1707.07012) [[code]](https://github.com/tensorflow/models/tree/master/research/slim/nets/nasnet)
- **[SENet]** Squeeze-and-Excitation Networks (2017.09) [[Paper]](https://arxiv.org/abs/1709.01507) [[code_Caffe]](https://github.com/hujie-frank/SENet) [[code_PyTorch]](https://github.com/moskomule/senet.pytorch)
- **[Capsules]** Dynamic Routing Between Capsules (2017.10) [[Paper]](https://arxiv.org/abs/1710.09829) [[code]](https://github.com/gram-ai/capsule-networks) 
- **[Non-Local]** Non-local Neural Networks (2017.11) [[Paper]](https://arxiv.org/abs/1711.07971) [[code]](https://github.com/AlexHex7/Non-local_pytorch) 
- **[PNASNet]** Progressive Neural Architecture Search (2017.12) [[Paper]](https://arxiv.org/abs/1712.00559) [[code_PyTorch](https://github.com/chenxi116/PNASNet.pytorch) [[code_TensorFlow]](https://github.com/tensorflow/models/blob/696b69a498b43f8e6a1ecb24bb82f7b9db87c570/research/slim/nets/nasnet/pnasnet.py)

### Light Weight Network
- **[Squeeze Net]** SqueezeNet: AlexNet-level accuracy with 50x fewer parameters and <0.5MB model size (2016.02) [[Paper]](https://arxiv.org/abs/1602.07360) [[code]](https://github.com/pytorch/vision/blob/master/torchvision/models/squeezenet.py)
- **[MobileNets]** MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications (2017.04) [[Paper]](https://arxiv.org/abs/1704.04861) [[code_TensorFlow]](https://github.com/tensorflow/models/blob/master/research/slim/nets/mobilenet_v1.py) [[code_PyTorch]](https://github.com/marvis/pytorch-mobilenet)
- **[ShuffleNet V1]** ShuffleNet: An Extremely Efficient Convolutional Neural Network for Mobile Devices (2017.07) [[Paper]](https://arxiv.org/abs/1707.01083) [[code]](https://github.com/jaxony/ShuffleNet)
- **[IGCV1]** Interleaved Group Convolutions for Deep Neural Networks (20017.07 *ICCV 2017)* [[Paper]](https://arxiv.org/abs/1707.02725) [[code]](https://github.com/hellozting/InterleavedGroupConvolutions)
- **[MobileNet V2]** MobileNetV2: Inverted Residuals and Linear Bottlenecks (2018.01 *CVPR 2018*) [[Paper]](https://arxiv.org/abs/1801.04381) [[code]](https://github.com/tonylins/pytorch-mobilenet-v2)
- **[SqueezeNext]** SqueezeNext: Hardware-Aware Neural Network Design (2018.03 *CVPR 2018*) [[Paper]](https://arxiv.org/abs/1803.10615) [[code_Caffe]](https://github.com/amirgholami/SqueezeNext) [[code_PyTorch]](https://github.com/luuuyi/SqueezeNext.PyTorch)
- **[IGCV2]** IGCV2: Interleaved Structured Sparse Convolutional Neural Networks (2018.04 *CVPR 2018*) [[Paper]](https://arxiv.org/abs/1804.06202) [[code]](https://github.com/homles11/IGCV3) 
- **[IGCV3]** IGCV3: Interleaved Low-Rank Group Convolutions for Efficient Deep Neural Networks (2018.06 *BMVC 2018*) [[Paper]](https://arxiv.org/abs/1806.00178) [[code]](https://github.com/homles11/IGCV3) 
- **[ShuffleNet V2]** ShuffleNet V2: Practical Guidelines for Efficient CNN Architecture Design (2018.07 *CVPR 2018*) [[Paper]](https://arxiv.org/abs/1807.11164) [[code]](https://github.com/miaow1988/ShuffleNet_V2_pytorch_caffe) [[code_PyTorch]](https://github.com/ericsun99/Shufflenet-v2-Pytorch)
 

## Semantic Segmentation
- **[FCN1]** Fully Convolutional Networks for Semantic Segmentation (2014.11,*CVPR 2015*) [[Paper1]](http://www.arxiv.org/abs/1411.4038) [[Paper1]](http://www.arxiv.org/abs/1605.06211) [[PyTorch]](https://github.com/wkentaro/pytorch-fcn) 
- **[DeepLab V1]** Semantic Image Segmentation with Deep Convolutional Nets and Fully Connected CRFs (2014.12, *ICLR 2015*) [[Paper]](https://arxiv.org/abs/1412.7062) [[Caffe]](https://github.com/cdmh/deeplab-public)  
- **[RNN-CRF]** Conditional Random Fields as Recurrent Neural Networks (2015.02, *ICCV 2015*) [[Paper]](https://arxiv.org/abs/1502.03240) [[PyTorch]](https://github.com/torrvision/crfasrnn) 
- **[U-Net]** U-Net: Convolutional Networks for Biomedical Image Segmentation (2015.05, *MICCAI 2015*) [[Paper]](https://arxiv.org/abs/1505.04597) [[PyTorch]](https://github.com/milesial/Pytorch-UNet) [[PyTorch_Hsu]](https://github.com/Hsuxu/carvana-pytorch-uNet)
- **[ParseNet]** ParseNet: Looking Wider to See Better (2015.06, *ICLR 2016*)  [[Paper]](https://arxiv.org/abs/1506.04579) [[Caffe]](https://github.com/debidatta/caffe-parsenet) 
- **[DAG]** DAG-Recurrent Neural Networks For Scene Labeling (2015.09, *CVPR 2016*)  [[Paper]](https://arxiv.org/abs/1509.00552) [[PyTorch]](https://github.com/sallymmx/DAG-RNN) 
- **[SegNet]** SegNet: A Deep Convolutional Encoder-Decoder Architecture for Image Segmentation (2015.09, *PAMI 2016*) [[Paper]](https://arxiv.org/abs/1511.00561) [[Caffe]](https://github.com/alexgkendall/caffe-segnet) [[TensoFlow]](https://github.com/tkuanlun350/Tensorflow-SegNet) [[PyTorch]](https://github.com/meetshah1995/pytorch-semseg/blob/master/ptsemseg/models/segnet.py)
- **[Dilated Conv]** Multi-Scale Context Aggregation by Dilated Convolutions (2015.11 *ICLR 2016*) [[Paper]](https://arxiv.org/abs/1511.07122) [[Caffe]](https://github.com/fyu/dilation)
- **[DeepLab V2]** DeepLab: Semantic Image Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs (2016.06 *TPAMI 2018*) [[Caffe]](https://bitbucket.org/aquariusjay/deeplab-public-ver2)
- **[RefineNet]** RefineNet: Multi-Path Refinement Networks for High-Resolution Semantic Segmentation (2016.11 *CVPR 2017*) [[Paper]](https://arxiv.org/abs/1611.06612) [[MatConvNet]](https://github.com/guosheng/refinenet) [[PyTorch]](https://github.com/thomasjpfan/pytorch_refinenet)
- **[IFCN]** Improving Fully Convolution Network for Semantic Segmentation (2016.11) [[Paper]](https://arxiv.org/abs/1611.08986)
- **[Tiramisu]** The One Hundred Layers Tiramisu: Fully Convolutional DenseNets for Semantic Segmentation (2016.11 *CVPRW 2017*) [[Paper]](https://arxiv.org/abs/1611.09326) [[Theano]](https://github.com/SimJeg/FC-DenseNet) [[PyTorch]](https://github.com/bfortuner/pytorch_tiramisu)
- **[PSPNet]** Pyramid Scene Parsing Network (2016.12 *CVPR 2017*) [[Paper]](https://arxiv.org/abs/1612.01105) [[Caffe]](https://github.com/hszhao/PSPNet) [[PyTorch1]](https://github.com/meetshah1995/pytorch-semseg/blob/master/ptsemseg/models/pspnet.py) [PyTorch2]](https://github.com/Lextal/pspnet-pytorch)
- **[DUC]** Understanding Convolution for Semantic Segmentation (2017.02 *WACV 2018*) [[Paper]](https://arxiv.org/abs/1702.08502) [[mxnet]](https://github.com/TuSimple/TuSimple-DUC)
- **[GCN]** Large Kernel Matters -- Improve Semantic Segmentation by Global Convolutional Network (2017.03 ) [[Paper]](https://arxiv.org/abs/1703.02719) [[PyTorch1]](https://github.com/MEDAL-IITB/Lung-Segmentation) [[PyTorch2]](https://github.com/SConsul/Global_Convolutional_Network)
- **[LovaszSoftmax]** The Lovász-Softmax loss: A tractable surrogate for the optimization of the intersection-over-union measure in neural networks (2017.05 *CVPR 2018*) [[Paper]](https://arxiv.org/abs/1705.08790) [[code]](https://github.com/bermanmaxim/LovaszSoftmax)
- **[DRN]** Dilated Residual Networks (2017.05 *CVPR 2017*) [[Paper]](https://arxiv.org/abs/1705.09914) [[PyTorch]](https://github.com/fyu/drn/blob/master/classify.py)
- **[Generalised Dice]** Generalised Dice overlap as a deep learning loss function for highly unbalanced segmentations (2017.07 ) [[Paper]](https://arxiv.org/abs/1707.03237)
- **[DeepLab V3+]** Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation (2018.2) [[Paper]](https://arxiv.org/abs/1802.02611) [[code_TensorFlow]](https://github.com/rishizek/tensorflow-deeplab-v3-plus) [[code_TensorFlow(official)]](https://github.com/tensorflow/models/tree/master/research/deeplab) [[code_Pytorch]](https://github.com/jfzhang95/pytorch-deeplab-xception)
- **[ESPNet]** ESPNet: Efficient Spatial Pyramid of Dilated Convolutions for Semantic Segmentation (2018.03 ECCV2018) [[Paper]](https://arxiv.org/abs/1803.06815) [[code]](https://github.com/sacmehta/ESPNet)
- **[Vortex Pooling]** Vortex Pooling: Improving Context Representation in Semantic Segmentation(2018.04) [[Paper]](https://arxiv.org/Paper/1804.06242)
- **[FPANet]** Pyramid Attention Network for Semantic Segmentation(2018.05) [[Paper]](https://arxiv.org/Paper/1805.10180)
- **[DANet]** Dual Attention Network for Scene Segmentation (2018.09—AAAI2019) [[Paper]](https://arxiv.org/abs/1809.02983) [[code]](https://github.com/junfu1115/DANet)
- **[DPC]** Searching for Efficient Multi-Scale Architectures for Dense Image Prediction (2018.09) [[Paper]](https://arxiv.org/abs/1809.04184) [[code]](https://github.com/tensorflow/models/tree/master/research/deeplab)
- **[Pixel Augmentation]** Pixel Level Data Augmentation for Semantic Image Segmentation using Generative Adversarial Networks (2018.11) [[Paper]](https://arxiv.org/abs/1811.00174)

### Real Time Segmentation
- **[ENet]** ENet: A Deep Neural Network Architecture for Real-Time Semantic Segmentation (2016.06 ) [[Paper]](https://arxiv.org/abs/1606.02147) [[Caffe]](https://github.com/TimoSaemann/ENet)
- **[ICNet]** ICNet for Real-Time Semantic Segmentation on High-Resolution Images (2017.04 ) [[Paper]](https://arxiv.org/abs/1704.08545) [[Caffe]](https://github.com/hszhao/ICNet) [[PyTorch]](https://github.com/meetshah1995/pytorch-semseg/blob/master/ptsemseg/models/icnet.py)

## Object Detection
- **[DAG]** Adversarial Examples for Semantic Segmentation and Object Detection (2017.03 *ICCV 2017*) [[Paper]](https://arxiv.org/abs/1703.08603) [[Caffe]](https://github.com/cihangxie/DAG)
- **[Focal Loss]** Focal Loss for Dense Object Detection (2017.07) [[Paper]](https://arxiv.org/abs/1708.02002)
- **[DSOD]** DSOD: Learning Deeply Supervised Object Detectors from Scratch (2017.07 *ICCV 2017*) [[Paper]](https://arxiv.org/abs/1708.01241) [[Caffe with SSD]](https://github.com/szq0214/DSOD) [[PyTorch]](https://github.com/uoip/SSD-variants) [[MXNet]](https://github.com/eureka7mt/mxnet-dsod)
- **[Cascade R-CNN]** Cascade R-CNN: Delving into High Quality Object Detection (2017.12 *CVPR 2018*) [[Paper]](https://arxiv.org/abs/1712.00726) [[Caffe]](https://github.com/zhaoweicai/Detectron-Cascade-RCNN) [[Note_Zhihu]](https://zhuanlan.zhihu.com/p/41825737)
- **[CornerNet]** CornerNet: Detecting Objects as Paired Keypoints (2018.08 *ECCV 2018*) [[Paper]](https://arxiv.org/abs/1808.01244) [[PyTorch]](https://github.com/princeton-vl/CornerNet) 
- **[Survey]** Deep Learning for Generic Object Detection: A Survey (2018.09 *IJCV 2018*) [[Paper]](https://arxiv.org/abs/1809.02165)
- **[Training From Scratch]** Rethinking ImageNet Pre-training (2018.11) [[Paper]](https://arxiv.org/abs/1811.08883)


## Image Caption
- **[Show, Attend and Tell]** Show, Attend and Tell: Neural Image Caption Generation with Visual Attention(2015) [[Paper]](https://arxiv.org/abs/1502.03044) [[code_tensorflow]](https://github.com/yunjey/show-attend-and-tell) [[code_PyTorch]](https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Image-Captioning)
- Image Captioning with Semantic Attention(2016) [[Paper]](https://arxiv.org/abs/1603.03925) [[code]](https://github.com/chapternewscu/image-captioning-with-semantic-attention)
- Bottom-Up and Top-Down Attention for Image Captioning and Visual Question Answering(2017) [[Paper]](https://arxiv.org/abs/1707.07998) [[code]](https://github.com/peteanderson80/bottom-up-attention)
- Convolutional Image Captioning(2017) [[Paper]](https://arxiv.org/abs/1711.09151) [[code]](https://github.com/aditya12agd5/convcap)
- CNN+CNN: Convolutional Decoders for Image Captioning (2018) [[Paper]](https://arxiv.org/abs/1805.09019)


## Generative Adversarial Networks
- **[MUNIT]** Multimodal Unsupervised Image-to-Image Translation (2018.04 *ECCV 2018*) [[Paper]](https://arxiv.org/abs/1804.04732)  [[PyTorch]](https://github.com/NVlabs/MUNIT)
- **[SAGAN]** Self-Attention Generative Adversarial Networks(2018.05) [[Paper]](https://arxiv.org/abs/1805.08318) [[code_PyTorch]](https://github.com/heykeetae/Self-Attention-GAN) 
- **[DIRT]** Diverse Image-to-Image Translation via Disentangled Representations(2018.08) [[Paper]](https://arxiv.org/abs/1808.00948) [[code_PyTorch]](https://github.com/HsinYingLee/DRIT) <font color=Gray >(Notes: maybe suitable for unpaired MR-CT synthesis for human body)</font>
- **[VID2VID]** Video-to-Video Synthesis(2018.08) [[Paper]](https://arxiv.org/abs/1808.06601) [[code_PyTorch]](https://github.com/NVIDIA/vid2vid)
- **[BigGAN]** Large Scale GAN Training for High Fidelity Natural Image Synthesis (2018.09) [[Paper]](https://arxiv.org/abs/1809.11096) [[code]](https://github.com/AaronLeong/BigGAN-pytorch)
- **[styleGAN]** A Style-Based Generator Architecture for Generative Adversarial Networks (2018.12) [[Paper]](https://arxiv.org/abs/1812.04948) 

## Attention Mechanism
- Show, Attend and Tell: Neural Image Caption Generation with Visual Attention(2015.02) [[Paper]](https://arxiv.org/abs/1502.03044) [[code_TensorFlow]](https://github.com/yunjey/show-attend-and-tell) [[code_PyTorch]](https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Image-Captioning)
- Image Captioning with Semantic Attention(2016.03) [[Paper]](https://arxiv.org/abs/1603.03925) [[code]](https://github.com/chapternewscu/image-captioning-with-semantic-attention)
- Attention Is All You Need(2017.06) [[Paper]](https://arxiv.org/abs/1706.03762) [[code_PyTorch]](https://github.com/jadore801120/attention-is-all-you-need-pytorch) [[code_TensorFlow]](https://github.com/Kyubyong/transformer)
- Bottom-Up and Top-Down Attention for Image Captioning and Visual Question Answering(2017.07) [[Paper]](https://arxiv.org/abs/1707.07998) [[code]](https://github.com/peteanderson80/bottom-up-attention)
- Attention U-Net:Learning Where to Look for the Pancreas(2018.04) [[Paper]](https://arxiv.org/abs/1804.03999) [[code]](https://github.com/ozan-oktay/Attention-Gated-Networks)
- Self-Attention Generative Adversarial Networks(2018.05) [[Paper]](https://arxiv.org/abs/1805.08318) [[code_PyTorch]](https://github.com/heykeetae/Self-Attention-GAN)
(Notes: 将自我注意机制引入到GAN的生成模型中，对于图像的纹理和几何上的联系提供全局的注意使得生成的图像更加的合理)
- Learning Visual Question Answering by Bootstrapping Hard Attention (2018.08) [[Paper]](https://arxiv.org/abs/1808.00300) [[code]](https://github.com/gnouhp/PyTorch-AdaHAN) (Note: Hard-Attention)
- Pervasive Attention: 2D Convolutional Neural Networks for Sequence-to-Sequence Prediction(2018.08) [[Paper]](https://arxiv.org/abs/1808.03867) [[code]](https://github.com/elbayadm/attn2d)


## Natural Language Processing Related
- **[Pervasive Attention]** Pervasive Attention: 2D Convolutional Neural Networks for Sequence-to-Sequence Prediction(2018.08) [[Paper]](https://arxiv.org/abs/1808.03867) [[code]](https://github.com/elbayadm/attn2d)


## Medical Image Analysis
- **[U-Net]** U-Net: Convolutional Networks for Biomedical Image Segmentation (2015.5) [[Paper]](https://arxiv.org/abs/1505.04597) [[code]](https://github.com/milesial/Pytorch-UNet) [[code_Hsu_Implementation]](https://github.com/Hsuxu/carvana-pytorch-uNet)
- **[V-Net]** V-Net: Fully Convolutional Neural Networks for Volumetric Medical Image Segmentation (2016.6) [[Paper]](https://arxiv.org/abs/1606.04797) [[code]](https://github.com/mattmacy/vnet.pytorch) [[code_Hsu_implementation]](https://github.com/Hsuxu/Magic-VNet)
- **[Tversky loss]** Tversky loss function for image segmentation using 3D fully convolutional deep networks (2017.06) [[Paper]](https://arxiv.org/abs/1706.05721)
- **[TDN]** Automated Detection of Clinically Significant Prostate Cancer in mp-MRI Images based on an End-to-End Deep Neural Network (2018.07 *TMI 2018*) [[Paper]](https://ieeexplore.ieee.org/iel7/42/8353174/08245842.pdf)
- **[AnatomyNet]** AnatomyNet: Deep Learning for Fast and Fully Automated Whole-volume Segmentation of Head and Neck Anatomy (2018.08) [[Paper]](https://arxiv.org/abs/1808.05238)
- Improving Data Augmentation for Medical Image Segmentation (2018.12 *MIDL 2018*) [[Paper]](https://openreview.net/forum?id=rkBBChjiG)

## Other Applications

### Super Resolution
- Enhanced Deep Residual Networks for Single Image Super-Resolution (2017.7 CVPR-2017) [[Paper]](https://arxiv.org/abs/1707.02921) [[code_PyTorch]](https://github.com/thstkdgus35/EDSR-PyTorch)

## Training Skills
### Data Augmentation
- **[Pairing Samples]** Data Augmentation by Pairing Samples for Images Classification [[Paper]](https://arxiv.org/abs/1801.02929) 
- **[AutoAugment]** AutoAugment: Learning Augmentation Policies from Data [[Paper]](https://arxiv.org/abs/1805.09501) 
- **[Albumentations]** Albumentations: fast and flexible image augmentations [[Paper]](https://arxiv.org/abs/1809.06839)
- **[Pixel Augmentation]** Pixel Level Data Augmentation for Semantic Image Segmentation using Generative Adversarial Networks (2018.11) [[Paper]](https://arxiv.org/abs/1811.00174)
  
### Normalization
- Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift(2015.02) [[Paper]](https://arxiv.org/abs/1502.03167)
- Layer Normalization(2016.07) [[Paper]](https://arxiv.org/abs/1607.06450)
- Instance Normalization: The Missing Ingredient for Fast Stylization (2016.07) [[Paper]](https://arxiv.org/abs/1607.08022)
- Group Normalization (2018.03)  [[Paper]](https://arxiv.org/abs/1803.08494) [[code]](https://github.com/shaohua0116/Group-Normalization-Tensorflow)
- How Does Batch Normalization Help Optimization? (2018.05-NeurIPS18) [[Paper]](https://arxiv.org/abs/1805.11604)
- Differentiable Learning-to-Normalize via Switchable Normalization (2018.06) [[Paper]](https://arxiv.org/abs/1806.10779) [[code]](https://github.com/switchablenorms/Switchable-Normalization)

### Initialization
- Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification (2015.02) [[Paper]](https://arxiv.org/abs/1502.01852)
- Understanding the difficulty of training deep feedforward neural networks [[Paper]](http://proceedings.mlr.press/v9/glorot10a.html)
- Training Techniques--An overview of gradient descent optimization algorithms [[url]](http://ruder.io/optimizing-gradient-descent/index.html)
- Synchronized-BatchNorm [[code_PyTorch]](https://github.com/vacancy/Synchronized-BatchNorm-PyTorch) [[code_MXNet]](https://github.com/zhanghang1989/MXNet-Gluon-SyncBN)


## Dataset and Contest

### Dataset
- [PASCAL VOC 2012](http://host.robots.ox.ac.uk/pascal/VOC/)<!-- The main goal of this challenge is to recognize objects from a number of visual object classes in realistic scenes (i.e. not pre-segmented objects). It is fundamentally a supervised learning learning problem in that a training set of labelled images is provided. -->
- [Cityscapes](https://www.cityscapes-dataset.com/)<!-- Large-scale dataset that contains a diverse set of stereo video sequences recorded in street scenes from 50 different cities, with high quality pixel-level annotations of 5 000 frames in addition to a larger set of 20 000 weakly annotated frames. -->
- [NYUv2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html)<!-- The NYU-Depth V2 data set is comprised of video sequences from a variety of indoor scenes as recorded by both the RGB and Depth cameras from the Microsoft Kinect. -->
- [PASCAL-Context](https://cs.stanford.edu/~roozbeh/pascal-context/)<!-- This dataset is a set of additional annotations for PASCAL VOC 2010. It goes beyond the original PASCAL semantic segmentation task by providing annotations for the whole scene. The statistics section has a full list of 400+ labels. -->
- [SUNRGBD](http://rgbd.cs.princeton.edu/)<!-- Dataset is captured by four different sensors and contains 10,335 RGB-D images, at a similar scale as PASCAL VOC. The whole dataset is densely annotated and includes 146,617 2D polygons and 64,595 3D bounding boxes with accurate object orientations, as well as a 3D room layout and scene category for each image.  -->
- [ADE20k](http://groups.csail.mit.edu/vision/datasets/ADE20K/)<!-- ADE20K Dataset contains more than 20K scene-centric images exhaustively annotated with objects and object parts. Specifically, the benchmark is divided into 20K images for training, 2K images for validation, and another batch of held-out images for testing. There are totally 150 semantic categories included for evaluation, which include stuffs like sky, road, grass, and discrete objects like person, car, bed. Note that there are non-uniform distribution of objects occuring in the images, mimicking a more natural object occurrence in daily scene. -->
- [Grand Challenges in Biomedical Image Analysis](https://grand-challenge.org): 
<!-- Grand Challenges in Biomedical Image Analysis -->

### Contest
- [AI Challenger](https://challenger.ai/)