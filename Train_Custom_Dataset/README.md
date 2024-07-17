# 标注自己的数据集，训练、评估、测试、部署自己的人工智能算法

代码测试[云GPU环境](https://www.runpod.io/)：GPU RTX 3060、CUDA v11.8

![计算机视觉解决的基本问题](https://zihao-download.obs.cn-east-3.myhuaweicloud.com/img_bed/20220803/cv_fund.png)

## 图像分类

### 构建自己的图像分类数据集

收集图像、下载样例数据集，删除系统多余文件，划分训练集、测试集，统计图像尺寸、比例分布、拍照地点位置分布，统计各类别图像数量

<https://www.bilibili.com/video/BV1Jd4y1T7rw>

### 【Pytorch】ImageNet预训练图像分类模型预测

使用Pytorch自带的预训练图像分类模型，分别对单张图像、视频、摄像头实时画面运行图像分类预测

<https://www.bilibili.com/video/BV1qe4y1D7zD>

### 【Pytorch】迁移学习Fine-tuning训练自己的图像分类模型

<https://www.bilibili.com/video/BV1Ng411C7WY>

### 【Pytorch】用训练得到的pytorch图像分类模型，识别图像、视频、摄像头画面

<https://www.bilibili.com/video/BV12d4y1P7xz>

### 测试集评估

计算各类别分类评估指标，绘制混淆矩阵、PR曲线、ROC曲线。

<https://www.bilibili.com/video/BV1bP411j7NK>

### 测试集语义特征降维可视化

抽取Pytorch训练得到的图像分类模型中间层的输出特征，作为输入图像的语义特征。计算测试集所有图像的语义特征，使用t-SNE和UMAP两种降维方法降维至二维和三维，可视化。

<https://www.bilibili.com/video/BV1VB4y1z7xN>

### 可解释性分析、显著性分析

CAM热力图系列算法：<https://www.bilibili.com/video/BV1JG4y1s74x>

## 单目标追踪（蜜蜂追踪）

<https://www.bilibili.com/video/BV1za411Y7Zm>

## 视频人流量计数+足迹追踪

<https://www.bilibili.com/video/BV1za411Y7Zm>

## 大模型摘要生成

<https://www.bilibili.com/video/BV1W44y1g7cB>

## CycleGAN图像风格迁移

<https://www.bilibili.com/video/BV1wv4y1T71F>

## OCR文字识别

<https://www.bilibili.com/video/BV1Ua411x7dB>
