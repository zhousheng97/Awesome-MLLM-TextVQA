# Awesome-MLLM-SceneTextVQA

✨✨This repository includes MLLM works on the Scene-Text VQA tasks.

## Introduction 

- Scene-Text Visual Question Answering (Scene-Text VQA) is a task where models answer questions based on textual information within visual scenes (**images or videos**), requiring both scene text recognition and reasoning.
- With the rise of Multimodal Large Language Models (MLLMs), this task is crucial for enhancing scene text-aware multimodal understanding. It pushes MLLMs to **integrate visual-textual information** and **improve real-world applications** like document understanding and assistive technologies.

# Table of Contents

- **Awesome Papers**
  - [Image-based Multimodal Large Language Models](#image-based-multimodal-large-language-models)
  - [Video-based Multimodal Large Language Models](#video-based-multimodal-large-language-models)
  - [Others](#others)

- **Awesome Datasets**
  - [Image Datasets](#image-datasets)
  - [Video Datasets](#video-datasets)
  - [Synthetic Datasets](#synthetic-datasets)
  - [Domain-specific Datasets](#domain-specific-datasets)
  - [Others](#others-1)

---

## Awesome Papers

### Image-based Multimodal Large Language Models


| Title | Venue | Date | Code | Demo |
|-------|-------|------|------|------|
| [Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond](https://llava-vl.github.io/blog/2024-01-30-llava-next/) [![GitHub stars](https://img.shields.io/github/stars/QwenLM/Qwen-VL?style=social)](https://github.com/QwenLM/Qwen-VL)| arXiv | 2023-10-13 | [GitHub](https://github.com/QwenLM/Qwen-VL) | Local Demo  |
| [BLIVA: A Simple Multimodal LLM for Better Handling of Text-rich Visual Questions](https://arxiv.org/pdf/2308.09936) [![GitHub stars](https://img.shields.io/github/stars/yfzhang114/SliME?style=social)](https://github.com/mlpc-ucsd/BLIVA)| AAAI | 2023-12-18 | [GitHub](https://github.com/mlpc-ucsd/BLIVA) |  Local Demo |
| [LLaVA-NeXT: Improved reasoning, OCR, and world knowledge](https://llava-vl.github.io/blog/2024-01-30-llava-next/) [![GitHub stars](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-NeXT?style=social)](https://github.com/LLaVA-VL/LLaVA-NeXT)| arXiv | 2024-01-30 | [GitHub](https://github.com/LLaVA-VL/LLaVA-NeXT) | -  |
| [Feast Your Eyes: Mixture-of-Resolution Adaptation for Multimodal Large Language Models](https://arxiv.org/pdf/2403.03003) [![GitHub stars](https://img.shields.io/github/stars/luogen1996/LLaVA-HR?style=social)](https://github.com/luogen1996/LLaVA-HR)| arXiv | 2024-03-05 | [GitHub](https://github.com/luogen1996/LLaVA-HR) | Local Demo  |
| [Monkey: Image Resolution and Text Label Are Important Things for Large Multi-modal Models](https://arxiv.org/pdf/2311.06607) [![GitHub stars](https://img.shields.io/github/stars/Yuliang-Liu/Monkey?style=social)](https://github.com/Yuliang-Liu/Monkey)| CVPR | 2024-02-27 | [GitHub](https://github.com/Yuliang-Liu/Monkey) | Local Demo  |
| [CogCoM: Train Large Vision-Language Models Diving into Details through Chain of Manipulations](https://arxiv.org/pdf/2402.04236) [![GitHub stars](https://img.shields.io/github/stars/THUDM/CogCoM?style=social)](https://github.com/THUDM/CogCoM)| arXiv | 2024-02-06 | [GitHub](https://github.com/THUDM/CogCoM) | [Demo](https://github.com/THUDM/CogCoM/blob/main/cogcom/demo/web_demo.py)  |
| [CogVLM: Visual Expert for Pretrained Language Models](https://arxiv.org/pdf/2311.03079) [![GitHub stars](https://img.shields.io/github/stars/THUDM/CogVLM?style=social)](https://github.com/THUDM/CogVLM)| arXiv | 2024-02-04 | [GitHub](https://github.com/THUDM/CogVLM) |Local Demo   |
| [CogAgent: A Visual Language Model for GUI Agents](https://arxiv.org/pdf/2312.08914) [![GitHub stars](https://img.shields.io/github/stars/THUDM/CogVLM?style=social)](https://github.com/THUDM/CogVLM)| CVPR (Highlight) | 2024-04-05 | [GitHub](https://github.com/THUDM/CogVLM) | Local Demo  |
| [MiniCPM-V: A GPT-4V Level MLLM on Your Phone](https://arxiv.org/pdf/2408.01800) [![GitHub stars](https://img.shields.io/github/stars/OpenBMB/MiniCPM-V?style=social)](https://github.com/OpenBMB/MiniCPM-V)| arXiv | 2024-05-23 | [GitHub](https://github.com/OpenBMB/MiniCPM-V) | [Demo](https://huggingface.co/spaces/OpenBMB/MiniCPM-V)  |
| [Beyond LLaVA-HD: Diving into High-Resolution Large Multimodal Models](https://arxiv.org/pdf/2406.08487) [![GitHub stars](https://img.shields.io/github/stars/yfzhang114/SliME?style=social)](https://github.com/yfzhang114/SliME)| arXiv | 2024-06-14 | [GitHub](https://github.com/yfzhang114/SliME) | -  |




### Video-based Multimodal Large Language Models
| Title | Venue | Date | Code | Demo |
|-------|-------|------|------|------|
| [MiniCPM-V 2.6: A GPT-4V Level MLLM for single image, multi-image and video understanding](https://arxiv.org/pdf/2408.01800) [![GitHub stars](https://img.shields.io/github/stars/OpenBMB/MiniCPM-V?style=social)](https://github.com/OpenBMB/MiniCPM-V)| arXiv | 2024-08-06 | [GitHub](https://github.com/OpenBMB/MiniCPM-V) | [Demo](http://120.92.209.146:8887/)  |
| [ShareGPT4Video: Improving Video Understanding and Generation with Better Captions](https://arxiv.org/pdf/2409.12191) [![GitHub stars](https://img.shields.io/github/stars/ShareGPT4Omni/ShareGPT4Video?style=social)](https://github.com/ShareGPT4Omni/ShareGPT4Video)| NeurIPS D&B track | 2024-10-01 | [GitHub](https://github.com/ShareGPT4Omni/ShareGPT4Video) | [Demo](https://huggingface.co/spaces/Lin-Chen/ShareCaptioner-Video)  
| [Qwen2-VL: Enhancing Vision-Language Model’s Perception of the World at Any Resolution](https://arxiv.org/pdf/2409.12191) [![GitHub stars](https://img.shields.io/github/stars/QwenLM/Qwen2-VL?style=social)](https://github.com/QwenLM/Qwen2-VL)| arXiv | 2024-10-03 | [GitHub](https://github.com/QwenLM/Qwen2-VL) | [Demo](https://huggingface.co/spaces/Qwen/Qwen2-VL)  |
| [Video Instruction Tuning with Synthetic Data](https://arxiv.org/pdf/2410.02713) [![GitHub stars](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-NeXT?style=social)](https://github.com/LLaVA-VL/LLaVA-NeXT)| arXiv | 2024-10-04 | [GitHub](https://github.com/LLaVA-VL/LLaVA-NeXT) | [Demo](https://huggingface.co/spaces/Tonic/Llava-Video)  |
| [VILA: Optimized Vision Language Models](https://arxiv.org/pdf/2412.04468) [![GitHub stars](https://img.shields.io/github/stars/NVlabs/VILA?style=social)](https://github.com/NVlabs/VILA)| arXiv | 2024-12-05 | [GitHub](https://github.com/NVlabs/VILA) | [Demo](https://vila.mit.edu/)  |
| [CogVLM2: Visual Language Models for Image and Video Understanding](https://arxiv.org/pdf/2408.16500) [![GitHub stars](https://img.shields.io/github/stars/THUDM/CogVLM2?style=social)](https://github.com/THUDM/CogVLM2)| arXiv | 2024-08-29 | [GitHub](https://github.com/THUDM/CogVLM2) | [Demo](http://cogvlm2-online.cogviewai.cn:7868/)  |
| [LongVILA: Scaling Long-Context Visual Language Models for Long Videos](https://arxiv.org/pdf/2408.10188) [![GitHub stars](https://img.shields.io/github/stars/NVlabs/VILA?style=social)](https://github.com/NVlabs/VILA/tree/main/longvila)| arXiv | 2024-12-13 | [GitHub](https://github.com/NVlabs/VILA/tree/main/longvila) | [Demo](https://huggingface.co/Efficient-Large-Model)  |


### Others

---

## Awesome Datasets

### Image Datasets

### Video Datasets


### Synthetic Datasets


### Domain-specific Datasets

### Others




