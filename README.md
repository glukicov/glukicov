## Hey there 👋 

[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://glukicov.github.io)

I am Gleb Lukicov, a machine learning engineer with a passion for **MLOps**. Visit [my homepage](https://glukicov.github.io) to read about my PhD research and ML projects. When I am not de-bugging my code, I am actively engaged in the [MLOps Community London](https://luma.com/aaif-london) as a co-host, 📝 [tech blogging](https://medium.com/@lukicov), or 🚴‍♂️ <a href=https://glukicov.github.io/#interests>road cycling</a>. You can contact me for collaborations ideas or questions on [LinkedIn](https://www.linkedin.com/in/glukicov/).


The projects below contain analysis code used in my PhD thesis and personal ML projects:

#### 1. [`EDMTracking`](https://github.com/glukicov/EDMTracking) code to perform Fourier transforms and regression analysis on large datasets. 
The Muon <i>g − 2</i> experiment at Fermilab, near Chicago, [discovered a tantalising sign of New Physics (a new force of nature!)](https://www.bbc.co.uk/news/science-environment-66407099). This was done by measuring a deviation between the experimental and theoretically predicted value of the muon magnetic anomaly. As part of [my PhD](https://glukicov.github.io/#research), I collaborated on the experiment with 200 scientists and engineers. This project contains analysis code to measure the Electric Dipole Moment (EDM) of the muon using the tracking detectors. The oscillation in the number of the observed tracks in the detector can be plotted and fitted, as shown below: 

<div style="text-align:center"><img src="https://raw.githubusercontent.com/glukicov/EDMTracking/master/docs/edm.gif" height="250" /></div>

#### 2. [`llm_pipelines_demo`](https://github.com/glukicov/llm_pipelines_demo?tab=readme-ov-file) End-to-end demo of local and remote pipelines with Kubeflow and Vertex AI.
To make your systems data-centric and model-agnostic, a robust evaluation framework is essential. Pipelines are particularly useful for this purpose. I demonstrate how to implement local testing using Kubeflow Pipelines to shorten the development cycle using Docker cache, multi-stage builds, dynamic user credentials injection, and experiment tracking on Google Cloud. 
Also included are infrastructure goodies like GitHub CI/CD & `pre-commit` config for *linting* and *testing*, local scripts with `typer`, project dependency management with `uv`, and static checking with `mypy`. This repo is a companion to [this blog post](https://medium.com/@lukicov/ml-pipelines-in-the-age-of-llms-from-local-containers-to-cloud-experiments-1b688dcebee5).

<div style="text-align:center"><img src="https://raw.githubusercontent.com/glukicov/llm_pipelines_demo/main/docs/imgs/demo.png" height="100" /></div>

#### 3. [`slideops`](https://github.com/glukicov/slideops) Turn a repository into a slide deck that tells you when it stops matching the code.
Your documentation is a build artifact, so it is worth treating it like one. **SlideOps** is a pair of Agent Skills: one turns a repository into a single-file HTML slide deck, the other tells you when that deck stops matching the code. Every reference in the deck carries its source file, the exact line range, and a hash of those lines, so the check costs zero tokens and runs in milliseconds. This repo is a companion to [this blog post](https://medium.com/@lukicov/your-documentation-is-a-build-artifact-start-treating-it-like-one-ab48df61b1e0).

<div style="text-align:center"><img src="https://raw.githubusercontent.com/glukicov/glukicov/master/images/x-hero-card.png" width="600" /></div>

#### 4. [`ML_GPU`](https://github.com/glukicov/ML_GPU) contains personal practice ML code, and Deep Learning on GPUs using `scikit-learn`, `TensorFlow` and `Keras`.

I wrote a practical guide on setting a personal GPU server for Machine Learning with Ubuntu 20.04 <a href=https://towardsdatascience.com/set-up-of-a-personal-gpu-server-for-machine-learning-with-ubuntu-20-04-100e787105ad target="_blank"> avaialbe on the Towards Data Science (TDS) website</a>.

<div style="text-align:center"><img src="https://raw.githubusercontent.com/glukicov/ML_GPU/master/docs/gpu.jpeg" height="200" /></div>
<i>Photo by Caspar Camille Rubin on Unsplash.</i>
