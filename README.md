# Awesome-Vision-Mamba-Models

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/Ruixxxx/Awesome-Vision-Mamba-Models?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/Ruixxxx/Awesome-Vision-Mamba-Models?style=flat-square)
[![Arxiv Page](https://img.shields.io/badge/Arxiv-2404.18861-red?style=flat-square)](https://arxiv.org/abs/2404.18861)

[NEWS.2024/11/10] **The latest version of our [paper](https://arxiv.org/abs/2404.18861v3) (v3) is now available! This update includes numerous high-quality papers on visual Mamba.**

[NEWS.2024/07/06] **The updated version of our [paper](https://arxiv.org/abs/2404.18861v2) is now available!**

[NEWS.2024/04/29] **Our [paper](https://arxiv.org/abs/2404.18861) is released!**

📢**NOTE:** If you have any questions, please don't hesitate to contact us at any of the following emails: [xurui7943@gmail.com](mailto:xurui7943@gmail.com), [syangcw@connect.ust.hk](mailto:syangcw@connect.ust.hk), [ywangrm@connect.ust.hk](mailto:ywangrm@connect.ust.hk), [yu.cai@connect.ust.hk](mailto:yu.cai@connect.ust.hk).

Mamba, a novel state space model, has gained recognition across diverse domains for its exceptional performance and efficient computational complexity. By addressing the limitations inherent in traditional visual foundation architectures, Mamba emerges as a promising contender poised to catalyze advancements in the field of computer vision.

:star: This repository hosts a curated collection of literature associated with Mamba models in computer vision. Feel free to star and fork. For further details, refer to the following paper:

**[Visual Mamba: A Survey and New Outlooks](https://arxiv.org/abs/2404.18861v2)**<br/>
Rui Xu, Shu Yang, Yihui Wang, Yu Cai, Bo Du, [Hao Chen](https://cse.hkust.edu.hk/~jhc/)<br/>
[SMART Lab](https://hkustsmartlab.github.io/), The Hong Kong University of Science and Technology<br/>
<br/>


## Contents
- [Mamba](#mamba)
- [Related Survey](#related-survey)
- [Visual Mamba Backbone Networks](#visual-mamba-backbone-networks)
- [Vision Application (Modality)](#vision-application)
  - [Image](#image)
    - [Natural Image](#natural-image)
    - [Remote Sensing Image](#remote-sensing-image)
    - [Medical Image](#medical-image)
  - [Video](#video)
  - [Point Cloud](#point-cloud)
  - [Multi-Modal](#multi-modal)
  - [Others](#others)
- [Valuable Insights](#valuable-insights)
- [Other Domains](#other-domains)
  - [Reinforcement Learning](#reinforcement-learning)
  - [Graph Learning](#graph-learning)
  - [Audio](#audio)
  - [Time Series](#time-series)

## Mamba
| Venue | Paper | Figure | Link | Code         |
| :-------- | :---- | :-------- | :--- | :----------- |
| COLM 2024 | Mamba: Linear-Time Sequence Modeling with Selective State Spaces | <img width="300" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/9b1d1ebf-213b-4aa8-8cc9-852a62c997bf"><br><img width="300" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/25b4bb74-5592-4953-8667-cb40ecc72914"> |[Link](https://arxiv.org/pdf/2312.00752)|[Code](https://github.com/state-spaces/mamba)|
| ICML 2024 | Transformers are SSMs: Generalized Models and Efficient Algorithms Through Structured State Space Duality | <img width="300" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/851656b3-b485-48d4-b7eb-51c0890c0e47"><br><img width="300" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/2605faae-8e96-4341-8468-d2d9a5e7c630"> |[Link](https://proceedings.mlr.press/v235/dao24a.html)|[Code](https://github.com/state-spaces/mamba)|
| ICLR 2026 | Mamba-3: Improved Sequence Modeling using State Space Principles | <img width="300" src="https://github.com/user-attachments/assets/e202c405-e904-4b3d-933b-b919478e7144" /> | [Link](https://openreview.net/forum?id=HwCvaJOiCj) | [Code](https://github.com/state-spaces/mamba) |

## Related Survey

| Venue | Paper | Link |
| :-------- | :---- | :-------- |
| Applied Sciences 2024 | A Survey on Visual Mamba | [Link](https://www.mdpi.com/2076-3417/14/13/5683) |
| Engineering Applications of AI 2025 | Mamba-360: Survey of State Space Models as Transformer Alternative for Long Sequence Modelling: Methods, Applications, and Challenges | [Link](https://www.sciencedirect.com/science/article/abs/pii/S0952197625012801) |
| IEEE TNNLS 2025 | Vision Mamba: A Comprehensive Survey and Taxonomy | [Link](https://doi.org/10.1109/TNNLS.2025.3610435) |
| ACM TIST 2026 | A Survey of Mamba | [Link](https://arxiv.org/pdf/2408.01129) |

## Visual Mamba Backbone Networks

| Venue | Paper | Link | Code         |
| :-------- | :---- | :--- | :----------- |
| ICML 2024 | Vision Mamba: Efficient Visual Representation Learning with Bidirectional State Space Model|[Link](https://proceedings.mlr.press/v235/zhu24f.html)|[Code](https://github.com/hustvl/Vim)|
| NeurIPS 2024 | VMamba: Visual State Space Model | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/baa2da9ae4bfed26520bb61d259a3653-Abstract-Conference.html) | [Code](https://github.com/MzeroMiko/VMamba) |
| ECCV 2024 Oral | Mamba-ND: Selective State Space Modeling for Multi-Dimensional Data | [Link](https://arxiv.org/pdf/2402.05892) | [Code](https://github.com/jacklishufan/Mamba-ND) |
| ECCV 2024 Workshop | LocalMamba: Visual State Space Model with Windowed Selective Scan| [Link](https://arxiv.org/pdf/2403.09338) | [Code](https://github.com/hunto/LocalMamba) |
| AAAI 2025 | EfficientVMamba: Atrous Selective Scan for Light Weight Visual Mamba | [Link](https://arxiv.org/pdf/2403.09977) | [Code](https://github.com/TerryPei/EfficientVMamba) |
| BMVC 2024 | PlainMamba: Improving Non-Hierarchical Mamba in Visual Recognition | [Link](https://arxiv.org/pdf/2403.17695) | [Code](https://github.com/ChenhongyiYang/PlainMamba) |
| NeurIPS 2024 | Multi-Scale VMamba: Hierarchy in Hierarchy Visual State Space Model | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/2d69e771d9f274f7c624198ea74f5b98-Abstract-Conference.html) | [Code](https://github.com/YuHengsss/MSVMamba) |
| NeurIPS 2024 | Vision Mamba Mender | [Link](https://openreview.net/pdf?id=9VnevS2YoR) | [Code](https://github.com/jiaconghu/Vision-Mamba-Mender) |
| NeurIPS 2024 | Exploring Token Pruning in Vision State Space Models | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/5af741d487c5f0b08bfe56e11d1883e4-Abstract-Conference.html) |  |
| NeurIPS 2024 | QuadMamba: Learning Quadtree-based Selective Scan for Visual State Space Model | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/d592bfaedf2f0861d7084cceba208d18-Abstract-Conference.html) | [Code](https://github.com/VISION-SJTU/QuadMamba) |
| WACV 2025 | PTQ4VM: Post-Training Quantization for Visual Mamba | [Link](https://openaccess.thecvf.com/content/WACV2025/html/Cho_PTQ4VM_Post-Training_Quantization_for_Visual_Mamba_WACV_2025_paper.html) | [Code](https://github.com/YoungHyun197/ptq4vm) |
| CVPR 2025 | Mamba-R: Vision Mamba Also Needs Registers | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_Mamba-Reg_Vision_Mamba_Also_Needs_Registers_CVPR_2025_paper.html) | [Code](https://github.com/wangf3014/Mamba-Reg) |
| PRICAI 2025 | Vim-F: Visual State Space Model Benefiting from Learning in the Frequency Domain | [Link](https://link.springer.com/chapter/10.1007/978-981-95-7084-3_23) | |
| ICLR 2025 | Autoregressive Pretraining with Mamba in Vision | [Link](https://openreview.net/forum?id=PQpvhUrA1C) | [Code](https://github.com/OliverRensu/ARM) |
| CVPR 2025 | MambaVision: A Hybrid Mamba-Transformer Vision Backbone | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Hatamizadeh_MambaVision_A_Hybrid_Mamba-Transformer_Vision_Backbone_CVPR_2025_paper.html) | [Code](https://github.com/NVlabs/MambaVision) |
| CVPR 2025 | GroupMamba: Parameter-Efficient and Accurate Group Visual State Space Model | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Shaker_GroupMamba_Efficient_Group-Based_Visual_State_Space_Model_CVPR_2025_paper.html) | [Code](https://github.com/Amshaker/GroupMamba) |
| ICCV 2025 | VSSD: Vision Mamba with Non-Causal State Space Duality | [Link](https://openaccess.thecvf.com/content/ICCV2025/html/Shi_VSSD_Vision_Mamba_with_Non-Causal_State_Space_Duality_ICCV_2025_paper.html) | [Code](https://github.com/YuHengsss/VSSD) |
| ICML 2025 | Stochastic Layer-Wise Shuffle: A Stochastic Training Technique for Vision Mamba Models | [Link](https://proceedings.mlr.press/v267/huang25d.html) |  |
| AAAI 2025 | SparX: A Sparse Cross-Layer Connection Mechanism for Hierarchical Vision Mamba and Transformer Networks | [Link](https://arxiv.org/abs/2409.09649) | [Code](https://github.com/LMMMEng/SparX) |
| IJCV 2026 | StableMamba: Distillation-free Scaling of Large SSMs for Images and Videos | [Link](https://doi.org/10.1007/s11263-026-02824-0) | |
| CVPR 2025 | MAP: Unleashing Hybrid Mamba-Transformer Vision Backbone's Potential with Masked Autoregressive Pretraining | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_MAP_Unleashing_Hybrid_Mamba-Transformer_Vision_Backbones_Potential_with_Masked_Autoregressive_CVPR_2025_paper.html) | [Code](https://github.com/yunxiangfu2001/MAP) |
| CVPR 2025 | Adventurer: Optimizing Vision Mamba Architecture Designs for Efficient Visual Recognition | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_Adventurer_Optimizing_Vision_Mamba_Architecture_Designs_for_Efficiency_CVPR_2025_paper.html) |  |
| ICLR 2025 | Spatial-Mamba: Effective Visual State Space Models via Structure-aware State Space Duality | [Link](https://arxiv.org/abs/2410.15091) | [Code](https://github.com/EdwardChasel/Spatial-Mamba) |
| CVPR 2025 | EfficientViM: Efficient Vision Mamba with Hidden State Mixer based State Space Duality | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Lee_EfficientViM_Efficient_Vision_Mamba_with_Hidden_State_Mixer_based_State_CVPR_2025_paper.html) | [Code](https://github.com/mlvlab/EfficientViM) |
| CVPR 2025 | MobileMamba: Lightweight Multi-Receptive Visual Mamba Network | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/He_MobileMamba_Lightweight_Multi-Receptive_Visual_Mamba_Network_CVPR_2025_paper.html) | [Code](https://github.com/lewandofski/MobileMamba) |
| ICCV 2025 | TinyViM: Frequency Decoupling for Tiny Hybrid Vision Mamba | [Link](https://openaccess.thecvf.com/content/ICCV2025/html/Ma_TinyViM_Frequency_Decoupling_for_Tiny_Hybrid_Vision_Mamba_ICCV_2025_paper.html) |  |
| CVPR 2025 | GG-SSMs: Graph-Generating State Space Models | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Zubic_GG-SSMs_Graph-Generating_State_Space_Models_CVPR_2025_paper.html) |  |
| ICLR 2025 | MambaQuant: Quantizing the Mamba Family with Variance Aligned Rotation Methods | [Link](https://openreview.net/forum?id=KI45uDnmzv) | [Code](https://github.com/mambaquant/mambaquant) |



## Vision Application
### Image

#### Natural Image

| Venue | Paper | Link | Code         | Task |
| :-------- | :---- | :--- | :----------- | :--- |
| ECCV 2024 | MambaIR: A Simple Baseline for Image Restoration with State-Space Model | [Link](https://arxiv.org/pdf/2402.15648) | [Code](https://github.com/csguoh/MambaIR) | Super-resolution/Denoising |
| IEEE TGRS 2024 | MiM-ISTD: Mamba-in-Mamba for Efficient Infrared Small Target Detection | [Link](https://arxiv.org/pdf/2403.02148) | [Code](https://github.com/txchen-USTC/MiM-ISTD) | Infrared Image Segmentation |
| IEEE TCSVT 2025 | VmambaIR: Visual State Space Model for Image Restoration | [Link](https://doi.org/10.1109/TCSVT.2025.3530090) | [Code](https://github.com/AlphacatPlus/VmambaIR) | Image Restoration |
| ECCV 2024 | ZigMa: A DiT-style Zigzag Mamba Diffusion Model | [Link](https://arxiv.org/pdf/2403.13802) | [Code](https://taohu.me/zigma/) | Generation |
| ACM MM 2024 | Learning Enriched Features via Selective State Spaces Model for Efficient Image Deblurring | [Link](https://doi.org/10.1145/3664647.3680624) |  | Image Deblurring |
| IEEE TPAMI 2025 | Gamba: Marry Gaussian Splatting with Mamba for single view 3D reconstruction | [Link](https://doi.org/10.1109/TPAMI.2025.3569596) | | 3D Reconstruction |
| NeurIPS 2024 | MambaAD: Exploring State Space Models for Multi-class Unsupervised Anomaly Detection | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/833b21da1956c6b92f6df253bf655cf5-Abstract-Conference.html) | [code](https://lewandofskee.github.io/projects/MambaAD) | Anomaly Detection |
| ACM MM 2024 | DGMamba: Domain Generalization via Generalized State Space Model | [Link](https://arxiv.org/pdf/2404.07794) | [Code](https://github.com/longshaocong/DGMamba) | Domain Generalization |
| ACM MM 2024 | FreqMamba: Viewing Mamba from a Frequency Perspective for Image Deraining | [Link](https://arxiv.org/pdf/2404.09476) | [Code](https://github.com/aSleepyTree/FreqMamba) | Deraining |
| MIPR 2024 | CU-Mamba: Selective State Space Models with Channel Learning for Image Restoration | [Link](https://doi.org/10.1109/MIPR62202.2024.00059) |  | Denoising/Deblurring |
| CVPR 2024 Workshop | DVMSR: Distillated Vision Mamba for Efficient Super-Resolution | [Link](https://arxiv.org/pdf/2405.03008) | [Code](https://github.com/nathan66666/DVMSR.git) | Super-Resolution |
| ICONIP 2024 | Retinexmamba: Retinex-based Mamba for Low-light Image Enhancement | [Link](https://doi.org/10.1007/978-981-96-6596-9_30) | [Code](https://github.com/YhuoyuH/RetinexMamba) | Image Enhancement |
| NeurIPS 2024 | MambaLLIE: Implicit Retinex-Aware Low Light Enhancement with Global-then-Local State Space | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/30699996ff411d48903c9752b782a5c1-Abstract-Conference.html) | [Code](https://mamballie.github.io/anon/) | Image Enhancement |
| WACV 2025 | SUM: Saliency Unification through Mamba for Visual Attention Modeling | [Link](https://openaccess.thecvf.com/content/WACV2025/html/Hosseini_SUM_Saliency_Unification_through_Mamba_for_Visual_Attention_Modeling_WACV_2025_paper.html) | [Code](https://github.com/Arhosseini77/SUM) | Visual Saliency Prediction |
| ECCV 2024 | MTMamba: Enhancing Multi-Task Dense Scene Understanding by Mamba-Based Decoders | [Link](https://arxiv.org/pdf/2407.02228) | [Code](https://github.com/EnVision-Research/MTMamba) | Multi-Task Dense Scene Understanding |
| ICML 2024 Workshop | Parallelizing Autoregressive Generation with Variational State Space Models | [Link](https://arxiv.org/pdf/2407.08415) |  | Generation |
| PRCV 2024 | ALMRR: Anomaly Localization Mamba on Industrial Textured Surface with Feature Reconstruction and Refinement | [Link](https://doi.org/10.1007/978-981-97-8692-3_27) | [Code](https://github.com/qsc1103/ALMRR) | Anomaly Localization |
| NeurIPS 2024 | Hamba: Single-view 3D Hand Reconstruction with Graph-guided Bi-Scanning Mamba | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/03e9a69e5b686c316a07d73f0cf5e225-Abstract-Conference.html) | [Code](https://humansensinglab.github.io/Hamba/) | 3D Hand Reconstruction |
| BMVC 2024 | MxT: Mamba x Transformer for Image Inpainting | [Link](https://bmvc2024.org/proceedings/295/) |  | Image Inpainting |
| WBIR 2024 Workshop | Mamba? Catch The Hype Or Rethink What Really Helps for Image Registration | [Link](https://arxiv.org/pdf/2407.19274) | [Code](https://github.com/rethink-reg) | Image Registration |
| ACM MM 2024 | Wave-Mamba: Wavelet State Space Model for Ultra-High-Definition Low-Light Image Enhancement | [Link](https://arxiv.org/pdf/2408.01276) | [Code](https://github.com/AlexZou14/Wave-Mamba) | Image Enhancement |
| AAAI 2025 | ZeroMamba: Exploring Visual State Space Model for Zero-Shot Learning | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/32366) | [Code](https://anonymous.4open.science/r/ZeroMamba/README.md) | Zero-Shot Learning |
| ICPR 2024 | DS MYOLO: A Reliable Object Detector Based on SSMs for Driving Scenarios | [Link](https://arxiv.org/pdf/2409.01093) |  | Object Detection |
| IEEE TITS 2025 | DSDFormer: An Innovative Transformer-Mamba Framework for Robust High-Precision Driver Distraction Identification | [Link](https://doi.org/10.1109/TITS.2025.3625645) |  | Driver Distraction Identification |
| IEEE TCSVT 2025 | Retinex-RAWMamba: Bridging Demosaicing and Denoising for Low-Light RAW Image Enhancement | [Link](https://doi.org/10.1109/TCSVT.2025.3589476) | [Code](https://github.com/Cynicarlos/RetinexRawMamba) | Image Enhancement |
| ECCV 2024 Workshop | Famba-V: Fast Vision Mamba with Cross-Layer Token Fusion | [Link](https://arxiv.org/pdf/2409.09808) | [Code](https://github.com/AIoT-MLSys-Lab/Famba-V) | Efficiency |
| WACV 2025 | Mamba-ST: State Space Model for Efficient Style Transfer | [Link](https://openaccess.thecvf.com/content/WACV2025/html/Han_Mamba-ST_State_Space_Model_for_Efficient_Style_Transfer_WACV_2025_paper.html) | [Code](https://github.com/FilippoBotti/MambaST) | Style Transfer |
| ACCV 2024 | OneBEV: Using One Panoramic Image for Bird's-Eye-View Semantic Mapping | [Link](https://arxiv.org/pdf/2409.13912) | [Code](https://github.com/JialeWei/OneBEV) | Bird's-Eye-View Semantic Mapping |
| Neurocomputing 2024 | MambaTSR: You only need 90k parameters for traffic sign recognition | [Link](https://www.sciencedirect.com/science/article/pii/S0925231224008750) | [Code](https://github.com/1024AILab/MambaTSR) | Traffic Sign Recognition |
| Scientific Reports 2024 | Toward identity preserving in face sketch-photo synthesis using a hybrid CNN-Mamba framework | [Link](https://www.nature.com/articles/s41598-024-72066-y) |  | Sketch-photo Synthesis |
| NeurIPS 2024 | Hybrid Mamba for Few-Shot Segmentation | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/86fe62e3b315d2578721562d9fd1a433-Abstract-Conference.html) | [Code](https://github.com/Sam1224/HMNet) | Few-Shot Segmentation |
| NeurIPS 2024 | START: A Generalized State Space Model with Saliency-Driven Token-Aware Transformation | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/63b2b056f48653b7cff0d8d233c96a4d-Abstract-Conference.html) | [Code](https://github.com/lingeringlight/START) | Domain Generalization |
| IJCV 2025 | Mamba Capsule Routing Towards Part-Whole Relational Camouflaged Object Detection | [Link](https://doi.org/10.1007/s11263-025-02530-3) | [Code](https://github.com/Liangbo-Cheng/mamba_capsule) | Camouflaged Object Detection |
| Automation in Construction 2024 | Topology-aware Mamba for Crack Segmentation in Structures | [Link](https://arxiv.org/pdf/2410.19894) | [Code](https://github.com/shengyu27/CrackMamba.) | Crack Segmentation |
| ACCV 2024 | Wavelet-based Mamba with Fourier Adjustment for Low-light Image Enhancement | [Link](https://arxiv.org/pdf/2410.20314) | [Code](https://github.com/mcpaulgeorge/WalMaFa) | Image Enhancement |
| Image and Vision Computing 2025 | ShadowMamba: State-Space Model with Boundary-Region Selective Scan for Shadow Removal | [Link](https://doi.org/10.1016/j.imavis.2025.105512) |  | Shadow Removal |
| NeurIPS 2024 | ECMamba: Consolidating Selective State Space Model with Retinex Guidance for Efficient Multiple Exposure Correction | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/5fd68e1c262099f846733435d620d574-Abstract-Conference.html) | [Code](https://github.com/LowlevelAI/ECMamba) | Multiple Exposure Correction |
| ACM MM 2024 | Realistic Full-Body Motion Generation from Sparse Tracking with State Space Model | [Link](https://openreview.net/pdf?id=dA6yat7UNM) |  | Motion Generation |
| NeurIPS 2024 | DiMSUM: Diffusion Mamba -- A Scalable and Unified Spatial-Frequency Method for Image Generation | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/39bc6e3cbf5a1991d33dc10ebff9a9cf-Abstract-Conference.html) | [Code](https://github.com/VinAIResearch/DiMSUM) | Generation |
| WACV 2025 | SEM-Net: Efficient Pixel Modelling for Image Inpainting with Spatially Enhanced SSM | [Link](https://openaccess.thecvf.com/content/WACV2025/html/Chen_SEM-Net_Efficient_Pixel_Modelling_for_Image_Inpainting_with_Spatially_Enhanced_WACV_2025_paper.html) | [Code](https://github.com/ChrisChen1023/SEM-Net) | Inpainting |
| IEEE SPL 2024 | LFSamba: Marry SAM with Mamba for Light Field Salient Object Detection | [Link](https://arxiv.org/pdf/2411.06652) | [Code](https://github.com/liuzywen/LFScribble) | Detection |
| NeurIPS 2024 Workshop | Diverse capability and scaling of diffusion and auto-regressive models when learning abstract rules | [Link](https://arxiv.org/pdf/2411.07873) |  | Rule Learning/Reasoning |
| IROS 2025 | MambaNUT: Nighttime UAV Tracking via Mamba-based Adaptive Curriculum Learning | [Link](https://doi.org/10.1109/IROS60139.2025.11247071) |  | Night UAV Tracking |
| CVPR 2025 | OSMamba: Omnidirectional Spectral Mamba with Dual-Domain Prior Generator for Exposure Correction | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Li_OSMamba_Omnidirectional_Spectral_Mamba_with_Dual-Domain_Prior_Generator_for_Exposure_CVPR_2025_paper.html) |  | Exposure Correction |
| AAAI 2025 | Selective Visual Prompting in Vision Mamba | [Link](https://arxiv.org/pdf/2412.08947) | [Code](https://github.com/zhoujiahuan1991/AAAI2025-SVP) | Domain Adaptation |
| IEEE TII 2025 | VarAD: Lightweight High-Resolution Image Anomaly Detection via Visual Autoregressive Modeling | [Link](https://arxiv.org/pdf/2412.17263) | [Code](https://github.com/caoyunkang/VarAD) | Anomaly Detection |
| CVPR 2025 | Efficient Visual State Space Model for Image Deblurring | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Kong_Efficient_Visual_State_Space_Model_for_Image_Deblurring_CVPR_2025_paper.html) | [Code](https://github.com/kkkls/EVSSMforDeblur) | Deblurring |
| ACCV 2024 | Image Deraining with Frequency-Enhanced State Space Model | [Link](https://arxiv.org/abs/2405.16470) |  | Deraining |
| AAAI 2025 | Mamba YOLO: A Simple Baseline for Object Detection with State Space Model | [Link](https://doi.org/10.1609/aaai.v39i8.32885) | [Code](https://github.com/HZAI-ZJNU/Mamba-YOLO) | Object Detection |
| ICML 2025 | FourierMamba: Fourier Learning Integration with State Space Models for Image Deraining | [Link](https://icml.cc/virtual/2025/poster/43723) | | Image Deraining |
| ICML 2025 | QMamba: On First Exploration of Vision Mamba for Image Quality Assessment | [Link](https://arxiv.org/abs/2406.09546) |  | Image Quality Assessment |
| ACCV 2024 | Mamba-based Light Field Super-Resolution with Efficient Subspace Scanning | [Link](https://openaccess.thecvf.com/content/ACCV2024/papers/Gao_Mamba-based_Light_Field_Super-Resolution_with_Efficient_Subspace_Scanning_ACCV_2024_paper.pdf) |  | Super-resolution |
| ACCV 2024 | PixMamba: Leveraging State Space Models in a Dual-Level Architecture for Underwater Image Enhancement | [Link](https://openaccess.thecvf.com/content/ACCV2024/html/Lin_PixMamba_Leveraging_State_Space_Models_in_a_Dual-Level_Architecture_for_ACCV_2024_paper.html) | [Code](https://github.com/weitunglin/pixmamba) | Image Enhancement |
| AAAI 2025 | Pose Magic: Efficient and Temporally Consistent Human Pose Estimation with a Hybrid Mamba-GCN Network | [Link](https://arxiv.org/abs/2408.02922) |  | Human Pose Estimation |
| AAAI 2025 | PoseMamba: Monocular 3D Human Pose Estimation with Bidirectional Global-Local Spatio-Temporal State Space Model | [Link](https://arxiv.org/abs/2408.03540) |  | 3D Human Pose Estimation |
| IEEE TIFS 2026 | Neural Architecture Search-Based Global–Local Vision Mamba for Palm-Vein Recognition | [Link](https://doi.org/10.1109/TIFS.2026.3679936) |  | Palm-Vein Recognition |
| CVPR 2025 | QMambaBSR: Burst Image Super-Resolution with Query State Space Model | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Di_QMambaBSR_Burst_Image_Super-Resolution_with_Query_State_Space_Model_CVPR_2025_paper.html) | [Code](https://github.com/LabShuHangGU/QMambaBSR) | Burst Super-Resolution |
| IEEE TPAMI 2025 | MTMamba++: Enhancing Multi-Task Dense Scene Understanding via Mamba-Based Decoders | [Link](https://doi.org/10.1109/TPAMI.2025.3593621) |  | Multi-Task Dense Prediction |
| ICLR 2025 | MambaPEFT: Exploring Parameter-Efficient Fine-Tuning for Mamba | [Link](https://arxiv.org/abs/2411.03855) |  | Parameter-Efficient Fine-Tuning |
| CVPR 2025 | Parameter Efficient Mamba Tuning via Projector-targeted Diagonal-centric Linear Transformation | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Ham_Parameter_Efficient_Mamba_Tuning_via_Projector-targeted_Diagonal-centric_Linear_Transformation_CVPR_2025_paper.html) |  | Parameter-Efficient Fine-Tuning |
| CVPR 2025 | MambaIRv2: Attentive State Space Restoration | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Guo_MambaIRv2_Attentive_State_Space_Restoration_CVPR_2025_paper.html) | [Code](https://github.com/csguoh/MambaIR) | Image Restoration |
| CVPR 2025 Workshop | XYScanNet: An Interpretable State Space Model for Perceptual Image Deblurring | [Link](https://arxiv.org/abs/2412.10338) |  | Deblurring |
| ICASSP 2025 | ViM-Disparity: Bridging the Gap of Speed, Accuracy and Memory for Disparity Map Generation | [Link](https://doi.org/10.1109/ICASSP49660.2025.10888223) | [Code](https://github.com/MBora/ViM-Disparity) | Disparity Map Generation |
| CVPR 2025 | MaIR: A Locality- and Continuity-Preserving Mamba for Image Restoration | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Li_MaIR_A_Locality-_and_Continuity-Preserving_Mamba_for_Image_Restoration_CVPR_2025_paper.html) | [Code](https://github.com/XLearning-SCU/MaIR) | Image Restoration |
| WACV 2025 | EDMB: Edge Detector with Mamba | [Link](https://openaccess.thecvf.com/content/WACV2025/html/Li_EDMB_Edge_Detector_with_Mamba_WACV_2025_paper.html) | [Code](https://github.com/Li-yachuan/EDMB) | Edge Detection |
| ACM MM 2025 | WMamba: Wavelet-based Mamba for Face Forgery Detection | [Link](https://arxiv.org/abs/2501.09617) |  | Face Forgery Detection |
| IEEE TIP 2025 | UniUIR: Considering Underwater Image Restoration as An All-in-One Learner | [Link](https://arxiv.org/abs/2501.12981) |  | Underwater Image Restoration |



#### Remote Sensing Image

| Venue | Paper | Link | Code         | Task |
| :-------- | :---- | :--- | :----------- | :--- |
| IEEE GRSL 2024 | RSMamba: Remote Sensing Image Classification with State Space Model | [Link](https://arxiv.org/pdf/2403.19654) | [Code](https://github.com/KyanChen/RSMamba) | Remote Sensing Images Classification|
| Heliyon 2024 | Samba: Semantic Segmentation of Remotely Sensed Images with State Space Model | [Link](https://doi.org/10.1016/j.heliyon.2024.e38495) | [Code](https://github.com/zhuqinfeng1999/Samba) | Semantic Segmentation |
| IEEE GRSL 2024 | RS3Mamba: Visual State Space Model for Remote Sensing Images Semantic Segmentation | [Link](https://arxiv.org/pdf/2404.02457) | [Code](https://github.com/sstary/SSRS) | Semantic Segmentation |
| IEEE TGRS 2025 | RS-Mamba for Large Remote Sensing Image Dense Prediction | [Link](https://doi.org/10.1109/TGRS.2024.3425540) | [Code](https://github.com/walking-shadow/Official_Remote_Sensing_Mamba) | Semantic Segmentation/Change Detection |
| IEEE TGRS 2024 | ChangeMamba: Remote Sensing Change Detection with Spatio-Temporal State Space Model | [Link](https://arxiv.org/pdf/2404.03425) | [Code](https://github.com/ChenHongruixuan/MambaCD) | Change Detection/Building Damage Assessment |
| IEEE TGRS 2024 | SSUMamba: Spatial-Spectral Selective State Space Model for Hyperspectral Image Denoising | [Link](https://arxiv.org/pdf/2405.01726) | [Code](https://github.com/lronkitty/SSUMamba) | Hyperspectral Image Denoising |
| IEEE TMM 2024 | Frequency-Assisted Mamba for Remote Sensing Image Super-Resolution | [Link](https://arxiv.org/pdf/2405.04964) | [Code](https://github.com/XY-boy/FreMamba)| Super-resolution |
| IEEE TGRS 2025 | GraphMamba: An Efficient Graph Structure Learning Vision Mamba for Hyperspectral Image Classification | [Link](https://doi.org/10.1109/TGRS.2024.3493101) | [Code](https://github.com/ahappyyang/GraphMamba) | Hyperspectral Image Classification |
| IEEE TGRS 2025 | DMM: Disparity-guided Multispectral Mamba for Oriented Object Detection in Remote Sensing | [Link](https://doi.org/10.1109/TGRS.2025.3578309) | [Code](https://github.com/Another-0/DMM) | Oriented Object Detection |
| IEEE TGRS 2025 | HTD-Mamba: Efficient Hyperspectral Target Detection with Pyramid State Space Model | [Link](https://doi.org/10.1109/TGRS.2025.3547019) | [Code](https://github.com/shendb2022/HTD-Mamba) | Hyperspectral Target Detection |
| IEEE TGRS 2025 | DualMamba: A Lightweight Spectral-Spatial Mamba-Convolution Network for Hyperspectral Image Classification | [Link](https://doi.org/10.1109/TGRS.2024.3516817) |  | Hyperspectral Image Classification |
| IEEE TGRS 2025 | CDMamba: Incorporating Local Clues Into Mamba for Remote Sensing Image Binary Change Detection | [Link](https://doi.org/10.1109/TGRS.2025.3545012) | [Code](https://github.com/zmoka-zht/CDMamba) | Change Detection |
| IEEE TGRS 2025 | 3DSS-Mamba: 3D-Spectral-Spatial Mamba for Hyperspectral Image Classification | [Link](https://doi.org/10.1109/TGRS.2024.3472091) |  | Hyperspectral Image Classification |
| Neurocomputing 2025 | Mamba-in-Mamba: Centralized Mamba-Cross-Scan in Tokenized Mamba Model for Hyperspectral Image Classification | [Link](https://doi.org/10.1016/j.neucom.2024.128751) | [Code](https://github.com/zhouweilian1904/Mamba-in-Mamba) | Hyperspectral Image Classification |
| IEEE JSTARS 2024 | Rethinking Scanning Strategies with Vision Mamba in Semantic Segmentation of Remote Sensing Imagery: An Experimental Study | [Link](https://doi.org/10.1109/JSTARS.2024.3472296) | | Semantic Segmentation |
| IEEE TGRS 2024 | MambaHSI: Spatial–Spectral Mamba for Hyperspectral Image Classification | [Link](https://ieeexplore.ieee.org/abstract/document/10604894) | [Code](https://github.com/li-yapeng/MambaHSI) | Hyperspectral Image Classification |
| Remote Sensing Letters 2025 | Multi-head Spatial-Spectral Mamba for Hyperspectral Image Classification | [Link](https://doi.org/10.1080/2150704X.2025.2461330) | [Code](https://github.com/MHassaanButt/MHA_SS_Mamba) | Hyperspectral Image Classification |
| IEEE GRSL 2024 | WaveMamba: Spatial-Spectral Wavelet Mamba for Hyperspectral Image Classification | [Link](https://doi.org/10.1109/LGRS.2024.3506034) | [Code](https://github.com/mahmad00) | Hyperspectral Image Classification |
| Neurocomputing 2025 | Spatial-Spectral Morphological Mamba for Hyperspectral Image Classification | [Link](https://doi.org/10.1016/j.neucom.2025.129995) | [Code](https://github.com/MHassaanButt/MorpMamba) | Hyperspectral Image Classification |
| IEEE GRSL 2024 | UNetMamba: An Efficient UNet-Like Mamba for Semantic Segmentation of High-Resolution Remote Sensing Images | [Link](https://arxiv.org/pdf/2408.11545) | [Code](https://github.com/EnzeZhu2001/UNetMamba) | Semantic Segmentation |
| IEEE GRSL 2024 | MambaFormerSR: A Lightweight model for Remote-Sensing Image Super-Resolution | [Link](https://ieeexplore.ieee.org/abstract/document/10663411) |  | Super-resolution |
| Scientific Reports 2024 | YOLOv5_mamba: unmanned aerial vehicle object detection based on bidirectional dense feedback network and adaptive gate feature fusion | [Link](https://www.nature.com/articles/s41598-024-73241-x) | [Code](https://github.com/xgyutu/yolo_mamba) | Object Detection |
| ECML/PKDD 2024 Workshop | A Deep Learning-Based Approach for Mangrove Monitoring | [Link](https://arxiv.org/pdf/2410.05443) | [Code](https://github.com/SVJLucas/MangroveAI) | Segmentation |
| IEEE TGRS 2024 | HyperMamba: A Spectral-Spatial Adaptive Mamba for Hyperspectral Image Classification | [Link](https://ieeexplore.ieee.org/document/10720896?denied=) | [Code](https://github.com/chiangliu/HyperMamba) | Hyperspectral Image Classification |
| ACM MM 2024 | VmambaSCI: Dynamic Deep Unfolding Network with Mamba for Compressive Spectral Imaging | [Link](https://openreview.net/pdf?id=MNvMDbaQXa) |  | Compressive Spectral Imaging |
| IEEE TGRS 2024 | ConMamba: CNN and SSM High-Performance Hybrid Network for Remote Sensing Change Detection | [Link](https://ieeexplore.ieee.org/abstract/document/10750064?casa_token=uO825sqHSPQAAAAA:JhplctaW117ODKA4BHb6crrDfQeF5u9B4nWkVVw6ESdZy3ecyunykKkXMocP7ZepwHV7wv5mdw) |  | Change Detection |
| IEEE TGRS 2024 | A Novel Remote Sensing Image Change Detection Approach Based on Multi-level State Space Model | [Link](https://ieeexplore.ieee.org/abstract/document/10756674?casa_token=Evht2bNP6I0AAAAA:PZy11rIEso_pLxrRU4S8DGbybY0gCFFmxs_6-5s4JNmm64En_CLpq8lcQ4xkR0PrQfYZUYRkrbA) | [Code](https://github.com/121zzy/MF-Mamba) | Change Detection |
| IEEE TGRS 2024 | Dynamic Token Augmentation Mamba for Cross-Scene Classification of Hyperspectral Image | [Link](https://ieeexplore.ieee.org/abstract/document/10768958?casa_token=AgqHwoE45fgAAAAA:QGbmKUKCq2DnLXvhQBO-fjiF1UuSr7wsa6Xc55DrjJBN80Q2dJCXt3BQ3dVgAwmiiUS2T-S9YQ) | [Code](https://github.com/Varro-pepsi/DTAM) | Cross-Scene Classification |
| IEEE GRSL 2024 | PPMamba:Enhancing Semantic Segmentation in Remote Sensing Imagery by SS2D | [Link](https://ieeexplore.ieee.org/document/10769411?denied=) | [Code](https://github.com/Jerrymo59/PPMambaSeg) | Semantic Segmentation |
| AAAI 2025 | Detail Matters: Mamba-Inspired Joint Unfolding Network for Snapshot Spectral Compressive Imaging | [Link](https://arxiv.org/pdf/2501.01262) | [Code](https://github.com/Mengjie-s/MiJUN) | Spectral Compressive Imaging |
| IGARSS 2025 | Mamba-MOC: A Multicategory Remote Object Counting via State Space Model | [Link](https://doi.org/10.1109/IGARSS55030.2025.11243409) | [Code](https://github.com/lp-094/Mamba-MOC) | Object Counting |
| IEEE TGRS 2025 | S2Mamba: A Spatial-spectral State Space Model for Hyperspectral Image Classification | [Link](https://arxiv.org/abs/2404.18213) |  | Hyperspectral Image Classification |
| Remote Sensing 2024 | Spectral-Spatial Mamba for Hyperspectral Image Classification | [Link](https://doi.org/10.3390/rs16132449) |  | Hyperspectral Image Classification |
| WACV 2025 | A Mamba-based Siamese Network for Remote Sensing Change Detection | [Link](https://openaccess.thecvf.com/content/WACV2025/html/Paranjape_A_Mamba-Based_Siamese_Network_for_Remote_Sensing_Change_Detection_WACV_2025_paper.html) |  | Change Detection |
| IEEE TGRS 2025 | MSFMamba: Multi-Scale Feature Fusion State Space Model for Multi-Source Remote Sensing Image Classification | [Link](https://arxiv.org/abs/2408.14255) |  | Remote Sensing Image Classification |
| IEEE TGRS 2025 | IGroupSS-Mamba: Interval Group Spatial–Spectral Mamba for Hyperspectral Image Classification | [Link](https://doi.org/10.1109/TGRS.2024.3502055) |  | Hyperspectral Image Classification |
| IGARSS 2025 | SITSMamba for Crop Classification based on Satellite Image Time Series | [Link](https://doi.org/10.1109/IGARSS55030.2025.11243832) | [Code](https://github.com/XiaoleiQinn/SITSMamba) | SITS Classification |
| ICASSP 2025 | UV-Mamba: A DCN-Enhanced State Space Model for Urban Village Boundary Identification in High-Resolution Remote Sensing Images | [Link](https://doi.org/10.1109/ICASSP49660.2025.10888896) |  | Segmentation |
| ICASSP 2026 | RemoteDet-Mamba: A Hybrid Mamba-CNN Network for Multi-modal Object Detection in Remote Sensing Images | [Link](https://arxiv.org/abs/2410.13532) |  | Object Detection |
| IGARSS 2025 | WSSM: Geographic-enhanced hierarchical state-space model for global station weather forecast | [Link](https://doi.org/10.1109/IGARSS55030.2025.11314061) |  | Weather Forecasting |
| IEEE GRSL 2025 | CDxLSTM: Boosting Remote Sensing Change Detection With Extended Long Short-Term Memory | [Link](https://doi.org/10.1109/LGRS.2025.3562480) | [Code](https://github.com/xwmaxwma/rschange) | Change Detection |
| IEEE TGRS 2025 | IRSRMamba: Infrared Image Super-Resolution via Mamba-based Wavelet Transform Feature Modulation Model | [Link](https://doi.org/10.1109/TGRS.2025.3584385) | [Code](https://github.com/yongsongH/IRSRMamba) | Infrared Image Super-resolution |



#### Medical Image

| Venue | Paper | Link | Code         | Task |
| :-------- | :---- | :--- | :----------- | :--- |
| MICCAI 2024 | SegMamba: Long-range Sequential Modeling Mamba For 3D Medical Image Segmentation | [Link](https://arxiv.org/pdf/2401.13560) | [Code](https://github.com/ge-xing/SegMamba) |3D Medical Segmentation|
| ISBI 2025 | nnMamba: 3D Biomedical Image Segmentation, Classification and Landmark Detection with State Space Model | [Link](https://doi.org/10.1109/ISBI60581.2025.10980694) | [Code](https://github.com/lhaof/nnMamba) | 3D Medical Segmentation |
| ACM TOMCCAP 2025 | VM-UNet: Vision Mamba UNet for Medical Image Segmentation | [Link](https://doi.org/10.1145/3767748) | [Code](https://github.com/JCruan519/VM-UNet) | 2D Medical Segmentation |
| MICCAI 2024 | Swin-UMamba: Mamba-based UNet with ImageNet-based pretraining | [Link](https://arxiv.org/pdf/2402.03302) | [Code](https://github.com/JiarunLiu/Swin-UMamba) | 2D Medical Segmentation |
| KBS 2024 | Semi-Mamba-UNet: Pixel-Level Contrastive Cross-Supervised Visual Mamba-based UNet for Semi-Supervised Medical Image Segmentation | [Link](https://arxiv.org/pdf/2402.07245) | [Code](https://github.com/ziyangwang007/Mamba-UNet) | 2D Medical Segmentation |
| IEEE BIBM 2024 | MamMIL: Multiple Instance Learning for Whole Slide Images with State Space Models | [Link](https://arxiv.org/pdf/2403.05160) | | Cancer Subtyping |
| MICCAI 2024 | MambaMIL: Enhancing Long Sequence Modeling with Sequence Reordering in Computational Pathology | [Link](https://arxiv.org/pdf/2403.06800) | [Code](https://github.com/isyangshu/MambaMIL) | Cancer Subtyping/ </br> Survival Prediction |
| MICCAI 2024 | LKM-UNet: Large Kernel Vision Mamba UNet for Medical Image Segmentation | [Link](https://arxiv.org/pdf/2403.07332) | [Code](https://github.com/wjh892521292/LKM-UNet) | Medical Image Segmentation |
| BIBM 2024 | MD-Dose: A diffusion model based on the Mamba for radiation dose prediction | [Link](https://doi.org/10.1109/BIBM62325.2024.10822581) | [Code](https://github.com/flj19951219/mamba_dose) | Radiation Dose Prediction (Segmentation) |
| ISBRA 2024 | VM-UNET-V2 Rethinking Vision Mamba UNet for Medical Image Segmentation | [Link](https://arxiv.org/pdf/2403.09157) | [Code](https://github.com/nobodyplayer1/VM-UNetV2) | 2D Medical Segmentation |
| Neurocomputing 2025 | H-vmunet: High-order Vision Mamba UNet for Medical Image Segmentation | [Link](https://doi.org/10.1016/j.neucom.2025.129447) | [Code](https://github.com/wurenkai/H-vmunet) | 2D Medical Segmentation |
| MIDL 2024 | ViM-UNet: Vision Mamba for Biomedical Segmentation | [Link](https://arxiv.org/pdf/2404.07705) | [Code](https://github.com/constantinpape/torch-em/blob/main/vimunet.md) | 2D Medical Segmentation (Cell/Neurite) |
| MICCAI 2024 | nnU-Net Revisited: A Call for Rigorous Validation in 3D Medical Image Segmentation | [Link](https://arxiv.org/pdf/2404.09556) | [Code](https://github.com/MIC-DKFZ/nnUNet) | 3D Medical Segmentation |
| CVPR 2024 Workshop | Vim4Path: Self-Supervised Vision Mamba for Histopathology Images | [Link](https://arxiv.org/pdf/2404.13222) | [Code](https://github.com/AtlasAnalyticsLab/Vim4Path) | Cancer Subtyping |
| MIPR 2024 | UU-Mamba: Uncertainty-aware U-Mamba for Cardiac Image Segmentation | [Link](https://doi.org/10.1109/MIPR62202.2024.00050) |  | Medical Image Segmentation |
| MICCAI 2024 Oral | Cardiovascular Disease Detection from Multi-View Chest X-rays with BI-Mamba | [Link](https://arxiv.org/pdf/2405.18533) | [Code](https://github.com/RPIDIAL/BI-Mamba) | CVD Risk Prediction |
| Scientific Reports 2025 | Combining Graph Neural Network and Mamba to Capture Local and Global Tissue Spatial Relationships in Whole Slide Images | [Link](https://doi.org/10.1038/s41598-025-99042-4) | [Code](https://github.com/rina-ding/gat-mamba) | Cancer Subtyping/Survival Prediction |
| WACV 2025 | Convolution and Attention-Free Mamba-based Cardiac Image Segmentation | [Link](https://openaccess.thecvf.com/content/WACV2025/html/Khan_CAMS_Convolution_and_Attention-Free_Mamba-Based_Cardiac_Image_Segmentation_WACV_2025_paper.html) | [Code](https://github.com/kabbas570/Convolution-and-Attention-Free-Mamba-based-Cardiac-Image-Segmentation/tree/main?utm_source=catalyzex.com) | Medical Image Segmentation |
| BMVC 2024 | On Evaluating Adversarial Robustness of Volumetric Medical Segmentation Models | [Link](https://arxiv.org/pdf/2406.08486) | [Code](https://github.com/HashmatShadab/Robustness-of-Volumetric-Medical-Segmentation-Models) | Medical Image Segmentation |
| MICCAI 2024 Workshop | Vision Mamba for Classification of Breast Ultrasound Images | [Link](https://arxiv.org/pdf/2407.03552) |  | Classification |
| MICCAI 2024 | Deform-Mamba Network for MRI Super-Resolution | [Link](https://arxiv.org/pdf/2407.05969) |  | Super-resolution |
| ICPR 2024 | Self-Prior Guided Mamba-UNet Networks for Medical Image Super-Resolution | [Link](https://doi.org/10.1007/978-3-031-78195-7_11) |  | Super-resolution |
| KDD Workshop 2024 | State Space Model-based Classification of Major Depressive Disorder Across Multiple Imaging Sites | [Link](https://openreview.net/pdf?id=wFgLDc4Gx8) |  | Medical Image Classification |
| MICCAI 2024 | ShapeMamba-EM: Fine-Tuning Foundation Model with Local Shape Descriptors and Mamba Blocks for 3D EM Image Segmentation | [Link](https://arxiv.org/pdf/2408.14114) |  | Medical Image Segmentation |
| ICME 2025 | MambaMIC: An Efficient Baseline for Microscopic Image Classification with State Space Models | [Link](https://doi.org/10.1109/ICME59968.2025.11209808) | [Code](https://github.com/zs1314/Microscopic-Mamba) | Medical Image Classification |
| ICASSP 2025 | SX-Stitch: An Efficient VMS-UNet Based Framework for Intraoperative Scoliosis X-Ray Image Stitching | [Link](https://doi.org/10.1109/ICASSP49660.2025.10888770) |  | Medical Image Stitching |
| ICASSP 2025 | MpoxMamba: A Grouped Mamba-based Lightweight Hybrid Network for Mpox Detection | [Link](https://doi.org/10.1109/ICASSP49660.2025.10888345) | [Code](https://github.com/YubiaoYue/MpoxMamba) | Medical Image Classification |
| Scientific Reports 2024 | A mixed Mamba U-net for prostate segmentation in MR images | [Link](https://www.nature.com/articles/s41598-024-71045-7) |  | Medical Image Segmentation |
| IEEE TMI 2025 | Serp-Mamba: Advancing High-Resolution Retinal Vessel Segmentation with Selective State-Space Model | [Link](https://ieeexplore.ieee.org/document/11059897/) |  | Medical Image Segmentation |
| MICCAI 2024 | Tri-Plane Mamba: Efficiently Adapting Segment Anything Model for 3D Medical Images | [Link](https://arxiv.org/pdf/2409.08492) | [Code](https://github.com/xmed-lab/TP-Mamba) | Medical Image Segmentation |
| ACCV 2024 Workshop | SkinMamba: A Precision Skin Lesion Segmentation Architecture with Cross-Scale Global State Modeling and Frequency Boundary Guidance | [Link](https://arxiv.org/pdf/2409.10890) | [Code](https://github.com/zs1314/SkinMamba) | Medical Image Segmentation |
| IEEE Sensors Journal 2025 | SPRMamba: Surgical Phase Recognition for Endoscopic Submucosal Dissection with Mamba | [Link](https://doi.org/10.1109/JSEN.2025.3649151) |  | Surgical Phase Recognition |
| WACV 2025 | MambaRecon: MRI Reconstruction with Structured State Space Models | [Link](https://openaccess.thecvf.com/content/WACV2025/html/Korkmaz_MambaRecon_MRI_Reconstruction_with_Structured_State_Space_Models_WACV_2025_paper.html) | [Code](https://github.com/yilmazkorkmaz1/MambaRecon) | Medical Image Reconstruction |
| MICCAI 2024 | EM-Net: Efficient Channel and Frequency Learning with Mamba for 3D Medical Image Segmentation | [Link](https://arxiv.org/pdf/2409.17675) | [Code](https://github.com/zang0902/EM-Net) | Medical Image Segmentation |
| MICCAI 2024 | MetaUNETR: Rethinking Token Mixer Encoding for Efficient Multi-organ Segmentation | [Link](https://papers.miccai.org/miccai-2024/paper/2749_paper.pdf) | [Code](https://github.com/lyupengju/MetaUNETR) | Medical Image Segmentation |
| MICCAI 2024 | PathMamba: Weakly Supervised State Space Model for Multi-class Segmentation of Pathology Images | [Link](https://papers.miccai.org/miccai-2024/paper/1354_paper.pdf) | [Code](https://github.com/hemo0826/PathMamba) | Medical Image Segmentation |
| MICCAI 2024 | Efficient and Gender-adaptive Graph Vision Mamba for Pediatric Bone Age Assessment | [Link](https://papers.miccai.org/miccai-2024/paper/2831_paper.pdf) | [Code](https://github.com/SCU-zly/GGVMamba) | Bone Age Assessment |
| MICCAI 2024 | Polyp-Mamba: Polyp Segmentation with Visual Mamba | [Link](https://papers.miccai.org/miccai-2024/paper/0697_paper.pdf) |  | Medical Image Segmentation |
| IEEE TMI 2024 | Unleash the Power of State Space Model for Whole Slide Image with Local Aware Scanning and Importance Resampling | [Link](https://ieeexplore.ieee.org/document/10706928) | [Code](https://github.com/HKU-MedAI/PAM) | Cancer Subtyping/Survival Prediction |
| IEEE TMI 2024 | Swin-UMamba+: Adapting Mamba-based vision foundation models for medical image segmentation | [Link](https://ieeexplore.ieee.org/abstract/document/10771659?casa_token=wPJNmR_Ia3YAAAAA:vqxUYPeJ1iZOIE8-pspWygZtQAiMk-nbA1IeBnMLJxNZJftxIqzqSyAX4ijPs6s_1SKtsteBvg) | [Code](https://github.com/JiarunLiu/Swin-UMamba) | Medical Image Segmentation |
| AAAI 2025 | S3Mamba: Small-Size-Sensitive Mamba for Lesion Segmentation | [Link](https://arxiv.org/pdf/2412.14546) | [Code](https://github.com/ErinWang2023/S3-Mamba) | Medical Image Segmentation |
| ICME 2025 | HCMA-UNet: A Hybrid CNN-Mamba UNet with Axial Self-Attention for Efficient Breast Cancer Segmentation | [Link](https://doi.org/10.1109/ICME59968.2025.11209819) | [Code](https://anonymous.4open.science/r/ICME2025_HCMA-UNet) | Medical Image Segmentation |
| IEEE TMI 2025 | Merging Context Clustering with Visual State Space Models for Medical Image Segmentation | [Link](https://arxiv.org/pdf/2501.01618) | [Code](https://github.com/zymissy/CCViM) | Medical Image Segmentation |
| ISBI 2025 | GLFC: Unified Global-Local Feature and Contrast Learning with Mamba-Enhanced UNet for Synthetic CT Generation from CBCT | [Link](https://arxiv.org/pdf/2501.02992) | [Code](https://github.com/HiLab-git/GLFC) | Medical Image Segmentation |
| IEEE TCSVT 2025 | DH-Mamba: Exploring Dual-Domain Hierarchical State Space Models for MRI Reconstruction | [Link](https://doi.org/10.1109/TCSVT.2025.3614828) | [Code](https://github.com/XiaoMengLiLiLi/DM-Mamba) | Reconstruction |
| IEEE TCSS 2025 | MSV-Mamba: A Multiscale Vision Mamba Network for Echocardiography Segmentation | [Link](https://doi.org/10.1109/TCSS.2025.3562441) |  | Medical Image Segmentation |
| Information Fusion 2025 | Polyp-Mamba: A Hybrid Multi-Frequency Perception Gated Selection Network for polyp segmentation | [Link](https://www.sciencedirect.com/science/article/pii/S1566253524005372?casa_token=_Eo-Hb9zwdgAAAAA:F2WfzIzK_IiDFgHtuZuP7RAN5KzVWtWrKrhhJaLcxMkPITCfH_KGgJ8tcknSvbVESPudpiXtjdc) |  | Medical Image Segmentation |
| Patterns 2025 | UltraLight VM-UNet: Parallel Vision Mamba Significantly Reduces Parameters for Skin Lesion Segmentation | [Link](https://arxiv.org/abs/2403.20035) | [Code](https://github.com/wurenkai/UltraLight-VM-UNet) | Medical Image Segmentation |
| IEEE TMM 2026 | T-Mamba: A Unified Framework with Long-Range Dependency in Dual-Domain for 2D & 3D Tooth Segmentation | [Link](https://doi.org/10.1109/tmm.2026.3668475) | [Code](https://github.com/isbrycee/T-Mamba) | 3D Medical Segmentation (Tooth) |
| MICCAI 2025 | Sparse Reconstruction of Optical Doppler Tomography with Alternative State Space Model | [Link](https://doi.org/10.1007/978-3-032-05325-1_50) |  | Medical Image Reconstruction |
| Exploration of Medicine 2025 | MUCM-Net: A Mamba Powered UCM-Net for Skin Lesion Segmentation | [Link](https://www.explorationpub.com/uploads/Article/A1001250/1001250.pdf) | [Code](https://github.com/chunyuyuan/MUCM-Net) | Skin Lesion Segmentation |
| ICCV 2025 | TokenUnify: Scaling Up Autoregressive Pretraining for Neuron Segmentation | [Link](https://openaccess.thecvf.com/content/ICCV2025/html/Chen_TokenUnify_Scaling_Up_Autoregressive_Pretraining_for_Neuron_Segmentation_ICCV_2025_paper.html) |  | Neuron Segmentation |
| IEEE JBHI 2025 | SliceMamba with Neural Architecture Search for Medical Image Segmentation | [Link](https://doi.org/10.1109/JBHI.2025.3564381) |  | Medical Image Segmentation |
| MIA 2025 | MambaMIM: Pre-training Mamba with State Space Token Interpolation | [Link](https://doi.org/10.1016/j.media.2025.103606) | [Code](https://github.com/FengheTan9/MambaMIM) | Medical Image Pre-training |
| RECOMB 2025 | Hierarchical Spatio-Temporal State-Space Modeling for fMRI Analysis | [Link](https://arxiv.org/abs/2408.13074) |  | fMRI Analysis |
| BIBM 2024 | MSVM-UNet: Multi-Scale Vision Mamba UNet for Medical Image Segmentation | [Link](https://doi.org/10.1109/BIBM62325.2024.10821761) | [Code](https://github.com/gndlwch2w/msvm-unet) | Medical Image Segmentation |
| ICASSP 2025 | OCTAMamba: A State-Space Model Approach for Precision OCTA Vascularization Segmentation | [Link](https://arxiv.org/abs/2409.08000) |  | OCTA Vascularization Segmentation |
| Information Fusion 2026 | MambaEviScrib: Mamba and Evidence-Guided Consistency Enhance CNN Robustness for Scribble-Supervised Medical Image Segmentation | [Link](https://arxiv.org/abs/2409.19370) |  | Medical Image Segmentation |
| CMIG 2025 | CT-Mamba: A Hybrid Convolutional State Space Model for Low-Dose CT Denoising | [Link](https://doi.org/10.1016/j.compmedimag.2025.102595) |  | Denoising |
| International Journal of Imaging Systems and Technology 2025 | Advancing Efficient Brain Tumor Multi‑Class Classification: New Insights From the Vision Mamba Model in Transfer Learning | [Link](https://doi.org/10.1002/ima.70177) |  | Multi-Class Classification |
| IEEE RA-L 2025 | MambaXCTrack: Mamba-Based Tracker With SSM Cross-Correlation and Motion Prompt for Ultrasound Needle Tracking | [Link](https://ieeexplore.ieee.org/abstract/document/10950072) |  | Ultrasound Needle Tracking |
| WACV 2025 | SAM-Mamba: Mamba Guided SAM Architecture for Generalized Zero-Shot Polyp Segmentation | [Link](https://openaccess.thecvf.com/content/WACV2025/html/Dutta_SAM-Mamba_Mamba_Guided_SAM_Architecture_for_Generalized_Zero-Shot_Polyp_Segmentation_WACV_2025_paper.html) | [Code](https://github.com/TapasKumarDutta1/SAM_Mamba_2025) | Medical Image Segmentation |
| CVPR 2025 | Unsupervised Foundation Model-Agnostic Slide-Level Representation Learning | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Lenz_Unsupervised_Foundation_Model-Agnostic_Slide-Level_Representation_Learning_CVPR_2025_paper.html) |  | Slide-Level Representation Learning |
| CVPR 2025 | 2DMamba: Efficient State Space Model for Image Representation with Applications on Giga-Pixel Whole Slide Image Classification | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Zhang_2DMamba_Efficient_State_Space_Model_for_Image_Representation_with_Applications_CVPR_2025_paper.html) | [Code](https://github.com/AtlasAnalyticsLab/2DMamba) | Medical Image Classification |
| ICCKE 2024 | Segmentation of Coronary Artery Stenosis in X-ray Angiography using Mamba Model | [Link](https://doi.org/10.1109/ICCKE65377.2024.10874801) |  | Coronary Artery Segmentation |
| MICCAI 2025 | Surface Vision Mamba: Leveraging Bidirectional State Space Model for Efficient Spherical Manifold Representation | [Link](https://link.springer.com/chapter/10.1007/978-3-032-04927-8_57) | [Code](https://github.com/Rongzhao-He/surface-vision-mamba) | Spherical Manifold Representation |



### Video

| Venue | Paper | Link | Code         | Task                                                           |
| :-------- | :---- | :--- | :----------- |:---------------------------------------------------------------|
| ECCV 2024 | VideoMamba: State Space Model for Efficient Video Understanding | [Link](https://arxiv.org/pdf/2403.06977) | [Code](https://github.com/OpenGVLab/VideoMamba) | Action Recognition/Video Understanding/Text-to-video Retrieval |
| ICLR 2024 | SSM Meets Video Diffusion Models: Efficient Video Generation with Structured State Spaces| [Link](https://arxiv.org/pdf/2403.07711)|[Code](https://github.com/shim0114/SSM-Meets-Video-Diffusion-Models)| Video Generation                                               |
| IJCV 2026 | Video Mamba Suite: State Space Model as a Versatile Alternative for Video Understanding | [Link](https://doi.org/10.1007/s11263-025-02597-y) | [Code](https://github.com/OpenGVLab/video-mamba-suite) | Action Recognition/Action Localization/... |
| CVPR 2024 Workshop | VMRNN: Integrating Vision Mamba and LSTM for Efficient and Accurate Spatiotemporal Forecasting | [Link](https://arxiv.org/pdf/2403.16536) | [Code](https://github.com/yyyujintang/VMRNN-PyTorch) | Spatiotemporal Forecasting                                     |
| ICCV 2025 | Snakes and Ladders: Two Steps Up for VideoMamba | [Link](https://doi.org/10.1109/ICCV51701.2025.02246) | [Code](https://github.com/hotfinda/videomambapro) | Video Understanding |
| AAAI 2025 | RhythmMamba: Fast Remote Physiological Measurement with Arbitrary Length Videos | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/33204) | [Code](https://github.com/zizhengguo/RhythmMamba) | Remote photoplethysmography  Prediction |
| NeurIPS 2024 | VFIMamba: Video Frame Interpolation with State Space Models | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/c1e9db5e1b04322963af91ac0c943568-Abstract-Conference.html) | [Code](https://github.com/MCG-NJU/VFIMamba) | Video Frame Interpolation                                      |
| ECCV 2024 | VideoMamba: Spatio-Temporal Selective State Space Model | [Link](https://arxiv.org/pdf/2407.08476) | [Code](https://github.com/jinyjelly/VideoMamba) | Action Recognition                                             |
| ACM MM 2024 Oral | RainMamba: Enhanced Locality Learning with State Space Models for Video Deraining | [Link](https://arxiv.org/pdf/2407.21773) | [Code](https://github.com/TonyHongtaoWu/RainMamba) | Deraining                                                      |
| IEEE TCSVT 2025 | MambaVT: Spatio-Temporal Contextual Modeling for robust RGB-T Tracking | [Link](https://doi.org/10.1109/TCSVT.2025.3557992) |  | RGB-T Tracking |
| ACM MM 2024 Oral | MambaTrack: A Simple Baseline for Multiple Object Tracking with State Space Model | [Link](https://arxiv.org/pdf/2408.09178) |  | Multiple Object Tracking                                       |
| Computers and Electronics in Agriculture 2025 | FMRFT: Fusion Mamba and DETR for Query Time Sequence Intersection Fish Tracking | [Link](https://doi.org/10.1016/j.compag.2025.110483) |  | Fish Tracking |
| IEEE JSTAR 2024 | TrackingMamba: Visual State Space Model for Object Tracking | [Link](https://ieeexplore.ieee.org/abstract/document/10678881) | [Code](https://github.com/KustTeamWQW/TrackingMamba) | Object Tracking                                                |
| CCBR 2024 | PhysMamba: Efficient Remote Physiological Measurement with SlowFast Temporal Difference Mamba | [Link](https://arxiv.org/pdf/2409.12031) | [Code](https://github.com/Chaoqi31/PhysMamba) | Remote Photoplethysmography                                    |
| NeurIPS 2024 | MambaSCI: Efficient Mamba-UNet for Quad-Bayer Patterned Video Snapshot Compressive Imaging | [Link](https://openreview.net/pdf?id=U4WeoyRHPd) | [Code](https://github.com/PAN083/MambaSCI) | Snapshot Compressive Imaging                                   |
| NeurIPS 2024 | Toward Dynamic Non-Line-of-Sight Imaging with Mamba Enforced Temporal Consistency | [Link](https://openreview.net/pdf?id=QiCJomIW3l) |  | Dynamic Reconstruction                                         |
| ACM MM 2024 | Object-Level Pseudo-3D Lifting for Distance-Aware Tracking | [Link](https://openreview.net/pdf?id=KBeJ7gxhCc) |  | Tracking                                                       |
| AAAI 2025 | Manta: Enhancing Mamba for Few-Shot Action Recognition of Long Sub-Sequence | [Link](https://arxiv.org/pdf/2412.07481) | [Code](https://github.com/wenbohuang1002/Manta) | Action Recognition                                             |
| AAAI 2025 | Exploring Enhanced Contextual Information for Video-Level Object Tracking | [Link](https://arxiv.org/pdf/2412.11023) | [Code](https://github.com/kangben258/MCITrack) | Tracking                                                       |
| AAAI 2025 | Robust Tracking via Mamba-based Context-aware Token Learning | [Link](https://arxiv.org/pdf/2412.13611) | [Code](https://github.com/GXNU-ZhongLab/TemTrack) | Tracking                                                       |
| AAAI 2025 | Efficient Self-Supervised Video Hashing with Selective State Spaces | [Link](https://arxiv.org/pdf/2412.14518) | [Code](https://github.com/gimpong/AAAI25-S5VH) | Hashing                                                        |
| IEEE TMM 2026 | STNMamba: Mamba-based Spatial-Temporal Normality Learning for Video Anomaly Detection | [Link](https://doi.org/10.1109/TMM.2026.3664969) |  | Anomaly Detection |
| CVPR 2025 | MambaVO: Deep Visual Odometry Based on Sequential Matching Refinement and Training Smoothing | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_MambaVO_Deep_Visual_Odometry_Based_on_Sequential_Matching_Refinement_and_CVPR_2025_paper.html) |  | Deep Visual Odometry |
| NeurIPS 2024 | Slot State Space Models | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/158ac5698e36a01ee5ca9e6732685b34-Abstract-Conference.html) | [Code](https://github.com/JindongJiang/SlotSSMs) | Object-Centric Learning |
| IEEE TPAMI 2025 | MADiff: Motion-Aware Mamba Diffusion Models for Hand Trajectory Prediction on Egocentric Videos | [Link](https://arxiv.org/abs/2409.02638) |  | Hand Trajectory Prediction |
| CVPR 2025 | MANTA: Diffusion Mamba for Efficient and Effective Stochastic Long-term Dense Anticipation | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Zatsarynna_MANTA_Diffusion_Mamba_for_Efficient_and_Effective_Stochastic_Long-Term_Dense_CVPR_2025_paper.html) |  | Dense Anticipation |



### Point Cloud

| Venue | Paper | Link | Code         | Task |
| :-------- | :---- | :--- | :----------- | :--- |
| NeurIPS 2024 | PointMamba: A Simple State Space Model for Point Cloud Analysis | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/395371f778ebd4854b88521100af30ad-Abstract-Conference.html) | [Code](https://github.com/LMD0311/PointMamba) | Classification, Part Segmentation |
| CVPR 2024 | State Space Models for Event Cameras | [Link](https://arxiv.org/pdf/2402.15584) | [Code](https://github.com/uzh-rpg/ssms_event_cameras) | Object Detection |
| ACM MM 2024 | MambaMOS: LiDAR-based 3D Moving Object Segmentation with Motion-aware State Space Model | [Link](https://arxiv.org/pdf/2404.12794) | [Code](https://github.com/Terminal-K/MambaMOS) | Object Segmentation |
| ACM MM 2024 | Mamba3D: Enhancing Local Features for 3D Point Cloud Analysis via State Space Model | [Link](https://arxiv.org/pdf/2404.14966) | [Code](https://github.com/xhanxu/Mamba3D) | Classification, Part Segmentation |
| NeurIPS 2024 | LCM: Locally Constrained Compact Point Cloud Model for Masked Point Modeling | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/bd592fc74cb0c5089c3e38eb762a793d-Abstract-Conference.html) | [Code](https://github.com/zyh16143998882/lcm) | Classification, Part Segmentation, Object Detection |
| NeurIPS 2024 | Voxel Mamba: Group-Free State Space Models for Point Cloud based 3D Object Detection | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/947b63838c90f1485188b9c673bc3a14-Abstract-Conference.html) | [Code](https://github.com/gwenzhang/Voxel-Mamba) | Object Detection |
| NeurIPS 2024 | 3DET-Mamba: Causal Sequence Modelling for End-to-End 3D Object Detection | [Link](https://openreview.net/pdf?id=iOleSlC80F) |  | Object Detection |
| ICIP 2024 | Mamba-PCGC: Mamba-Based Point Cloud Geometry Compression | [Link](https://ieeexplore.ieee.org/document/10647269) |  | Geometry Compression |
| NeurIPS 2024 | LION: Linear Group RNN for 3D Object Detection in Point Clouds | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/189699197ead7a012c7fa4cdc4cc413d-Abstract-Conference.html) | [Code](https://happinesslz.github.io/projects/LION/) | Object Detection |
| AAAI 2025 | SMamba: Sparse Mamba for Event-based Object Detection | [Link](https://arxiv.org/pdf/2501.11971) | [Code](https://github.com/Zizzzzzzz/SMamba) | Object Detection |
| AISTATS 2025 | Application of Structured State Space Models to High energy physics with locality-sensitive hashing | [Link](https://arxiv.org/pdf/2501.16237) | [Code](https://github.com/chengjiang123/Lampa) | High Energy Physics Tasks |
| AAAI 2025 | Point Cloud Mamba: Point Cloud Learning via State Space Model | [Link](https://arxiv.org/abs/2403.00762) | [Code](https://github.com/SkyworkAI/PointCloudMamba) | Classification, Segmentation |
| AAAI 2025 | 3DMambaIPF: A State Space Model for Iterative Point Cloud Filtering | [Link](https://arxiv.org/abs/2404.05522) |  | Point Cloud Filtering |
| IEEE TPAMI 2025 | Rethinking Efficient and Effective Point-based Networks for Event Camera Classification and Regression | [Link](https://doi.org/10.1109/TPAMI.2025.3556561) |  | Event Camera Classification |
| CVPR 2025 | MAMBA4D: Efficient Long-Sequence Point Cloud Video Understanding with Disentangled Spatial-Temporal State Space Models | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_Mamba4D_Efficient_4D_Point_Cloud_Video_Understanding_with_Disentangled_Spatial-Temporal_CVPR_2025_paper.html) |  | Point Cloud Video Understanding |
| AAAI 2025 | Pamba: Enhancing Global Interaction in Point Clouds via State Space Model | [Link](https://arxiv.org/abs/2406.17442) |  | Point Cloud Analysis |
| ROBIO 2024 | MV-MOS: Multi-View Feature Fusion for 3D Moving Object Segmentation | [Link](https://doi.org/10.1109/ROBIO64047.2024.10907321) | [Code](https://github.com/Chengjt1999/MV-MOS) | Object Segmentation |
| IEEE TCSVT 2025 | MambaEVT: Event Stream-Based Visual Object Tracking Using State Space Model | [Link](https://doi.org/10.1109/TCSVT.2025.3588533) | [Code](https://github.com/Event-AHU/MambaEVT) | Object Tracking |
| IEEE RA-L 2025 | OMEGA: Efficient Occlusion-Aware Navigation for Air-Ground Robots in Dynamic Environments via State Space Model | [Link](https://ieeexplore.ieee.org/document/10803034) |  | Robot Navigation |
| ACM MM Asia 2024 | SpikMamba: When SNN meets Mamba in Event-based Human Action Recognition | [Link](https://doi.org/10.1145/3696409.3700204) | [Code](https://github.com/Typistchen/SpikMamba) | Action Recognition |
| Communications in Transportation Research 2025 | MetaSSC: Enhancing 3D Semantic Scene Completion for Autonomous Driving through Meta-Learning and Long-sequence Modeling | [Link](https://doi.org/10.1016/j.commtr.2025.100184) |  | 3D Semantic Scene Completion |


### Multi-Modal

| Venue | Paper | Link | Code         | Task | Modality|
| :-------- | :---- | :--- | :----------- | :--- | :--- |
| Information Fusion 2025 | Pan-Mamba: Effective pan-sharpening with State Space Model | [Link](https://doi.org/10.1016/j.inffus.2024.102779) | [Code](https://github.com/alexhe101/Pan-Mamba) | Pansharpening | HISR Images & LRMS Images |
| ECCV 2024 | InstructGIE: Towards Generalizable Image Editing | [Link](https://arxiv.org/pdf/2403.05018) | [Code](https://github.com/cr8br0ze/InstructGIE-Code) | Image Editing | Image & Text|
| ECCV 2024 | Motion Mamba: Efficient and Long Sequence Motion Generation with Hierarchical and Bidirectional Selective SSM | [Link](https://arxiv.org/pdf/2403.07487) | [Code](https://steve-zeyu-zhang.github.io/MotionMamba) | Text-to-Motion Generation | Motion & Text|
| NeurIPS 2024 Workshop | VL-Mamba: Exploring State Space Models for Multimodal Learning | [Link](https://arxiv.org/abs/2403.13600) | [Code](https://yanyuanqiao.github.io/vl-mamba) | MLLM tasks | Image & Text |
| NeurIPS 2024 | MambaTalk: Efficient Holistic Gesture Synthesis with Selective State Space Models| [Link](https://papers.nips.cc/paper_files/paper/2024/hash/23c9c94227f937cfb50592a15e7fbb63-Abstract-Conference.html) |  | Gesture Synthesis | Speech & Motion |
| ECCV 2024 | ReMamber: Referring Image Segmentation with Mamba Twister | [Link](https://arxiv.org/pdf/2403.17839) | [Code](https://github.com/yyh-rain-song/ReMamber) | Referring Image Segmentation | Image & Text |
| BIBM 2025 | SurvMamba: State Space Model with Multi-grained Multi-modal Interaction for Survival Prediction | [Link](https://doi.org/10.1109/BIBM66473.2025.11356727) |  | Cancer Subtyping/Survival Prediction | WSIs & Gene |
| WACV 2025 | Sigma: Siamese Mamba Network for Multi-Modal Semantic Segmentation | [Link](https://openaccess.thecvf.com/content/WACV2025/html/Wan_Sigma_Siamese_Mamba_Network_for_Multi-Modal_Semantic_Segmentation_WACV_2025_paper.html) | [Code](https://github.com/zifuwan/Sigma) | Semantic Segmentation | RGB Images & Depth/Thermal Images |
| IEEE TGRS 2024 | Efficient Remote Sensing Image Fusion With State Space Model| [Link](https://arxiv.org/pdf/2404.07932) | [Code](https://github.com/PSRben/FusionMamba) | Pansharpening | HISR Images & LRMS Images|
| PRCV 2024 | Mamba-FETrack: Frame-Event Tracking via State Space Model | [Link](https://arxiv.org/pdf/2404.18174) | [Code](https://github.com/Event-AHU/Mamba_FETrack) | RGB-Event Tracking | RGB Frames & Event |
| IEEE GRSL 2024 | RSCaMa: Remote Sensing Image Change Captioning with State Space Model | [Link](https://arxiv.org/abs/2404.18895v2) | [Code](https://github.com/chen-yang-liu/rscama) | Image Captioning | Remote Sensing Image & Text |
| MIA 2025 | MMR-Mamba: Multi-modal MRI reconstruction with Mamba and spatial-frequency information fusion | [Link](https://doi.org/10.1016/j.media.2025.103549) |  | Image Fusion | Multi-Contrast MRI |
| IEEE TIP 2025 | S4Fusion: Saliency-Aware Selective State Space Model for Infrared and Visible Image Fusion | [Link](https://doi.org/10.1109/TIP.2025.3583132) |  | Image Fusion | RGB Images & Infrared Images |
| NeurIPS 2024 | Meteor: Mamba-based Traversal of Rationale for Large Language and Vision Models | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/473a9a75edc46eff5ff224d53d5f7294-Abstract-Conference.html) | [Code](https://github.com/ByungKwanLee/Meteor) | Large Language and Vision Model | Image & Text (Question/Rationale) |
| NeurIPS 2024 | Coupled Mamba: Enhanced Multi-modal Fusion with Coupled State Space Model | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/6e09c213ac18d6375704a4f3ea75c4f8-Abstract-Conference.html) | | multi-modal sentiment analysis | Text & Video & Audio |
| NeurIPS 2024 | RoboMamba: Multimodal State Space Model for Efficient Robot Reasoning and Manipulation | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/46a126492ea6fb87410e55a58df2e189-Abstract-Conference.html) | [Code](https://github.com/lmzpai/roboMamba) | Robot Reasoning and Manipulation | Image & Text |
| ACM MM 2024 | MambaGesture: Enhancing Co-Speech Gesture Generation with Mamba and Disentangled Multi-Modality Fusion | [Link](https://arxiv.org/pdf/2407.19976) |  | Co-Speech Gesture Generation | Motion & Audio |
| ITSC 2024 | MambaST: A Plug-and-Play Cross-Spectral Spatial-Temporal Fuser for Efficient Pedestrian Detection | [Link](https://arxiv.org/pdf/2408.01037) | [Code](https://github.com/XiangboGaoBarry/MambaST) | Pedestrian Detection | RGB & Thermal Images |
| ACML 2024 | ColorMamba: Towards High-quality NIR-to-RGB Spectral Translation with Mamba | [Link](https://proceedings.mlr.press/v260/zhai25a.html) | [Code](https://github.com/alexyangxx/colormamba) | NIR-to-RGB Translation | NIR Images & RGB Images |
| ACM TOMCCAP 2025 | JambaTalk: Speech-driven 3D Talking Head Generation based on a Hybrid Transformer-Mamba Model | [Link](https://doi.org/10.1145/3793196) |  | 3D Talking Head Generation | Motion & Audio |
| IEEE TGRS 2024 | Mask-Guided Mamba Fusion for Drone-based Visible-Infrared Vehicle Detection | [Link](https://ieeexplore.ieee.org/abstract/document/10659747) |  | Cross-Modal Detection | RGB Images & Infrared Image |
| IEEE TGRS 2024 | Joint Classification of Hyperspectral and LiDAR Data Based on Mamba | [Link](https://ieeexplore.ieee.org/abstract/document/10679212?casa_token=PSm9wdS69EUAAAAA:yur-wqMr9d5SqGTGx9n2__Xjd_mtmdSDpow15PJeDLmC6k9C9_0FQcIDowYh-pkamF75Om-_gQ) | [Code](https://github.com/Dilingliao/IEEE_TGRS_2024_HLMamba) | Classification | HSI Images & LiDAR Points |
| MICCAI 2024 | LM-UNet: Whole-Body PET-CT Lesion Segmentation with Dual-Modality-Based Annotations Driven by Latent Mamba U-Net | [Link](https://papers.miccai.org/miccai-2024/paper/1851_paper.pdf) | [Code](https://github.com/Joey-S-Liu/LM-UNet) | Medical Image Segmentation | PET & CT |
| ICLR 2025 | EMMA: Empowering Multi-modal Mamba with Structural and Hierarchical Alignment | [Link](https://openreview.net/forum?id=Ev4iw23gdI) |  | MLLM tasks | Image & Text |
| ISBI 2025 | R2Gen-Mamba: A Selective State Space Model for Radiology Report Generation | [Link](https://arxiv.org/pdf/2410.18135) | [Code](https://github.com/YonghengSun1997/R2Gen-Mamba) | Radiology Report Generation | Image & Text |
| BDAI 2025 | MSCrackMamba: Leveraging Vision Mamba for Crack Detection in Fused Multispectral Imagery | [Link](https://doi.org/10.1109/BDAI66031.2025.11325509) |  | Crack Detection | RGB Images & Infrared Images |
| CVIP 2025 | DiM-Gestor: Co-Speech Gesture Generation with Adaptive Layer Normalization Mamba-2 | [Link](https://doi.org/10.1109/CVIP67348.2025.11291529) | [Code](https://github.com/zf223669/DiMGestures) | Co-Speech Gesture Generation | Motion & Audio |
| IEEE GRSL 2024 | A Mamba-Diffusion Framework for Multimodal Remote Sensing Image Semantic Segmentation | [Link](https://ieeexplore.ieee.org/document/10733944?denied=) | [Code](https://github.com/WenliangDu/MambaDiffusion) | Semantic Segmentation | VIS Images & SAR Images |
| IEEE TIV 2024 | SeqMamba-MPR: A Spatial-Temporal Mamba Network for Place Recognition Using Sequential Multi-Modal Data | [Link](https://ieeexplore.ieee.org/document/10734248) |  | Place Recognition | LiDAR points & RGB Images |
| IEEE GRSL 2024 | S2CrossMamba: Spatial–Spectral Cross-Mamba for Multimodal Remote Sensing Image Classification | [Link](https://ieeexplore.ieee.org/abstract/document/10738515?casa_token=IxWeVx07xUkAAAAA:qyeQseQyU3UhqRO3qsBmumfYS7RRpn28Nd6K03UDcaDZAewWalSe_-mCcvfp1CgmMubRKxNo0w) | [Code](https://github.com/HyperSystemAndImageProc/S2CrossMamba) | Classification | HISR Images & LRMS Images |
| Scientific Reports 2024 | ReMamba: a hybrid CNN-Mamba aggregation network for visible-infrared person re-identification | [Link](https://www.nature.com/articles/s41598-024-80766-8) |  | Visible-infrared Re-identification | RGB Images & Infrared Images |
| IEEE TCSVT 2024 | MDNet: Mamba-Effective Diffusion-Distillation Network for RGB-Thermal Urban Dense Prediction | [Link](https://ieeexplore.ieee.org/abstract/document/10770251?casa_token=V-RNRrYSKqMAAAAA:Lfdw-KDRdew8kNCHWpKGjk6jhAeKIk3FWhwAq3LlJ-1qvnhIs-b1Dicx45RPqhBmLTTWQp57ag) | [Code](https://github.com/Tortoisewhp/MDNet) | Dense Prediction | RGB Images & Thermal Images |
| CVPR 2025 | AlignMamba: Enhancing Multimodal Mamba with Local and Global Cross-modal Alignment | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Li_AlignMamba_Enhancing_Multimodal_Mamba_with_Local_and_Global_Cross-modal_Alignment_CVPR_2025_paper.html) |  | Multi-Modality Fusion | Video & Text & Audio |
| AAAI 2025 | LOMA: Language-assisted Semantic Occupancy Network via Triplane Mamba | [Link](https://arxiv.org/pdf/2412.08388) |  | Occupancy Prediction | Image & Text |
| AAAI 2025 | MambaPro: Multi-Modal Object Re-Identification with Mamba Aggregation and Synergistic Prompt | [Link](https://arxiv.org/pdf/2412.10707) | [Code](https://github.com/924973292/MambaPro) | Object Re-Identification | RGB Images & Near Infrared Images & Thermal Infrared Images |
| AAAI 2025 | Light-T2M: A Lightweight and Fast Model for Text-to-motion Generation | [Link](https://arxiv.org/pdf/2412.11193) | [Code](https://github.com/qinghuannn/light-t2m) | Text-to-motion Generation | Motion & Text |
| AAAI 2025 | Exploiting Multimodal Spatial-temporal Patterns for Video Object Tracking | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/32372) | [Code](https://github.com/NJU-PCALab/STTrack) | Video Object Tracking | RGB Videos & TIR/Depth/Event |
| ICASSP 2025 | Trusted Mamba Contrastive Network for Multi-View Clustering | [Link](https://arxiv.org/pdf/2412.16487) |  | Multi-View Clustering | Image & Text |
| AAAI 2025 | H-MBA: Hierarchical MamBa Adaptation for Multi-Modal Video Understanding in Autonomous Driving | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/32220) |  | Video Understanding | Video & Text |
| AAAI 2025 | Skip Mamba Diffusion for Monocular 3D Semantic Scene Completion | [Link](https://arxiv.org/pdf/2501.07260) | [Code](https://github.com/xrkong/skimba) | Semantic Scene Completion | RGB Images & LiDAR Points |
| IEEE TMM 2025 | AVS-Mamba: Exploring Temporal and Multi-modal Mamba for Audio-Visual Segmentation | [Link](https://arxiv.org/pdf/2501.07810) | [Code](https://github.com/SitongGong/AVS-Mamba) | Audio-Visual Segmentation | Video & Audio |
| ICCV 2025 | LiT: Delving into a Simplified Linear Diffusion Transformer for Image Generation | [Link](https://openaccess.thecvf.com/content/ICCV2025/html/Wang_LiT_Delving_into_a_Simple_Linear_Diffusion_Transformer_for_Image_ICCV_2025_paper.html) | [Code](https://techmonsterwang.github.io/LiT/) | Image Generation | Image & Text |
| Information Fusion 2025 | An efficient cross-view image fusion method based on selected state space and hashing for promoting urban perception | [Link](https://www.sciencedirect.com/science/article/pii/S1566253524005153?casa_token=2aVkBWS0bhYAAAAA:7Hkhy6Mi8dPGAgxtTB5aJCJN7H6MjwZOdTdURrcg5n_LFb93LE-Lv5yEa7AFFddHmvlUCa_8w2Q) |  | Cross-view Geolocation | Street-view Images & Aerial-view Images |
| AAAI 2025 | Cobra: Extending Mamba to Multi-Modal Large Language Model for Efficient Inference | [Link](https://arxiv.org/abs/2403.14520) | [Code](https://github.com/h-zhao1997/cobra) | Multimodal LLM | Image & Text |
| IEEE TMM 2025 | Fusion-Mamba for Cross-modality Object Detection | [Link](https://doi.org/10.1109/TMM.2025.3599020) |  | Object Detection | RGB & Infrared Images |
| Visual Intelligence 2025 | FusionMamba: Dynamic Feature Enhancement for Multimodal Image Fusion with Mamba | [Link](https://doi.org/10.1007/s44267-024-00072-9) | [Code](https://github.com/millieXie/FusionMamba) | Image Fusion | Multi-Modal Images |
| IEEE TIP 2025 | Text-controlled Motion Mamba: Text-Instructed Temporal Grounding of Human Motion | [Link](https://doi.org/10.1109/TIP.2025.3624601) |  | Temporal Grounding | Motion & Text |
| IEEE TCSVT 2025 | CFMW: Cross-modality Fusion Mamba for Robust Object Detection under Adverse Weather with Multimodal Camera | [Link](https://arxiv.org/abs/2404.16302) | [Code](https://github.com/lhy-zjut/CFMW) | Object Detection | RGB & Infrared Images |
| AAAI 2025 | RGBT Tracking via All-layer Multimodal Interactions with Progressive Fusion Mamba | [Link](https://arxiv.org/abs/2408.08827) |  | RGB-T Tracking | RGB & Thermal Images |
| IEEE JBHI 2026 | R2GenCSR: Mining Contextual and Residual Information for LLMs-based Radiology Report Generation | [Link](https://arxiv.org/abs/2408.09743) |  | Radiology Report Generation | Image & Text |
| CVPR 2025 | OccMamba: Semantic Occupancy Prediction with State Space Models | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Li_OccMamba_Semantic_Occupancy_Prediction_with_State_Space_Models_CVPR_2025_paper.html) |  | Semantic Occupancy Prediction | LiDAR Points & RGB Images |
| AAAI 2025 | MUSE: Mamba is Efficient Multi-scale Learner for Text-video Retrieval | [Link](https://arxiv.org/abs/2408.10575) |  | Text-Video Retrieval | Video & Text |
| IEEE TETCI 2026 | DualKanbaFormer: An Efficient Selective Sparse Framework for Multimodal Aspect-Based Sentiment Analysis | [Link](https://doi.org/10.1109/tetci.2026.3671067) |  | Multi-modal Sentiment Analysis | Image & Text |
| IROS 2025 | MambaPlace:Text-to-Point-Cloud Cross-Modal Place Recognition with Attention Mamba Mechanisms | [Link](https://ieeexplore.ieee.org/document/11246747/) | [Code](https://github.com/nuozimiaowu/MambaPlace/tree/main) | Cross-Modal Place Recognition | Point Cloud & Text |
| IEEE TCSVT 2025 | Shuffle Mamba: State Space Models with Random Shuffle for Multi-Modal Image Fusion | [Link](https://arxiv.org/abs/2409.01728) |  | Image Fusion | Infrared & Visible Images |
| ICASSP 2025 | Mamba Fusion: Learning Actions Through Questioning | [Link](https://doi.org/10.1109/ICASSP49660.2025.10888933) | [Code](https://github.com/Dongzhikang/MambaVL) | Action Prediction/Action Anticipation | Video & Text |
| ICASSP 2025 | Mamba-YOLO-World: Marrying YOLO-World with Mamba for Open-Vocabulary Detection | [Link](https://doi.org/10.1109/ICASSP49660.2025.10888334) | [Code](https://github.com/Xuan-World/Mamba-YOLO-World) | Open-Vocabulary Detection | Image & Text |
| ADMA 2025 | Mamba-Enhanced Text-Audio-Video Alignment Network for Emotion Recognition in Conversations | [Link](https://doi.org/10.1007/978-981-95-3459-3_37) | [Code](https://github.com/Alena-Xinran/MaTAV) | Multi-modal Emotion Recognition | Text & Audio & Video |
| IROS 2025 | GraspMamba: A Mamba-based Language-driven Grasp Detection Framework with Hierarchical Feature Learning | [Link](https://arxiv.org/abs/2409.14403) | [Code](https://airvlab.github.io/grasp-anything/?utm_source=catalyzex.com) | Grasp Detection | Image & Text |
| ACM MM Asia 2024 | LMHaze: Intensity-aware Image Dehazing with a Large-scale Multi-intensity Real Haze Dataset | [Link](https://doi.org/10.1145/3696409.3700178) |  | Dehazing | Image & Text |
| Neurocomputing 2025 | MambaSOD: Dual Mamba-Driven Cross-Modal Fusion Network for RGB-D Salient Object Detection | [Link](https://doi.org/10.1016/j.neucom.2025.129447) | [Code](https://github.com/YueZhan721/MambaSOD) | Salient Object Detection | RGB Images & Depth Images |
| ACM MM Workshop 2024 | Moyun: A Diffusion-Based Model for Style-Specific Chinese Calligraphy Generation | [Link](https://doi.org/10.1145/3746278.3759378) |  | Style-Specific Chinese Calligraphy Generation | Image & Text |
| ICASSP 2025 | DepMamba: Progressive Fusion Mamba for Multimodal Depression Detection | [Link](https://doi.org/10.1109/ICASSP49660.2025.10889975) | [Code](https://github.com/Jiaxin-Ye/DepMamba) | Multi-modal Depression Detection | Video & Audio |
| CVPR 2025 | CXPMRG-Bench: Pre-training and Benchmarking for X-ray Medical Report Generation on CheXpert Plus Dataset | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_CXPMRG-Bench_Pre-training_and_Benchmarking_for_X-ray_Medical_Report_Generation_on_CVPR_2025_paper.html) | [Code](https://github.com/Event-AHU/Medical_Image_Analysis) | Medical Report Generation | Image & Text |
| EMNLP 2024 | Shaking Up VLMs: Comparing Transformers and Structured State Space Models for Vision & Language Modeling | [Link](https://aclanthology.org/2024.emnlp-main.793/) | [Code](https://github.com/gpantaz/vl_mamba?utm_source=catalyzex.com) | MLLM Tasks | Image & Text |
| EMNLP 2025 Findings | LongLLaVA: Scaling Multi-modal LLMs to 1000 Images Efficiently via a Hybrid Mamba-Transformer Model | [Link](https://aclanthology.org/2025.findings-emnlp.1168) | [Code](https://github.com/FreedomIntelligence/LongLLaVA) | Multimodal LLM | Image & Text |
| IROS 2025 | Mamba Policy: Towards Efficient 3D Diffusion Policy with Hybrid Selective State Models | [Link](https://doi.org/10.1109/IROS60139.2025.11247625) | [Code](https://github.com/AndyCao1125/MambaPolicy) | Robot Manipulation | 3D Point Cloud & Text |
| CVPR 2025 | MambaVLT: Time-Evolving Multimodal State Space Model for Vision-Language Tracking | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_MambaVLT_Time-Evolving_Multimodal_State_Space_Model_for_Vision-Language_Tracking_CVPR_2025_paper.html) |  | Vision-Language Tracking | RGB Images & Text |
| CVPR 2025 | LinGen: Towards High-Resolution Minute-Length Text-to-Video Generation with Linear Computational Complexity | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_LinGen_Towards_High-Resolution_Minute-Length_Text-to-Video_Generation_with_Linear_Computational_Complexity_CVPR_2025_paper.html) |  | Text-to-Video Generation | Video & Text |
| IEEE TPAMI 2025 | OccScene: Semantic Occupancy-based Cross-task Mutual Learning for 3D Scene Generation | [Link](https://arxiv.org/abs/2412.11183) |  | 3D Scene Generation | Images & Occupancy Grids |
| CVPR 2025 | Completion as Enhancement: A Degradation-Aware Selective Image Guided Mamba Fusion Network for Depth Completion | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Yan_Completion_as_Enhancement_A_Degradation-Aware_Selective_Image_Guided_Network_for_CVPR_2025_paper.html) |  | Depth Completion | RGB Images & Depth |



### Others
| Venue | Paper | Link | Code         | Task |
| :-------- | :---- | :--- | :----------- | :--- |
| PLOS ONE 2025 | Res-VMamba: Fine-Grained Food Category Visual Classification Using Selective State Space Models with Deep Residual Learning | [Link](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0322695) | [Code](https://github.com/ChiShengChen/ResVMamba) | Food Classification |
| ICRA 2025 | Motion-Guided Dual-Camera Tracker for Low-Cost Skill Evaluation of Gastric Endoscopy | [Link](https://arxiv.org/abs/2403.05146) | [Code](https://github.com/PieceZhang/MotionDCTrack) | Endoscope Tip Tracking |
| Neural Computing and Applications 2026 | Music to Dance as Language Translation using Sequence Models | [Link](https://doi.org/10.1007/s00521-026-11905-7) | [Code](http://github.com/meowatthemoon/MDLT) | Music-to-Dance |
| ICLR 2025 | Sports-Traj: A Unified Trajectory Generation Model for Multi-Agent Movement in Sports | [Link](https://arxiv.org/abs/2405.17680) | [Code](https://github.com/colorfulfuture/UniTraj-pytorch) | Trajectory Generation |
| Sleep 2025 | Mamba-based deep learning approach for sleep staging on a wireless multimodal wearable system without electroencephalography | [Link](https://doi.org/10.1093/sleep/zsag022) |  | Sleep Staging |
| Scientific Reports 2025 | Optimising TinyML with Quantization and Distillation of Transformer and Mamba Models for Indoor Localisation on Edge Devices | [Link](https://doi.org/10.1038/s41598-025-94205-9) | [Code](https://github.com/AloeUoB/tinyML_indoor_localisation) | Indoor Localisation |
| Journal of Physics: Photonics 2025 | Bidirectional Mamba state-space model for anomalous diffusion | [Link](https://doi.org/10.1088/2515-7647/add42c) | [Code](https://github.com/EMetBrown-Lab/Mamba-EMetBrown-ANDI2) | Anomalous Diffusion Analysis |
| ICCC 2024 | ST-Mamba: Spatial-Temporal Mamba for Traffic Flow Estimation Recovery with Missing Data | [Link](https://doi.org/10.1109/ICCC62479.2024.10681692) |  | Traffic Flow Estimation |



## Valuable Insights

| Venue | Paper | Link |
| :-------- | :---- | :-------- |
| ACL 2025 | The Hidden Attention of Mamba Models | [Link](https://aclanthology.org/2025.acl-long.76/) |
| CVPR 2025 | MambaOut: Do We Really Need Mamba for Vision? | [Link](https://openaccess.thecvf.com/content/CVPR2025/html/Yu_MambaOut_Do_We_Really_Need_Mamba_for_Vision_CVPR_2025_paper.html) |
| NeurIPS 2024 | Demystify Mamba in Vision: A Linear Attention Perspective | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/e618724ac897c6cf3fbfb273f8695d67-Abstract-Conference.html) |
| ICLR 2025 | A Unified Implicit Attention Formulation for Gated-Linear Recurrent Sequence Models | [Link](https://arxiv.org/abs/2405.16504) |
| NeurIPS 2024 | MambaLRP: Explaining Selective State Space Sequence Models | [Link](https://proceedings.neurips.cc/paper_files/paper/2024/hash/d6d0e41e0b1ed38c76d13c9e417a8f1f-Abstract-Conference.html) |
| CVPR 2025 Workshop | Towards Evaluating the Robustness of Visual State Space Models | [Link](https://openaccess.thecvf.com/content/CVPR2025W/AdvML/papers/Malik_Towards_Evaluating_the_Robustness_of_Visual_State_Space_Models_CVPRW_2025_paper.pdf) |


## Other Domains

### Reinforcement Learning
| Venue | Paper | Link | Code                                              |
| :-------- | :---- | :--- |:--------------------------------------------------|
| IROS 2024 | Proprioception Is All You Need: Terrain Classification for Boreal Forests | [Link](https://arxiv.org/pdf/2403.16877) | [Code](https://github.com/norlab-ulaval/BorealTC) |
| IEEE Access 2025 | Mamba as a motion encoder for robotic imitation learning | [Link](https://doi.org/10.1109/ACCESS.2025.3561283) |  |
| ICCMA 2024 | Context Aware Mamba-based Reinforcement Learning for Social Robot Navigation | [Link](https://doi.org/10.1109/ICCMA63715.2024.10843924) |  |
| NeurIPS 2024 | Is Mamba Compatible with Trajectory Optimization in Offline Reinforcement Learning? | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/5c186016d0844767209dc36e9e61441b-Abstract-Conference.html) |                                                   |
| NeurIPS 2024 | Decision Mamba: A Multi-Grained State Space Model with Self-Evolution Regularization for Offline RL | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/288b63aa98084366c4536ba0574a0f22-Abstract-Conference.html) |                                                   |
| CoRL 2024 | MaIL: Improving Imitation Learning with Selective State Space Models | [Link](https://openreview.net/pdf?id=IssXUYvVTg) | [Code](https://github.com/ALRhub/MaIL)            |
| IEEE TMRB 2024 | Visuomotor Policy Learning for Task Automation of Surgical Robot | [Link](https://ieeexplore.ieee.org/document/10685114) | [Code](https://github.com/helloskylake/surrr)     |
| NeurIPS 2024 | Decision Mamba: Reinforcement Learning via Hybrid Selective Sequence Modeling | [Link](https://openreview.net/pdf?id=wFzIMbTsY7) |                                                   |
| ICRA 2026 | DiSPo: Diffusion-SSM based Policy Learning for Coarse-to-Fine Action Abstraction | [Link](https://arxiv.org/abs/2409.14719) |  |
| ICLR 2025 | Drama: Mamba-Enabled Model-Based Reinforcement Learning Is Sample and Parameter Efficient | [Link](https://arxiv.org/abs/2410.08893) | [Code](https://github.com/IcarusWizard/DRAMA) |
| AAMAS 2025 | Multi-Agent Reinforcement Learning with Selective State-Space Models | [Link](https://dl.acm.org/doi/10.5555/3709347.3743910) | [Code](https://sites.google.com/view/multi-agent-mamba) |
| ICML 2025 | A Large Recurrent Action Model: xLSTM enables Fast Inference for Robotics Tasks | [Link](https://proceedings.mlr.press/v267/schmied25a.html) | [Code](https://github.com/ml-jku/LRAM) |
| AAAI 2025 | GLAM: Global-Local Variation Awareness in Mamba-based World Model | [Link](https://ojs.aaai.org/index.php/AAAI/article/view/33880) | [Code](https://github.com/GLAM2025/glam) |


### Graph Learning
| Venue | Paper | Link | Code         |
| :-------- | :---- | :--- | :----------- |
| KDD 2024 | Graph Mamba: Towards Learning on Graphs with State Space Models | [Link](https://arxiv.org/pdf/2402.08678) | [Code](https://github.com/graphmamba/gmn) |
| KDD 2024 Workshop | Identifying Subphenotypes for Sepsis with Acute Kidney Injury via Multimodal Graph State Space Models | [Link](https://openreview.net/pdf?id=34QhRg0Zto) | |
| AAAI 2025 | DG-Mamba: Robust and Efficient Dynamic Graph Structure Learning with Selective State Space Models | [Link](https://arxiv.org/pdf/2412.08160) | [Code](https://github.com/RingBDStack/DG-Mamba) |
| AAAI 2025 | MOL-Mamba: Enhancing Molecular Representation with Structural & Electronic Insights | [Link](https://arxiv.org/pdf/2412.16483) | [Code](https://github.com/xian-sh/MOL-Mamba) |
| AAAI 2025 | BrainMAP: Learning Multiple Activation Pathways in Brain Networks | [Link](https://arxiv.org/pdf/2412.17404) | [Code](https://github.com/LzyFischer/Graph-Mamba) |
| TMLR 2025 | DyGMamba: Efficiently Modeling Long-Term Temporal Dependency on Continuous-Time Dynamic Graphs with State Space Models | [Link](https://arxiv.org/abs/2408.04713) |  |
| NeurIPS 2025 | DyG-Mamba: Continuous State Space Modeling on Dynamic Graphs | [Link](https://arxiv.org/abs/2408.06966) | [Code](https://github.com/haoyfan/DyG-Mamba) |
| IJCNN 2025 | Topological Deep Learning with State-Space Models: A Mamba Approach for Simplicial Complexes | [Link](https://doi.org/10.1109/IJCNN64981.2025.11227272) |  |
| IJCAI 2025 | Mamba-Based Graph Convolutional Networks: Tackling Over-smoothing in Graph Neural Networks | [Link](https://doi.org/10.24963/ijcai.2025/595) |  |



### Audio
| Venue | Paper | Link | Code         |
| :-------- | :---- | :--- | :----------- |
| IEEE SPL 2024 | Multichannel Long-Term Streaming Neural Speech Enhancement for Static and Moving Speakers | [Link](https://arxiv.org/pdf/2403.07675) | [Code](https://github.com/Audio-WestlakeU/NBSS) |
| IMWUT 2025 | TRAMBA: A Hybrid Transformer and Mamba Architecture for Practical Audio and Bone Conduction Speech Super Resolution and Enhancement on Mobile and Wearable Platforms | [Link](https://doi.org/10.1145/3699757) |  |
| Interspeech 2024 | Audio Mamba: Selective State Spaces for Self-Supervised Audio Representations | [Link](https://arxiv.org/pdf/2406.02178) | [Code](https://github.com/SarthakYadav/audio-mamba-official)|
| Interspeech 2024 | RawBMamba: End-to-End Bidirectional State Space Model for Audio Deepfake Detection | [Link](https://arxiv.org/pdf/2406.06086) | [Code](https://github.com/cyjie429/RawBMamba)|
| Interspeech 2024 | Exploring the Capability of Mamba in Speech Applications | [Link](https://arxiv.org/pdf/2406.16808) | |
| SLT 2024 Workshop | An Analysis of Linear Complexity Attention Substitutes with BEST-RQ | [Link](https://arxiv.org/pdf/2409.02596) |  |
| SLT 2024 | Speech-Mamba: Long-Context Speech Recognition with Selective State Spaces Models | [Link](https://arxiv.org/pdf/2409.18654) | [Code](https://github.com/xiaoxue1117/speech-mamba-public) |
| ICASSP 2025 | Mamba-based Segmentation Model for Speaker Diarization | [Link](https://arxiv.org/pdf/2410.06459) | [Code](https://github.com/nttcslab-sp/mamba-diarization) |
| SLT 2024 | Mamba-based Decoder-Only Approach with Bidirectional Speech Modeling for Speech Recognition | [Link](https://arxiv.org/pdf/2411.06968) | [Code](https://github.com/YoshikiMas/madeon-asr) |
| LAMIR 2024 Workshop | AEROMamba: An efficient architecture for audio super-resolution using generative adversarial networks and state space models | [Link](https://arxiv.org/pdf/2411.07364) | [Code](https://github.com/aeromamba-super-resolution/aeromamba) |
| Interspeech 2025 | MASV: Speaker Verification with Global and Local Context Mamba | [Link](https://www.isca-archive.org/interspeech_2025/liu25_interspeech.html) |  |
| Expert Systems 2024 | A barking emotion recognition method based on Mamba and Synchrosqueezing Short-Time Fourier Transform | [Link](https://www.sciencedirect.com/science/article/pii/S0957417424020803) | [Code](https://github.com/yangcjya/A-barking-emotion-recognition-method-based-on-Mamba) |
| ICASSP 2025 | Mamba-SEUNet: Mamba UNet for Monaural Speech Enhancement | [Link](https://arxiv.org/pdf/2412.16626) |  |
| ICASSP 2025 | Temporal-Frequency State Space Duality: An Efficient Paradigm for Speech Emotion Recognition | [Link](https://arxiv.org/pdf/2412.16904) |  |
| APSIPA ASC 2024 | U-Mamba-Net: A highly efficient Mamba-based U-net style network for noisy and reverberant speech separation | [Link](https://arxiv.org/pdf/2412.18217) |  |
| AAAI 2025 | BSDB-Net: Band-Split Dual-Branch Network with Selective State Spaces Mechanism for Monaural Speech Enhancement | [Link](https://arxiv.org/pdf/2412.19099) |  |
| ICASSP 2025 | Improved Feature Extraction Network for Neuro-Oriented Target Speaker Extraction | [Link](https://arxiv.org/pdf/2501.01673) |  |
| IEEE SLT 2024 | An Investigation of Incorporating Mamba for Speech Enhancement | [Link](https://arxiv.org/abs/2405.06573) |  |
| IEEE TASLP 2025 | Mamba in Speech: Towards an Alternative to Self-Attention | [Link](https://doi.org/10.1109/TASLPRO.2025.3566210) |  |
| IEEE SLT 2024 | SSAMBA: Self-Supervised Audio Representation Learning with Mamba State Space Model | [Link](https://doi.org/10.1109/SLT61566.2024.10832304) | [Code](https://github.com/SiavashShams/ssamba) |
| ICASSP 2025 | Speech Slytherin: Examining the Performance and Efficiency of Mamba for Speech Separation | [Link](https://doi.org/10.1109/ICASSP49660.2025.10889391) | [Code](https://github.com/xi-j/Mamba-TasNet) |
| CIAC 2025 | SELD-Mamba: Selective State-Space Model for Sound Event Localization and Detection with Source Distance Estimation | [Link](https://arxiv.org/abs/2408.05057) |  |
| ICASSP 2025 | MusicMamba: A Dual-Feature Modeling Approach for Generating Chinese Traditional Music with SSM | [Link](https://doi.org/10.1109/ICASSP49660.2025.10890633) |  |
| ICASSP 2025 | Cross-attention Inspired Selective State Space Models for Target Sound Extraction | [Link](https://arxiv.org/abs/2409.04803) |  |
| Interspeech 2025 | TF-Mamba: A Time-Frequency Network for Sound Source Localization | [Link](https://arxiv.org/abs/2409.05034) |  |
| ICASSP 2025 | Vector Quantized Diffusion Model Based Speech Bandwidth Extension | [Link](https://doi.org/10.1109/ICASSP49660.2025.10889180) |  |
| ICASSP 2025 | Rethinking Mamba in Speech Processing by Self-Supervised Models | [Link](https://doi.org/10.1109/ICASSP49660.2025.10889111) |  |
| ICASSP 2025 | MambaFoley: Foley Sound Generation using Selective State-Space Models | [Link](https://arxiv.org/abs/2409.09162) |  |
| ICASSP 2025 | Wave-U-Mamba: An End-To-End Framework For High-Quality And Efficient Speech Super Resolution | [Link](https://doi.org/10.1109/ICASSP49660.2025.10890511) |  |
| ICASSP 2025 | Self-supervised Learning for Acoustic Few-Shot Classification | [Link](https://arxiv.org/abs/2409.09647) |  |
| ICASSP 2025 | Ultra-Low Latency Speech Enhancement - A Comprehensive Study | [Link](https://doi.org/10.1109/ICASSP49660.2025.10889823) |  |
| ICASSP 2025 | Leveraging Joint Spectral and Spatial Learning with MAMBA for Multichannel Speech Enhancement | [Link](https://arxiv.org/abs/2409.10376) |  |
| ICASSP 2025 Oral | DeFT-Mamba: Universal Multichannel Sound Separation and Polyphonic Audio Classification | [Link](https://doi.org/10.1109/ICASSP49660.2025.10890324) |  |
| ICASSP 2025 | Mamba for Streaming ASR Combined with Unimodal Aggregation | [Link](https://doi.org/10.1109/ICASSP49660.2025.10887599) |  |
| ICLR 2025 | Joint Fine-tuning and Conversion of Pretrained Speech and Language Models towards Linear Complexity | [Link](https://arxiv.org/abs/2410.06846) | [Code](https://github.com/idiap/linearize-distill-pretrained-transformers) |
| ISCAS 2025 | CleanUMamba: A Compact Mamba Network for Speech Denoising using Channel Pruning | [Link](https://arxiv.org/abs/2410.11062) |  |
| ICASSP 2025 | SepMamba: State-space models for speaker separation using Mamba | [Link](https://doi.org/10.1109/ICASSP49660.2025.10888846) | [Code](https://github.com/andrasschin/SepMamba) |
| IEEE JSTSP 2025 | SAV-SE: Scene-aware Audio-Visual Speech Enhancement with Selective State Space Model | [Link](https://doi.org/10.1109/JSTSP.2025.3558654) |  |
| IEEE SPL 2025 | XLSR-Mamba: A Dual-Column Bidirectional State Space Model for Spoofing Attack Detection | [Link](https://arxiv.org/abs/2411.10027) |  |
| ICASSP 2025 | BEST-STD: Bidirectional Mamba-Enhanced Speech Tokenization for Spoken Term Detection | [Link](https://doi.org/10.1109/ICASSP49660.2025.10887234) |  |
| ICASSP 2025 | TAME: Temporal Audio-based Mamba for Enhanced Drone Trajectory Estimation and Classification | [Link](https://doi.org/10.1109/ICASSP49660.2025.10888776) |  |
| INTERSPEECH 2025 | xLSTM-SENet: xLSTM for Single-Channel Speech Enhancement | [Link](https://arxiv.org/abs/2501.06146) | [Code](https://github.com/NikolaiKyhne/xLSTM-SENet) |
| ICASSP 2025 | MSECG: Incorporating Mamba for Robust and Efficient ECG Super-Resolution | [Link](https://doi.org/10.1109/ICASSP49660.2025.10890523) |  |




### Time Series
| Venue | Paper | Link | Code         |
| :-------- | :---- | :--- | :----------- |
| ECAI 2024 | TimeMachine: A Time Series is Worth 4 Mambas for Long-term Forecasting | [Link](https://arxiv.org/pdf/2403.09898) | [Code](https://github.com/Atik-Ahamed/TimeMachine) |
| Information Fusion 2025 | TSCMamba: Mamba Meets Multi-View Learning for Time Series Classification | [Link](https://doi.org/10.1016/j.inffus.2025.103079) |  |
| NeurIPS 2024 | Chimera: Effectively Modeling Multivariate Time Series with 2-Dimensional State Space Models | [Link](https://papers.nips.cc/paper_files/paper/2024/hash/d8e80772c27beff4ae1676fb147bbf26-Abstract-Conference.html) |  |
| CIKM 2025 | SST: Multi-Scale Hybrid Mamba-Transformer Experts for Time Series Forecasting | [Link](https://doi.org/10.1145/3746252.3761394) | [Code](https://github.com/XiongxiaoXu/SST) |
| IJCAI 2024 Workshop | SpoT-Mamba: Learning Long-Range Dependency on Spatio-Temporal Graphs with Selective State Spaces | [Link](https://arxiv.org/pdf/2406.11244) | [Code](https://github.com/bdi-lab/SpoT-Mamba) |
| ICECCE 2024 | Integration of Mamba and Transformer -- MAT for Long-Short Range Time Series Forecasting with Application to Weather Dynamics | [Link](https://arxiv.org/pdf/2409.08530) |  |
| IEEE IOTJ 2024 | HARMamba: Efficient and Lightweight Wearable Sensor Human Activity Recognition Based on Bidirectional Mamba | [Link](https://ieeexplore.ieee.org/abstract/document/10683697?casa_token=jQ61e2FtabEAAAAA:ZXVlr_VGC9IG49KLG9Y5X52MYIwEj6lQQBBXMplO7_xy2Ndhz_BPHDALOrZDlISzhGeUxjf4fQ) |  |
| SLT 2024 | SWIM: Short-Window CNN Integrated with Mamba for EEG-Based Auditory Spatial Attention Decoding | [Link](https://arxiv.org/pdf/2409.19884) | [Code](https://github.com/windowso/SWIM-ASAD) |
| IEEE GRSL 2024 | SPPMamba: State Space Models for Seismic Phase Arrival Picking | [Link](https://ieeexplore.ieee.org/abstract/document/10706215?casa_token=hWVsPICbbNQAAAAA:WGHXOb9fYNughXy-VPnJiWuGecfFA9nEqoISkGwf3mSFo58qcoGjwDZEsQ0GrVh1v9G8n6vZKA) |  |
| NeurIPS 2024 Workshop | Sequential Order-Robust Mamba for Time Series Forecasting | [Link](https://arxiv.org/pdf/2410.23356) | [Code](https://github.com/seunghan96/SOR-Mamba) |
| Scientific Reports 2024 | Application of multi-modal temporal neural network based on enhanced sparrow optimization in lithium battery life prediction | [Link](https://www.nature.com/articles/s41598-024-78211-x) |  |
| Scientific Reports 2024 | Mastering seismic time series response predictions using an attention-Mamba transformer model for bridge bearings and piers across varied testing conditions | [Link](https://www.nature.com/articles/s41598-024-79195-4) |  |
| ICASSP 2025 | SSM2Mel: State Space Model to Reconstruct Mel Spectrogram from the EEG | [Link](https://arxiv.org/pdf/2501.10402) |  |
| CGI 2024 | Mamba-Spike: Enhancing the Mamba Architecture with a Spiking Front-End for Efficient Temporal Data Processing | [Link](https://arxiv.org/abs/2408.11823) | [Code](https://github.com/ECNU-Cross-Innovation-Lab/Mamba-Spike) |
| KDD 2025 | SDE: A Simplified and Disentangled Dependency Encoding Framework for State Space Models in Time Series Forecasting | [Link](https://doi.org/10.1145/3711896.3737119) |  |
| ISCAS 2025 | SlimSeiz: Efficient Channel-Adaptive Seizure Prediction Using a Mamba-Enhanced Network | [Link](https://arxiv.org/abs/2410.09998) | [Code](https://github.com/guoruilu/SlimSeiz) |
| KDD 2025 | SSD-TS: Exploring the Potential of Linear State Space Models for Diffusion Models in Time Series Imputation | [Link](https://doi.org/10.1145/3711896.3737135) |  |
| ICLR 2025 | FACTS: A Factored State-Space Framework For World Modelling | [Link](https://arxiv.org/abs/2410.20922) | [Code](https://github.com/NanboLi/FACTS) |
| ICASSP 2025 | MSEMG: Surface Electromyography Denoising with a Mamba-based Efficient Network | [Link](https://doi.org/10.1109/ICASSP49660.2025.10887547) | [Code](https://github.com/tonyliu0910/MSEMG) |
| ICBC 2025 | CryptoMamba: Leveraging State Space Models for Accurate Bitcoin Price Prediction | [Link](https://doi.org/10.1109/ICBC64466.2025.11114565) | [Code](https://github.com/MShahabSepehri/CryptoMamba) |

If you find this repository is useful for you, please cite our paper:
```
@misc{2024visual_mamba,
      title={Visual Mamba: A Survey and New Outlooks},
      author={Rui Xu and Shu Yang and Yihui Wang and Yu Cai and Bo Du and Hao Chen},
      year={2024},
      eprint={2404.18861},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

Other works of HKUST [SMART Lab](https://hkustsmartlab.github.io/):
```
@inproceedings{MambaMIL,
  author       = {Shu Yang and Yihui Wang and Hao Chen},
  title        = {MambaMIL: Enhancing Long Sequence Modeling with Sequence Reordering in Computational Pathology},
  booktitle    = {International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)},
  volume       = {15004},
  pages        = {296--306},
  publisher    = {Springer},
  year         = {2024}
}
```
