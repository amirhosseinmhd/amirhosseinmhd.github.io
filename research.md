---
layout: page
title: Research
custom_class: research-page
order: 1
---

## Research Assistant, York University
**Jan 2024 - Present** | Toronto, Canada
*Supervisor: [Dr. Hina Tabassum](https://www.eecs.yorku.ca/~hinat/)*

Our work focuses on inferring from highly noisy sensory data—specifically Wi-Fi Channel State Information (CSI). The goal is to make sensing from this data modality more practical for real-world scenarios.

**Reformulating of The Activity Recognitoin Problem**: On the first step, we reformulated the inference problem where multiple subjects perform different activities simultaneously as a set prediction problem. Building on this formulation, we proposed a novel attention-based architecture tailored to this domain. 

**Edge-Cloud Architecture Friendly**: To enable practical deployment, we developed a split design with an extremely lightweight backbone (~118K parameters) residing at edge devices for feature extraction. We further designed an ultra-low error quantization scheme that uses only 0.2% of the original bandwidth to transmit features to the cloud, dramatically reducing communication costs while maintaining performance. The contributions have been compiled into a manuscript submitted to IEEE TNNLS ([preprint](https://drive.google.com/file/d/1dVKppsO394Ga2lzDtE2oBjuVBvVD6MyR/view?usp=sharing)).

![System Architecture](/detailed_diagaram-1.png)

**Learning without Labels**: To leverage the abundance of unlabeled Wi-Fi data accumulated in routers, we are developing methods to learn structure from data without supervision. Using a predictive architecture inspired by JEPA combined with VICReg-like regularization, we aim to pre-train models that discover useful representations from unannotated sensory data.

![RepLearning](/JEPA_Architecture.png)


---

## Research Assistant, Aalto University

**Nov 2022 - April 2023** | Helsinki, Finland
*Supervisor: [Dr. Alexander Jung](https://users.aalto.fi/~junga1/)*

Our work addressed federated learning in highly heterogeneous environments where individual data generators lack sufficient data for training large models. The key challenges here were that participants had heterogeneous data distributions and varying computational resources, yet needed to collaborate in a privacy-preserving manner.

**Collaborative Learning in Heterogeneous Environment**: We proposed an algorithm where each participant selects a hypothesis space tailored to their computational constraints, then identifies collaborators with similar data distributions using zeroth-order selection criteria while receiving gradient updates—preserving privacy while enabling effective collaboration. Our analysis demonstrates that this approach achieves oracle-level performance despite the unkown graph strcture. 

The work is detailed in our [preprint](https://arxiv.org/pdf/2409.02064) and source code can be found in [Github](https://github.com/amirhosseinmhd/clustered_federated_learning)

![Client Selection](/Selection_of_Clients.gif)

---

## Notable Projects

### Energy-Based Transformer Models for Text Generation

**Fall 2025 - Present**

Developing energy-based transformer architectures for text generation tasks, focusing on reformulating sequence modeling as an energy minimization problem, in hope to develop system two thinkers.

### Self-Supervised Learning for CSI Representation Learning

**Spring 2024**

Implemented contrastive self-supervised learning frameworks (SimCLR, DirectCLR) for Channel State Information data representation without relying on labeled data. Demonstrated competitive performance with supervised methods while using unlabeled datasets from SignFi.

### Implementing Various Generative Models from Scratch

**Spring 2025**

During Deep Generative Modelling course, implemented various generative models from scratch including VAEs, Diffusion Models, and GANs. Focused on understanding the theoretical foundations and practical implementations of these models using PyTorch.

### AI-Generated Code Evaluation Using Log Probability

**Fall 2024**

Developed a probabilistic framework for evaluating LLM-generated Python code without execution, combining statistical analysis with ML classifiers. Validated on HumanEval and MBPP benchmarks, showing significant improvements in scalability over traditional execution-based testing.

### Open-set Speech Synthesizer Models Classification

**Spring 2022**

Developed a Transformer-based model for open-set synthetic speech classification using self-supervised learning (wav2vec 2.0) and a two-stage architecture for handling unknown synthesis methods. Presented at ICASSP.

### Persian Music Genre Classification

**Winter 2022**

Implemented classic ML models (XGBoost, MLP, SVM) for Persian music genre classification with full ML pipeline from data collection to evaluation using Librosa and Surfboard.
