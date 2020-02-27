# Awesome-Tensorflow2 💛 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
基于Tensorflow2开发的优秀扩展包及项目
![Tensorflow](https://github.com/1044197988/Awesome-Tensorflow2/blob/master/Logo/Logo.jpg)

# Tensorflow2说明
2019 谷歌开发者大会于 9 月 10 日和 11 日在上海举办，大会将分享众多开发经验与工具。在第一天的 KeyNote 中，谷歌发布了很多开发工具新特性，并介绍而它们是如何构建更好的应用。值得注意的是，TensorFlow 刚刚发布了 2.0 RC01 版和 1.15，谷歌表示 1.15 是 1.x 的最后一次更新了。TensorFlow 2.0 相信大家已经非常熟悉了，它重点还是放在优化 Keras 和 Eager Execution 的能力，它希望通过这两种 API 简化整个开发流程。所以，未来的趋势肯定是Tensorflow2.0，在此我整合了许多的优秀库及项目到这个贡献库里。

# 提示
有些项目目前仍在进行中，将在未来支持Tensorflow2，这样的项目也包含在下面列表中。（意味着目前并不支持二版本）

# Contents <a name="TOC" />👈
<!-- MarkdownTOC depth=4 -->
* [Tutorials](#github-tutorials)
* [Model](#Model)
* [Projects](#Projects)
* [Other](#other)
<!-- /MarkdownTOC --> 

## Tutorials 💛💛💛💛💛<a name="github-tutorials" />
* [tensorflow.google.cn](https://tensorflow.google.cn/beta)
* [dragen1860/TensorFlow-2.x-Tutorials](https://github.com/dragen1860/TensorFlow-2.x-Tutorials)
* [dragen1860/Deep-Learning-with-TensorFlow-book](https://github.com/dragen1860/Deep-Learning-with-TensorFlow-book)
* [czy36mengfei/tensorflow2_tutorials_chinese](https://github.com/czy36mengfei/tensorflow2_tutorials_chinese)
* [yusugomori/deeplearning-tf2](https://github.com/yusugomori/deeplearning-tf2)
* [YunYang1994/TensorFlow2.0-Examples](https://github.com/YunYang1994/TensorFlow2.0-Examples)

## Model 💛💛💛💛💛<a name="Model" />
### Classification 分类
* [tensorflow/models](https://github.com/tensorflow/models)<br>
该存储库包含在TensorFlow中实现的许多不同模型。<br>
* [1044197988/TF.Keras-Commonly-used-models](https://github.com/1044197988/TF.Keras-Commonly-used-models)<br>
该贡献库为我整理的一些常用的分类、分割模型，包含分割的一些指标、损失函数，但不提供预训练模型的载入。分割模型列表如下：<br>
![Segmentation](https://github.com/1044197988/Awesome-Tensorflow2/blob/master/Logo/2.png)

#### Large library 大型库
* [qubvel/classification_models](https://github.com/qubvel/classification_models#architectures)

#### Model 模型
* [qubvel/efficientnet](https://github.com/qubvel/efficientnet)
* [nsarang/MnasNet](https://github.com/nsarang/MnasNet)
* [calmisential/MobileNetV3_TensorFlow2](https://github.com/calmisential/MobileNetV3_TensorFlow2)
* [calmisential/TensorFlow2.0_ResNet](https://github.com/calmisential/TensorFlow2.0_ResNet)
* [calmisential/TensorFlow2.0_InceptionV3](https://github.com/calmisential/TensorFlow2.0_InceptionV3)
* [calmisential/TensorFlow2.0_Image_Classification](https://github.com/calmisential/TensorFlow2.0_Image_Classification)

##### Capsnet model 胶囊网络模型
* [prabhuomkar/hicr-capsnet](https://github.com/prabhuomkar/hicr-capsnet)

##### Semi-supervised learning 半监督学习
* [ntozer/mixmatch-tensorflow2.0](https://github.com/ntozer/mixmatch-tensorflow2.0)
* [schatty/prototypical-networks-tf](https://github.com/schatty/prototypical-networks-tf)

##### Generative-models and Self encoder 生成模型和自编码
* [timsainb/tensorflow2-generative-models](https://github.com/timsainb/tensorflow2-generative-models)
* [DequanZhu/GANs-collections-tf2.0_keras-eager_mode](https://github.com/DequanZhu/GANs-collections-tf2.0_keras-eager_mode)
* [Hourout/GAN-keras](https://github.com/Hourout/GAN-keras)
* [Net-Mist/style-transfer-tf2](https://github.com/Net-Mist/style-transfer-tf2)
* [mnicnc404/CartoonGan-tensorflow](https://github.com/mnicnc404/CartoonGan-tensorflow)
* [ialhashim/StyleGAN-Tensorflow2](https://github.com/ialhashim/StyleGAN-Tensorflow2)
* [leafinity/SAGAN-tensorflow2.0](https://github.com/leafinity/SAGAN-tensorflow2.0)
* [Lornatang/TensorFlow2-GAN](https://github.com/Lornatang/TensorFlow2-GAN)
* [ppooiiuuyh/SinGAN-tensorflow2.0](https://github.com/ppooiiuuyh/SinGAN-tensorflow2.0)
* [hollygrimm/tf2-cyclegan](https://github.com/hollygrimm/tf2-cyclegan)
* [drewszurko/tensorflow-WGAN-GP](https://github.com/drewszurko/tensorflow-WGAN-GP)
* [mgmk2/StyleGAN](https://github.com/mgmk2/StyleGAN)
* [LynnHo/CycleGAN-Tensorflow-2](https://github.com/LynnHo/CycleGAN-Tensorflow-2)

### Segmentation 分割
#### Large library 大型库
* [qubvel/segmentation_models](https://github.com/qubvel/segmentation_models)

#### Model 模型 
* [srihari-humbarwadi/FastFCN_TF2.0](https://github.com/srihari-humbarwadi/FastFCN_TF2.0)
* [bonlime/keras-deeplab-v3-plus](https://github.com/bonlime/keras-deeplab-v3-plus)
* [matterport/Mask_RCNN](https://github.com/matterport/Mask_RCNN)
* [srihari-humbarwadi/DeepLabV3_Plus-Tensorflow2.0](https://github.com/srihari-humbarwadi/DeepLabV3_Plus-Tensorflow2.0)

### Super resolution 超分辨率
#### Model 模型
* [krasserm/super-resolution](https://github.com/krasserm/super-resolution)<br>
包含以下模型：<br>
用于单图像超分辨率（EDSR）的增强型深度残留网络，是NTIRE 2017超分辨率挑战赛的冠军。<br>
广泛激活以实现高效，准确的图像超分辨率（WDSR），是NTIRE 2018超分辨率挑战赛（真实轨道）的获胜者。<br>
使用生成对抗网络（SRGAN）的逼真的单图像超分辨率。<br>
* [HasnainRaz/Fast-SRGAN](https://github.com/HasnainRaz/Fast-SRGAN)
* [gs18113/ESPCN-TensorFlow2](https://github.com/gs18113/ESPCN-TensorFlow2)
### Object detection 目标检测
#### Model 模型
* [zzh8829/yolov3-tf2](https://github.com/zzh8829/yolov3-tf2)
* [srihari-humbarwadi/YOLOv1-TensorFlow2.0](https://github.com/srihari-humbarwadi/YOLOv1-TensorFlow2.0)
* [cjpurackal/m2det-tf](https://github.com/cjpurackal/m2det-tf)
* [reliefs/mtcnn-tensorflow2](https://github.com/reliefs/mtcnn-tensorflow2)
* [1044197988/Centernet-Tensorflow2.0](https://github.com/1044197988/Centernet-Tensorflow2.0)
* [calmisential/TensorFlow2.0_FasterRCNN](https://github.com/calmisential/TensorFlow2.0_FasterRCNN)
* [Stick-To/Object-Detection-Tensorflow2](https://github.com/Stick-To/Object-Detection-Tensorflow2)
* [hux999/tf-fcos](https://github.com/hux999/tf-fcos)

### NLP Model 自然语言处理模型
#### Large library 大型库
* [tensorflow/tensor2tensor](https://github.com/tensorflow/tensor2tensor)<br>
Tensor2Tensor或简称T2T，是一个深度学习模型和数据集的库，旨在使深度学习更易于访问并加速ML研究。Google Brain团队和用户社区的研究人员和工程师积极使用和维护T2T 。<br>
* [huggingface/transformers](https://github.com/huggingface/transformers)<br>
TensorFlow 2.0和PyTorch的最新自然语言处理，（以前称为pytorch-transformers和pytorch-pretrained-bert）提供用于自然语言理解（NLU）和自然语言生成（NLG）的最新通用架构（BERT，GPT-2，RoBERTa，XLM，DistilBert，XLNet ...） ）包含超过32种以100多种语言编写的预训练模型，以及TensorFlow 2.0和PyTorch之间的深层互操作性。<br>

#### Model 模型
* [codertimo/BERT-tf2](https://github.com/codertimo/BERT-tf2)
* [ShaneTian/TextCNN](https://github.com/ShaneTian/TextCNN)
* [strutive07/transformer-tensorflow2.0](https://github.com/strutive07/transformer-tensorflow2.0)
* [thisisiron/nmt-attention-tf](https://github.com/thisisiron/nmt-attention-tf)
* [kpe/bert-for-tf2](https://github.com/kpe/bert-for-tf2)
* [akanyaani/gpt-2-tensorflow2.0](https://github.com/akanyaani/gpt-2-tensorflow2.0)

### Point Model 点云模型
* [dgriffiths3/pointnet2-tensorflow2](https://github.com/dgriffiths3/pointnet2-tensorflow2)

## Projects 💛💛💛💛💛<a name="Projects" />
### 视觉较大项目
* [giovgiac/neptune](https://github.com/giovgiac/neptune)
### 分割
* [Shathe/Semantic-Segmentation-Tensorflow-2](https://github.com/Shathe/Semantic-Segmentation-Tensorflow-2)
* [1044197988/Semantic-segmentation-of-remote-sensing-images](https://github.com/1044197988/Semantic-segmentation-of-remote-sensing-images)
### NLP
* [jason9693/MusicTransformer-tensorflow2.0](https://github.com/jason9693/MusicTransformer-tensorflow2.0)
* [xingchensong/Speech-Transformer-tf2.0](https://github.com/xingchensong/Speech-Transformer-tf2.0)
* [drukka/command-words-recognition-keras](https://github.com/drukka/command-words-recognition-keras)
* [bryanlimy/tf2-transformer-chatbot](https://github.com/bryanlimy/tf2-transformer-chatbot)
* [gibrano/chatbot](https://github.com/gibrano/chatbot)
### 目标检测
* [liushuan/YOLO-V3-Tensorflow2.0-Face-Detect-via-Wider-Face](https://github.com/liushuan/YOLO-V3-Tensorflow2.0-Face-Detect-via-Wider-Face)
* [burnpiro/tiny-face-detection-tensorflow2](https://github.com/burnpiro/tiny-face-detection-tensorflow2)
### 验证码识别
* [ybsdegit/captcha_keras](https://github.com/ybsdegit/captcha_keras)
### 文字检测、识别
* [RaidasGrisk/tf2-fots](https://github.com/RaidasGrisk/tf2-fots)
* [RaidasGrisk/tf2-crnn](https://github.com/RaidasGrisk/tf2-crnn)
### 人脸识别
* [DequanZhu/FaceNet-and-FaceLoss-collections-tensorflow2.0](https://github.com/DequanZhu/FaceNet-and-FaceLoss-collections-tensorflow2.0)
* [Fei-Wang/insightface](https://github.com/Fei-Wang/insightface)
* [610265158/Peppa_Pig_Face_Engine](https://github.com/610265158/Peppa_Pig_Face_Engine)
* [610265158/faceboxes-tensorflow](https://github.com/610265158/faceboxes-tensorflow)


## Other 💛💛💛💛💛<a name="Other" />
### 脚本
* [hacker-lin/train_test_valid_split](https://github.com/hacker-lin/train_test_valid_split)
* [ravindrabharathi/tf_utils](https://github.com/ravindrabharathi/tf_utils)
### 解释性工具
* [sicara/tf-explain](https://github.com/sicara/tf-explain)
### 推荐系统和CTR预测模型
* [JianzhouZhan/Awesome-RecSystem-Models](https://github.com/JianzhouZhan/Awesome-RecSystem-Models)
* [cheungdaven/DeepRec](https://github.com/cheungdaven/DeepRec)
* [Hourout/CTR-keras](https://github.com/Hourout/CTR-keras)
* [hojinYang/recsys-implementation.tensorflow2](https://github.com/hojinYang/recsys-implementation.tensorflow2)
* [SSSxCCC/Recommender-System](https://github.com/SSSxCCC/Recommender-System)
### 用于分布式培训，评估，模型选择和快速原型制作
* [zurutech/ashpy](https://github.com/zurutech/ashpy)
### AutoML
* [keras-team/keras-tuner](https://github.com/keras-team/keras-tuner)
* [keras-team/autokeras](https://github.com/keras-team/autokeras)
* [tensorflow/adanet](https://github.com/tensorflow/adanet)
### 元学习
* [siavash-khodadadeh/MetaLearning-TF2.0](https://github.com/siavash-khodadadeh/MetaLearning-TF2.0)
### 强化学习
* [danaugrs/huskarl](https://github.com/danaugrs/huskarl)
* [keiohta/tf2rl](https://github.com/keiohta/tf2rl)
### 神经结构化学习
* [neural-structured-learning](https://github.com/tensorflow/neural-structured-learning)
### 强大的扩展
* [tensorflow/addons](https://github.com/tensorflow/addons)
### 迭代矩阵平方根归一化网络（称为快速MPN-COV），该网络非常有效，适合大规模数据集
* [XuChunqiao/Tensorflow-Fast-MPNCOV](https://github.com/XuChunqiao/Tensorflow-Fast-MPNCOV)
### TF-GAN是用于培训和评估生成对抗网络GAN的轻量级库
* [tensorflow/gan](https://github.com/tensorflow/gan)
### 官方数据集包
* [tensorflow/datasets](https://github.com/tensorflow/datasets)
### NLP
* [tensorflow/text](https://github.com/tensorflow/text)
### 大型基于TF2的封装扩展库
* [tensorlayer/tensorlayer](https://github.com/tensorlayer/tensorlayer)
### TF2项目模板
* [michaeltinsley/TF2-Project-Template](https://github.com/michaeltinsley/TF2-Project-Template)
### GCN图神经网络
* [breadbread1984/GCN-tf2.0](https://github.com/breadbread1984/GCN-tf2.0)
### RBF径向基
* [PetraVidnerova/rbf_for_tf2](https://github.com/PetraVidnerova/rbf_for_tf2)
### 新型的高性能可解释的深表格式数据学习网络TabNet
* [titu1994/tf-TabNet](https://github.com/titu1994/tf-TabNet)
### 优化器
* [OverLordGoldDragon/keras-adamw](https://github.com/OverLordGoldDragon/keras-adamw)
### 用于单通道语音分离的双路径RNN
* [sp-uhh/dual-path-rnn](https://github.com/sp-uhh/dual-path-rnn)
### 新型数据处理技术
* [AakashKumarNain/AugMix_TF2](https://github.com/AakashKumarNain/AugMix_TF2)
### 使用tensorflow 2构建的多任务学习包
* [AmazaspShumik/mtlearn](https://github.com/AmazaspShumik/mtlearn)
### TensowFlow2.0上的CBAM（卷积块注意模块）实现
* [zhangkaifang/CBAM-TensorFlow2.0](https://github.com/zhangkaifang/CBAM-TensorFlow2.0)
### Spektral是一个基于Keras API和TensorFlow 2的用于图深度学习的Python库。该项目的主要目标是提供一个简单而灵活的框架来创建图神经网络（GNN）。
* [danielegrattarola/spektral](https://github.com/danielegrattarola/spektral)
