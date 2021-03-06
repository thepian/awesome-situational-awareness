# Awesome Situational Awareness: [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of pieces making up situational awareness and related area (e.g. object recognition, pose estimation) resources, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision).

If an entity is to have situational awareness it must recognise what is currently happening around it in a general sense. 
It must recognise the situation and its component parts.
- Actors present
- Ongoing actions
- Objects implying a role


## Contents
 - [Awesome Lists](#awesome-lists)
 - [Action Recognition and Video Understanding](#action-recognition-and-video-understanding)
 - [Object Recognition](#object-recognition)
 - [Pose Estimation](#pose-estimation)
 - [Visual Relationship Detection](#visual-relationship-detection) [Dataset](#dataset)
 - [Dataset Preparation](#dataset-preparation)
 - [Tools](#tools)
 
## Awesome Lists

(For a [Full List]())

 - [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
 - [Awesome Deep Vision](https://github.com/kjw0612/awesome-deep-vision)
 - [Awesome Domain Adaptation](https://github.com/zhaoxin94/awesome-domain-adaptation)
 - [Awesome Object Detection](https://github.com/amusi/awesome-object-detection)
 - [Awesome Action Recognition](https://github.com/jinwchoi/awesome-action-recognition)
 - [Awesome Scene Understanding](https://github.com/bertjiazheng/awesome-scene-understanding)
 - [Awesome Adversarial Machine Learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning)
 - [Awesome Adversarial Deep Learning](https://github.com/chbrian/awesome-adversarial-examples-dl)
 - [Awesome Face](https://github.com/polarisZhao/awesome-face)
 - [Awesome Face Recognition](https://github.com/ChanChiChoi/awesome-Face_Recognition)
 - [Awesome Human Pose Estimation](https://github.com/wangzheallen/awesome-human-pose-estimation)
 - [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets)
 - [Awesome Dataset Tools](https://github.com/jsbroks/awesome-dataset-tools)
 - [Awesome Mobile Machine Learning](https://github.com/fritzlabs/Awesome-Mobile-Machine-Learning)
 - [Awesome Machine Learning Interpretability](https://github.com/jphall663/awesome-machine-learning-interpretability)
 - [Awesome Production Machine Learning](https://github.com/EthicalML/awesome-production-machine-learning)
 - [Awesome Deep HDR](https://github.com/vinthony/awesome-deep-hdr)
 - [Awesome Video Generation](https://github.com/matthewvowels1/Awesome-Video-Generation)
 - [Awesome GAN applications](https://github.com/nashory/gans-awesome-applications)
 - [Awesome Generative Modeling](https://github.com/zhoubolei/awesome-generative-modeling)
 - [Awesome Image Classification](https://github.com/weiaicunzai/awesome-image-classification)
 - [Awesome Deep Learning](https://github.com/ChristosChristofidis/awesome-deep-learning)
 - [Awesome Deep Learning for Tracking and Detection](https://github.com/abhineet123/Deep-Learning-for-Tracking-and-Detection)
 - [Awesome Human Pose Estimation](https://github.com/wangzheallen/awesome-human-pose-estimation)
 - [Awesome Deep Learning for Video Analysis](https://github.com/HuaizhengZhang/Awsome-Deep-Learning-for-Video-Analysis)
 - [Awesome Visual Transformer](https://github.com/dk-liang/Awesome-Visual-Transformer)
 - [Awesome Embodied Vision](https://github.com/ChanganVR/awesome-embodied-vision)
 - [Awesome Anomaly Detection](https://github.com/hoya012/awesome-anomaly-detection)
 - [Awesome Makeup Transfer](https://github.com/thaoshibe/awesome-makeup-transfer)
 - [Awesome Learning with Label Noise](https://github.com/subeeshvasu/Awesome-Learning-with-Label-Noise)
 - [Awesome Deblurring](https://github.com/subeeshvasu/Awesome-Deblurring)
 - [Awsome Deep Geometry Learning](https://github.com/subeeshvasu/Awsome_Deep_Geometry_Learning)
 - [Awesome Image Distortion Correction](https://github.com/subeeshvasu/Awesome-Image-Distortion-Correction)
 - [Awsome GAN Training](https://github.com/subeeshvasu/Awsome-GAN-Training)

## Action Recognition and Video Understanding

### Summary posts
* [Deep Learning for Videos: A 2018 Guide to Action Recognition](http://blog.qure.ai/notes/deep-learning-for-videos-action-recognition-review) - Summary of major landmark action recognition research papers till 2018
* [Literature Survey: Human Action Recognition](https://towardsdatascience.com/literature-survey-human-action-recognition-cc7c3818a99a) - Brief human action recognition literature survey of work published between 2014 and 2019.


### Video Representation
* [Why Can't I Dance in the Mall? Learning to Mitigate Scene Bias in Action Recognition](https://papers.nips.cc/paper/8372-why-cant-i-dance-in-the-mall-learning-to-mitigate-scene-bias-in-action-recognition.pdf) - J. Choi et al., NeurIPS2019. [[project web]](http://chengao.vision/SDN/) [[code]](https://github.com/vt-vl-lab/SDN) [[arXiv]](https://arxiv.org/abs/1912.05534)
* [SlowFast Networks for Video Recognition](https://arxiv.org/abs/1812.03982) - C. Feichtenhofer et al., ICCV2019. [[code]](https://github.com/facebookresearch/SlowFast)
* [Large-scale weakly-supervised pre-training for video action recognition](https://research.fb.com/wp-content/uploads/2019/05/Large-scale-weakly-supervised-pre-training-for-video-action-recognition.pdf?) - D. Ghadiyaram et al., arXiv2019.
* [Video Classification with Channel-Separated Convolutional Networks](https://arxiv.org/pdf/1904.02811.pdf) - D. Tran et al., arXiv2019.
* [DistInit: Learning Video Representations without a Single Labeled Video](https://arxiv.org/pdf/1901.09244.pdf) - R. Girdhar et al., arXiv2019.
* [SCSampler: Sampling Salient Clips from Video for Efficient Action Recognition](https://arxiv.org/pdf/1904.04289.pdf) - B. Korbar et al., arXiv2019.
* [Video Action Transformer Network](https://arxiv.org/pdf/1812.02707.pdf) - R. Girdhar et al., CVPR2019. [[project web]](https://rohitgirdhar.github.io/ActionTransformer/)
* [Learning Correspondence from the Cycle-consistency of Time](https://arxiv.org/pdf/1903.07593.pdf) - X. Wang et al., CVPR2019. [[code]](https://github.com/xiaolonw/TimeCycle) [[project web]](https://ajabri.github.io/timecycle/)
* [Representation Flow for Action Recognition](https://arxiv.org/pdf/1810.01455.pdf) - AJ. Piergiovanni and M. S. Ryoo et al., CVPR2019.
* [Collaborative Spatiotemporal Feature Learning for Video Action Recognition](https://arxiv.org/pdf/1903.01197.pdf) - C. Li et al., CVPR2019.
* [Learning Video Representations from Correspondence Proposals](https://arxiv.org/pdf/1905.07853.pdf) - X. Liu et al., CVPR2019.
* [Timeception for Complex Action Recognition](https://arxiv.org/pdf/1812.01289.pdf) - N. Hussein et al., CVPR2019.
* [The Visual Centrifuge: Model-Free Layered Video Representations](https://arxiv.org/pdf/1812.01461.pdf) - J.-B. Alayrac et al., CVPR2019.
* [Long-Term Feature Banks for Detailed Video Understanding](https://arxiv.org/pdf/1812.05038.pdf) - C.-Y. Wu. et al., CVPR2019. [[code]](https://github.com/facebookresearch/video-long-term-feature-banks/)
* [Temporal Relational Reasoning in Videos](https://arxiv.org/pdf/1711.08496.pdf) - B. Zhou et al., ECCV2018. [[code]](https://github.com/metalbubble/TRN-pytorch) [[project web]](http://relation.csail.mit.edu/)
* [Action Recognition Zoo](https://github.com/coderSkyChen/Action_Recognition_Zoo) -
Codes for popular action recognition models, written based on pytorch, verified on the something-something dataset.
* [Videos as Space-Time Region Graphs](https://arxiv.org/pdf/1806.01810.pdf) - X. Wang and A. Gupta, ECCV2018.
* [Can Spatiotemporal 3D CNNs Retrace the History of 2D CNNs and ImageNet?](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hara_Can_Spatiotemporal_3D_CVPR_2018_paper.pdf) - K. Hara et al., CVPR2019. [[code]](https://github.com/kenshohara/3D-ResNets-PyTorch)
* [A Closer Look at Spatiotemporal Convolutions for Action Recognition](https://arxiv.org/pdf/1711.11248.pdf) - D. Tran et al., CVPR2018. [[code]](https://github.com/facebookresearch/R2Plus1D) [[PyTorch]](https://github.com/irhumshafkat/R2Plus1D-PyTorch)
* [Attend and Interact: Higher-Order Object Interactions for Video Understanding](https://arxiv.org/abs/1711.06330) - CY. Ma et al., CVPR 2018.
* [Non-Local Neural Networks](https://arxiv.org/abs/1711.07971) - X. Wang et al., CVPR2018. [[code]](https://github.com/facebookresearch/video-nonlocal-net)
* [Rethinking Spatiotemporal Feature Learning For Video Understanding](https://arxiv.org/pdf/1712.04851.pdf) - S. Xie et al., arXiv2017.
* [ConvNet Architecture Search for Spatiotemporal Feature Learning](https://arxiv.org/abs/1708.05038) - D. Tran et al, arXiv2017. Note: Aka Res3D. [[code]](https://github.com/facebook/C3D): In the repository, C3D-v1.1 is the Res3D implementation.
* [Learning Spatio-Temporal Representation with Pseudo-3D Residual Networks](http://openaccess.thecvf.com/content_ICCV_2017/papers/Qiu_Learning_Spatio-Temporal_Representation_ICCV_2017_paper.pdf) - Z. Qui et al, ICCV2017. [[code]](https://github.com/ZhaofanQiu/pseudo-3d-residual-networks)
* [Quo Vadis, Action Recognition? A New Model and the Kinetics Dataset](https://arxiv.org/pdf/1705.07750.pdf) - J. Carreira et al, CVPR2017. [[code]](https://github.com/deepmind/kinetics-i3d)[[PyTorch code]](https://github.com/hassony2/kinetics_i3d_pytorch), [[another PyTorch code]](https://github.com/piergiaj/pytorch-i3d)
* [Learning Spatiotemporal Features with 3D Convolutional Networks](http://vlg.cs.dartmouth.edu/c3d/c3d_video.pdf) - D. Tran et al, ICCV2015. [[the official Caffe code]](https://github.com/facebook/C3D) [[project web]](http://vlg.cs.dartmouth.edu/c3d/) Note: Aka C3D. [[Python Wrapper]](https://github.com/chuckcho/C3D/tree/python-wrapper) Note that the official caffe does not support python wrapper. [[TensorFlow]](https://github.com/hx173149/C3D-tensorflow), [[TensorFlow + Keras]](https://github.com/axon-research/c3d-keras), [[Another TensorFlow Implemetation]](https://github.com/frankgu/C3D-tensorflow.git), [[Keras C3D Project web]](https://imatge.upc.edu/web/resources/c3d-model-keras-trained-over-sports-1m): [[Keras code]](https://gist.github.com/albertomontesg/d8b21a179c1e6cca0480ebdf292c34d2), [[Pretrained weights]](https://www.dropbox.com/s/ypiwalgtlrtnw8b/c3d-sports1M_weights.h5?dl=0).
* [Deep Temporal Linear Encoding Networks](https://arxiv.org/abs/1611.06678) - A. Diba et al, CVPR2017.
* [Temporal Convolutional Networks: A Unified Approach to Action Segmentation and Detection](https://arxiv.org/pdf/1611.05267.pdf) - C. Lea et al, CVPR 2017. [[code]](https://github.com/colincsl/TemporalConvolutionalNetworks)
* [Long-term Temporal Convolutions](https://arxiv.org/pdf/1604.04494v1.pdf) - G. Varol et al, TPAMI2017. [[project web]](http://www.di.ens.fr/willow/research/ltc/) [[code]](https://github.com/gulvarol/ltc)
* [Temporal Segment Networks: Towards Good Practices for Deep Action Recognition](https://arxiv.org/pdf/1608.00859.pdf) - L. Wang et al, arXiv 2016. [[code]](https://github.com/yjxiong/temporal-segment-networks)
* [Convolutional Two-Stream Network Fusion for Video Action Recognition](https://arxiv.org/pdf/1604.06573.pdf) - C. Feichtenhofer et al, CVPR2016. [[code]](https://github.com/feichtenhofer/twostreamfusion)
* [Two-Stream Convolutional Networks for Action Recognition in Videos](http://www.robots.ox.ac.uk/~vgg/publications/2014/Simonyan14b/simonyan14b.pdf.pdf) - K. Simonyan and A. Zisserman, NIPS2014.

#### Useful Code Repos on Video Representation Learning
* [[3D ResNet PyTorch]](https://github.com/kenshohara/3D-ResNets-PyTorch)
* [[PyTorch Video Research]](https://github.com/gsig/PyVideoResearch)
* [[M-PACT: Michigan Platform for Activity Classification in Tensorflow]](https://github.com/MichiganCOG/M-PACT)
* [[Inflated models on PyTorch]](https://github.com/hassony2/inflated_convnets_pytorch)
* [[I3D models transfered from Tensorflow to PyTorch]](https://github.com/hassony2/kinetics_i3d_pytorch)
* [[A Two Stream Baseline on Kinectics dataset]](https://github.com/gurkirt/2D-kinectics)
* [[MMAction]](https://github.com/open-mmlab/mmaction)
* [[PySlowFast]](https://github.com/facebookresearch/slowfast)
* [[Decord]](https://github.com/dmlc/decord) Efficient video reader for python
* [[I3D models converted from Tensorflow to Core ML]](https://github.com/lukereichold/VisualActionKit)
* [[Extract frame and optical-flow from videos, #docker]](https://github.com/epic-kitchens/epic-kitchens-100-annotations/blob/master/README.md#erratum)
* [[NVIDIA-DALI, video loading pipelines]](https://docs.nvidia.com/deeplearning/dali/user-guide/docs/examples/sequence_processing/video/video_reader_label_example.html)
* [[NVIDIA optical-flow SDK]](https://developer.nvidia.com/opticalflow-sdk)

### Action Classification
* [Neural Graph Matching Networks for Fewshot 3D Action Recognition](http://openaccess.thecvf.com/content_ECCV_2018/papers/Michelle_Guo_Neural_Graph_Matching_ECCV_2018_paper.pdf) - M. Guo et al., ECCV2018.
* [Temporal 3D ConvNets using Temporal Transition Layer](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w19/Diba_Temporal_3D_ConvNets_CVPR_2018_paper.pdf) - A. Diba et al., CVPRW2018.
* [Temporal 3D ConvNets: New Architecture and Transfer Learning for Video Classification](https://arxiv.org/abs/1711.08200) - A. Diba et al., arXiv2017.
* [Attentional Pooling for Action Recognition](https://arxiv.org/abs/1711.01467) - R. Girdhar and D. Ramanan, NIPS2017. [[code]](https://github.com/rohitgirdhar/AttentionalPoolingAction)
* [Fully Context-Aware Video Prediction](https://arxiv.org/pdf/1710.08518v1.pdf) - Byeon et al, arXiv2017.
* [Hidden Two-Stream Convolutional Networks for Action Recognition](https://arxiv.org/pdf/1704.00389.pdf) - Y. Zhu et al, arXiv2017. [[code]](https://github.com/bryanyzhu/Hidden-Two-Stream)
* [Dynamic Image Networks for Action Recognition](https://www.robots.ox.ac.uk/~vgg/publications/2016/Bilen16a/bilen16a.pdf) - H. Bilen et al, CVPR2016. [[code]](https://github.com/hbilen/dynamic-image-nets) [[project web]](http://www.robots.ox.ac.uk/~vgg/publications/2016/Bilen16a/)
* [Long-term Recurrent Convolutional Networks for Visual Recognition and Description](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Donahue_Long-Term_Recurrent_Convolutional_2015_CVPR_paper.pdf) - J. Donahue et al, CVPR2015. [[code]](https://github.com/LisaAnne/lisa-caffe-public/tree/lstm_video_deploy) [[project web]](http://jeffdonahue.com/lrcn/)
* [Describing Videos by Exploiting Temporal Structure](http://arxiv.org/pdf/1502.08029v4.pdf) - L. Yao et al, ICCV2015. [[code]](https://github.com/yaoli/arctic-capgen-vid) note: from the same group of RCN paper “Delving Deeper into Convolutional Networks for Learning Video Representations"
* [Two-Stream SR-CNNs for Action Recognition in Videos](http://wanglimin.github.io/papers/ZhangWWQW_CVPR16.pdf) - L. Wang et al, BMVC2016.
* [Real-time Action Recognition with Enhanced Motion Vector CNNs](http://arxiv.org/abs/1604.07669) - B. Zhang et al, CVPR2016. [[code]](https://github.com/zbwglory/MV-release)
* [Action Recognition with Trajectory-Pooled Deep-Convolutional Descriptors](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Wang_Action_Recognition_With_2015_CVPR_paper.pdf) - L. Wang et al, CVPR2015. [[code]](https://github.com/wanglimin/TDD)

### Skeleton-Based Action Classification
* [Actional-Structural Graph Convolutional Networks for Skeleton-Based Action Recognition](http://openaccess.thecvf.com/content_CVPR_2019/html/Li_Actional-Structural_Graph_Convolutional_Networks_for_Skeleton-Based_Action_Recognition_CVPR_2019_paper.html) - M. Li et al., CVPR2019.
* [An Attention Enhanced Graph Convolutional LSTM Network for Skeleton-Based Action Recognition](https://arxiv.org/abs/1902.09130) - C. Si et al., CVPR2019.
* [View Adaptive Neural Networks for High Performance Skeleton-Based Human Action Recognition](https://ieeexplore.ieee.org/abstract/document/8630687) - P. Zhang et al., TPAMI2019.
* [Spatial Temporal Graph Convolutional Networks for Skeleton-Based Action Recognition](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPaper/17135) - S. Yan et al., AAAI2018. [[code]](https://github.com/yysijie/st-gcn)
* [Deep Progressive Reinforcement Learning for Skeleton-Based Action Recognition](http://openaccess.thecvf.com/content_cvpr_2018/html/Tang_Deep_Progressive_Reinforcement_CVPR_2018_paper.html) - Y. Tang et al., CVPR2018.
* [Co-occurrence Feature Learning from Skeleton Data for Action Recognition and Detection with Hierarchical Aggregation](https://dl.acm.org/citation.cfm?id=3304527) - C. Li et al., IJCAI2018.
* [Part-based Graph Convolutional Network for Action Recognition](http://bmvc2018.org/contents/papers/1003.pdf) - K. Thakkar et al., BMVC2018.

### Temporal Action Detection
* [Rethinking the Faster R-CNN Architecture for Temporal Action Localization](https://arxiv.org/pdf/1804.07667v1.pdf) - Yu-Wei Chao et al., CVPR2018
* [Weakly Supervised Action Localization by Sparse Temporal Pooling Network](https://arxiv.org/pdf/1712.05080) - Phuc Nguyen et al., CVPR 2018
* [Temporal Deformable Residual Networks for Action Segmentation in Videos](http://web.engr.oregonstate.edu/~sinisa/research/publications/cvpr18_TDRN.pdf) - P. Lei and S. Todrovic., CVPR2018.
* [End-to-End, Single-Stream Temporal Action Detection in Untrimmed Videos](http://vision.stanford.edu/pdf/buch2017bmvc.pdf) - Shayamal Buch et al., BMVC 2017 [[code]](https://github.com/shyamal-b/ss-tad)
* [Cascaded Boundary Regression for Temporal Action Detection](https://arxiv.org/abs/1705.01180) - Jiyang Gao et al., BMVC 2017 [[code](https://github.com/jiyanggao/CBR)]
* [Temporal Tessellation: A Unified Approach for Video Analysis](http://openaccess.thecvf.com/content_ICCV_2017/papers/Kaufman_Temporal_Tessellation_A_ICCV_2017_paper.pdf) - Kaufman et al., ICCV2017. [[code]](https://github.com/dot27/temporal-tessellation)
* [Temporal Action Detection with Structured Segment Networks](http://cn.arxiv.org/pdf/1704.06228v2) - Y. Zhao et al., ICCV2017. [[code]](https://github.com/yjxiong/action-detection) [[project web]](http://yjxiong.me/others/ssn/)
* [Temporal Context Network for Activity Localization in Videos](https://arxiv.org/pdf/1708.02349.pdf) - X. Dai et al., ICCV2017.
* [Detecting the Moment of Completion: Temporal Models for Localising Action Completion](https://arxiv.org/abs/1710.02310) - F. Heidarivincheh et al., arXiv2017.
* [CDC: Convolutional-De-Convolutional Networks for Precise Temporal Action Localization in Untrimmed Videos](https://arxiv.org/abs/1703.01515/) - Z. Shou et al, CVPR2017. [[code]](https://bitbucket.org/columbiadvmm/cdc)
* [SST: Single-Stream Temporal Action Proposals](http://vision.stanford.edu/pdf/buch2017cvpr.pdf) - S. Buch et al, CVPR2017. [[code]](https://github.com/shyamal-b/sst)
* [R-C3D: Region Convolutional 3D Network for Temporal Activity Detection](https://arxiv.org/abs/1703.07814) - H. Xu et al, arXiv2017. [[code]](https://github.com/VisionLearningGroup/R-C3D) [[project web]](http://ai.bu.edu/r-c3d/) [[PyTorch]](https://github.com/sunnyxiaohu/R-C3D.pytorch)
* [DAPs: Deep Action Proposals for Action Understanding](https://ivul.kaust.edu.sa/Documents/Publications/2016/DAPs%20Deep%20Action%20Proposals%20for%20Action%20Understanding.pdf) - V. Escorcia et al, ECCV2016. [[code]](https://github.com/escorciav/daps) [[raw data]](https://github.com/escorciav/daps)
* [Online Action Detection using Joint Classification-Regression Recurrent Neural Networks](https://arxiv.org/abs/1604.05633) - Y. Li et al, ECCV2016. Noe: RGB-D Action Detection
* [Temporal Action Localization in Untrimmed Videos via Multi-stage CNNs](http://dvmmweb.cs.columbia.edu/files/dvmm_scnn_paper.pdf) - Z. Shou et al, CVPR2016. [[code]](https://github.com/zhengshou/scnn) Note: Aka S-CNN.
* [Fast Temporal Activity Proposals for Efficient Detection of Human Actions in Untrimmed Videos](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Heilbron_Fast_Temporal_Activity_CVPR_2016_paper.pdf) - F. Heilbron et al, CVPR2016. [[code]](https://github.com/cabaf/sparseprop) Note: Depends on [C3D](http://vlg.cs.dartmouth.edu/c3d/), aka SparseProp.
* [Actionness Estimation Using Hybrid Fully Convolutional Networks](https://arxiv.org/abs/1604.07279) - L. Wang et al, CVPR2016. [[code]](https://github.com/wanglimin/actionness-estimation/) Note: The code is not a complete verision. It only contains a demo, not training. [[project web]](http://wanglimin.github.io/actionness_hfcn/index.html)
* [Learning Activity Progression in LSTMs for Activity Detection and Early Detection](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Ma_Learning_Activity_Progression_CVPR_2016_paper.pdf) - S. Ma et al, CVPR2016.
* [End-to-end Learning of Action Detection from Frame Glimpses in Videos](http://vision.stanford.edu/pdf/yeung2016cvpr.pdf) - S. Yeung et al, CVPR2016. [[code]](https://github.com/syyeung/frameglimpses) [[project web]](http://ai.stanford.edu/~syyeung/frameglimpses.html) Note: This method uses reinforcement learning
* [Fast Action Proposals for Human Action Detection and Search](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Yu_Fast_Action_Proposals_2015_CVPR_paper.pdf) - G. Yu and J. Yuan, CVPR2015. Note: code for FAP is NOT available online. Note: Aka FAP.
* [Bag-of-fragments: Selecting and encoding video fragments for event detection and recounting](https://staff.fnwi.uva.nl/t.e.j.mensink/publications/mettes15icmr.pdf) - P. Mettes et al, ICMR2015.
* [Action localization in videos through context walk](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Soomro_Action_Localization_in_ICCV_2015_paper.pdf) - K. Soomro et al, ICCV2015.

### Spatio-Temporal Action Detection
* [A Better Baseline for AVA](https://arxiv.org/pdf/1807.10066.pdf) - R. Girdhar et al., ActivityNet Workshop, CVPR2018.
* [Real-Time End-to-End Action Detection with Two-Stream Networks](https://arxiv.org/abs/1802.08362) - A. El-Nouby and G. Taylor, arXiv2018.
* [Human Action Localization with Sparse Spatial Supervision](https://arxiv.org/pdf/1605.05197.pdf) - P. Weinzaepfel et al., arXiv2017.
* [Unsupervised Action Discovery and Localization in Videos](http://openaccess.thecvf.com/content_ICCV_2017/papers/Soomro_Unsupervised_Action_Discovery_ICCV_2017_paper.pdf) - K. Soomro and M. Shah, ICCV2017.
* [Spatial-Aware Object Embeddings for Zero-Shot Localization and Classification of Actions](https://arxiv.org/pdf/1707.09145.pdf) - P. Mettes and C. G. M. Snoek, ICCV2017.
* [Action Tubelet Detector for Spatio-Temporal Action Localization](https://arxiv.org/abs/1705.01861) - V. Kalogeiton et al, ICCV2017. [[code]](https://github.com/vkalogeiton/caffe/tree/act-detector) [[project web]](http://thoth.inrialpes.fr/src/ACTdetector/)
* [Tube Convolutional Neural Network (T-CNN) for Action Detection in Videos](https://arxiv.org/pdf/1703.10664.pdf) - [R. Hou](http://www.cs.ucf.edu/~rhou/) et al, ICCV2017. [[project web]](http://crcv.ucf.edu/projects/TCNN/)
* [Chained Multi-stream Networks Exploiting Pose, Motion, and Appearance for Action Classification and Detection](https://arxiv.org/abs/1704.00616) - M. Zolfaghari et al, ICCV2017. [[project web]](https://lmb.informatik.uni-freiburg.de/projects/action_chain/)
* [TORNADO: A Spatio-Temporal Convolutional Regression Network for Video Action Proposal](http://openaccess.thecvf.com/content_ICCV_2017/papers/Zhu_TORNADO_A_Spatio-Temporal_ICCV_2017_paper.pdf) - H. Zhu et al., ICCV2017.
* [Online Real time Multiple Spatiotemporal Action Localisation and Prediction](https://arxiv.org/pdf/1611.08563v3.pdf) - [G. Singh](http://gurkirt.github.io/) et al, ICCV2017. [[code]](https://github.com/gurkirt/realtime-action-detection)
* [AMTnet: Action-Micro-Tube regression by end-to-end trainable deep architecture](https://arxiv.org/pdf/1704.04952.pdf) - S. Saha et al, ICCV2017.
* [Am I Done? Predicting Action Progress in Videos](https://arxiv.org/abs/1705.01781) - F. Becattini et al, BMVC2017.
* [Generic Tubelet Proposals for Action Localization](https://arxiv.org/abs/1705.10861) - J. He et al, arXiv2017.
* [Incremental Tube Construction for Human Action Detection](https://arxiv.org/pdf/1704.01358.pdf) - H. S. Behl et al, arXiv2017.
* [Multi-region two-stream R-CNN for action detection](https://www.robots.ox.ac.uk/~vgg/rg/papers/peng16eccv.pdf) - [X. Peng](http://xjpeng.weebly.com/) and C. Schmid. ECCV2016. [[code]](https://github.com/pengxj/action-faster-rcnn)
* [Spot On: Action Localization from Pointly-Supervised Proposals](http://jvgemert.github.io/pub/spotOnECCV16.pdf) - P. Mettes et al, ECCV2016.
* [Deep Learning for Detecting Multiple Space-Time Action Tubes in Videos](https://arxiv.org/abs/1608.01529) - S. Saha et al, BMVC2016. [[code]](https://bitbucket.org/sahasuman/bmvc2016_code) [[project web]](http://sahasuman.bitbucket.org/bmvc2016/)
* [Learning to track for spatio-temporal action localization](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Weinzaepfel_Learning_to_Track_ICCV_2015_paper.pdf) - P. Weinzaepfel et al. ICCV2015.
* [Action detection by implicit intentional motion clustering](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Chen_Action_Detection_by_ICCV_2015_paper.pdf) - W. Chen and J. Corso, ICCV2015.
* [Finding Action Tubes](https://people.eecs.berkeley.edu/~gkioxari/ActionTubes/action_tubes.pdf) - G. Gkioxari and J. Malik CVPR2015. [[code]](https://github.com/gkioxari/ActionTubes) [[project web]](https://people.eecs.berkeley.edu/~gkioxari/ActionTubes/)
* [APT: Action localization proposals from dense trajectories](http://jvgemert.github.io/pub/gemertBMVC15APTactionProposals.pdf) - J. Gemert et al, BMVC2015. [[code]](https://github.com/jvgemert/apt)
* [Spatio-Temporal Object Detection Proposals](https://hal.inria.fr/hal-01021902/PDF/proof.pdf) - D. Oneata et al, ECCV2014. [[code]](https://bitbucket.org/doneata/proposals) [[project web]](http://lear.inrialpes.fr/~oneata/3Dproposals/)
* [Action localization with tubelets from motion](http://isis-data.science.uva.nl/cgmsnoek/pub/jain-tubelets-cvpr2014.pdf) - M. Jain et al, CVPR2014.
* [Spatiotemporal deformable part models for action detection](http://crcv.ucf.edu/papers/cvpr2013/cvpr2013-sdpm.pdf) - [Y. Tian](http://www.cs.ucf.edu/~ytian/index.html) et al, CVPR2013. [[code]](http://www.cs.ucf.edu/~ytian/sdpm.html)
* [Action localization in videos through context walk](http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Soomro_Action_Localization_in_ICCV_2015_paper.pdf) - K. Soomro et al, ICCV2015.
* [Fast Action Proposals for Human Action Detection and Search](http://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Yu_Fast_Action_Proposals_2015_CVPR_paper.pdf) - G. Yu and J. Yuan, CVPR2015. Note: code for FAP is NOT available online. Note: Aka FAP.

### Ego-Centric Action Recognition
* [Actor and Observer: Joint Modeling of First and Third-Person Videos](https://arxiv.org/pdf/1804.09627.pdf) - G. Sigurdsson et al., CVPR2018. [[code]](https://github.com/gsig/actor-observer)

### Miscellaneous
* [What and How Well You Performed? A Multitask Learning Approach to Action Quality Assessment](https://arxiv.org/pdf/1904.04346.pdf) - P. Parma and B. T. Morris. CVPR2019.
* [PathTrack: Fast Trajectory Annotation with Path Supervision](http://openaccess.thecvf.com/content_ICCV_2017/papers/Manen_PathTrack_Fast_Trajectory_ICCV_2017_paper.pdf) - S. Manen et al., ICCV2017.
* [CortexNet: a Generic Network Family for Robust Visual Temporal Representations](https://arxiv.org/pdf/1706.02735.pdf) A. Canziani and E. Culurciello - arXiv2017. [[code]](https://github.com/atcold/pytorch-CortexNet) [[project web]](https://engineering.purdue.edu/elab/CortexNet/)
* [Slicing Convolutional Neural Network for Crowd Video Understanding](http://www.ee.cuhk.edu.hk/~jshao/papers_jshao/jshao_cvpr16_scnn.pdf) - J. Shao et al, CVPR2016. [[code]](https://github.com/amandajshao/Slicing-CNN)
* [Two-Stream (RGB and Flow) pretrained model weights](https://github.com/craftGBD/caffe-GBD/tree/master/models/action_recognition)

### Action Recognition Datasets
* [Video Dataset Overview from Antoine Miech](https://www.di.ens.fr/~miech/datasetviz/)
* [HACS](http://hacs.csail.mit.edu/)
* [Moments in Time](http://moments.csail.mit.edu/), [paper](http://moments.csail.mit.edu/data/moments_paper.pdf)
* [AVA](https://research.google.com/ava/), [paper](https://arxiv.org/abs/1705.08421), [[INRIA web]](http://thoth.inrialpes.fr/ava/getava.php) for missing videos
* [Kinetics](https://deepmind.com/research/open-source/open-source-datasets/kinetics/), [paper](https://arxiv.org/pdf/1705.07750.pdf), [download toolkit](https://github.com/activitynet/ActivityNet/tree/master/Crawler/Kinetics)
* [OOPS](https://oops.cs.columbia.edu/data/) - A dataset of unintentional action, [paper](https://arxiv.org/abs/1911.11206)
* [COIN](https://coin-dataset.github.io/) - a large-scale dataset for comprehensive instructional video analysis, [paper](https://arxiv.org/abs/1903.02874)
* [YouTube-8M](https://research.google.com/youtube8m/), [technical report](https://arxiv.org/abs/1609.08675)
* [YouTube-BB](https://research.google.com/youtube-bb/), [technical report](https://arxiv.org/pdf/1702.00824.pdf)
* [DALY](http://thoth.inrialpes.fr/daly/) Daily Action Localization in Youtube videos. Note: Weakly supervised action detection dataset. Annotations consist of start and end time of each action, one bounding box per each action per video.
* [20BN-JESTER](https://www.twentybn.com/datasets/jester), [20BN-SOMETHING-SOMETHING](https://www.twentybn.com/datasets/something-something)
* [ActivityNet](http://activity-net.org/) Note: They provide a download script and evaluation code [here](https://github.com/activitynet) .
* [Charades](http://allenai.org/plato/charades/)
* [Charades-Ego](https://prior.allenai.org/projects/charades-ego), [paper](https://arxiv.org/pdf/1804.09626.pdf) - First person and third person video aligned dataset
* [EPIC-Kitchens](https://epic-kitchens.github.io/), [paper](https://arxiv.org/abs/1804.02748) - First person videos recorded in kitchens. Note they provide download scripts and a python library [here](https://github.com/epic-kitchens)
* [Sports-1M](http://cs.stanford.edu/people/karpathy/deepvideo/classes.html) - Large scale action recognition dataset.
* [THUMOS14](http://crcv.ucf.edu/THUMOS14/) Note: It overlaps with [UCF-101](http://crcv.ucf.edu/data/UCF101.php) dataset.
* [THUMOS15](http://www.thumos.info/home.html) Note: It overlaps with [UCF-101](http://crcv.ucf.edu/data/UCF101.php) dataset.
* [HOLLYWOOD2](http://www.di.ens.fr/~laptev/actions/hollywood2/): [Spatio-Temporal annotations](https://staff.fnwi.uva.nl/p.s.m.mettes/index.html#data)
* [UCF-101](http://crcv.ucf.edu/data/UCF101.php), [annotation provided by THUMOS-14](http://crcv.ucf.edu/ICCV13-Action-Workshop/index.files/UCF101_24Action_Detection_Annotations.zip), and [corrupted annotation list](https://github.com/jinwchoi/Jinwoo-Computer-Vision-and-Machine-Learing-papers-to-read/blob/master/UCF101_Spatial_Annotation_Corrupted_file_list),  [UCF-101 corrected annotations](https://github.com/gurkirt/corrected-UCF101-Annots) and [different version annotaions](https://github.com/jvgemert/apt). And there are also some pre-computed spatiotemporal action detection [results](https://drive.google.com/drive/folders/0B-LzM05qEdk0aG5pTE94VFI1SUk)
* [UCF-50](http://crcv.ucf.edu/data/UCF50.php).
* [UCF-Sports](http://crcv.ucf.edu/data/UCF_Sports_Action.php), note: the train/test split link in the official website is broken. Instead, you can download it from [here](http://pascal.inrialpes.fr/data2/oneata/data/ucf_sports/videos.txt).
* [HMDB](http://serre-lab.clps.brown.edu/resource/hmdb-a-large-human-motion-database/)
* [J-HMDB](http://jhmdb.is.tue.mpg.de/)
* [LIRIS-HARL](http://liris.cnrs.fr/voir/activities-dataset/)
* [KTH](http://www.nada.kth.se/cvap/actions/)
* [MSR Action](https://www.microsoft.com/en-us/download/details.aspx?id=52315) Note: It overlaps with [KTH](http://www.nada.kth.se/cvap/actions/) datset.
* [Sports Videos in the Wild](http://cvlab.cse.msu.edu/project-svw.html)
* [NTU RGB+D](https://github.com/shahroudy/NTURGB-D)
* [Mixamo Mocap Dataset](http://mocap.cs.cmu.edu/)
* [UWA3D Multiview Activity II Dataset](http://staffhome.ecm.uwa.edu.au/~00053650/databases.html)
* [Northwestern-UCLA Dataset](https://users.eecs.northwestern.edu/~jwa368/my_data.html)
* [SYSU 3D Human-Object Interaction Dataset](http://www.isee-ai.cn/~hujianfang/ProjectJOULE.html)
* [MEVA (Multiview Extended Video with Activities) Dataset](http://mevadata.org)

### Video Annotation
* [Efficiently scaling up crowdsourced video annotation](http://cvrr.ucsd.edu/ece285/Spring2014/papers/Vondrick_IJCV2013.pdf) - C. Vondrick et. al, IJCV2013. [[code]](https://github.com/cvondrick/vatic)
* [The Design and Implementation of ViPER](https://www.cs.umd.edu/grad/scholarlypapers/papers/davidm-viper.pdf) - D. Mihalcik and D. Doermann, Technical report.
* [VTT: Visual Object Tagging Tool](https://github.com/microsoft/VoTT). Modern app to annotate objects in videos and images. It facilitates the development of an end-to-end machine learning pipeline encompassing the annotation/export/import of assets. Moreover, it could run as a native app or via web.
* [VIA: VGG Image Annotator](http://www.robots.ox.ac.uk/~vgg/software/via/). Simple and standalone manual annotation web-app for image, audio and video. It runs in the web browser and does not require any installation or setup.

## Object Recognition

### Object Detection
* [Training a Custom Object Detection Model With Yolo-V5](https://medium.com/analytics-vidhya/training-a-custom-object-detection-model-with-yolo-v5-aa9974c07088)
Using Google Colab.
* [Object Detection on Custom Dataset with YOLO (v5) using PyTorch and Python](https://curiousily.com/posts/object-detection-on-custom-dataset-with-yolo-v5-using-pytorch-and-python/)
* [Deformable Convolutional Networks](http://openaccess.thecvf.com/content_ICCV_2017/papers/Dai_Deformable_Convolutional_Networks_ICCV_2017_paper.pdf) - J. Dai et al., ICCV2017. [[official code]](https://github.com/msracver/Deformable-ConvNets)
* [Detectron](https://github.com/facebookresearch/Detectron) - Open Source Object Detection Framework from Facebook AI Research. Includes Mask R-CNN, FPN, and etc. Caffe2 implementation.
* [Mask R-CNN](https://arxiv.org/abs/1703.06870) - K. He et al, [[Detectron]](https://github.com/facebookresearch/Detectron), [[TensorFlow + Keras]](https://github.com/matterport/Mask_RCNN), [[MXNet]](https://github.com/TuSimple/mx-maskrcnn), [[TensorFlow]](https://github.com/CharlesShang/FastMaskRCNN), [[PyTorch]](https://github.com/felixgwu/mask_rcnn_pytorch) - State-of-the-art object detection/instance segmentation algorithm.
* [Faster R-CNN](https://arxiv.org/abs/1506.01497) - S. Ren et al, NIPS2015. [[official MatCaffe code]](https://github.com/ShaoqingRen/faster_rcnn), [[PyCaffe]](https://github.com/rbgirshick/py-faster-rcnn), [[TensorFlow]](https://github.com/smallcorgi/Faster-RCNN_TF), [[Another TF implementation]](https://github.com/CharlesShang/TFFRCNN) [[Keras]](https://github.com/yhenon/keras-frcnn) - State-of-the-art object detector.
* [YOLO](https://pjreddie.com/media/files/papers/yolo.pdf) - J. Redmon et al, CVPR2016. [[official code]](https://github.com/pjreddie/darknet.git), [[TensorFLow]](https://github.com/gliese581gg/YOLO_tensorflow) - Fast object detector.
* [YOLO9000](https://arxiv.org/abs/1612.08242) - J. Redmon and A. Farhadi, CVPR2017. [[official code]](https://pjreddie.com/darknet/yolo/) - State-of-the-art object detector which can detect 9000 objects in realtime.
* [SSD](https://arxiv.org/abs/1512.02325) - W. Liu et al, ECCV2016. [[official PyCaffe code]](https://github.com/weiliu89/caffe/tree/ssd), [[TensorFlow]](https://github.com/balancap/SSD-Tensorflow), [[Keras]](https://github.com/rykov8/ssd_keras) - State-of-the-art object detector with realtime processing speed.
* [RetinaNet](https://arxiv.org/abs/1708.02002) - Tsung-Yi Lin, Priya Goyal, Ross Girshick, Kaiming He and Piotr Dollár, Facebook AI Research FAIR & ICCV 2017.[[Keras]](https://github.com/fizyr/keras-retinanet) - State-of-the-art object detector with realtime processing speed.

### Video Object Detection
* [Detect to Track and Track to Detect] - C. Feichtenhofer et al., ICCV2017. [[code]](https://github.com/feichtenhofer/detect-track), [[project web]](http://www.robots.ox.ac.uk/~vgg/research/detect-track/)
* [Flow-Guided Feature Aggregation for Video Object Detection] - X. Zhu et al., ICCV2017. [[code]](https://github.com/msracver/Flow-Guided-Feature-Aggregation), aka FGFA

### Video Object Detection Datasets
* [ImageNet VID](http://image-net.org/challenges/LSVRC/2017/download-images-1p39.php)
* [YouTube-8M](https://research.google.com/youtube8m/), [technical report](https://arxiv.org/abs/1609.08675)
* [YouTube-BB](https://research.google.com/youtube-bb/), [technical report](https://arxiv.org/pdf/1702.00824.pdf)

### Face Recognition
* [RetinaFace on PyTorch](https://github.com/biubug6/Pytorch_Retinaface) MobileNet 0.25 / ResNet50. [Custom Train & Inference](https://github.com/ternaus/retinaface).  [Paper: Single-stage Dense Face Localisation](https://arxiv.org/abs/1905.00641).
* [awesome-Face_Recognition](https://github.com/ChanChiChoi/awesome-Face_Recognition)
* [Tencent FaceDetection DSFD](https://github.com/Tencent/FaceDetection-DSFD)

### Human Detection Repositories

* [YOLO-Hand-Detection](https://github.com/cansik/yolo-hand-detection) variants including YOLOv4-Tiny Cross-Hands.
* [Finger Detection and Tracking](https://github.com/amarlearning/Finger-Detection-and-Tracking)
* [Unified Gesture Recognition and Fingertip Detection](https://github.com/MahmudulAlam/Unified-Gesture-and-Fingertip-Detection)
* [YoloV4_Dectection_Example.ipynb](https://colab.research.google.com/github/sicara/tf2-yolov4/blob/master/notebooks/YoloV4_Dectection_Example.ipynb#scrollTo=qhgxoREBFHKn)


## Pose Estimation

### Pose Estimation
* [Alpha Pose](http://www.mvig.org/research/alphapose.html) is an accurate multi-person pose estimator, which is the first [open-source](https://github.com/MVIG-SJTU/AlphaPose) system that achieves 70+ mAP (72.3 mAP) on COCO dataset and 80+ mAP (82.1 mAP) on MPII dataset. To match poses that correspond to the same person across frames, we also provide an efficient online pose tracker called Pose Flow. It is the first open-source online pose tracker that achieves both 60+ mAP (66.5 mAP) and 50+ MOTA (58.3 MOTA) on PoseTrack Challenge dataset.
* [Detect-and-Track: Efficient Pose Estimation in Videos](https://arxiv.org/abs/1712.09184) - R. Girdhar et al., arXiv2017.
* [OpenPose Library](https://github.com/CMU-Perceptual-Computing-Lab/openpose) - Caffe based realtime pose estimation library from CMU.
* [Realtime Multi-Person 2D Pose Estimation using Part Affinity Fields](https://arxiv.org/abs/1611.08050) - Z. Cao et al, CVPR2017. [[code]](https://github.com/ZheC/Realtime_Multi-Person_Pose_Estimation) depends on the [[caffe RT pose]](https://github.com/CMU-Perceptual-Computing-Lab/caffe_rtpose.git) - Earlier version of OpenPose from CMU.
* [DensePose](https://arxiv.org/abs/1802.00434v1) [[code]](https://github.com/facebookresearch/DensePose) - Dense pose human estimation in the wild implemented in the Detectron framework.
* [MultiPoseNet: Fast Multi-Person Pose Estimation using Pose Residual Network](https://arxiv.org/abs/1807.04067) - M. Kocabas et al, ECCV2018. [[code]](https://github.com/salihkaragoz/pose-residual-network-pytorch)
* [DeepLabCut: markerless pose estimation of user-defined body parts with deep learning](https://www.nature.com/articles/s41593-018-0209-y) - A. Mathis et al, Nature Neuroscience 2018. [[code]](https://github.com/DeepLabCut/DeepLabCut)

### Pose Repositories

* [AlphaPose for pytorch](https://github.com/MVIG-SJTU/AlphaPose) - PyTorch based realtime and accurate pose estimation and tracking tool from SJTU.


## Visual Relationship Detection


### Visual Relationship Detection
* `NIPS 2017` - [Pixels to Graphs by Associative Embedding ](https://arxiv.org/pdf/1706.07365.pdf) Alejandro -et al.[[offical code]](https://github.com/princeton-vl/px2graph)
* `2018` - [Attentive Relational Networks for Mapping Images to Scene Graphs](https://arxiv.org/abs/1811.10696v1) Mengshi Qi et al.
* `AAAI 2019` - [Large-Scale Visual Relationship Understanding](https://arxiv.org/abs/1804.10660) - Ji Zhang et al, AAAI 2019.
* `2018` - [Improving Visual Relationship Detection using Semantic Modeling of Scene Descriptions](https://arxiv.org/abs/1809.00204) - Stephan Baier et al.
* `AAAI 2018` - [Visual Relationship Detection with Deep Structural Ranking](http://vipl.ict.ac.cn/uploadfile/upload/2018030615400539.pdf) - Kongming Liang et al, AAAI 2018, [[official pytorch=0.2.0 code]](https://github.com/GriffinLiang/vrd-dsr).
* `ECCV 2018` - [Visual Relationship Prediction via Label Clustering and Incorporation of Depth Information](https://arxiv.org/abs/1809.02945) - Hsuan-Kung Yang et al, ECCV 2018 workshop.
* `ECCV 2018` - [Shuffle-Then-Assemble: Learning Object-Agnostic Visual Relationship Features](https://arxiv.org/abs/1808.00171) - Xu Yang et al, ECCV 2018, [[tensorflow]](https://github.com/yangxuntu/vrd)
* `CVPR 2018` - [Relation Networks for Object Detection](https://arxiv.org/abs/1711.11575) - Han Hu et al, CVPR 2018 oral paper, [[official MXNet code]](https://github.com/msracver/Relation-Networks-for-Object-Detection), [[pytorch]](https://github.com/heefe92/Relation_Networks-pytorch).
* `CVPR 2018` - [Tensorize, Factorize and Regularize: Robust Visual Relationship Learning](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hwang_Tensorize_Factorize_and_CVPR_2018_paper.pdf) - Seong Jae Hwang et al, CVPR2018.
* `CVPR 2018` - [Referring Relationships](https://github.com/StanfordVL/ReferringRelationships) - Ranjay Krishna et al, , [[official keras code]](https://github.com/StanfordVL/ReferringRelationships).
* `ICME 2018` - [Visual Relationship Detection Based on Guided Proposals and Semantic Knowledge Distillation](https://arxiv.org/abs/1805.10802) - François Plesse et al, ICME 2018.
* `2018` - [Natural Language Guided Visual Relationship Detection](https://arxiv.org/abs/1711.06032) - Wentong Liao et al.
* `ACM MM 2018` - [Context-Dependent Diffusion Network for Visual Relationship Detection](https://arxiv.org/abs/1809.06213) - Zhen Cui et al, 2018 ACM Multimedia Conference.
* `ICCV 2017` - [PPR-FCN: Weakly Supervised Visual Relation Detection via Parallel Pairwise R-FCN](https://arxiv.org/abs/1708.01956) - Hanwang Zhang et al, ICCV 2017. [[official Matlab code]](https://github.com/yjy941124/PPR-FCN)
* `ICCV 2017` - [Phrase Localization and Visual Relationship Detection with Comprehensive Image-Language Cues](https://arxiv.org/abs/1611.06641) - Bryan A. Plummer et al, ICCV 2017, [[official Matlab code]](https://github.com/BryanPlummer/pl-clc).
* `ICCV 2017` - [Visual Relationship Detection with Internal and External Linguistic Knowledge Distillation](https://arxiv.org/abs/1707.09423) - Ruichi Yu et al, ICCV 2017.
* `ICCV 2017` - [Weakly-supervised learning of visual relations](https://arxiv.org/abs/1707.09472) - Julia Peyre et al, ICCV 2017, [[official Matlab code]](https://github.com/jpeyre/unrel).
* `CVPR 2017` - [Detecting Visual Relationships with Deep Relational Networks](https://arxiv.org/abs/1704.03114) - Bo Dai et al, CVPR 2017 oral, [[official caffe code]](https://github.com/doubledaibo/drnet_cvpr2017)
* `CVPR 2017` - [ViP-CNN: Visual Phrase Guided Convolutional Neural Network](https://arxiv.org/abs/1702.07191) - Yikang Li et al, CVPR 2017.
* `CVPR 2017` - [Scene Graph Generation by Iterative Message Passing](https://arxiv.org/abs/1701.02426) - Danfei Xu et al, CVPR 2017.
* `CVPR 2017` - [Deep Variation-Structured Reinforcement Learning for Visual Relationship and Attribute Detection](https://arxiv.org/abs/1703.03054) - Xiaodan Liang et al, CVPR 2017, [[pytorch]](https://github.com/nexusapoorvacus/DeepVariationStructuredRL).
* `CVPR 2017` - [Relationship Proposal Networks](http://openaccess.thecvf.com/content_cvpr_2017/html/Zhang_Relationship_Proposal_Networks_CVPR_2017_paper.html) - Ji Zhang et al, CVPR 2017.
* `CVPR 2017` - [Visual Translation Embedding Network for Visual Relation Detection](https://arxiv.org/abs/1702.08319) - Hanwang Zhang et al, CVPR 2017.
* `ECCV 2016` - [Visual Relationship Detection with Language Priors](https://cs.stanford.edu/people/ranjaykrishna/vrd/vrd.pdf) - Lu et al, ECCV 2016 Oral, [[official Matlab code]](https://github.com/Prof-Lu-Cewu/Visual-Relationship-Detection).



### Scene Graph
* `CVPR 2018` - [Neural Motifs: Scene Graph Parsing with Global Context](https://arxiv.org/abs/1711.06640) - Rowan Zellers et al, CVPR 2018, [[official pytorch=0.3.0 code]](https://github.com/rowanz/neural-motifs).
* `IJCAI 2018` - [Representation Learning for Scene Graph Completion via Jointly Structural and Visual Embedding](https://www.ijcai.org/proceedings/2018/0132.pdf) - Hai Wan et al, IJCAI-18.
* `ICCV 2017` - [Scene Graph Generation From Objects, Phrases and Region Captions](http://openaccess.thecvf.com/content_iccv_2017/html/Li_Scene_Graph_Generation_ICCV_2017_paper.html) - Yikang Li et al, ICCV 2017.
* `CVPR 2017` - [Scene Graph Generation by Iterative Message Passing](https://arxiv.org/pdf/1701.02426.pdf) - Danfei Xu et al, CVPR 2017.

### Video Visual Relation Detection

* `ACM MM 2017` - [Video Visual Relation Detection](http://lms.comp.nus.edu.sg/research/VidVRD/VidVRD-MM17.pdf) - Xindi Shang et al, 2017 ACM Multimedia Conference, [Video Visual Relation Detection](http://software.nju.edu.cn/rentw/publication/mm17-shangxd_pot.pdf)


### Dataset

* `The Open Images Dataset V4`, `IJCV 2018` - [The Open Images Dataset V4: Unified image classification, object detection, and visual relationship detection at scale](https://arxiv.org/abs/1811.00982) - Alina Kuznetsova et al, IJCV 2018.
* `Visual Genome`, `2016` - [Visual Genome: Connecting Language and Vision Using Crowdsourced Dense Image Annotations](https://visualgenome.org/static/paper/Visual_Genome.pdf) - Ranjay Krishna et al, [official web] (https://visualgenome.org/).
* `VRD`, `ECCV 2016` - [Visual Relationship Detection with Language Priors](https://cs.stanford.edu/people/ranjaykrishna/vrd/) - Lu et al, ECCV 2016 Oral.
* `VidVRD`, `ACM MM 2017` - [Video Visual Relation Dataset](https://lms.comp.nus.edu.sg/research/VidVRD.html) - Xindi Shang et al, 2018 ACM Multimedia Conference, [VidVRD-helper](https://github.com/xdshang/VidVRD-helper).
* [20 Free Image Datasets for Computer Vision](https://lionbridge.ai/datasets/20-best-image-datasets-for-computer-vision/)
* [How to Create Your Own Image Dataset for Deep Learning with googleimagedownloader](https://towardsdatascience.com/how-to-create-your-own-image-dataset-for-deep-learning-b53f1c22c443)
* [How to scrape Google for Images to train your Machine Learning classifiers on](https://medium.com/@intprogrammer/how-to-scrape-google-for-images-to-train-your-machine-learning-classifiers-on-565076972ce)


## Competitions

### Competitions
* [ActEV (Activities in Extended Video](https://actev.nist.gov/sdl) - Activity detection in security camera videos. Runs through 2021. Hosted by NIST.

### Dataset Preparation

* [Open Images Dataset V6 + Extensions](https://storage.googleapis.com/openimages/web/index.html) Download specific labels with [oidv6](https://pypi.org/project/oidv6/)
* [Synthetic Data Generation for Object Detection Presentation](https://www.hackster.io/dmitrywat/synthetic-data-generation-for-object-detection-e0f023)
* [SynDataGeneration](https://github.com/debidatta/syndata-generation) Generate synthetic scenes for the task of instance/object detection
* [How to label custom images for YOLO – YOLO 3](https://cloudxlab.com/blog/label-custom-images-for-yolo/)


### Tools
* [Weights and Biases](wandb.ai) Experiment tracking, logging, comparison. [Examples](https://docs.wandb.ai/examples). [Saving & Restoring](https://wandb.ai/lavanyashukla/save_and_restore/reports/Saving-and-Restoring-Models-with-W-B--Vmlldzo3MDQ3Mw).
[Track Model Performance](https://wandb.ai/lavanyashukla/visualize-models/reports/Track-Model-Performance--Vmlldzo1NTk2MA).
* [hackster.io](hackster.io) Hardware AI community
* [aXeleRate](https://github.com/AIWintermuteAI/aXeleRate/blob/master/axelerate/infer.py) Tools to generate models for the edge K210/Coral/etc made by Hardware AI
* [PyTorch for iOS](https://pytorch.org/mobile/ios/) Demo for MobileNet v2 on iOS.
* [GTX1070 + OS X Sierra + PyTorch](https://gist.github.com/dandanwei/18708e7bd5fd2b227f86bca668343093)
* [TensorFlow + OS X Sierra](https://gist.github.com/geekcui/d0800d62e377e0103b1cc2b889ed1128)
* [PyTorch ARM Mac 16-core Neural Engine](https://github.com/pytorch/pytorch/issues/47688)
* [Leveraging ML Compute for Accelerated Training on Mac](https://machinelearning.apple.com/updates/ml-compute-training-on-mac)
* [Building PyTorch on ROCm](https://lernapparat.de/pytorch-rocm/). [prebuilt packages](https://rocmdocs.amd.com/en/latest/Deep_learning/Deep-learning.html#pytorch)

* [Get SH*T Done with PyTorch](https://github.com/curiousily/Getting-Things-Done-with-Pytorch). [Read Here](https://bit.ly/gtd-with-pytorch).



## Licenses
License

This is intended for personal use at this time.

