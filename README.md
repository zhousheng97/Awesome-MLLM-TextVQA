# Awesome-MLLM-TextVQA

✨✨This repository includes MLLM works on the real-world Scene-Text VQA tasks.

## Introduction 

- Text Visual Question Answering (TextVQA) is a task where models answer questions based on textual information within visual scenes (**images or videos**), requiring both scene text recognition and reasoning.
- With the rise of Multimodal Large Language Models (MLLMs), this task is crucial for enhancing scene-text-aware multimodal understanding. It pushes MLLMs to **integrate visual-textual information** and **improve real-world QA assistance**.

# Table of Contents

- **Awesome Datasets**
  - [Image Datasets](#image-datasets)
  - [Video Datasets](#video-datasets)
  
- **Awesome Papers**
  - [Image-based Multimodal Large Language Models](#image-based-multimodal-large-language-models)
  - [Video-based Multimodal Large Language Models](#video-based-multimodal-large-language-models)


---

## Awesome Datasets
### Image Datasets
| Name | Paper | Venue | Download Link | Split | Leaderboard |
|-------|-------|------|------|-------|-------|
| TextVQA | [Towards VQA Models That Can Read](https://arxiv.org/pdf/1904.08920) | CVPR | [GitHub](https://textvqa.org/) | train / val / test | |
| ST-VQA | [Scene Text Visual Question Answering](https://arxiv.org/pdf/1905.13648) | ICCV | [GitHub](https://rrc.cvc.uab.es/?ch=11) | train / val / test | |
| OCRBench | [OCRBench: On the Hidden Mystery of OCR in Large Multimodal Models](https://arxiv.org/pdf/2305.07895) | SCIS | [GitHub](https://github.com/Yuliang-Liu/MultimodalOCR/) | test |  [Link](https://huggingface.co/spaces/echo840/ocrbench-leaderboard) |
| OCRBench v2 | [OCRBench v2: An Improved Benchmark for Evaluating Large Multimodal Models on Visual Text Localization and Reasoning](https://arxiv.org/pdf/2501.00321) | arxiv | [GitHub](https://github.com/Yuliang-Liu/MultimodalOCR/) | test |  [Link](https://huggingface.co/spaces/ling99/OCRBench-v2-leaderboard) |


### Video Datasets
| Name | Paper | Venue | Download Link | Split | Leaderboard |
|-------|-------|------|------|-------|-------|
| M4viteVQA | [Towards Video Text Visual Question Answering: Benchmark and Baseline](https://arxiv.org/pdf/1905.13648) | NeurIPS'2022 | [GitHub](https://github.com/bytedance/VTVQA) | train / val / test | |
| RoadTextVQA | [Reading Between the Lanes: Text VideoQA on the Road](https://arxiv.org/html/2307.03948) | ICDAR'2023 | [GitHub](https://github.com/georg3tom/RoadtextVQA) | train / val / test | |
| NewsVideoQA | [Watching the News: Towards VideoQA Models that can Read](https://arxiv.org/abs/2211.05588) | WACV'2023 | [GitHub](https://github.com/soumyasj/NewsVideoQA) | test | [link](https://rrc.cvc.uab.es/?ch=24&com=evaluation&task=1)|
| ViTXT-GQA | [Scene-Text Grounding for Text-Based Video Question Answering](https://arxiv.org/abs/2409.14319) | arxiv'2024 | [GitHub](https://github.com/zhousheng97/ViTXT-GQA) | test | |
| EgoTextVQA | [EgoTextVQA: Towards Egocentric Scene-Text Aware Video Question Answering](https://arxiv.org/abs/2502.07411) | CVPR'2025 | [GitHub](https://github.com/zhousheng97/EgoTextVQA) | test | [Link](https://zhousheng97.github.io/EgoTextVQA_page/) |

---

## Awesome Papers
### Image-based Multimodal Large Language Models


| Title | Venue | Date | Code | Demo |
|-------|-------|------|------|------|
| [Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond](https://llava-vl.github.io/blog/2024-01-30-llava-next/) [![GitHub stars](https://img.shields.io/github/stars/QwenLM/Qwen-VL?style=social)](https://github.com/QwenLM/Qwen-VL)| arXiv | 2023-10-13 | [GitHub](https://github.com/QwenLM/Qwen-VL) | Local Demo  |
| [BLIVA: A Simple Multimodal LLM for Better Handling of Text-rich Visual Questions](https://arxiv.org/pdf/2308.09936) [![GitHub stars](https://img.shields.io/github/stars/yfzhang114/SliME?style=social)](https://github.com/mlpc-ucsd/BLIVA)| AAAI | 2023-12-18 | [GitHub](https://github.com/mlpc-ucsd/BLIVA) |  Local Demo |
| [InternVL: Scaling up Vision Foundation Models and Aligning for Generic Visual-Linguistic Tasks](https://arxiv.org/pdf/2312.14238) [![GitHub stars](https://img.shields.io/github/stars/OpenGVLab/InternVL?style=social)](https://github.com/OpenGVLab/InternVL)| CVPR (Oral) | 2024-01-15 | [GitHub](https://github.com/OpenGVLab/InternVL) | [Demo](https://internvl.opengvlab.com/) |
| [LLaVA-NeXT: Improved reasoning, OCR, and world knowledge](https://llava-vl.github.io/blog/2024-01-30-llava-next/) [![GitHub stars](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-NeXT?style=social)](https://github.com/LLaVA-VL/LLaVA-NeXT)| arXiv | 2024-01-30 | [GitHub](https://github.com/LLaVA-VL/LLaVA-NeXT) | -  |
| [Feast Your Eyes: Mixture-of-Resolution Adaptation for Multimodal Large Language Models](https://arxiv.org/pdf/2403.03003) [![GitHub stars](https://img.shields.io/github/stars/luogen1996/LLaVA-HR?style=social)](https://github.com/luogen1996/LLaVA-HR)| arXiv | 2024-03-05 | [GitHub](https://github.com/luogen1996/LLaVA-HR) | Local Demo  |
| [Monkey: Image Resolution and Text Label Are Important Things for Large Multi-modal Models](https://arxiv.org/pdf/2311.06607) [![GitHub stars](https://img.shields.io/github/stars/Yuliang-Liu/Monkey?style=social)](https://github.com/Yuliang-Liu/Monkey)| CVPR | 2024-02-27 | [GitHub](https://github.com/Yuliang-Liu/Monkey) | Local Demo  |
| [TextMonkey: An OCR-Free Large Multimodal Model for Understanding Document](https://arxiv.org/pdf/2403.04473) [![GitHub stars](https://img.shields.io/github/stars/Yuliang-Liu/Monkey?style=social)](https://github.com/Yuliang-Liu/Monkey)| arxiv | 2024-05-15 | [GitHub](https://github.com/Yuliang-Liu/Monkey/blob/main/monkey_model/text_monkey/README.md) | Local Demo  |
| [CogCoM: Train Large Vision-Language Models Diving into Details through Chain of Manipulations](https://arxiv.org/pdf/2402.04236) [![GitHub stars](https://img.shields.io/github/stars/THUDM/CogCoM?style=social)](https://github.com/THUDM/CogCoM)| arXiv | 2024-02-06 | [GitHub](https://github.com/THUDM/CogCoM) | [Demo](https://github.com/THUDM/CogCoM/blob/main/cogcom/demo/web_demo.py)  |
| [CogVLM: Visual Expert for Pretrained Language Models](https://arxiv.org/pdf/2311.03079) [![GitHub stars](https://img.shields.io/github/stars/THUDM/CogVLM?style=social)](https://github.com/THUDM/CogVLM)| arXiv | 2024-02-04 | [GitHub](https://github.com/THUDM/CogVLM) |Local Demo   |
| [CogAgent: A Visual Language Model for GUI Agents](https://arxiv.org/pdf/2312.08914) [![GitHub stars](https://img.shields.io/github/stars/THUDM/CogVLM?style=social)](https://github.com/THUDM/CogVLM)| CVPR (Highlight) | 2024-04-05 | [GitHub](https://github.com/THUDM/CogVLM) | Local Demo  |
| [MiniCPM-V: A GPT-4V Level MLLM on Your Phone](https://arxiv.org/pdf/2408.01800) [![GitHub stars](https://img.shields.io/github/stars/OpenBMB/MiniCPM-V?style=social)](https://github.com/OpenBMB/MiniCPM-V)| arXiv | 2024-05-23 | [GitHub](https://github.com/OpenBMB/MiniCPM-V) | [Demo](https://huggingface.co/spaces/OpenBMB/MiniCPM-V)  |
| [Beyond LLaVA-HD: Diving into High-Resolution Large Multimodal Models](https://arxiv.org/pdf/2406.08487) [![GitHub stars](https://img.shields.io/github/stars/yfzhang114/SliME?style=social)](https://github.com/yfzhang114/SliME)| arXiv | 2024-06-14 | [GitHub](https://github.com/yfzhang114/SliME) | -  |
| [Compression with Global Guidance: Towards Training-free High-Resolution MLLMs Acceleration](https://arxiv.org/pdf/2501.05179) [![GitHub stars](https://img.shields.io/github/stars/xuyang-liu16/GlobalCom2?style=social)](https://github.com/xuyang-liu16/GlobalCom2)| arXiv | 2025-01-09 | [GitHub](https://github.com/xuyang-liu16/GlobalCom2) | -  |
| [LLaVA-UHD v2: an MLLM Integrating High-Resolution Feature Pyramid via Hierarchical Window Transformer](https://arxiv.org/pdf/2412.13871) [![GitHub stars](https://img.shields.io/github/stars/thunlp/LLaVA-UHD?style=social)](https://github.com/thunlp/LLaVA-UHD)| arXiv | 2024-12-18 | [GitHub](https://github.com/thunlp/LLaVA-UHD) | -  |
| [Efficient Architectures for High Resolution Vision-Language Models](https://arxiv.org/pdf/2412.13871) [![GitHub stars](https://img.shields.io/github/stars/miguelscarv/pheye?style=social)](https://github.com/miguelscarv/pheye)| arXiv | 2025-01-05 | [GitHub](https://github.com/miguelscarv/pheye) | -  |




### Video-based Multimodal Large Language Models
| Title | Venue | Date | Code | Demo |
|-------|-------|------|------|------|
| [MiniCPM-V 2.6: A GPT-4V Level MLLM for single image, multi-image and video understanding](https://arxiv.org/pdf/2408.01800) [![GitHub stars](https://img.shields.io/github/stars/OpenBMB/MiniCPM-V?style=social)](https://github.com/OpenBMB/MiniCPM-V)| arXiv | 2024-08-06 | [GitHub](https://github.com/OpenBMB/MiniCPM-V) | [Demo](http://120.92.209.146:8887/)  |
| [ShareGPT4Video: Improving Video Understanding and Generation with Better Captions](https://arxiv.org/pdf/2409.12191) [![GitHub stars](https://img.shields.io/github/stars/ShareGPT4Omni/ShareGPT4Video?style=social)](https://github.com/ShareGPT4Omni/ShareGPT4Video)| NeurIPS D&B track | 2024-10-01 | [GitHub](https://github.com/ShareGPT4Omni/ShareGPT4Video) | [Demo](https://huggingface.co/spaces/Lin-Chen/ShareCaptioner-Video)  
| [Qwen2-VL: Enhancing Vision-Language Model’s Perception of the World at Any Resolution](https://arxiv.org/pdf/2409.12191) [![GitHub stars](https://img.shields.io/github/stars/QwenLM/Qwen2-VL?style=social)](https://github.com/QwenLM/Qwen2-VL)| arXiv | 2024-10-03 | [GitHub](https://github.com/QwenLM/Qwen2-VL) | [Demo](https://huggingface.co/spaces/Qwen/Qwen2-VL)  |
| [Video Instruction Tuning with Synthetic Data](https://arxiv.org/pdf/2410.02713) (LLaVA-Video) [![GitHub stars](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-NeXT?style=social)](https://github.com/LLaVA-VL/LLaVA-NeXT)| arXiv | 2024-10-04 | [GitHub](https://github.com/LLaVA-VL/LLaVA-NeXT) | [Demo](https://huggingface.co/spaces/Tonic/Llava-Video)  |
| [VILA: Optimized Vision Language Models](https://arxiv.org/pdf/2412.04468) [![GitHub stars](https://img.shields.io/github/stars/NVlabs/VILA?style=social)](https://github.com/NVlabs/VILA)| arXiv | 2024-12-05 | [GitHub](https://github.com/NVlabs/VILA) | [Demo](https://vila.mit.edu/)  |
| [CogVLM2: Visual Language Models for Image and Video Understanding](https://arxiv.org/pdf/2408.16500) [![GitHub stars](https://img.shields.io/github/stars/THUDM/CogVLM2?style=social)](https://github.com/THUDM/CogVLM2)| arXiv | 2024-08-29 | [GitHub](https://github.com/THUDM/CogVLM2) | [Demo](http://cogvlm2-online.cogviewai.cn:7868/)  |
| [LongVILA: Scaling Long-Context Visual Language Models for Long Videos](https://arxiv.org/pdf/2408.10188) [![GitHub stars](https://img.shields.io/github/stars/NVlabs/VILA?style=social)](https://github.com/NVlabs/VILA/tree/main/longvila)| arXiv | 2024-12-13 | [GitHub](https://github.com/NVlabs/VILA/tree/main/longvila) | [Demo](https://huggingface.co/Efficient-Large-Model)  |
| [Oryx MLLM: On-Demand Spatial-Temporal Understanding at Arbitrary Resolution](https://arxiv.org/pdf/2409.12961) [![GitHub stars](https://img.shields.io/github/stars/Oryx-mllm/Oryx?style=social)](https://github.com/Oryx-mllm/Oryx)| arXiv | 2024-09-19 | [GitHub](https://github.com/Oryx-mllm/Oryx) | [Demo](https://huggingface.co/spaces/THUdyh/Oryx)  |


### Others



