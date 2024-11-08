# Survival-Guide
Teaching You How to Survive in the Lab (实验室求生指南)

## 研0阶段

#### 基本科研工具
硬件环境：笔记本电脑至少配备30系列的显卡    
软件环境：双系统Ubuntu 20.04及以上 (ubuntu系统单独一个500G/1T固态硬盘)，Cuda，Cudnn，Anaconda，FanQiang，游览器(Chrome)，录屏软件(SimpleScreenRecoder)

#### 基础知识学习
掌握ROS基础知识！      
掌握Python/Pytorch基本语法！       
请通过CSDN，知乎，B站或相关论文建立以下概念的认知！       

什么是卷积，池化，激活函数，全连接层，批归一化等常见网络元素？     
什么是RNN，LSTM，GRU，Transformer，Mamba等常见网络基础模块？适用于什么任务场景？    
常见的损失函数有哪些？哪些适合分类任务，哪些适合回归任务？              
代码上如何实现数据处理，并行计算，网络搭建，优化器设置以及网络优化？        
什么是二维/三维目标检测、跟踪、分割？什么是占据栅格预测 (OCC)？什么是基于环视BEV的目标检测？什么是NeRF (Neural Radiance Fields)和3D Gaussian Splatting？

跟李沐学AI [Link](https://space.bilibili.com/1567748478/channel/seriesdetail?sid=358497)    
PyTorch深度学习快速入门教程 [Link](https://www.bilibili.com/video/BV1hE411t7RN/?spm_id_from=333.337.search-card.all.click&vd_source=fa42d88ec19eff6dbea9dd604c15f925)

#### 文献阅读能力
请利用Mendeley文献工具分门别类管理文献，初期可以借助一些翻译器阅读文献，后期尽量避免(遇到不会的单词再去百度翻译); 重点阅读Abstract，Introduction和Method，对Related Work简要阅读，Experiment部分主要阅读表格数据、评价指标与常用数据集; 初期速度约为4-5小时一篇论文.     

以下将提供环境感知相关领域的基础文章，请按顺序或者兴趣进行阅读，请注意在阅读过程中寻找同一任务文章之间的联系，例如：思想的继承与发展关系？ 请对某一任务的相关论文进行集中阅读与总结，切勿各个任务论文交叉阅读. 

(以下论文仅为基础知识，并非是目前最前沿的主流方向，因此需要快速掌握).        
##### 点云分类/特征编码
PointNet: Deep learning on point sets for 3D classification and segmentation [CVPR 2017]

PointNet ++ : Deep Hierarchical Feature Learning on Point Sets in a Metric Space [NIPS 2017]

PointMamba: A Simple State Space Model for Point Cloud Analysis [NIPS 2024]

##### 三维点云目标检测 (Only LiDRA)

SECOND: Sparsely Embedded Convolutional Detection [Sensors 2018]

PointPillars: Fast Encoders for Object Detection from Point Clouds [CVPR 2019]

PointRCNN: 3D object proposal generation and detection from point cloud [CVPR 2019]

Center-based 3D Object Detection and Tracking [CVPR 2021]

VoxelNeXt: Fully Sparse VoxelNet for 3D Object Detection and Tracking [CVPR 2023]

##### 三维点云目标跟踪 (3D SOT)

P2B: Point-to-box network for 3D object tracking in point clouds [CVPR 2020]

Box-Aware Feature Enhancement for Single Object Tracking on Point Clouds [ICCV 2021]

PTTR: Relational 3D Point Cloud Object Tracking with Transformer [CVPR 2022]

Beyond 3D Siamese Tracking: A Motion-Centric Paradigm for 3D Single Object Tracking in Point Clouds [CVPR 2022]

##### 三维点云分割 (Semantic Segmentation)

TemporalLidarSeg: LiDAR-based Recurrent 3D Semantic Segmentation with Temporal Memory Alignment [3DV 2020]

Polarnet: An improved grid representation for online Lidar point clouds semantic segmentation [CVPR 2020]

CENet: Toward Concise and Efficient Lidar Semantic Segmentation for Autonomous Driving [ICME 2022]

RangeViT: Towards Vision Transformers for 3D Semantic Segmentation in Autonomous Driving [CVPR 2023]

RangeFormer: Rethinking Range View Representation for LiDAR Segmentation [ICCV 2023]

#### 代码实践能力
