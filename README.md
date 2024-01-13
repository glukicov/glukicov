## Hey there 👋 

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://glukicov.github.io)

I am Gleb Lukicov, a machine learning engineer based in London with a passion for 🤩 MLOps. Visit [my homepage](https://glukicov.github.io) to read about my PhD research and ML projects. When I am not de-bugging my code, I am actively engaged in the 🚀 [MLOps Community London](https://mlops.community/) as a co-host, doing 📝 [tech blogging](https://medium.com/@lukicov), or 🚴‍♂️<a href=https://glukicov.github.io/#interests>road cycling</a>. You can [contact me](https://www.linkedin.com/in/glukicov/) with any questions and collaborations ideas.


The project repositories below contain some of the analysis code used in my PhD thesis and personal ML projects:

#### 1. [`EDMTracking`](https://github.com/glukicov/EDMTracking) contains analysis code (Python, C++, Bash) to perform Fourier transforms and regression on large datasets. 
The Muon <i>g − 2</i> experiment at Fermilab, near Chicago, [discovered a tantalising sign of New Physics (a new force of nature!)](https://www.bbc.co.uk/news/science-environment-66407099). This was done by measuring a deviation between the experimental and theoretically predicted value of the muon magnetic anomaly. As part of my PhD, I collaborated on the experiment with 200 scientists and engineers. 

This project contains analysis code to measure the Electric Dipole Moment (EDM) of the muon using the tracking detectors. The oscillation in the number of the observed tracks in the detector can be plotted and fitted, as shown below 

<div style="text-align:center"><img src="https://github.com/glukicov/EDMTracking/blob/master/docs/edm.gif" height="250" /></div>

#### 2. [`alignTrack`](https://github.com/glukicov/alignTrack) is the detector calibration codebase (C++, Python, Fortran) using iterative optimisation and data simulation.
This project contains code and plotting scripts for the internal alignment (calibration) of the tracking detector. The alignment procedure aims to establish the corrections to the assumed detector position, and hence, minimise the residuals. This minimisation of the residuals is a statistical problem, involving the optimisation of the <i>p</i>-values (i.e. track quality) of fitted tracks in data. 

This work led to a publication (arXiv:1909.12900): <a href=https://arxiv.org/pdf/1909.12900.pdf target="_blank"> https://arxiv.org/pdf/1909.12900.pdf</a>, where alignment results with data are discussed.

Alignment software infrastructure is shown below 

<div style="text-align:center"><img src="https://github.com/glukicov/alignTrack/blob/master/mpIIDESY/align_4.png" height="300" /></div>

#### 3. [`ML_GPU`](https://github.com/glukicov/ML_GPU) contains personal practice ML code, and Deep Learning on GPUs using scikit-learn, TensorFlow and Keras.

I wrote a practical guide on setting a personal GPU server for Machine Learning with Ubuntu 20.04 <a href=https://towardsdatascience.com/set-up-of-a-personal-gpu-server-for-machine-learning-with-ubuntu-20-04-100e787105ad target="_blank"> avaialbe on the Towards Data Science (TDS) website</a>

<div style="text-align:center"><img src="https://github.com/glukicov/ML_GPU/blob/master/docs/gpu.jpeg" height="200" /></div>
<i>Photo by Caspar Camille Rubin on Unsplash.</i>

<!--
**glukicov/glukicov** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
