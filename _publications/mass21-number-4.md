---
title: "CWmin Estimation and Collision Identification in Wi-Fi Systems"
collection: publications
permalink: publications/mass21_paper
excerpt: 'Jensen-Shannon DIvergence, Cross-corrleation, Wi-Fi, Markovian Analysis'
date: May 2021
venue: 'IEEE MASS 2021, Virtual'
paperurl: 'mass21.pdf'
#citation: 'A. -H. Yazdani-Abyaneh and M. Krunz, "CWmin Estimation and Collision Identification in Wi-Fi Systems," 2021 IEEE 18th International Conference on Mobile Ad Hoc and Smart Systems (MASS), 2021, pp. 490-498, doi: 10.1109/MASS52906.2021.00067.'
---

Wi-Fi networks are susceptible to aggressive behavior caused by selfish or malicious devices that reduce their minimum contention window size (CWmin) to below the standard CWmin. In this paper, we propose a scheme called Minimum Contention Window Estimation (CWE) to detect aggressive stations with low CWmin’s, where the AP estimates the CWmin value of all stations transmitting uplink by monitoring their backoff values over a period of time and keeping track of the idle time each station spends during backoff. To correctly estimate each backoff value, we present a cross-correlation based technique that uses the frequency offset between the AP and each station to identify stations involved in uplink collisions. The AP constructs empirical distributions for the monitored backoff values and compares them with a set of nominal PMF’s, created via Markov analysisof the DCF protocol to estimate CWmin of various stations. After detecting the aggressive stations, the AP can choose to stopserving those stations. Simulation results show that the accuracy of our collision detection technique is 96%, 94%, and 88% when there are 3, 6, and 9 stations in the WLAN, respectively. For the former WLAN settings, the estimation accuracy of CWE scheme is 100%, 98.81%, and 96.3%, respectively


[Download paper](https://amirhya.github.io/amir.github.io//publications/mass21.pdf)

[Link to conference draft](https://ieeexplore.ieee.org/document/9637728)
