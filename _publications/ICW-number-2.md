---
title: "Intelligent-CW: AI-based framework for controlling contention window in WLANs"
collection: publications
permalink: publications/ICW_paper
excerpt: 'CSMA/CA, Random Forests, CWmin, Wi-FI, 5G NR-U, LTE-LAA'
date: November 2019
venue: 'IEEE DySPAN 2019, Newark, NJ, USA'
paperurl: 'ICW.pdf'

#citation: 'A. H. Y. Abyaneh, M. Hirzallah and M. Krunz, "Intelligent-CW: AI-based Framework for Controlling Contention Window in WLANs," 2019 IEEE International Symposium on Dynamic Spectrum Access Networks (DySPAN), 2019, pp. 1-10, doi: 10.1109/DySPAN.2019.8935851.'
---
The heterogeneity of technologies that operate over the unlicensed 5 GHz spectrum, such as LTE-Licensed-AssistedAccess (LAA), 5G New Radio Unlicensed (NR-U), and WiFi, calls for more intelligent and efficient techniques to coordinate channel access beyond what current standards offer. Wi-Fi standards require nodes to adopt a fixed value for the minimum contention window (CWmin), which prohibits a node from reacting to aggressive nodes that set their CWmin to small values. To address this problem, we propose a framework called Intelligent-CW (ICW) that allows nodes to adapt their CWmin values based on observed transmissions, ensuring they receive their fair share of the channel airtime. The CWmin value at a node is set based on a random forest, a machine learning model that includes a large number of decision trees. We train the random forest in a supervised manner over a large number of WLAN scenarios, including different misbehaving and aggressive scenarios. Under aggressive scenarios, our simulation results reveal that ICW provides nodes with higher throughput (153.9% gain) and 64% lower frame latency than standard techniques. In order to measure the fairness contribution of individual nodes, we introduce a new fairness metric. Based on this metric, ICW is shown to provide 10.89× improvement in fairness in aggressive scenarios compared to standard techniques.


[Download paper](https://amirhya.github.io/amir.github.io//publications/ICW.pdf)

[Link to conference draft](https://ieeexplore.ieee.org/abstract/document/8935851)
