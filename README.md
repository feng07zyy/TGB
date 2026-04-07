# TGB

Official repository for the paper **"Stealthy and Adjustable Text-Guided Backdoor Attacks on Multimodal Pretrained Models"**.

> This repository is currently under construction.  
> The full source code will be released after the paper is accepted.

## Overview

TGB is a **text-guided backdoor attack** designed for multimodal pretrained models. TGB uses **naturally occurring words in textual descriptions** as triggers, making the attack more practical and stealthy in real-world applications. In addition, TGB introduces **visual adversarial perturbations** on poisoned samples to modulate how strongly the model learns the textual trigger. This enables a **controllable and adjustable** backdoor attack, allowing the attack success rate to be flexibly increased or suppressed under different settings. Extensive experiments on downstream multimodal tasks, including **Composed Image Retrieval (CIR)** and **Visual Question Answering (VQA)**, demonstrate that TGB can achieve strong attack effectiveness while largely preserving benign performance, revealing important security vulnerabilities in multimodal pretrained models.

## Acknowledgements

Parts of this repository are built upon or inspired by previous excellent open-source projects. We sincerely thank the authors for making their code and research publicly available.

- [CLIP4Cir](https://github.com/ABaldrati/CLIP4Cir)
- [PubMedCLIP](https://github.com/sarahESL/PubMedCLIP)
- [CLIP](https://github.com/openai/CLIP)

## Citation
