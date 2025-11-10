---
layout: page
title: Research
custom_class: research-page
---

## Research Assistant, York University
**Jan 2024 - Present** | Toronto, Canada
*Supervisor: [Dr. Hina Tabassum](https://www.eecs.yorku.ca/~hinat/)*

Our work focuses on inferring from highly noisy sensory data—specifically Wi-Fi Channel State Information (CSI). The goal is to make sensing from this data modality more practical for real-world scenarios.

**Reformulating of The Activity Recognitoin Problem**: On the first step, we reformulated the inference problem where multiple subjects perform different activities simultaneously as a set prediction problem. Building on this formulation, we proposed a novel attention-based architecture tailored to this domain. 

**Edge-Cloud Friendly**: To enable practical deployment, we developed a split design with an extremely lightweight backbone (~118K parameters) residing at edge devices for feature extraction. We further designed an ultra-low error quantization scheme that uses only 0.2% of the original bandwidth to transmit features to the cloud, dramatically reducing communication costs while maintaining performance. The contributions have been compiled into a manuscript submitted to IEEE TNNLS ([preprint](https://drive.google.com/file/d/1dVKppsO394Ga2lzDtE2oBjuVBvVD6MyR/view?usp=sharing)).

![System Architecture](/detailed_diagaram-1.png)

**Learning without Labels**: To leverage the abundance of unlabeled Wi-Fi data accumulated in routers, we are developing methods to learn structure from data without supervision. Using a predictive architecture inspired by JEPA combined with VICReg-like regularization, we aim to pre-train models that discover useful representations from unannotated sensory data.

![RepLearning](/JEPA_Architecture.png)


---

## Research Assistant, Aalto University

**Nov 2022 - Feb 2023** | Helsinki, Finland
*Supervisor: [Dr. Alexander Jung](https://users.aalto.fi/~junga1/)*

- Developed a novel model-agnostic federated learning algorithm enabling heterogeneous model architectures
- Implemented knowledge distillation techniques for efficient information distribution in federated networks
- Extended the framework to handle non-networked datasets using regret minimization principles
- Co-authored paper submitted to JML ([arXiv:2409.02064](https://arxiv.org/abs/2409.02064))

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
