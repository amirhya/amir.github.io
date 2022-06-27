---
permalink: /
title: "Intelligent Wireless Conenctivity"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Biography
=========
Hi, everyone, I am Amir-Hossein Yazdani-Abyaneh!
I have been a graduate student at University of Arizona's ECE departement since January 2019. Before that I graduated from Amirkabir University of Technology (Tehran Polytechnique) in 2018 with a BSc in Electrical and Electronics Engineering with a concentration on telecommunicaitons.

My reserach interests are machine learning algorithms and protocols for spectrum sharing and homogeneious coexistence of heterogeneous technologies. I present a summary of my works in [Publications](https://amirhya.github.io/amir.github.io//publications/) and Industry work.


* Volunteer to teach children

<div align="center">
<img src="https://amirhya.github.io/amir.github.io//images/profile.jpg">
</div>
<br/>



Current Occupation
======
* I am currently working at NTT Docomo Innovations Inc as a Research Engineer Intern working on joint communication and sensing.

Research Experience
======
* Research Engineer Intern (May 2022 present): NTT Docomo Innovations Inc, Palo Alto, CA
  * Joint Communication and Sensing
* Research Engineer Intern (January 2022 - May 2022): ED2 Corporation, Tucson, AZ
  * mmWave 5G Demo:
    * Software: [Eurocom's Open Air Interface (OAI) 5G](https://gitlab.eurecom.fr/oai/openairinterface5g), bash scripts, and c programming
    * Hardware: mmWave antennas, mmWave reapeaters, and USRP B210s  
* Graduate Research Assistant (Januanry 2019 - May 2022): University of Arizona
  * Cross-Technology Coexistence in Unlicensed Bands Jan. 2019 – May 2022 
    * Wireless communication systems and protocols: OFDMA, TX/RX radio chain, 802.11 systems, LTE-LAA, 5G NR-U, successive interference cancellation, carrier frequency offset fingerprinting 
    * Machine learning algorithms: Conventional ML, CNN, RNN, and deep-QNN design (Python: sklearn, PyTorch, TensorFlow, Keras).
    * Radio hardware: NI/Ettus USRP, USRP RIO, USRP Flex RIOs configuration and setup, beginner LabVIEW FPGA programming, LabVIEW 802.11 application framework, LabVIEW communication design suite, Field-Fox Network and microwave analyzers, and Keysight MXA signal analyzer
    * Mathematics: Markov chain analysis, statistical inference, optimization, reinforcement learning theory, information theory
    * Signal processing: Cross-correlation-based identification algorithm design, digital filter design (Python and MATLAB)
    * Discrete-event simulators: 802.11 ac simulator design (C/C++ and ns-3)
  * Machine Learning Based Sensing in Unlicensed bands July 2022 - May 2022
    * Wireless communication systems and protocols: OFDM, MIMO communication and channel characterization, LTE and 5G frame construction and settings
    * Machine learning algorithms: Neural architecture search and hyper parameter optimization algorithms (Python: Keras and KerasTuner)
    * Radio hardware: Multiple transmitter/receiver synchronization, MATLAB SDR toolbox
    * Signal processing: FFT, STFT, moving average/max
    * HPC: Remote learning-job submission and automatic job creation (VSCode, Linux) on Google colab and UofA computing servers
  * RFI Mitigation of Terrestrial Transmitters with Radio Astronomy Telescopes Sep. 2020 - May 2022
    * Interference mitigation: Telescope radiation pattern modeling, link budget analysis based on ITU-R RA recommendations, beam-forming, interference learning with distributed-sensor networks
    * Experimentation: Over the air transmissions of Wi-Fi waveforms with USRPs (using LabVIEW ) at the SMT telescope (in Mt. Grahm, Tucson, AZ), telescope observational methods, telescope receiver characteristics
* Undergraduate Research Assistant (September 2017 - September 2018): Amirkabir University of Technology (tehran Polytechnique)
  * Wi-Fi Indoor Localization Using CSI:
    * CNN Learning Algorithm and Architectural Design: Double-input classification algorithm to train CNN for feature extraction and localization authentication (Tensorflow and Keras)
    * Statistical Learning: PCA and SPCA analysis (Python and MATLAB)
    * Experimentation: Gathering CSI from 5300i NIC’s with a modified firmware (Linux)


* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
