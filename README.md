# Awesome-Vision-Mamba-Models

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/Ruixxxx/Awesome-Vision-Mamba-Models?style=flat-square)
![GitHub issues](https://img.shields.io/github/issues/Ruixxxx/Awesome-Vision-Mamba-Models?style=flat-square)
[![Arxiv Page](https://img.shields.io/badge/Arxiv-2404.18861-red?style=flat-square)](https://arxiv.org/abs/2404.18861)

[NEWS.2024/04/29] **Our [paper](https://arxiv.org/abs/2404.18861) is released!**

[NEWS.2024/05/02] **🎉🎉🎉Congratulations to [Vision Mamba](https://arxiv.org/abs/2401.09417) on being accepted in ICML 2024.**

📢**NOTE:** If you have any questions, please don't hesitate to contact us at any of the following emails: [rui.xu@whu.edu.cn](mailto:rui.xu@whu.edu.cn), [syangcw@connect.ust.hk](mailto:syangcw@connect.ust.hk), [ywangrm@connect.ust.hk](mailto:ywangrm@connect.ust.hk).

Mamba, a novel state space model, has gained recognition across diverse domains for its exceptional performance and efficient computational complexity. By addressing the limitations inherent in traditional visual foundation architectures, Mamba emerges as a promising contender poised to catalyze advancements in the field of computer vision.

:star: This repository hosts a curated collection of literature associated with Mamba models in computer vision. Feel free to star and fork. For further details, refer to the following paper:

**[A Survey on Vision Mamba: Models, Applications and Challenges](https://arxiv.org/abs/2404.18861)**<br/>
Rui Xu, Shu Yang, Yihui Wang, Bo Du, [Hao Chen](https://cse.hkust.edu.hk/~jhc/)<br/>
[SMART Lab](https://hkustsmartlab.netlify.app/), The Hong Kong University of Science and Technology<br/>
<br/>

If you find this repository is useful for you, please cite our paper:
```
@misc{2024vision_mamba,
      title={A Survey on Vision Mamba: Models, Applications and Challenges}, 
      author={Rui Xu and Shu Yang and Yihui Wang and Bo Du and Hao Chen},
      year={2024},
      eprint={},
      archivePrefix={arXiv 2404.18861},
      primaryClass={}
}
```

## Contents
- [Backbone](#backbone-for-representation-learning)
- [Related Survey](#related-survey)
- [Vision Application (Modality)](#vision-application)
  - [Image](#image)
    - [Natural Image](#natural-image)
    - [Remote Sensing Image](#remote-sensing-image)
    - [Medical Image](#medical-image)
  - [Video](#video)
  - [Point Cloud](#point-cloud)
  - [Multi-Modal](#multi-modal)
  - [Others](#others)
- [Useful Source](#useful-source)
- [Other Domains](#other-domains)
  - [Reinforcement Learning](#reinforcement-learning)
  - [Graph Learning](#graph-learning)
  - [Mixture of Experts](#moe)

## Backbone for Representation Learning
<img width="361" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/5d8ad736-d978-4bc7-a714-779f65bba661">


[Detailed Performance Comparison](SOTA_Results.md)


| Date      | Paper | Figure    | Link | Code         |
| :-------- | :---- | :-------- | :--- | :----------- |
| Arxiv 24.01.17 (ICML24)| Vision Mamba: Efficient Visual Representation Learning with Bidirectional State Space Model|<img width="684" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/6d32c807-3d2f-457e-8927-fa4bbe595064"> |[Link](https://arxiv.org/abs/2401.09417)|[Code](https://github.com/hustvl/Vim)|
| Arxiv 24.01.18 | VMamba: Visual State Space Model | <img width="806" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/039e24f6-5f89-4772-bb84-7409aeef4da0"> <img width="833" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/75158bbf-18e9-45fc-93e0-7d84c062ed0d"> | [Link](https://arxiv.org/abs/2401.10166) | [Code](https://github.com/MzeroMiko/VMamba) |
| Arxiv 24.02.08 | Mamba-ND: Selective State Space Modeling for Multi-Dimensional Data | <img width="712" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/0ee52771-63ec-4e1d-bd24-aff9fe83c8e6"> | [Link](https://arxiv.org/pdf/2402.05892) | [Code](https://github.com/jacklishufan/Mamba-ND) |
| Arxiv 24.03.14 | LocalMamba: Visual State Space Model with Windowed Selective Scan| <img width="710" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/1c2bcfb8-72d0-4f33-b561-f926952455ff"> | [Link](https://arxiv.org/pdf/2403.09338) | [Code](https://github.com/hunto/LocalMamba) |
| Arxiv 24.03.15 | EfficientVMamba: Atrous Selective Scan for Light Weight Visual Mamba | <img width="719" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/7e034c04-3359-456e-a2b3-720b4b37e975"> | [Link](https://arxiv.org/pdf/https://arxiv.org/pdf/2403.09977) | [Code](https://github.com/TerryPei/EfficientVMamba) |
| Arxiv 24.03.22 | SiMBA: Simplified Mamba-based Architecture for Vision and Multivariate Time series | <img width="622" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/bef43ea0-0d1e-4c2f-93e1-231b41394195"> | [Link](https://arxiv.org/pdf/2403.15360) | [Code](https://github.com/badripatro/Simba) |
| Arxiv 24.03.26 | PlainMamba: Improving Non-Hierarchical Mamba in Visual Recognition | <img width="713" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/d1170f9a-b9b2-4c4d-ab44-cd6c52a07c8d"> | [Link](https://arxiv.org/pdf/2403.17695) | [Code](https://github.com/ChenhongyiYang/PlainMamba) |
| Arxiv 24.05.23 | Multi-Scale VMamba: Hierarchy in Hierarchy Visual State Space Model | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/6914cba9-995f-4aa5-b550-1ddc4fe0dad4) ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/e8557985-5453-49ce-93f9-ce217c9113d8) | [Link](https://arxiv.org/pdf/2405.14174) | [Code](https://github.com/YuHengsss/MSVMamba) |
| Arxiv 24.05.23 | Scalable Visual State Space Model with Fractal Scanning | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/e53d5bc9-79ef-46a4-9321-81d0748e321f) | [Link](https://arxiv.org/pdf/2405.14480) |  |
| Arxiv 24.05.23 | Mamba-R: Vision Mamba ALSO Needs Registers | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/1948c30d-11a1-4d41-ab1b-34ab64c74a86) | [Link](https://arxiv.org/pdf/2405.14858) | [Code](https://github.com/wangf3014/Mamba-Reg) |
| Arxiv 24.05.29 | Vim-F: Visual State Space Model Benefiting from Learning in the Frequency Domain | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/c4c00462-752f-4dce-a60c-85fc34d16d6c) | [Link](https://arxiv.org/pdf/2405.18679) | [Code](https://github.com/yws-wxs/Vim-F) |
| Arxiv 24.06.11 | Autoregressive Pretraining with Mamba in Vision | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/69728c3f-6edf-480d-92ba-fda299f767a7) ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/5ced04e7-46b9-40e2-8f5a-6f0c8a68d2ca) | [Link](https://arxiv.org/pdf/2406.07537) | [Code](https://github.com/OliverRensu/ARM) |



## Related Survey

| Date      | Paper | Link |
| :-------- | :---- | :-------- |
| Arxiv 24.04.15|State Space Model for New-Generation Network Alternative to Transformers: A Survey | [Link](https://arxiv.org/pdf/2404.09516) |
| Arxiv 24.04.24|A Survey on Visual Mamba | [Link](https://arxiv.org/pdf/2404.15956v2) |
| Arxiv 24.04.24|Mamba-360: Survey of State Space Models as Transformer Alternative for Long Sequence Modelling: Methods, Applications, and Challenges | [Link](https://arxiv.org/pdf/2404.16112) |
| Arxiv 24.05.07|Vision Mamba: A Comprehensive Survey and Taxonomy | [Link](https://arxiv.org/pdf/2405.04404) |
| Arxiv 24.06.05|Computation-Efficient Era: A Comprehensive Survey of State Space Models in Medical Image Analysis | [Link](https://arxiv.org/abs/2406.03430) |

## Vision Application
### Image

#### Natural Image

| Date      | Paper | Figure    | Link | Code         | Task |
| :-------- | :---- | :-------- | :--- | :----------- | :--- |
| Arxiv 24.02.06| U-shaped Vision Mamba for Single Image Dehazing | <img width="848" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/3ca0831b-711c-4073-841e-2eba4f2e718d"> | [Link](https://arxiv.org/pdf/2402.04139) | [Code](https://github.com/zzr-idam) | Dehazing/Low Light Enhancement/Deraining |
| Arxiv 24.02.08| Scalable Diffusion Models with State Space Backbone | <img width="588" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/9d900e4b-4c3c-427a-a857-681a3f3470dd"> | [Link](https://arxiv.org/pdf/2402.05608) | [Code](https://github.com/feizc/DiS) | Image Generation |
| Arxiv 24.02.23| MambaIR: A Simple Baseline for Image Restoration with State-Space Model | <img width="708" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/22041ebc-cae7-4e72-a537-a7af3429b6d8"> | [Link](https://arxiv.org/pdf/2402.15648) | [Code](https://github.com/csguoh/MambaIR) | Super-resolution/Denoising |
| Arxiv 24.03.04| MiM-ISTD: Mamba-in-Mamba for Efficient Infrared Small Target Detection | <img width="847" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c38ffac7-65b7-452c-b0ec-c3a17f8de860"> | [Link](https://arxiv.org/pdf/2403.02148) | [Code](https://github.com/txchen-USTC/MiM-ISTD) | Infrared Image Segmentation |
| Arxiv 24.03.13| Activating Wider Areas in Image Super-Resolution | <img width="700" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/dfaf5b9a-19e0-4058-a4aa-a9af26df6334"> | [Link](https://arxiv.org/pdf/2403.08330) | | Super-resolution |
| Arxiv 24.03.18| VmambaIR: Visual State Space Model for Image Restoration |<img width="485" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/1126cd48-1c85-4c09-883f-c4a50b922fd0">|[Link](https://arxiv.org/pdf/2403.11423)| [Code](https://github.com/AlphacatPlus/VmambaIR) |Image Restoration| 
| Arxiv 24.03.20| ZigMa: A DiT-style Zigzag Mamba Diffusion Model | <img width="702" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/3a14b8da-188b-4c00-a054-c4cb47562f9e"> | [Link](https://arxiv.org/pdf/2403.13802) | [Code](https://taohu.me/zigma/) | Generation |
| Arxiv 24.03.27| Gamba: Marry Gaussian Splatting with Mamba for single view 3D reconstruction | <img width="564" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/361b14b9-6291-47d1-b8e0-ae667db5aa22"> | [Link](https://arxiv.org/pdf/2403.18795) | | 3D Reconstruction |
| Arxiv 24.03.29| Learning Enriched Features via Selective State Spaces Model for Efficient Image Deblurring | <img width="730" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/a84a1311-1ed4-4c51-828c-94b9e5b95578"> | [Link](https://arxiv.org/pdf/2403.20106) | | Image Deblurring |
| Arxiv 24.04.04| InsectMamba: Insect Pest Classification with State Space Model |<img width="554" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/2bb11b9a-c952-4f12-afd9-1ba2bce3ce9c"> | [Link](https://arxiv.org/pdf/2404.03611)| | Image Classification|
| Arxiv 24.04.09| MambaAD: Exploring State Space Models for Multi-class Unsupervised Anomaly Detection |<img width="793" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/0d601311-b0bf-48e1-b0d6-17ee9c3101d0">  | [Link](https://arxiv.org/pdf/2404.06564) | [code](https://lewandofskee.github.io/projects/MambaAD) | Anomaly Detection |
| Arxiv 24.04.11| DGMamba: Domain Generalization via Generalized State Space Model |<img width="720" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/50d5a8bb-d701-40a1-9f17-52a7d9c96221"> | [Link](https://arxiv.org/pdf/2404.07794) | [Code](https://github.com/longshaocong/DGMamba) | Domain Generalization |
| Arxiv 24.04.15| FreqMamba: Viewing Mamba from a Frequency Perspective for Image Deraining | <img width="798" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/430aabed-9c3f-40f5-b062-d748829d20fa"> | [Link](https://arxiv.org/pdf/2404.09476) |  | Deraining |
| Arxiv 24.04.17| CU-Mamba: Selective State Space Models with Channel Learning for Image Restoration | <img width="1102" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/d4c0ac33-8541-4cf0-84aa-bd5b0958516f"> | [Link](https://arxiv.org/pdf/2404.11778) | | Denoising/Deblurring |
| Arxiv 24.04.22| MambaUIE: Unraveling the Ocean's Secrets with Only 2.8 FLOPs | <img width="687" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/7e84a297-ea0f-4e27-b9cc-cdb36b2b0e6f"> | [Link](https://arxiv.org/pdf/2404.13884) | [Code](https://github.com/1024AILab/MambaUIE) | Image Enhancement |
| Arxiv 24.05.03| FER-YOLO-Mamba: Facial Expression Detection and Classification Based on Selective State Space | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/d0855ac0-d7f5-4bcd-8b99-d87630bf35f7) | [Link](https://arxiv.org/pdf/2405.01828) | [Code](https://github.com/SwjtuMa/FER-YOLO-Mamba) | Emotion recognition & Facial Expression Recognition & Detection |
| Arxiv 24.05.05| DVMSR: Distillated Vision Mamba for Efficient Super-Resolution | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/4a23e2ba-ade9-4822-b6f2-3606928e4bca) | [Link](https://arxiv.org/pdf/2405.03008) | [Code](https://github.com/nathan66666/DVMSR.git) | Super-Resolution |
| Arxiv 24.05.05| SMCD: High Realism Motion Style Transfer via Mamba-based Diffusion | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/833a3d9b-fd96-43f3-8957-da759366ac58) | [Link](https://arxiv.org/abs/2405.02844) |  | Motion Style Transfer |
| Arxiv 24.05.06| Retinexmamba: Retinex-based Mamba for Low-light Image Enhancement | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/51ad0eb7-9f0d-4ad7-ad24-70f3831db65d) | [Link](https://arxiv.org/pdf/2405.03349) | [Code](https://github.com/YhuoyuH/RetinexMamba) | Image Enhancement |
| Arxiv 24.05.07| VMambaCC: A Visual State Space Model for Crowd Counting | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/aaaf64a2-b2b7-441f-98cd-c842135d1893) | [Link](https://arxiv.org/pdf/2405.03978) |  | Crowd Counting |
| Arxiv 24.05.14| WaterMamba: Visual State Space Model for Underwater Image Enhancement | <img width="551" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/2307c102-8490-44d7-bf66-add22160739d">|[Link](https://arxiv.org/pdf/2405.08419) | | Image Enhancement |
| Arxiv 24.05.16| IRSRMamba: Infrared Image Super-Resolution via Mamba-based Wavelet Transform Feature Modulation Model | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/a9a70fb6-87cc-47cf-bf31-dd0dced8eaf3) | [Link](https://arxiv.org/pdf/2405.09873) | [Code](https://github.com/yongsongH/IRSRMamba) | Infrared Image Super-resolution |
| Arxiv 24.05.23| Efficient Visual State Space Model for Image Deblurring | <img width="540" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/a1f85d94-136f-432b-ba51-de322b500539"> |[Link](https://arxiv.org/pdf/2405.14343) | [Code](https://github.com/kkkls/EVSSM)| Image Deblurring |
| Arxiv 24.05.23| DiM: Diffusion Mamba for Efficient High-Resolution Image Synthesis | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/4669e2bd-4530-427e-9162-8cb4c709450a) | [Link](https://arxiv.org/pdf/2405.14224) | [Code](https://github.com/tyshiwo1/DiM-DiffusionMamba/) | Generation |
| Arxiv 24.05.25| Scaling Diffusion Mamba with Bidirectional SSMs for Efficient Image and Video Generation | <img width="548" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/e904635f-26e9-4690-b215-f9ea741bb354"> | [Link](https://arxiv.org/pdf/2405.15881) | | Generation |
| Arxiv 24.05.26| Image Deraining with Frequency-Enhanced State Space Model |<img width="439" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/8fd63341-7281-4911-a506-a814f5fb56df"> | [Link](https://arxiv.org/pdf/2405.16470) | | Image Deraining |
| Arxiv 24.05.28| MambaVC: Learned Visual Compression with Selective State Spaces | <img width="533" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/9591e9ef-7984-4851-bf09-dee72676c5e4"> | [Link](https://arxiv.org/pdf/2405.15413) | [Code](https://github.com/QinSY123/2024-MambaVC) |Visual Compression|
| Arxiv 24.05.29| FourierMamba: Fourier Learning Integration with State Space Models for Image Deraining |![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/ea2528c3-bf05-4852-b1bb-5732326c1aa4) | [Link](https://arxiv.org/pdf/2405.19450) | | Image Deraining |


#### Remote Sensing Image

| Date      | Paper | Figure    | Link | Code         | Task |
| :-------- | :---- | :-------- | :--- | :----------- | :--- |
| Arxiv 24.02.19| Pan-Mamba: Effective pan-sharpening with State Space Model | <img width="716" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/9cead6ad-ce09-4597-a985-8181b407523d"> | [Link](https://arxiv.org/pdf/2402.12192) | [Code](https://github.com/alexhe101/Pan-Mamba) | Pan-sharpening |
| Arxiv 24.03.28| RSMamba: Remote Sensing Image Classification with State Space Model | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/5a8fd6df-ad6f-41fb-a0d7-7fce465566c1)  | [Link](https://arxiv.org/pdf/2403.19654) | [Code](https://github.com/KyanChen/RSMamba) | Remote Sensing Images Classification|
| Arxiv 24.04.02| Samba: Semantic Segmentation of Remotely Sensed Images with State Space Model | <img width="402" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c64ee6cc-ced1-4d27-b1af-27582f089fb0"> | [Link](https://arxiv.org/pdf/2404.01705) | [Code](https://github.com/zhuqinfeng1999/Samba) | Semantic Segmentation |
| Arxiv 24.04.03| RS3Mamba: Visual State Space Model for Remote Sensing Images Semantic Segmentation | <img width="502" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/1767d964-15ea-4085-a1f0-937cba3cf915"> | [Link](https://arxiv.org/pdf/2404.02457) | [Code](https://github.com/sstary/SSRS) | Semantic Segmentation |
| Arxiv 24.04.03| RS-Mamba for Large Remote Sensing Image Dense Prediction | <img width="942" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/4c47c3b7-5df8-4d77-93ba-d35263916f03"> | [Link](https://arxiv.org/pdf/2404.02668) | [Code](https://github.com/walking-shadow/Official_Remote_Sensing_Mamba) | Semantic Segmentation/Change Detection |
| Arxiv 24.04.04| ChangeMamba: Remote Sensing Change Detection with Spatio-Temporal State Space Model | <img width="1023" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/476bf8d5-625e-4e65-ad19-bc14817c9a58">  | [Link](https://arxiv.org/pdf/2404.03425) | [Code](https://github.com/ChenHongruixuan/MambaCD) | Change Detection/Building Damage Assessment |
| Arxiv 24.04.12| SpectralMamba: Efficient Mamba for Hyperspectral Image Classification | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/ed4437bb-a15b-4818-8dad-8fa7ac7c0213) | [Link](https://arxiv.org/pdf/2404.08489) | [Code](https://github.com/danfenghong/SpectralMamba) | Hyperspectral Image Classification |
| Arxiv 24.04.15| HSIDMamba: Exploring Bidirectional State-Space Models for Hyperspectral Denoising | <img width="947" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/91ebd913-ef36-400e-a83c-8d24fc5536b3"> | [Link](https://arxiv.org/pdf/2404.09697) | | Hyperspectral Denoising |
| Arxiv 24.04.28| S2Mamba: A Spatial-spectral State Space Model for Hyperspectral Image Classification | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/e8cad91d-5c01-45f9-ba38-53d6b41b7f14) | [Link](https://arxiv.org/pdf/2404.18213) | [Code](https://github.com/PURE-melo/S2Mamba) | Hyperspectral Image Classification |
| Arxiv 24.04.29| Spectral-Spatial Mamba for Hyperspectral Image Classification | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/94bc56de-3aca-40b7-a9b8-4f7d11f0bd21) | [Link](https://arxiv.org/pdf/2404.18401) | | Hyperspectral Image Classification |
| Arxiv 24.05.02| SOAR: Advancements in Small Body Object Detection for Aerial Imagery Using State Space Models and Programmable Gradients | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/79270936-2d0e-405c-b8aa-8c3f83cfc1b9) | [Link](https://arxiv.org/pdf/2405.01699) | [Code](https://github.com/yash2629/S.O.A.R) | Detection |
| Arxiv 24.05.02| SSUMamba: Spatial-Spectral Selective State Space Model for Hyperspectral Image Denoising | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/34d3f660-a63d-45d4-91de-7ff416638543) | [Link](https://arxiv.org/pdf/2405.01726) | [Code](https://github.com/lronkitty/SSUMamba) | Hyperspectral Image Denoising |
| Arxiv 24.05.08| Frequency-Assisted Mamba for Remote Sensing Image Super-Resolution | <img width="745" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/51b4b08f-8086-4e57-8006-3e9ba06ff205"> | [Link](https://arxiv.org/pdf/2405.04964) | | Super Resolution |
| Arxiv 24.05.13| GMSR:Gradient-Guided Mamba for Spectral Reconstruction from RGB Images | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/d54a5f65-c11a-41f3-a19b-266a8232d955) | [Link](https://arxiv.org/pdf/2405.07777) | [Code](https://github.com/wxy11-27/GMSR) | Spectral Reconstruction from RGB Images |
| Arxiv 24.05.14| Rethinking Scanning Strategies with Vision Mamba in Semantic Segmentation of Remote Sensing Imagery: An Experimental Study | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/6d448bec-2670-4b6c-8ad4-9f98fe035e46) | [Link](https://arxiv.org/pdf/2405.08493) | | Semantic Segmentation |
| Arxiv 24.05.16| RSDehamba: Lightweight Vision Mamba for Remote Sensing Satellite Image Dehazing | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/036a8218-8c32-4900-aec2-4bc14bab7603) | [Link](https://arxiv.org/pdf/2405.10030) | | Dehazing |
| Arxiv 24.05.17| CM-UNet: Hybrid CNN-Mamba UNet for Remote Sensing Image Semantic Segmentation | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/abbdeaf8-5063-4349-b769-01d925a8ff48) | [Link](https://arxiv.org/pdf/2405.10530) | [Code](https://github.com/xiaobul/cm-unet) | Semantic Segmentation |
| Arxiv 24.05.20| Mamba-in-Mamba: Centralized Mamba-Cross-Scan in Tokenized Mamba Model for Hyperspectral Image Classification | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/f7b0dbed-0104-4b8b-b60c-8cc4d55482b5) | [Link](https://arxiv.org/pdf/2405.12003) | [Code](https://github.com/zhouweilian1904/Mamba-in-Mamba) | Hyperspectral Image Classification |
| Arxiv 24.05.21| 3DSS-Mamba: 3D-Spectral-Spatial Mamba for Hyperspectral Image Classification | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/e3d1175f-2b6b-4a7a-af83-264993b549c5) | [Link](https://arxiv.org/pdf/2405.12487) |  | Hyperspectral Image Classification |
| Arxiv 24.06.11| DualMamba: A Lightweight Spectral-Spatial Mamba-Convolution Network for Hyperspectral Image Classification | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/fbf7a27a-6d14-446d-ad94-2631f943c5af) | [Link](https://arxiv.org/pdf/2406.07050) |  | Hyperspectral Image Classification |


#### Medical Image

| Date      | Paper | Figure    | Link | Code         | Task |
| :-------- | :---- | :-------- | :--- | :----------- | :--- |
| Arxiv 24.01.09| U-Mamba: Enhancing Long-range Dependency for Biomedical Image Segmentation | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/0bb9063c-ee32-4269-a803-778f2c6f2d64) | [Link](https://arxiv.org/pdf/2401.04722) | [Code](https://wanglab.ai/u-mamba.html) | 2D Medical Segmentation/ </br> 3D Medical Segmentation |
| Arxiv 24.01.24| SegMamba: Long-range Sequential Modeling Mamba For 3D Medical Image Segmentation | <img width="635" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/690c8341-1f17-4f8f-929a-d7f31094ad64"> | [Link](https://arxiv.org/pdf/2401.13560) | [Code](https://github.com/ge-xing/SegMamba) |3D Medical Segmentation|
| Arxiv 24.02.04| VM-UNet: Vision Mamba UNet for Medical Image Segmentation | <img width="544" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/320dda01-12dc-4e37-992d-8551c99b475a"> | [Link](https://arxiv.org/pdf/2402.02491) | [Code](https://github.com/JCruan519/VM-UNet) | 2D Medical Segmentation |
| Arxiv 24.02.05| nnMamba: 3D Biomedical Image Segmentation, Classification and Landmark Detection with State Space Model | <img width="949" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/2b1669ec-d1f5-4c6c-a743-1620ab83fef3"> | [Link](https://arxiv.org/pdf/2402.03526) | [Code](https://github.com/lhaof/nnMamba) | 3D Medical Segmentation |
| Arxiv 24.02.05| Swin-UMamba: Mamba-based UNet with ImageNet-based pretraining | <img width="711" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/2b1c8b89-2b8c-4273-ae25-833f87fc97c2"> | [Link](https://arxiv.org/pdf/2402.03302) | [Code](https://github.com/JiarunLiu/Swin-UMamba) | 2D Medical Segmentation |
| Arxiv 24.02.07| Mamba-UNet: UNet-Like Pure Visual Mamba for Medical Image Segmentation | <img width="698" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/0a09dda6-986b-480d-8445-1db4a02f16f1"> | [Link](https://arxiv.org/pdf/2402.05079) | [Code](https://github.com/ziyangwang007/MambaUNet) | 2D Medical Segmentation |
| Arxiv 24.02.09| FD-Vision Mamba for Endoscopic Exposure Correction | <img width="666" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/f87cc9c6-efa9-40ca-bf76-af7dd19b2277"> | [Link](https://arxiv.org/pdf/2402.06378) | [Code](https://github.com/zzr-idam/FDVM-Net) | Endoscopic Exposure Correction |
| Arxiv 24.02.11| Semi-Mamba-UNet: Pixel-Level Contrastive Cross-Supervised Visual Mamba-based UNet for Semi-Supervised Medical Image Segmentation | <img width="623" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/e702b599-682b-42b0-8477-a72972843803"> | [Link](https://arxiv.org/pdf/2402.07245) | [Code](https://github.com/ziyangwang007/Mamba-UNet) | 2D Medical Segmentation |
| Arxiv 24.02.13| P-Mamba: Marrying Perona Malik Diffusion with Mamba for Efficient Pediatric Echocardiographic Left Ventricular Segmentation | <img width="717" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/cbbc8a01-b1bb-44bf-8954-4485605a8326"> | [Link](https://arxiv.org/pdf/2402.08506v2) | | 2D Medical Segmentation |
| Arxiv 24.02.16| Weak-Mamba-UNet: Visual Mamba Makes CNN and ViT Work Better for Scribble-based Medical Image Segmentation | <img width="706" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/909947ae-9ba2-47f9-b257-620663d55820"> | [Link](https://arxiv.org/pdf/2402.10887) | [Code](https://github.com/ziyangwang007/Mamba-UNet) | 2D Medical Segmentation|
| Arxiv 24.02.28| MambaMIR: An Arbitrary-Masked Mamba for Joint Medical Image Reconstruction and Uncertainty Estimation |<img width="733" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/ea55e5c2-27bb-4155-a1b3-769fbb46c1f3"> | [Link](https://arxiv.org/pdf/2402.18451v1) | [Code](https://github.com/ayanglab/MambaMIR) | Medical Image Reconstruction/Uncertainty Estimation |
| Arxiv 24.03.06| MedMamba: Vision Mamba for Medical Image Classification | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/40c97c50-9c24-41e2-b449-d1cf9a58c887) | [Link](https://arxiv.org/pdf/2403.03849) | [Code](https://github.com/YubiaoYue/MedMamba) | 2D Medical Classification |
| Arxiv 24.03.08| LightM-UNet: Mamba Assists in Lightweight UNet for Medical Image Segmentation | <img width="587" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/20237455-6ec6-49a1-81ba-05553c69910d"> | [Link](https://arxiv.org/pdf/2403.05246) | [Code](https://github.com/MrBlankness/LightM-UNet) | 2D Medical Segmentation/ </br> 3D Medical Segmentation |
| Arxiv 24.03.08| MamMIL: Multiple Instance Learning for Whole Slide Images with State Space Models | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/44567e8c-0cc8-4cc7-a4ed-a2376bfea6ae) | [Link](https://arxiv.org/pdf/2403.05160) | | Cancer Subtyping |
| Arxiv 24.03.11 (MICCAI24)| MambaMIL: Enhancing Long Sequence Modeling with Sequence Reordering in Computational Pathology | <img width="516" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/fc147a4e-8a81-4862-b222-b52929def042"> | [Link](https://arxiv.org/pdf/2403.06800) | [Code](https://github.com/isyangshu/MambaMIL) | Cancer Subtyping/ </br> Survival Prediction |
| Arxiv 24.03.12| Large Window-based Mamba UNet for Medical Image Segmentation: Beyond Convolution and Self-attention | <img width="848" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/2e91f2b6-e13d-48b1-9012-91b8ce5f1f43"> | [Link](https://arxiv.org/pdf/2403.07332) | [Code](https://github.com/wjh892521292/LMa-UNet) | 2D Medical Segmentation/ </br> 3D Medical Segmentation |
| Arxiv 24.03.13| MD-Dose: A Diffusion Model based on the Mamba for Radiotherapy Dose Prediction | <img width="683" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/4440c5f1-1197-4295-b585-52314a144539"> | [Link](https://arxiv.org/pdf/2403.08479) | [Code](https://github.com/flj19951219/mamba_dose) | Radiation Dose Prediction (Segmentation) |
| Arxiv 24.03.14| VM-UNET-V2 Rethinking Vision Mamba UNet for Medical Image Segmentation | <img width="702" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/3f285231-30db-4737-a790-e69f0646d155"> | [Link](https://arxiv.org/pdf/2403.09157) | [Code](https://github.com/nobodyplayer1/VM-UNetV2) | 2D Medical Segmentation |
| Arxiv 24.03.20|H-vmunet: High-order Vision Mamba UNet for Medical Image Segmentation| <img width="748" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/88ae6463-46e9-4c84-a658-160bbbf4d9cf"> | [Link](https://arxiv.org/pdf/2403.13642) | [Code](https://github.com/wurenkai/H-vmunet) | 2D Medical Segmentation |
| Arxiv 24.03.20| ProMamba: Prompt-Mamba for polyp segmentation | <img width="741" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/56106afc-1d80-42db-bb9f-a6daaed7abc8"> | [Link](https://arxiv.org/pdf/2403.13660) | | 2D Medical Segmentation |
| Arxiv 24.03.25| CMViM: Contrastive Masked Vim Autoencoder for 3D Multi-modal Representation Learning for AD classification | <img width="707" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c71f93de-e730-40b2-bb23-74a07c868ab7"> | [Link](https://arxiv.org/pdf/2403.16520) | | Alzheimer’s disease Classification (CT/MRI)|
| Arxiv 24.03.26| Integrating Mamba Sequence Model and Hierarchical Upsampling Network for Accurate Semantic Segmentation of Multiple Sclerosis Legion |  <img width="622" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c0b134c5-f7e4-4794-86e2-b20ddca84469"> | [Link](https://arxiv.org/pdf/2403.17432) | | 2D Medical Segmentation (2D MRI) |
| Arxiv 24.03.26| Serpent: Scalable and Efficient Image Restoration via Multi-scale Structured State Space Models | <img width="633" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/5d4acab4-a1bb-4563-8551-151295f08bf2"> | [Link](https://arxiv.org/pdf/2403.17902) | | Image Resotration|
| Arxiv 24.03.26| Rotate to Scan: UNet-like Mamba with Triplet SSM Module for Medical Image Segmentation | <img width="830" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/100bc4e7-65e1-43d9-815d-99b394e12b4f"> | [Link](https://arxiv.org/pdf/2403.17701) |  | 2D Medical Segmentation |
| Arxiv 24.03.29| UltraLight VM-UNet: Parallel Vision Mamba Significantly Reduces Parameters for Skin Lesion Segmentation | <img width="725" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/14d04b8b-cbe6-429d-984d-3ac7dd894bf3"> | [Link](https://arxiv.org/pdf/2403.20035) | [Code](https://github.com/wurenkai/UltraLight-VM-UNet) | 2D Medical Segmentation |
| Arxiv 24.04.01| T-Mamba: Frequency-Enhanced Gated Long-Range Dependency for Tooth 3D CBCT Segmentation | <img width="603" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/b01c38ef-6623-4e9b-867b-ba6f39575b5c"> | [Link](https://arxiv.org/pdf/2404.01065) | [Code](https://github.com/isbrycee/T-Mamba) | 3D Medical Segmentation (Tooth) |
| Arxiv 24.04.10| ViM-UNet: Vision Mamba for Biomedical Segmentation | <img width="581" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/1c32deb4-7695-4cb6-bbc7-5912a69bed98"> | [Link](https://arxiv.org/pdf/2404.07705) | [Code](https://github.com/constantinpape/torch-em/blob/main/vimunet.md) | 2D Medical Segmentation (Cell/Neurite) |
| Arxiv 24.04.19| Vim4Path: Self-Supervised Vision Mamba for Histopathology Images | <img width="939" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/9e5d4ef7-89f5-47da-bf5e-38367997f54f"> | [Link](https://arxiv.org/pdf/2404.13222) | [Code](https://github.com/AtlasAnalyticsLab/Vim4Path) | Cancer Subtyping |
| Arxiv 24.04.26| Optimizing Universal Lesion Segmentation: State Space Model-Guided Hierarchical Networks with Feature Importance Adjustment | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/8677a439-1c4b-4b4e-8dc1-f0003167c855) | [Link](https://arxiv.org/pdf/2404.17235) |  | Universal Lesion Segmentation |
| Arxiv 24.04.26| Sparse Reconstruction of Optical Doppler Tomography Based on State Space Model | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/383012cc-e1f4-40b1-94f3-46156ae240ad) | [Link](https://arxiv.org/pdf/2404.17484) |  | ODT Sparse Reconstruction |
| Arxiv 24.05.05| AC-MAMBASEG: An adaptive convolution and Mamba-based architecture for enhanced skin lesion segmentation | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/3a114a55-479a-467a-af92-029b2af250c1) | [Link](https://arxiv.org/pdf/2405.03011) | [Code](https://github.com/vietthanh2710/AC-MambaSeg) | Skin Lesion Segmentation |
| Arxiv 24.05.08| HC-Mamba: Vision MAMBA with Hybrid Convolutional Techniques for Medical Image Segmentation | <img width="689" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/dd95c6d9-9d34-4460-9936-e6de2971dab8">| [Link](https://arxiv.org/pdf/2405.05007) | | 2D Medical Segmentation |
| Arxiv 24.05.09| VM-DDPM: Vision Mamba Diffusion for Medical Image Synthesis |<img width="724" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/fe63dac2-8500-48cb-8237-2b0c02f5be38">| [Link](https://arxiv.org/pdf/2405.05667)| | Medical Image Generation |
| Arxiv 24.05.24| MUCM-Net: A Mamba Powered UCM-Net for Skin Lesion Segmentation | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/4e59cd89-00a0-4c97-9e2d-2df413843b4c) | [Link](https://arxiv.org/pdf/2405.15925) | [Code](https://github.com/chunyuyuan/MUCM-Net) | Medical Image Segmentation |
| Arxiv 24.05.25| UU-Mamba: Uncertainty-aware U-Mamba for Cardiac Image Segmentation | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/d1b6f917-07c7-491b-82cd-a726d89a4d50) | [Link](https://arxiv.org/pdf/2405.17496) | | Medical Image Segmentation |
| Arxiv 24.05.27| TokenUnify: Scalable Autoregressive Visual Pre-training with Mixture Token Prediction | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/e557c853-cc47-4e48-a5f4-ca506402d717) | [Link](https://arxiv.org/pdf/2405.16847) | [Code](https://github.com/ydchen0806/TokenUnify) | Pre-training/Medical Image Segmentation | 
| Arxiv 24.05.27| Enhancing Global Sensitivity and Uncertainty Quantification in Medical Image Reconstruction with Monte Carlo Arbitrary-Masked Mamba | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/39dcf5e1-83e8-4490-a1d7-002b27ca2e75) | [Link](https://arxiv.org/pdf/2405.17659) | | Medical Image Reconstruction |
| Arxiv 24.05.28| Cardiovascular Disease Detection from Multi-View Chest X-rays with BI-Mamba | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/ef8f07aa-0f26-4afe-9eed-ecd68cf65062) | [Link](https://arxiv.org/pdf/2405.18533) | [Code](https://github.com/RPIDIAL/BI-Mamba) | CVD Risk Prediction |
| Arxiv 24.06.01| SAM-VMNet: Deep Neural Networks For Coronary Angiography Vessel Segmentation | <img width="602" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/b5d17a68-7e29-4012-9d2e-449bba21745d"> | [Link](https://arxiv.org/pdf/2406.00492) | | Medical Image Segmentation |





### Video

| Date      | Paper | Figure    | Link | Code         | Task |
| :-------- | :---- | :-------- | :--- | :----------- | :--- |
| Arxiv 24.01.25| Vivim: a Video Vision Mamba for Medical Video Object Segmentation | <img width="596" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/e30c0ceb-5399-44b5-99b7-65ada043c87c"> | [Link](https://arxiv.org/pdf/2401.14168) | [Code](https://github.com/scott-yjyang/Vivim) | Medical Video Segmentation |
| Arxiv 24.03.11| VideoMamba: State Space Model for Efficient Video Understanding | <img width="728" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/08797465-f93f-49ce-b724-91b67fabbabd"> | [Link](https://arxiv.org/pdf/2403.06977) | [Code](https://github.com/OpenGVLab/VideoMamba) | Action Recognition/Video Understanding/Text-to-video Retrieval |
| Arxiv 24.03.12| SSM Meets Video Diffusion Models: Efficient Video Generation with Structured State Spaces| <img width="655" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/1b1ce7b5-392c-46dd-b4e2-d6e03f6af1ab"> | [Link](https://arxiv.org/pdf/2403.07711)|[Code](https://github.com/shim0114/SSM-Meets-Video-Diffusion-Models)| Video Generation |
| Arxiv 24.03.14| Video Mamba Suite: State Space Model as a Versatile Alternative for Video Understanding | <img width="704" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/70fb7829-d28e-4bbc-b326-fcb167dad979"> | [Link](https://arxiv.org/pdf/2403.09626) | [Code](https://github.com/OpenGVLab/video-mamba-suite) | Action Recognition/Action Localization/... |
| Arxiv 24.04.09| RhythmMamba: Fast Remote Physiological Measurement with Arbitrary Length Videos | <img width="881" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/f1b0f8a1-f10f-43c6-8203-701ae0376af2"> | [Link](https://arxiv.org/pdf/2404.06483) | [Code](https://github.com/zizhengguo/RhythmMamba) | Remote photoplethysmography  Prediction |
| Arxiv 24.04.11| Simba: Mamba augmented U-ShiftGCN for Skeletal Action Recognition in Videos | <img width="697" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/ea35cf6a-e2a6-4eab-8da7-2cb7cd098507"> | [Link](https://arxiv.org/pdf/2404.07645) | | Skeleton Action Recognition|
| Arxiv 24.05.05| Matten: Video Generation with Mamba-Attention | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/f4f44af1-8ad6-4fbf-8b10-3ea8ad99a4bf) | [Link](https://arxiv.org/pdf/2405.03025) |  | Video Generation |
| Arxiv 24.05.30| DeMamba: AI-Generated Video Detection on Million-Scale GenVideo Benchmark | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/f6f4c8d6-5c22-44a3-a56f-24990315596d) | [Link](https://arxiv.org/pdf/2405.19707) | [Code](https://github.com/chenhaoxing/DeMamba) | AI-Generated Video Detection |



### Point Cloud

| Date      | Paper | Figure    | Link | Code         | Task |
| :-------- | :---- | :-------- | :--- | :----------- | :--- |
| Arxiv 24.02.16| PointMamba: A Simple State Space Model for Point Cloud Analysis | <img width="718" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/e252e787-0189-4f94-bea1-2944d50b18f4"> | [Link](https://arxiv.org/pdf/2402.10739) | [Code](https://github.com/LMD0311/PointMamba) | Classification, Part Segmentation |
| Arxiv 24.03.01| Point Cloud Mamba: Point Cloud Learning via State Space Model|<img width="692" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/6a315d04-afe6-41d1-b8d5-d931a891a681"> | [Link](https://arxiv.org/pdf/2403.00762) | [Code](https://github.com/SkyworkAI/PointCloudMamba) | Classification, Part Segmentation, Semantic Segmentation |
| Arxiv 24.03.11| Point Mamba: A Novel Point Cloud Backbone Based on State Space Model with Octree-Based Ordering Strategy| <img width="882" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c1c7c020-28cc-4ca6-b271-1d3cf665243f"> | [Link](https://arxiv.org/pdf/2403.06467) | [Code](https://github.com/IRMVLab/Point-Mamba) | Classification, Semantic Segmentation |
| Arxiv 24.04.08|3DMambaIPF: A State Space Model for Iterative Point Cloud Filtering via Differentiable Rendering | <img width="1028" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/ab137b17-85c1-4b6c-96d4-9ae5bfd45a1b"> | [Link](https://arxiv.org/pdf/2404.05522) | | Point Cloud Filtering |
| Arxiv 24.04.10|3DMambaComplete: Exploring Structured State Space Model for Point Cloud Completion | <img width="1020" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/da19fb01-52bd-4a55-b0ca-9681fdaef9ed"> | [Link](https://arxiv.org/pdf/2404.07106) |  | Point Cloud Completion |
| Arxiv 24.04.23| Mamba3D: Enhancing Local Features for 3D Point Cloud Analysis via State Space Model | <img width="959" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/6b565138-1c2d-4201-bd34-8b4343a62ec9"> | [Link](https://arxiv.org/pdf/2404.14966) | | Classification, Part Segmentation |
| Arxiv 24.05.09| Rethinking Efficient and Effective Point-based Networks for Event Camera Classification and Regression: EventMamba | <img width="1528" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/2a7422a9-9483-4b5c-be57-5b2c04f4b614"> | [Link](https://arxiv.org/abs/2405.06116) | | Classification, Regression |
| Arxiv 24.05.13| OverlapMamba: Novel Shift State Space Model for LiDAR-based Place Recognition | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/d0f1b07e-8f8e-4e3e-b58b-205dcda758b3) | [Link](https://arxiv.org/pdf/2405.07966) | [Code](https://github.com/scnu-rislab/overlapmamba) | LiDAR Place Recognition |
| Arxiv 24.05.23| MAMBA4D: Efficient Long-Sequence Point Cloud Video Understanding with Disentangled Spatial-Temporal State Space Models | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/66156d4f-c0e6-4636-bd1f-6e9cc2575c97) | [Link](https://arxiv.org/pdf/2405.14338) |  | Point Cloud Video Understanding |
| Arxiv 24.05.24| PoinTramba: A Hybrid Transformer-Mamba Framework for Point Cloud Analysis | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/d40f7136-4d8d-4ef5-a4de-394ae1fcac83) | [Link](https://arxiv.org/pdf/2405.15463) | [Code](https://github.com/xiaoyao3302/PoinTramba) | Classification, Part Segmentation |
| Arxiv 24.05.27| LCM: Locally Constrained Compact Point Cloud Model for Masked Point Modeling | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/5e99d4e4-9c05-4d14-a38a-30641f49328b) | [Link](https://arxiv.org/pdf/2405.17149) | | Classification, Part Segmentation, Object Detection |



### Multi-Modal

| Date      | Paper | Figure    | Link | Code         | Task | Modality|
| :-------- | :---- | :-------- | :--- | :----------- | :--- | :--- |
| Arxiv 24.01.25| MambaMorph: a Mamba-based Framework for Medical MR-CT Deformable Registration | <img width="705" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/0584bfee-1ed2-4d5b-984e-c374491adab9"> | [Link](https://arxiv.org/pdf/2401.13934) | [Code](https://github.com/Guo-Stone/MambaMorph) | Registration | MRI & CT|
| Arxiv 24.03.07| InstructGIE: Towards Generalizable Image Editing | <img width="912" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/45b0c86f-f473-4eb7-a821-7be8e3be417d"> | [Link](https://arxiv.org/pdf/2403.05018) | | Image Editing | Image & Text|
| Arxiv 24.03.12| Motion Mamba: Efficient and Long Sequence Motion Generation with Hierarchical and Bidirectional Selective SSM | <img width="910" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/9ef9c705-657d-4b6d-b229-6e2e4270682f"> | [Link](https://arxiv.org/pdf/2403.07487) | [Code](https://steve-zeyu-zhang.github.io/MotionMamba) | Text-to-Motion Generation | Motion & Text|
| Arxiv 24.03.20| VL-Mamba: Exploring State Space Models for Multimodal Learning | <img width="718" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/aa912eb8-13a7-488f-9601-d298ed6796e2"> | [Link](https://arxiv.org/pdf/2403.13600) | [Code](https://yanyuanqiao.github.io/vl-mamba) | MLLM tasks | Image & Text |
| Arxiv 24.03.21| Cobra: Extending Mamba to Multi-Modal Large Language Model for Efficient Inference | <img width="626" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/df845d03-3739-4b78-9328-6c2df2e98aad"> | [Link](https://arxiv.org/pdf/2403.14520) | [Code](https://sites.google.com/view/cobravlm) | MLLM tasks | Image & Text |
| Arxiv 24.03.26| ReMamber: Referring Image Segmentation with Mamba Twister | <img width="715" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/08c3e6e4-49ca-4081-bea6-ed4c7b046c0b"> | [Link](https://arxiv.org/pdf/2403.17839) | | Referring Image Segmentation | Image & Text |
| Arxiv 24.04.01| SpikeMba: Multi-Modal Spiking Saliency Mamba for Temporal Video Grounding| <img width="727" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/04cba5ac-b2f0-4357-b447-1e14a1d2617b"> | [Link](https://arxiv.org/pdf/2404.01174) | | Temporal Video Grounding | Video & Text |
| Arxiv 24.04.05| Sigma: Siamese Mamba Network for Multi-Modal Semantic Segmentation | <img width="702" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/a972740b-774c-4e14-a914-791aa5f519b8"> | [Link](https://arxiv.org/pdf/2404.04256) | [Code](https://github.com/zifuwan/Sigma) | Semantic Segmentation | RGB Images & Depth/Thermal Images |
| Arxiv 24.04.07| VMambaMorph: a Multi-Modality Deformable Image Registration Framework based on Visual State Space Model with Cross-Scan Module | <img width="711" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/6d47fc18-f044-49ed-8724-941a4fe46ebc"> | [Link](https://arxiv.org/pdf/2404.05105) | [Code](https://github.com/ziyangwang007/VMambaMorph) | Registration | MRI & CT|
| Arxiv 24.04.11| SurvMamba: State Space Model with Multi-grained Multi-modal Interaction for Survival Prediction| <img width="813" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c9307069-4672-47ed-9706-1003a5ad5eff"> | [Link](https://arxiv.org/pdf/2404.08027) | | Cancer Subtyping/Survival Prediction | WSIs & Gene|
| Arxiv 24.04.11| FusionMamba: Efficient Image Fusion with State Space Model| <img width="816" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/2182cfb2-fa6f-4dea-ab2b-d21b906a683f"> | [Link](https://arxiv.org/pdf/2404.07932) | | Pansharpening | HISR Images & LRMS Images|
| Arxiv 24.04.12| MambaDFuse: A Mamba-based Dual-phase Model for Multi-modality Image Fusion | <img width="1035" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/5921c2d4-d50d-48a3-928a-1dc69a60deb6"> | [Link](https://arxiv.org/pdf/2404.08406) | | Multi-modality Image Fusion  | RGB & Thermal Images, MRI & CT/PET/SPECT|
| Arxiv 24.04.14|Fusion-Mamba for Cross-modality Object Detection | <img width="902" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/97b716a5-f647-43d9-a1fe-dc8b2b02670d"> | [Link](https://arxiv.org/pdf/2404.09146) | | Visible-infrared Images Fusion | RGB Images & Infrared Images |
| Arxiv 24.04.14|A Novel State Space Model with Local Enhancement and State Sharing for Image Fusion| <img width="1013" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/df942cab-7802-4314-b7a7-549439b74f06"> | [Link](https://arxiv.org/pdf/2404.09293) | |  Pansharpening | HISR Images & LRMS Images|
| Arxiv 24.04.15| FusionMamba: Dynamic Feature Enhancement for Multimodal Image Fusion with Mamba | <img width="906" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/87093676-286c-4e35-89b7-7e573679cc67"> | [Link](https://arxiv.org/pdf/2404.09498) | [Code](https://github.com/millieXie/FusionMamba) | Image Fusion | RGB & Infrared Images, MRI & CT/PET/SPECT, PC & GFP|
| Arxiv 24.04.17| Text-controlled Motion Mamba: Text-Instructed Temporal Grounding of Human Motion | <img width="810" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/f27aa176-65e2-44db-a172-56712e789729"> | [Link](https://arxiv.org/pdf/2404.11375) | |  Temporal Grounding | Motion & Text |
| Arxiv 24.04.25| CFMW: Cross-modality Fusion Mamba for Multispectral Object Detection under Adverse Weather Conditions | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/5384d699-ed2f-46f5-bc56-2e61c03d2a51) | [Link](https://arxiv.org/pdf/2404.16302) | [Code](https://github.com/lhy-zjut/CFMW) |  Visible-infrared Images Fusion | RGB Images & Infrared Images|
| Arxiv 24.04.27| Revisiting Multi-modal Emotion Learning with Broad State Space Models and Probability-guidance Fusion | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/c0df9475-fa5b-4b5e-af29-44ace6ae7ef2) | [Link](https://arxiv.org/pdf/2404.17858) | | Multi-modal Emotion Recognition | Text & Video & Audio |
| Arxiv 24.04.28| Mamba-FETrack: Frame-Event Tracking via State Space Model | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/0893109c-1e78-4f43-be58-e61beebe6f4c) | [Link](https://arxiv.org/pdf/2404.18174) | [Code](https://github.com/Event-AHU/Mamba_FETrack) | RGB-Event Tracking | RGB Frames & Event |
| Arxiv 24.04.29| RSCaMa: Remote Sensing Image Change Captioning with State Space Model | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/cf319422-e155-4106-a3d6-2f59b3be82a8) | [Link](https://arxiv.org/abs/2404.18895v2) | [Code](https://github.com/chen-yang-liu/rscama) | Image Captioning | Remote Sensing Image & Text |
| Arxiv 24.04.30| CLIP-Mamba: CLIP Pretrained Mamba Models with OOD and Hessian Evaluation | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/55656071/a38f3ef2-f6e7-46bf-b5b9-dd22cafeac0e) | [Link](https://arxiv.org/pdf/2404.19394) | [Code](https://github.com/raytrun/mamba-clip) | OOD | Image & Text |
| Arxiv 24.05.22| I2I-Mamba: Multi-modal medical image synthesis via selective state space modeling | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/1bd027fe-54fd-4d4e-8a77-6d1086803ea8) | [Link](https://arxiv.org/pdf/2405.14022) | [Code](https://github.com/icon-lab/I2I-Mamba) | Medical Image Generation | MRI/CT |
| Arxiv 24.05.24| Meteor: Mamba-based Traversal of Rationale for Large Language and Vision Models | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/69cb87ad-3a1e-4f3c-983b-005b315b719b) | [Link](https://arxiv.org/pdf/2405.15574) | [Code](https://github.com/ByungKwanLee/Meteor) | Large Language and Vision Model | Image & Text (Qestion/Rationale) |
| Arxiv 24.05.29| Coupled Mamba: Enhanced Multi-modal Fusion with Coupled State Space Model | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/20546aeb-f54a-477d-822c-f085f831dc7d) | [Link](https://arxiv.org/pdf/2405.18014) | | multi-modal sentiment analysis | Text & Video & Audio |
| Arxiv 24.05.31| S4Fusion: Saliency-aware Selective State Space Model for Infrared Visible Image Fusion |<img width="539" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/74030174/15ab4235-93bd-4e6d-b836-79142bfa84ec"> | [Link](https://arxiv.org/pdf/2405.20881) | |Image Fusion |
### Others
| Date      | Paper | Figure    | Link | Code         | Task |
| :-------- | :---- | :-------- | :--- | :----------- | :--- |
| Arxiv 24.02.24|Res-VMamba: Fine-Grained Food Category Visual Classification Using Selective State Space Models with Deep Residual Learning | <img width="683" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/e8ed3e23-e305-4b8a-a706-0601c1ef3b1b"> | [Link](https://arxiv.org/pdf/2402.15761) | [Code](https://github.com/ChiShengChen/ResVMamba) | Food Classification |
| Arxiv 24.03.08|Motion-Guided Dual-Camera Tracker for Low-Cost Skill Evaluation of Gastric Endoscopy | <img width="943" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/4cce4533-8d35-4acc-8cb3-6ad44603dc04"> | [Link](https://arxiv.org/pdf/2403.05146) | [Code](https://github.com/PieceZhang/MotionDCTrack) | Endoscope Tip Tracking |
| Arxiv 24.03.14| MambaTalk: Efficient Holistic Gesture Synthesis with Selective State Space Models| <img width="429" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/42ea6b78-cb43-401b-9f81-764a521cfa17"> | [Link](https://arxiv.org/pdf/2403.09471) |  | Gesture Synthesis |
| Arxiv 24.03.15| On the low-shot transferability of [V]-Mamba? | <img width="440" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/8e5c32ed-e499-44c5-9c33-ef5cd6873140"> | [Link](https://arxiv.org/pdf/2403.10696) | | Few-shot Learning |
| Arxiv 24.03.22| Music to Dance as Language Translation using Sequence Models | <img width="541" alt="image" src="https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/3e647680-22c7-4885-9ada-f32d9288f1ba"> | [Link](https://arxiv.org/pdf/2403.15569) | [Code](http://github.com/meowatthemoon/MDLT) | Music-to-Dance |
| Arxiv 24.05.08| Traj-LLM: A New Exploration for Empowering Trajectory Prediction with Pre-trained Large Language Models | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/453639a0-a917-4ef3-8d15-5118bb019466) | [Link](https://arxiv.org/abs/2405.04909) | | Trajectory Prediction with LLM |



## Valuable insights

| Date      | Paper | Link |
| :-------- | :---- | :-------- |
| Arxiv 24.03.03|The Hidden Attention of Mamba Models | [Link](https://arxiv.org/abs/2403.01590) |
| Arxiv 24.03.16|Understanding Robustness of Visual State Space Models for Image Classification | [Link](https://arxiv.org/abs/2403.10935) |
| Arxiv 24.05.13|MambaOut: Do We Really Need Mamba for Vision? | [Link](https://arxiv.org/pdf/2405.07992) |
| Arxiv 24.05.26|Demystify Mamba in Vision: A Linear Attention Perspective | [Link](https://arxiv.org/pdf/2405.16605) |



## Other Domains

### Reinforcement Learning
| Date      | Paper | Figure    | Link | Code         |
| :-------- | :---- | :-------- | :--- | :----------- |
| Arxiv 24.05.20 | Is Mamba Compatible with Trajectory Optimization in Offline Reinforcement Learning? | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/fa757c1f-c200-4387-8ee0-dc373eabf7d1) | [Link](https://arxiv.org/pdf/2405.12094) | |

### Graph Learning
| Date      | Paper | Figure    | Link | Code         |
| :-------- | :---- | :-------- | :--- | :----------- |
| Arxiv 24.05.22| HeteGraph-Mamba: Heterogeneous Graph Learning via Selective State Space Model | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/4d8e3a9c-d908-4203-8a6d-1f5e62e1ecbb) | [Link](https://arxiv.org/pdf/2405.13915) | |

### Audio
| Date      | Paper | Figure    | Link | Code         |
| :-------- | :---- | :-------- | :--- | :----------- |
| Arxiv 24.04.02| SPMamba: State-space model is all you need in speech separation | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/26057f58-3c03-4600-a0a4-24699035068a) | [Link](https://github.com/JusperLee/SPMamba) | |
| Arxiv 24.05.02| TRAMBA: A Hybrid Transformer and Mamba Architecture for Practical Audio and Bone Conduction Speech Super Resolution and Enhancement on Mobile and Wearable Platforms | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/813edf33-51e8-4c9e-8ed6-11065464c6bc) | [Link](https://arxiv.org/pdf/2405.01242) | |
| Arxiv 24.05.10| An Investigation of Incorporating Mamba for Speech Enhancement | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/d21c2e96-6e7b-471d-89c9-e88a20d07b2e) | [Link](https://arxiv.org/pdf/2405.06573) | |
| Arxiv 24.05.20| SSAMBA: Self-Supervised Audio Representation Learning with Mamba State Space Model| ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/c6228d72-8667-4c45-a9c2-591cc89a8f11) | [Link](https://arxiv.org/pdf/2405.11831) | [Code](https://github.com/SiavashShams/ssamba)|
| Arxiv 24.05.21| Mamba in Speech: Towards an Alternative to Self-Attention | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/3225b8b2-c3df-42c0-a415-e995f3a195b6) | [Link](https://arxiv.org/pdf/2405.12609) | |
| Arxiv 24.05.22| Audio Mamba: Pretrained Audio State Space Model For Audio Tagging|  | [Link](https://arxiv.org/pdf/2405.07022) | [Code](https://github.com/diggerdu/AudioMamba)|
| Arxiv 24.06.10| RawBMamba: End-to-End Bidirectional State Space Model for Audio Deepfake Detection | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/57466105/52326d04-e98e-40b2-a2d4-7f90fbcb137d) | [Link](https://arxiv.org/pdf/2406.06086) | [Code](https://github.com/cyjie429/RawBMamba)|

### Time Series Forecasting
| Date      | Paper | Figure    | Link | Code         |
| :-------- | :---- | :-------- | :--- | :----------- |
| Arxiv 24.04.23 | Integrating Mamba and Transformer for Long-Short Range Time Series Forecasting | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/80ddb918-c007-4f00-97cc-1e1724c82ead) | [Link](https://arxiv.org/pdf/2404.14757) | |
| Arxiv 24.04.24 | Bi-Mamba+: Bidirectional Mamba for Time Series Forecasting | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/9218c082-cda9-4072-8ddb-4fc0ae53899a) | [Link](https://arxiv.org/pdf/2404.15772) | |
| Arxiv 24.05.11 | DTMamba : Dual Twin Mamba for Time Series Forecasting | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/72c7ed39-c905-4a7f-b567-68042ea27e5c) | [Link](https://arxiv.org/pdf/2405.12094) | |
| Arxiv 24.05.25 | Time-SSM: Simplifying and Unifying State Space Models for Time Series Forecasting | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/0f26280e-a19d-479f-a28f-93e4df1bd4ba) | [Link](https://arxiv.org/pdf/2405.16312) | |
| Arxiv 24.05.26 | MambaTS: Improved Selective State Space Models for Long-term Time Series Forecasting | ![image](https://github.com/Ruixxxx/Awesome-Vision-Mamba-Models/assets/88369000/41c611a4-d711-4621-be4e-d60960724adc) | [Link](https://arxiv.org/pdf/2405.16440) | |

