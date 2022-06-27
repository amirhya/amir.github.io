---
title: "Signal detection and classification in shared spectrum: A deep learning approach"
collection: publications
permalink: /publication/infocom21_paper
excerpt: 'Machine learning, signal classification, coexistence, convolutional neural networks, recurrent neural networks,
dynamic spectrum access, software-defined radio.'
date: May 2021
venue: 'IEEE INFOCOM 2021, Virtual'
paperurl: 'infocom21.pdf'
#citation: 'Zhang, W., Feng, M., Krunz, M. and Abyaneh, A.H.Y., 2021, May. Signal detection and classification in shared spectrum: A deep learning approach. In IEEE INFOCOM 2021-IEEE Conference on Computer Communications (pp. 1-10). IEEE.'
---

Accurate identification of the signal type in a sharedspectrum scenario is critical for fair allocation of channel access. It facilitates scheduling the transmissions of coexisting systems (e.g., Wi-Fi, LTE LAA, and 5G NR-U) and avoids collisions, especially when spectrum dynamics change rapidly. In this work, we develop deep neural networks (DNNs) to detect coexisting signal types based on In-phase/Quadrature (I/Q) samples without decoding. By using segments of the samples of the received signal as input, a Convolutional Neural Network (CNN) and a Recurrent Neural Network (RNN) are combined and trained using categorical cross-entropy (CE) optimization. The classification results show high accuracy for the proposed DNN, even when the received signal is under the mixture. We then exploit spectrum analysis of I/Q sequences to further improve the classification accuracy. By applying Short-time Fourier Transform (STFT), additional information in the frequency domain can be gained. Accordingly, we enlarge the input size of the DNN. To verify the effectiveness of the proposed detection framework, we conduct over-the-air (OTA) experiments using USRP radios. The RF signal is transmitted between antennas and is then captured to evaluate the classification performance of our approach.

[Download paper](https://amirhya.github.io/amir.github.io//publications/infocom21.pdf)

[Link to conference draft](https://ieeexplore.ieee.org/abstract/document/9488834)



