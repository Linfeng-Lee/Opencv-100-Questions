# Opencv的100道题目
## 1-10题的题目：
### 1-20需要引入头文件：A_1_10.h
- [通道交换](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A1.cpp "通道交换")
- [灰度化](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A2.cpp "灰度化")
- [二值化](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A3.cpp "二值化")
- [大津二值化算法](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A4.cpp "大津二值化算法")
- [RGB->HSV色域变换](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A5.cpp "RGB->HSV色域变换")
- [减色处理](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A6.cpp "减色处理")
- [平均池化](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A7.cpp "平均池化")
- [最大池化](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A8.cpp "最大池化")
- [高斯滤波](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A9.cpp "高斯滤波")
- [中值滤波](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A10.cpp "中值滤波")

## 1-10题重要算法解析：
### 一维高斯分布
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/一维高斯分布.png)
### 二维高斯分布
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/二维高斯分布.png)
### 最大类内方差
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/最大类内方差1.png)
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/最大类内方差2.png)


## 11-10题的题目：
- [均值滤波器](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A11.cpp "均值滤波器")
- [Motion Filter](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A12.cpp "Motion Filter")
- [MAX-MIN滤波器](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A13.cpp "MAX-MIN滤波器")
- [差分滤波器](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A14.cpp "差分滤波器")
- [Sobel滤波器](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A15.cpp "Sobel滤波器")
- [Prewitt滤波器](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A16.cpp "Prewitt滤波器")
- [Laplacian滤波器](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A17.cpp "Laplacian滤波器")
- [Emboss滤波器](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A18.cpp "Emboss滤波器")
- [LoG滤波器](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A19.cpp "LoG滤波器")
- [直方图(C++)](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A20.cpp "直方图")
- [直方图(python)](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A20.py "直方图")
### 11-20需要引入头文件：A_11_20.h
11-20题全是关于滤波器的题目
### 什么是边缘？
边缘一般是指图像中某一局部强度剧烈变化的区域。强度变化一般有2中情况，阶跃效应和屋顶效应。而边缘检测的任务就是找到具有阶跃变化或者屋顶变化的像素点的集合。
边缘检测基本原理：
- 对于阶跃效应：一阶微分的峰值为边缘点，二阶微分的零点为边缘点。
具体来说，从阶跃效应的那张图可以看到边缘处的斜率（一阶导）最大，所以一阶微分的峰值是边缘点，而斜率是先增大后减小的，即边缘点的二阶导为0处。
#### 阶跃效应
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/阶跃效应.png)

- 对于屋顶效应：一阶微分的零点为边缘点，二阶微分的峰值为边缘点。
#### 屋顶效应
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/屋顶效应.png)


## 11-20题重要算法解析：
### 均值滤波器
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/均值滤波卷积核.png)
### 运动滤波器
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/运动滤波器.png)
### MAX-MIN滤波器(效果图)
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/max-min.png)
### 差分滤波器
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/垂直滤波器.png)

![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/水平滤波器.png)

### Sobel滤波器
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/Sobel卷积核.png)
### Prewitt滤波器
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/prewitt算子.png)
### Laplacian滤波器
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/4领域拉普拉斯算子.png)
### Emboss滤波器
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/Emboss算子.png)
### LoG滤波器
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/高斯拉普拉斯算子.png)
### 直方图
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/直方图.png)

## 21-30题的题目：
### 11-20需要引入头文件：A_21_30.h
- [直方图归一化](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A21.cpp "直方图归一化")
- [直方图操作](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A22.cpp "直方图操作")
- [直方图均衡化](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A23.cpp "直方图均衡化")
- [伽玛校正](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A24.cpp "伽玛校正")
- [最邻近插值](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A25.cpp "最邻近插值")
- [双线性插值](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A26.cpp "双线性插值")
- [双三次插值](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A27.cpp "双三次插值")
- [仿射变换-平行移动](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A28.cpp "仿射变换-平行移动")
- [仿射变换-放大缩小](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A29.cpp "仿射变换-放大缩小")
- [仿射变换-旋转](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/A30.cpp "仿射变换-旋转")

## 21-30题重要算法解析：
### 均值方差均方差
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/均值方差标准差.jpg)
### 伽马矫正
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/伽马矫正.png)
### 最邻近插值
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/最邻近插值.png)
### 双线性插值
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/双线性插值1.png)
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/双线性插值2.png)
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/双线性插值4.png)
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/双线性插值3.png)
### BiCubic函数
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/BiCubic函数.png)
### 双三次插值
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/双三次插值2.png)
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/双三次插值1.png)
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/双三次插值5.png)
### 齐次坐标系到笛卡尔坐标系转换
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/齐次到笛卡尔坐标.png)
### 放射变换
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/仿射变换1.png)
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/仿射变换2.png)
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/仿射变换3.png)
#### 平移量为0的仿射变换
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/平移量为0的仿射变换.png)  
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/仿射变换4.png)  
![GitHub set up](https://github.com/omega-Lee/Opencv-100-Questions/blob/master/images/放射变换5.png)

