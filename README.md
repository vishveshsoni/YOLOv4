# YOLOv4

[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)

<img src = "https://media.proprofs.com/images/discuss/user_images/153336/10563727321.jpg"/>

# New in YOLOv4!

  - YOLOv4 claims to have state-of-the-art accuracy while maintains a high processing frame rate. It achieves an accuracy of 43.5% AP (65.7% AP₅₀) for the MS COCO with an approximately 65 FPS inference speed on Tesla V100.
  - Improvements can be made in the training process (like data augmentation, class imbalance, cost function, soft labeling etc…) to advance accuracy. These improvements have no impact on inference speed and called “bag of freebies”. Then, there are “bag of specials” which impacts the inference time slightly with a good return in performance. These improvements include the increase of the receptive field, the use of attention, feature integration like skip-connections & FPN, and post-processing like non-maximum suppression. In this article, we will discuss how the feature extractor and the neck are designed as well as all these Bof and BoS goodies.
 
<img src = "https://miro.medium.com/max/1400/1*H3QlBG3U0s5XpOsI6xwsag.jpeg"/>


> notebook demonstrate step by step process to intialize and infernce on model.

#
**Credits & References**
[Paper: YOLOv4 Optimal Speed and Accuracy of Object Detection ]("https://arxiv.org/pdf/2004.10934.pdf")
[Github Repo]("https://github.com/AlexeyAB/darknet")


  
