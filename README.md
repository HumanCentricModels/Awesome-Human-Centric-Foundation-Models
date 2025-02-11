# Awesome-Human-Centric-Foundation-Models [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![PR's Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](http://makeapullrequest.com) ![visitors](https://visitor-badge.laobi.icu/badge?page_id=HumanCentricModels.Awesome-Human-Centric-Foundation-Models) 

## 🏠 About
Here is a curated list of papers about **H**uman-**c**entric **F**oundation **M**odels (**HcFM**) with strong generalization, board applicability, and high fidelity.
According to the supported downstream tasks, HcFMs can be divided into four categories: 
Human-centric perception foundation models, 
Human-centric AIGC foundation models, 
Human-centric Foundation Models for Unified Perception and Generation Modeling, 
and Human-centric Agentic Foundation models.


The repository is updated regularly.  If you find it useful, please kindly star ⭐ this repo and [cite](#citation) the paper.

#### [How to submit a pull request?](https://github.com/hitcslj/Awesome-AIGC-3D/blob/main/how-to-PR.md)


## Table of Contents
- [Awesome-Human-Centric-Foundation-Models](#awesome-human-centric-foundation-models)
  - [Human-centric perception foundation models](#human-centric-perception-foundation-models)
  - [Human-centric AIGC foundation models](#human-centric-aigc-foundation-models)
  - [Human-centric Foundation Models for Unified Perception and Generation Modeling](#human-centric-foundation-models-for-unified-perception-and-generation-modeling)
  - [Human-centric Agentic Foundation models](#human-centric-agentic-foundation-models)
  - [Talks](#talks)
  - [Related workshops](#related-workshops)

## Human-centric perception foundation models
|    Date    |  Keywords  | Paper                                                                                                                                                                                 | Publication | Others |
|:----------:|:----------:| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:-----------:| :---------: |
| 2024-12-19 |   RefHCM   | [RefHCM: A Unified Model for Referring Perceptions in Human-Centric Scenarios](https://arxiv.org/abs/2412.14643) |    Arxiv    | [github](https://github.com/JJJYmmm/RefHCM)|
| 2024-10-20 |    PBoB    | [Efficient Multi-modal Human-Centric Contrastive Pre-training with a Pseudo Body-Structured Prior](https://link.springer.com/chapter/10.1007/978-981-97-8620-6_8)|   PRCV'24   | - |
| 2024-8-22  |  Sapiens   |[Sapiens: Foundation for Human Vision Models](https://arxiv.org/abs/2408.12569)|   ECCV'24    | [project](https://about.meta.com/realitylabs/codecavatars/sapiens)|
| 2024-7-14  | MMPedstron |[When Pedestrian Detection Meets Multi-Modal Learning: Generalist Model and Benchmark Dataset](https://arxiv.org/abs/2407.10125)|    ECCV'24|   [github](https://github.com/BubblyYi/MMPedestron)|
| 2023-12-9  |   HQNet    | [You Only Learn One Query: Learning Unified Human Query for Single-Stage Multi-Person Multi-Task Human-Centric Perception](https://arxiv.org/abs/2312.05525) | ECCV'24| [github](https://github.com/lishuhuai527/COCO-UniHuman)|
| 2023-12-4  |    Hulk    | [Hulk: A Universal Knowledge Translator for Human-Centric Tasks](https://arxiv.org/abs/2312.01697) |    Arxiv    | [github](https://github.com/OpenGVLab/Hulk)|
| 2023-10-31 |    HAP     | [HAP: Structure-Aware Masked Image Modeling for Human-Centric Perception](https://arxiv.org/abs/2310.20695) | NeurIPS'23  | [github](https://github.com/junkunyuan/HAP)|
| 2023-3-30  |  SOLIDER   | [Beyond Appearance: a Semantic Controllable Self-Supervised Learning Framework for Human-Centric Visual Tasks](https://arxiv.org/abs/2303.17602) |   CVPR'23   | [github](https://github.com/tinyvision/SOLIDER) |
| 2023-3-10  |    PATH    | [HumanBench: Towards General Human-centric Perception with Projector Assisted Pretraining](https://arxiv.org/abs/2303.05675)|   CVPR'23   | [github](https://github.com/OpenGVLab/HumanBench)|
|  2023-3-6  |   UniHCP   | [UniHCP: A Unified Model for Human-Centric Perceptions](https://arxiv.org/abs/2303.02936) |   CVPR'23   | [github](https://github.com/OpenGVLab/UniHCP) |
|  2023-2-2  |  LiftedCL  | [LiftedCL: Lifting Contrastive Learning for Human-Centric Perception](https://openreview.net/forum?id=WHlt5tLz12T) |   ICLR'23   | [github](https://github.com/RichardChen20/LiftedCL)|
| 2022-3-25  |   HCMOCO   | [Versatile Multi-Modal Pre-Training for Human-Centric Perception](https://arxiv.org/abs/2203.13815) |   CVPR'22   | [github](https://github.com/hongfz16/HCMoCo) |


## Human-centric AIGC foundation models
|   Date   |  Keywords  | Paper                                                                                                                                                                                 | Publication | Others |
|:--------:|:----------:| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |:-----------:| :---------: |
| 2025-2-3 |   OmniHuman| [OmniHuman-1: Rethinking the Scaling-Up of One-Stage Conditioned Human Animation Models](https://arxiv.org/abs/2502.01061) | Arxiv | [project](https://omnihuman-lab.github.io/) |
|2024-5-27| Human4DiT | [Human4DiT: 360-degree Human Video Generation with 4D Diffusion Transformer](https://arxiv.org/abs/2405.17405)| ToG'24| [project](https://human4dit.github.io/)
|2024-4-1| CosmicMan| [CosmicMan: A Text-to-Image Foundation Model for Humans](https://arxiv.org/abs/2404.01294)| CVPR'24| [project](https://cosmicman-cvpr2024.github.io/) | 
|2023-10-12|HyperHuman| [HyperHuman: Hyper-Realistic Human Generation with Latent Structural Diffusion](https://arxiv.org/abs/2310.08579)| ICLR'24|[project](https://snap-research.github.io/HyperHuman/) |
|2023-9-25| UnitedHuman| [UnitedHuman: Harnessing Multi-Source Data for High-Resolution Human Generation](https://arxiv.org/abs/2309.14335)| ICCV'23| [project](https://unitedhuman.github.io/)|
|2023-9-5| AniPortraitGAN| [AniPortraitGAN: Animatable 3D Portrait Generation from 2D Image Collections](https://arxiv.org/abs/2309.02186)|SIGGRAPH Asia'23| [github](https://github.com/kathrinawu/AniPortraitGAN)|
|2023-5-3|AG3D| [AG3D: Learning to Generate 3D Avatars from 2D Image Collections](https://arxiv.org/abs/2305.02312)| ICCV'23| [project](https://zj-dong.github.io/AG3D/)|
|2023-4-9|HumanSD| [HumanSD: A Native Skeleton-Guided Diffusion Model for Human Image Generation](https://arxiv.org/abs/2304.04269)| CVPR'23| [project](https://idea-research.github.io/HumanSD/)
|2022-4-25|StypleGAN-Human| [StyleGAN-Human: A Data-Centric Odyssey of Human Generation](https://arxiv.org/abs/2204.11823)| ECCV'22|[project](https://stylegan-human.github.io/)|
|2020-7-7|SofGAN|[SofGAN: A Portrait Image Generator with Dynamic Styling](https://arxiv.org/abs/2007.03780)| ToG'22| [project](https://apchenstu.github.io/sofgan/)|


## Human-centric Foundation Models for Unified Perception and Generation Modeling
|    Date    |  Keywords   | Paper                                                                                                                                                                                 | Publication | Others |
|:----------:|:-----------:| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------: |
| 2024-12-1  |     LOM     | [The Language of Motion: Unifying Verbal and Non-verbal Language of 3D Human Motion](https://arxiv.org/abs/2412.10523) | Arxiv| [project](https://languageofmotion.github.io/)  |
| 2024-12-1  | ChatGarment | [ChatGarment: Garment Estimation, Generation and Editing via Large Language Models](https://arxiv.org/abs/2412.17811)| Arxiv| [project](https://chatgarment.github.io/)  |
| 2024-11-9  |   UniPose   | [UniPose: A Unified Multimodal Framework for Human Pose Comprehension, Generation and Editing](https://arxiv.org/abs/2411.16781)|Arxiv | - |
| 2024-10-17 | MotionGPT-2 | [MotionGPT-2: A General-Purpose Motion-Language Model for Motion Generation and Understanding](https://arxiv.org/abs/2410.21747)|Arxiv | - |
|  2024-6-1|     FaceGPT        |[FaceGPT: Self-supervised Learning to Chat about 3D Human Faces](https://arxiv.org/abs/2406.07163)| Arxiv| - |
|2024-5-17|M3-GPT| [M3GPT: An Advanced Multimodal, Multitask Framework for Motion Comprehension and Generation](https://arxiv.org/abs/2405.16273)|NeurIPS'24|[github](https://github.com/luomingshuang/M3GPT)|
|2024-5-17|ChatHuman|[ChatHuman: Language-driven 3D Human Understanding with Retrieval-Augmented Tool Reasoning](https://arxiv.org/abs/2405.04533)|ECCV'24|[github](https://github.com/linjing7/ChatHuman)|
|2024-5-17|MotionLLM|[MotionLLM: A Conversational Framework for Human Motion Generation with LLMs](https://arxiv.org/abs/2405.17013)|Arxiv|[project](https://knoxzhao.github.io/MotionLLM/)|
|2024-3-8|CoMo|[CoMo: Controllable Motion Generation through Language Guided Pose Code Editing](https://arxiv.org/abs/2403.13900)|ECCV’24|[github](https://github.com/yh2371/CoMo)|

## Human-centric Agentic Foundation models
|   Date    |  Keywords   | Paper                                                                                                                                                                                 | Publication |                               Others                               |
|:---------:|:-----------:| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: |:------------------------------------------------------------------:|
| 2024-7-15 | superPADL| [Superpadl: Scaling language-directed physics-based control with progressive supervised distillation](https://dl.acm.org/doi/pdf/10.1145/3641519.3657492?casa_token=ujkwAenPDpMAAAAA:FfVzH0p2G9GRHrg5lXcEhkvWXZqXUwEdZVlVfOgZO3PQSyPiblMfel_pGFFtk2mw8BPxmmLbtkQa)| SIGGRAPH'24| [project](https://research.nvidia.com/labs/toronto-ai/super_padl/) |
|2024-6-28| HumanVLA| [HumanVLA: Towards Vision-Language Directed Object Rearrangement by Physical Humanoid](https://arxiv.org/abs/2406.19972)| Arxiv|          [project](https://github.com/AllenXuuu/HumanVLA)          |
|2024-3-28| Puppeteer| [Hierarchical World Models as Visual Whole-Body Humanoid Controllers](https://arxiv.org/abs/2405.18418)| Arxiv|          [project](https://nicklashansen.com/rlpuppeteer)          |
| 2024-3-18| Project GR00T| [Project GR00T](https://nvidianews.nvidia.com/news/foundation-model-isaac-robotics-platform) | Nvidia Announcement|        [project](https://developer.nvidia.com/isaac/gr00t/)        |


## Talks
- [Learning foundation models for 3D humans: a data request](https://www.dropbox.com/scl/fi/s5cnkmnzxx5hb3o2uiagm/SiyuTang.mp4?rlkey=bf729wf0bmicwsm7biz4ygve4&st=hpv5zjkw&dl=0), Siyu Tang
- [Human Models for Embodied AI](https://www.dropbox.com/scl/fi/2cb6ua4x9dzqe5tdidlql/ECCVW2024_HumanFoundation_Xavier.mp4?rlkey=5scm64sv60w6wcolu5xx78esg&st=ai4x8egp&dl=0), Xavier Puig
- [Towards Anatomically Correct Digital Human: From Imaging to Foundation Models](https://www.dropbox.com/scl/fi/w529zzoony2p834vtxkps/ECCVW2024_HumanFoundation_Jingyi.mp4?rlkey=pnh061apolg5if8hnbd3dkrwn&st=hwvs5k0m&dl=0), Jingyi Yu

## Related workshops
- [Human-Centric Representation Learning Workshop at AAAI 2024](https://hcrl-workshop.github.io/2024/schedule.html)
- [Foundation Models for 3D Humans Workshop at ECCV 2024](https://human-foundation.github.io/workshop-eccv-2024/)
- [The 5th International Workshop on Human-centric Multimedia Analysis at ACM MM24](https://hcma2024.github.io/)

## License 
Awesome Human-centric foundation models is released under the [MIT license](./LICENSE).

## Acknowledgement
We're very grateful to the repository creators of "[Awesome-LLM-3D](https://github.com/ActiveVisionLab/Awesome-LLM-3D)" and "[Awesone-AIGC-3D](https://github.com/hitcslj/Awesome-AIGC-3D)" for their well-organized template, which helped us structure our survey paper's GitHub repository.


[//]: # (## Citation)

[//]: # (If you find this project useful in your research, please consider citing:)

[//]: # (```BibTeX)

[//]: # ()
[//]: # (```)

## Contact
contact: `tangshixiang2016@gmail.com` and `wy024@ie.cuhk.edu.hk`.  
