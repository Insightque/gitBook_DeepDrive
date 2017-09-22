![](https://i.imgur.com/OPatJnW.png)
# List 

[Awesome Autonomous Vehicles](https://github.com/takeitallsource/awesome-autonomous-vehicles)

[Bookmark of 3D CNN Rearch](https://github.com/NotAndOr/bookmarks/blob/master/20170203.md)

# Project

[Project: Development of AEB System for Pedestrian Protection (4th year)](https://github.com/nlkim0817/ProjAEB_4thYear)

# Post/Article
- [3D Convolutional Neural Networks — A Reading List](http://davidstutz.de/3d-convolutional-neural-networks-a-reading-list/)



## 참고 논문

### 1. 3D DL 

[Instant Object Detection in Lidar Point Clouds](http://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7927715&tag=1)

[Fast LIDAR-based Road Detection Using Fully Convolutional Neural Networks](https://arxiv.org/abs/1703.03613): 2017.03

### 2. Fusion 

[Fusing LIDAR and images for pedestrian detection using convolutional neural networks](http://ieeexplore.ieee.org/abstract/document/7487370/): 2016.04


[RegNet: Multimodal sensor registration using deep neural networks](http://ieeexplore.ieee.org/document/7995968/#full-text-section): 2017.06, LiDAR + monocular camera, 

[Multi-Modal Obstacle Detection in Unstructured Environments with Conditional Random Fields](https://arxiv.org/abs/1706.02908): 2017.06
- Unstructured Environments: 농장 
- lidar + camera sensing using a conditional random field

### 3. RNN/RL

[3DCNN-DQN-RNN: A Deep Reinforcement Learning Framework for Semantic Parsing of Large-scale 3D Point Clouds](https://arxiv.org/abs/1707.06783): 2017.07, 3D CNN + RNN + DQN

# Datasets
- Princeton Shape Benchmark (PSB) [Shilane et al. 2004] 

- Engineering Shape Benchmark (ESB) [Jayanti et al. 2006]

- PSB [Shilane et al. 2004]

- National Taiwan University (NTU) dataset [Chen et al. 2003] 

- SHREC’09 [Godil et al. 2009]

- [Semantic3D.net: A new Large-scale Point Cloud Classification Benchmark](https://arxiv.org/abs/1704.03847): 2017.04, Datasets, 도시, four billion~



---
[3D Vehicle Detection](https://experiencor.github.io/sdc_3d.html)

1. Detect 2D BBoxes of other vehicles visible on CAMERA frame. This can be achieved by YOLOv2 or SqueezeDet. It turns out that SqueezeDet works better for this job and is selected.

2. Determine the dimension and the orientation of detected vehicles. As demonstrated in [https://arxiv.org/abs/1612.00496], dimension and orientation of other vehicles can be regressed from the image patch of corresponding 2D BBoxes.

3. Determine the location in 3D of detected vehicles. This can be achived by localizing the point cloud region whose projection stays within the detected 2D BBoxes.


---

https://www.draw.io/?lightbox=1&highlight=0000ff&edit=_blank&layers=1&nav=1&title=3D_CNN_Trend.xml#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D0B6Ry8c3OoOuqVUh1b2tyc2lhMEE%26export%3Ddownload


Deep S.Shape(2016)[23] 