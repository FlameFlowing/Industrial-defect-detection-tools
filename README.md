# Industrial-visual-defect-inspection-reference-database

# 开源视觉库
### opencv
开源图像算法库。涵盖传统图像处理（滤波、边缘检测）、机器学习（SVM、KNN）、深度学习（集成TensorFlow/PyTorch模型）

官网

https://opencv.org/

教程
官网文档

https://docs.opencv.org/

中文官方文档

http://www.woshicver.com/

github 官网示例
https://github.com/opencv/opencv/tree/master/samples/cpp

中文论坛

https://www.opencv.org.cn/forum/

菜鸟教程

https://www.runoob.com/opencv/opencv-tutorial.html

### dlib
专注于人脸检测、姿态估计和机器学习算法（如SVM、聚类），C++实现高效，适合嵌入式场景。

官网

https://dlib.net/
https://github.com/davisking/dlib

### SimpleCV
基于Python的简化视觉库，集成OpenCV和PIL，适合快速原型开发。

官网

http://simplecv.org/

### BoofCV
纯Java实现，支持实时图像处理、3D重建和SLAM，适合跨平台应用。

官网

https://boofcv.org/


# 商业机器视觉软件


## MVTec halcon
提供付费许可证，算法库高度封装（超过2000个算子）。工业级精度：专为机器视觉设计，支持亚像素级测量和3D视觉（双目、结构光）。

官网

https://www.mvtec.com/

教程 

官网文档

https://www.mvtec.com/products/halcon/work-with-halcon/documentation

halcon学习网

http://www.ihalcon.com/

halcon算子在线查询

https://www.51halcon.com/halcon/


### MVTec MERLIC
Halcon的“简化版”，提供图形化界面和预配置工具链，适合快速部署工业检测。无需编程，支持与PLC直接通信。

### MVTec DeepLearningTool
深度学习的物体检测，分类，语义分割，实例分割，异常值检测以及 Deep OCR

## Cognex 
### VisionPro

康耐视旗下产品，软硬件一体化解决方案（如In-Sight系列相机）。图形化编程（QuickBuild）和拖拽工具链，降低开发难度。

官网

https://support.cognex.com/en/downloads/visionpro?page=404&lang=zh-cn

教程

官网支持

https://support.cognex.com/zh-cn/ssologin/index?ReturnUrl=%2Fzh-cn

## AQRose (阿丘科技)
### AIDI（深度学习平台）
全流程AI开发：覆盖数据标注、模型训练、部署及监控，支持小样本学习和迁移学习。
行业场景适配：预置电子、锂电、光伏等行业的缺陷检测模型，减少定制化成本。

### AQVision（视觉系统应用开发平台）
全流程图形化开发：通过树状流程设计（支持串行、并行、汇总结构），用户可直观搭建视觉检测流程，涵盖图像采集、处理、分析到决策的全链路
深度集成AI模型管理：与阿丘的工业AI算法平台AIDI无缝协同，支持模型调用、推理及全链路管理，省去算法集成环节

### AQCV（传统视觉算法库）
多语言支持：提供C++、C#、Python接口，兼容Windows/Linux系统。
工业级工具链：包含定位（模板匹配）、测量（Blob分析）、OCR等核心算法

## Saige（思特威视）
### SaigeVision
国产工业视觉平台：专注于工业检测领域，提供2D/3D视觉算法库和图形化开发工具。
深度学习集成：支持缺陷检测、分类等复杂任务，提供预训练模型适配工具。
硬件兼容性：支持主流工业相机（海康、Basler）和运动控制卡（雷赛、固高）。

## Neurocle（韩国纽酷尔）
### Neuro-T
深度学习驱动：以AI视觉为核心，主打“零代码”自动化模型训练与部署。
全流程工具链：从数据标注、模型训练到嵌入式设备推理一站式解决。

## 华睿（浙江华睿科技）
### MVP
国产全栈方案：硬件（工业相机、智能读码器）+ 软件（MVP算法平台）深度集成。
行业垂直化：深耕物流、纺织、汽车零部件等领域，提供行业专用工具包。
高性能计算：支持多相机同步采集和GPU加速（基于NVIDIA CUDA）。