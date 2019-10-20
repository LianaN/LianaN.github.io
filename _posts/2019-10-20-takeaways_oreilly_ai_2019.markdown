---
layout: post
title:  "Takeaways from O'Reilly AI 2019 (London)"
date:   2019-10-20 10:00:00 +0200
tag:
- conference
- o'reilly
- AI
category: blog
author: liananapalkova
---

My takeaways from the recent <a href="https://www.oreilly.com/radar/highlights-from-ai-london-2019/" target="_blank">O'Reilly AI conference (London)</a>:

<p style="text-align:center;"><img src="/images/conferences/2019/oreilly.jpg" width="700" /></p>


## Reinforcement learning (RL)
RL starts finding its way into more application fields and more companies (Amazon, Ericsson, Adobe, etc.). For example, deep RL has already outperformed supervised learning and rule-based models to personalize product recommendations.

<p style="text-align:center;"><img src="/images/conferences/2019/oreilly_drl.jpg" width="700" /></p>

*Figure 1. Ian Massingham (Amazon Web Services). "Start Your Engines: Making Deep Reinforcement Learning Accessible to All Developers"*


* Open-source libraries for reinforcement learning:
	- <a href="https://rllib.io" target="_blank">RLlib</a>: supports TensorFlow, TensorFlow Eager, and PyTorch
	- <a href="https://github.com/ray-project/ray" target="_blank">Ray</a>: a framework for building and running distributed applications (RLlib is built on top of Ray)
	- <a href="https://github.com/facebookresearch/ReAgent" target="_blank">ReAgent</a> (previously known as Horizon): supports PyTorch
* Relevant research papers:
	- <a href="https://arxiv.org/abs/1811.00260" target="_blank">Gaud J. et. al. (2019) Horizon: Facebook’s Open Source Applied Reinforcement Learning Platform</a>
	- <a href="https://youtu.be/HEqQ2_1XRTs" target="_blank">Chen M. et. al. (2019) Reinforcement Learning for Recommender Systems: A Case Study on Youtube</a>
	- <a href="https://arxiv.org/abs/1805.02343" target="_blank">Zhao X. et. al. (2018) Deep Reinforcement Learning for Page-wise Recommendations</a>
	
	
## Federated Learning (FL)
FL enables model training on decentralised data that are distributed over millions of mobile devices. The goal is to provide highly personalized models, while reducing the costs and risks related to sensitive data handling.
Google already uses FL at scale to enable predictive input capabilities in the Android keyboard (Gboard), on-device search for Pixel phones, etc.

<p style="text-align:center;"><img src="/images/conferences/2019/fa1.jpg" width="700" /></p>

*Figure 2. Alex Ingerman (Google). "Federated learning introduction and examples with TensorFlow Federated"*

* <a href="http://tensorflow.org/federated" target="_blank">TensorFlow Federated</a>: an open-source framework that enables all ML developers to experiment with federated technologies.


## Generative Adversarial Networks (GANs)
There is a growing adoption of GANs for an automated language generation.

<p style="text-align:center;"><img src="/images/conferences/2019/gan.jpg" width="700" /></p>

*Figure 3. Rajib Biswas (Ericsson). "Adversarial network for natural language systhesis"*

* Models: SeqGAN, LeakGAN, MaskGAN:
* Capturing nuances and semantics of natural languages (especially, for longer sentences) is still an open issue.
* Relevant research papers:
	- <a href="https://arxiv.org/abs/1801.07736" target="_blank">Fedus W. et. al. (2018) MaskGAN: Better Text Generation via Filling in the______</a>
	- <a href="https://arxiv.org/abs/1709.08624" target="_blank">Guo J. et. al. (2017) Long Text Generation via Adversarial Training with Leaked Information</a>
	- <a href="https://arxiv.org/pdf/1609.05473.pdf" target="_blank">Yu L. et. al. (2017) SeqGAN: Sequence Generative Adversarial Nets with Policy Gradient</a>


## Data pre-processing

"AI starts with good data". Some tasks of data cleaning and enrichment can be automated using machine learning.

<p style="text-align:center;"><img src="/images/conferences/2019/holoclean.jpg" width="700" /></p>

*Figure 4. Ihab	Ilyas (University of Waterloo). "A Scalable Prediction Engine for Automating Structured Data Prep"*

* <a href="https://github.com/HoloClean/HoloClean" target="_blank">HoloClean</a> - a statistical inference engine to impute, clean, and enrich structured data built on top of PyTorch and PostgreSQL


## Building and deploying AI applications at scale
Many talks were dedicated to building and deploying scalable AI pipelines.

<p style="text-align:center;"><img src="/images/conferences/2019/iot_edge.jpg" width="700" /></p>

*Figure 5. Yan Zhang and Mathew Salvaris (Microsoft). "Deploying machine learning models on the edge"*

* How to analyze data on devices, a.k.a. "at the edge", instead of in the cloud <a href="https://github.com/microsoft/deploy-MLmodels-on-iotedge" target="_blank">Demo - Deploy ML models on Azure IoT Edge</a>
* <a href="https://github.com/Microsoft/DistributedDeepLearning" target="_blank">Distributed training reference architecture (Azure)</a>
* <a href="https://github.com/Microsoft/AKSDeploymentTutorialAML" target="_blank">How to deploy a pretrained deep learning model on a GPU enabled Kubernetes cluster throught Azure Machine Learning (AzureML)</a>
* <a href="https://github.com/ray-project/ray/tree/master/python/ray/autoscaler" target="_blank">How to setup a cluster (examples for AWS and Kubernetes) using Ray framework</a>


## Useful utilities:

* <a href="https://github.com/nteract/papermill" target="_blank">Papermill -  a tool for parameterizing, executing, and analyzing Jupyter Notebooks</a>
* <a href="https://github.com/google/python-fire" target="_blank">Python Fire - a tool for automatically generating CLIs from any Python object</a>
* <a href="https://github.com/cookiecutter/cookiecutter#python" target="_blank">Cookiecutter - a tool for creating projects from project templates</a>


## A bit of humor:

* Dramatized vision of what a rush hour may look like in the future - <a href="https://vimeo.com/106226560" target="_blank">Artwork of Fernando Livschitz</a>
* <a href="https://federated.withgoogle.com" target="_blank">Comic from Google AI: Federated Learning</a>



