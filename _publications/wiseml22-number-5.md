---
title: "Automatic Machine Learning for Multi-Receiver CNN Technology Classifiers"
collection: publications
permalink: /publication/wiseml22_paper
excerpt: 'Signal classification, CNN, AutoML, multi-receiver, HyperOpt, Hyperband, Wi-Fi, LTE-LAA, 5G NR-U, SDR'
date: May 20222
venue: 'ACM WiSec/WiseML 2022, San Antonio, TX, USA'
paperurl: 'wiseml22.pdf'
#citation: 'Amir-Hossein Yazdani-Abyaneh and Marwan Krunz. 2022. Automatic Machine Learning for Multi-Receiver CNN Technology Classifiers. In Proceedings of the 2022 ACM Workshop on Wireless Security and Machine Learning (WiseML '22). Association for Computing Machinery, New York, NY, USA, 39–44. https://doi.org/10.1145/3522783.3529524'
---
Convolutional Neural Networks (CNNs) are one of the most studied family of deep learning models for signal classification, including modulation, technology, detection, and identification. In this work, we focus on technology classification based on raw I/Q samples collected from multiple synchronized receivers. As an example use case, we study protocol identification of Wi-Fi, LTE-LAA, and 5G NR-U technologies that coexist over the 5 GHz Unlicensed National Information Infrastructure (U-NII) bands. Designing and training accurate CNN classifiers involve significant time and effort that goes to fine-tuning a model’s architectural settings (e.g., number of convolutional layers and their filter size) and determining the appropriate hyperparameter configurations, such as learning rate and batch size. We tackle the former by defining architectural settings themselves as hyperparameters. We attempt to automatically optimize these architectural parameters, along with other preprocessing (e.g., number of I/Q samples within each classifier input) and learning hyperparameters, by forming a Hyperparameter Optimization (HyperOpt) problem, which we solve in a near-optimal fashion using the Hyperband algorithm. The resulting near-optimal CNN (OCNN) classifier is then used to study classification accuracy for OTA as well as simulations datasets, considering various SNR values. We show that using a larger number of receivers to construct multi-channel inputs for CNNs does not necessarily improve classification accuracy. Instead, this number should be defined as a preprocessing hyperparameter to be optimized via Hyperband. OTA results reveal that our OCNN classifiers improve classification accuracy by 24.58% compared to manually tuned CNNs. We also study the effect of min-max normalization of I/Q samples within each classifier’s input on generalization accuracy over simulated datasets with SNRs other than training set’s SNR, and show an average of 108.05% improvement when I/Q samples are normalized


[Download paper](https://amirhya.github.io/amir.github.io//publications/wiseml22.pdf)

[Link to conference draft](https://dl.acm.org/doi/abs/10.1145/3522783.3529524)

[Link to presentation video](https://youtu.be/D_QUV2MzzaQ?t=15829)
