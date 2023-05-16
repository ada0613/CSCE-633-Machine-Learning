# Improving Generalization of Deep AUC Maximization for Medical Image Classification

## Abstract
Deep AUC Maximization (DAM) has shown promising results in various machine learning applications, including medical image classification tasks. However, its generalization capability is often limited when applied to small datasets, leading to overfitting. This project aims to improve the generalization of DAM for medical image classification tasks on small datasets.

## Introduction
DAM has emerged as a powerful technique for learning deep neural networks by maximizing the AUC score of a model on a dataset. Despite its successful applications in various machine learning tasks, its generalization ability is often hindered when applied to small datasets, resulting in overfitting. This repository contains the code and resources associated with the study that aims to address this limitation and enhance the generalization of DAM for medical image classification tasks, specifically when working with small datasets.

## Dataset
The experiments were conducted using the MedMNIST dataset. You can download the dataset from [here](https://github.com/MedMNIST/MedMNIST).

## Methodology
Experiments were conducted on seven medical image classification tasks from the MedMNIST dataset, utilizing the LibAUC library. Different network structures were explored to improve the performance of DAM on these tasks, with a focus on surpassing the benchmark results reported in the MedMNIST paper.

For 2-D datasets, such as BreastMNIST, PneumoniaMNIST, and ChestMNIST, the ResNet-18 architecture was employed. For 3-D datasets, including NoduleMNIST3D, AdrenalMNIST3D, VesselMNIST3D, and SynapseMNIST3D, ResNet-18 combined with a 3D extension was utilized.

## Results
Through a comprehensive approach involving multiple directions of improvement, this project demonstrates innovative ideas to enhance the generalization of LibAUC. The findings of this study contribute to the development of more robust and generalizable DAM-based models for medical image classification tasks, particularly when dealing with small datasets.

## References
1. Jiancheng Yang, Rui Shi, DonglaiWei, Zequan Liu, Lin Zhao, Bilian Ke, Hanspeter Pfister, and
Bingbing Ni. "MedMNIST v2 - a large-scale lightweight benchmark for 2d and 3d biomedical
image classification." _Scientific Data_, 10(1), Jan 2023.
2. He, Kaiming, Xiangyu Zhang, Shaoqing Ren, and Jian Sun. "Deep residual learning for image recognition." _In Proceedings of the IEEE conference on computer vision and pattern recognition_, pp. 770-778. 2016.
3. Hara, Kensho, Hirokatsu Kataoka, and Yutaka Satoh. "Can spatiotemporal 3d cnns retrace the history of 2d cnns and imagenet?." _In Proceedings of the IEEE conference on Computer Vision and Pattern Recognition_, pp. 6546-6555. 2018.
4. Yuan, Zhuoning and Qiu, Zi-Hao and Li, Gang and Zhu, Dixian and Guo, Zhishuai and Hu, Quanqi and Wang, Bokun and Qi, Qi and Zhong, Yongjian and Yang, Tianbao. 2022. "LibAUC: A Deep Learning Library for X-risk Optimization." [https://libauc.org/](https://libauc.org/)

