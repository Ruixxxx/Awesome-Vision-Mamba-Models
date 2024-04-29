Here presents detailed performance results for various backbone models on the ImageNet-1K classification task, along with results for detection and segmentation benchmarks.

### Table 1: Comparison of different backbones on ImageNet-1K classification

| **Backbone**                 | **Image Size**  | **Params** | **FLOPs** | **Top-1 ACC** |
|----------------------------|-----------------|------------|-----------|---------------|
| **ConvNets**               |                 |            |           |               |
| RegNetY-4G                 | 224<sup>2</sup> | 21M        | 4.0G      | 80.0          |
| RegNetY-8G                 | 224<sup>2</sup> | 39M        | 8.0G      | 81.7          |
| RegNetY-16G                | 224<sup>2</sup> | 84M        | 16.0G     | 82.9          |
| EffNet-B3                  | 300<sup>2</sup> | 12M        | 1.8G      | 81.6          |
| EffNet-B4                  | 380<sup>2</sup> | 19M        | 4.2G      | 82.9          |
| EffNet-B5                  | 456<sup>2</sup> | 30M        | 9.9G      | 83.6          |
| EffNet-B6                  | 528<sup>2</sup> | 43M        | 19.0G     | 84.0          |
| **Transformers**           |                 |            |           |               |
| ViT-B/16                   | 384<sup>2</sup> | 86M        | 55.4G     | 77.9          |
| ViT-L/16                   | 384<sup>2</sup> | 307M       | 190.7G    | 76.5          |
| DeiT-Ti                    | 224<sup>2</sup> | 6M         | 1.3G      | 72.2          |
| DeiT-S                     | 224<sup>2</sup> | 22M        | 4.6G      | 79.8          |
| DeiT-B                     | 224<sup>2</sup> | 86M        | 17.5G     | 81.8          |
| DeiT-B                     | 384<sup>2</sup> | 86M        | 55.4G     | 83.1          |
| Swin-T                     | 224<sup>2</sup> | 29M        | 4.5G      | 81.3          |
| Swin-S                     | 224<sup>2</sup> | 50M        | 8.7G      | 83.0          |
| Swin-B                     | 224<sup>2</sup> | 88M        | 15.4G     | 83.5          |
| **SSMs**                   |                 |            |           |               |
| S4ND-ViT-B                 | 224<sup>2</sup> | 89M        | -         | 80.4          |
| S4ND-ConvNeXt-T            | 224<sup>2</sup> | 30M        | -         | 82.2          |
| Vim-Ti                     | 224<sup>2</sup> | 7M         | 1.5G      | 76.1          |
| Vim-S                      | 224<sup>2</sup> | 26M        | 5.1G      | 80.5          |
| PlainMamba-L1              | 224<sup>2</sup> | 7M         | 3.0G      | 77.9          |
| PlainMamba-L2              | 224<sup>2</sup> | 25M        | 8.1G      | 81.6          |
| PlainMamba-L3              | 224<sup>2</sup> | 50M        | 14.4G     | 82.3          |
| Mamba-2D-S                 | 224<sup>2</sup> | 24M        | -         | 81.7          |
| Mamba-2D-B                 | 224<sup>2</sup> | 92M        | -         | 83.0          |
| VMamba-T                   | 224<sup>2</sup> | 22M        | 5.6G      | 82.5          |
| VMamba-S                   | 224<sup>2</sup> | 44M        | 11.2G     | 83.6          |
| VMamba-B                   | 224<sup>2</sup> | 75M        | 18G       | 83.9          |
| EffVMamba-T                | 224<sup>2</sup> | 6M         | 0.8G      | 76.5          |
| EffVMamba-S                | 224<sup>2</sup> | 11M        | 1.3G      | 78.7          |
| EffVMamba-B                | 224<sup>2</sup> | 33M        | 4.0G      | 81.8          |
| LocalVim-T                 | 224<sup>2</sup> | 8M         | 1.5G      | 76.2          |
| LocalVim-S                 | 224<sup>2</sup> | 28M        | 4.8G      | 81.2          |
| LocalVMamba-T              | 224<sup>2</sup> | 26M        | 5.7G      | 82.7          |
| LocalVMamba-S              | 224<sup>2</sup> | 50M        | 11.4G     | 83.7          |
| SiMBA-S                    | 224<sup>2</sup> | 15.3M      | 2.4G      | 81.7          |
| SiMBA-B                    | 224<sup>2</sup> | 22.8M      | 4.2G      | 83.5          |
| SiMBA-L                    | 224<sup>2</sup> | 36.6M      | 7.6G      | 84.4          |

### Table 2: Results of object detection and instance segmentation on MS COCO mini-val using Mask R-CNN 1x schedule and 3x schedule. FLOPs are computed using input size 1280x800.

| **Backbone**        | **Params** | **FLOPs** | **AP<sup>b</sup>** | **AP<sub>50**</sub><sup>b</sup> | **AP<sub>75</sub><sup>b</sup>** | **AP<sup>m</sup>** | **AP<sub>50</sub><sup>m</sup>** | **AP<sub>75</sub><sup>m</sup>** |
|---------------------|------------|-----------|--------------------|---------------------------------|---------------------------------|--------------------|---------------------------------|---------------------------------|
| **Mask R-CNN 1× schedule** |     |           |                    |                                 |                                 |                    |                                 |                                 |
| **ConvNets**        |            |           |                    |                                 |                                 |                    |                                 |                                 |
| ResNeXt101-32x4d    | 63M        | 340G      | 41.9               | -                               | -                               | 37.5               | -                               | -                               |
| ResNeXt101-64x4d    | 102M       | 493G      | 42.8               | -                               | -                               | 38.4               | -                               | -                               |
| ConvNeXt-T          | 48M        | 262G      | 44.2               | 66.6                            | 48.3                            | 40.1               | 63.3                            | 42.8                            |
| ConvNeXt-S          | 70M        | 348G      | 45.4               | 67.9                            | 50.0                            | 41.8               | 65.2                            | 45.1                            |
| **Transformers**    |            |           |                    |                                 |                                 |                    |                                 |                                 |
| ViT-Adpt-T          | 29M        | 349G      | 41.1               | 62.5                            | 44.3                            | 37.5               | 59.7                            | 39.9                            |
| ViT-Adpt-S          | 49M        | 403G      | 44.7               | 65.8                            | 48.3                            | 39.9               | 62.5                            | 42.8                            |
| ViT-Adpt-B          | 131M       | 883G      | 47.0               | 68.2                            | 51.4                            | 41.8               | 65.1                            | 44.9                            |
| PVT-Small           | 44M        | -         | 40.4               | 62.9                            | 43.8                            | 37.8               | 60.1                            | 40.3                            |
| PVT-Medium          | 64M        | -         | 42.0               | 64.4                            | 45.6                            | 39.0               | 61.6                            | 42.1                            |
| PVT-Large           | 81M        | -         | 42.9               | 65.0                            | 46.6                            | 39.5               | 61.9                            | 42.5                            |
| Swin-Tiny           | 48M        | 264G      | 42.2               | -                               | -                               | 39.1               | -                               | -                               |
| Swin-Small          | 69M        | 354G      | 44.8               | -                               | -                               | 40.9               | -                               | -                               |
| ViL-Tiny            | 26M        | 145G      | 41.4               | 63.5                            | 45.0                            | 38.1               | 60.3                            | 40.8                            |
| ViL-Small           | 45M        | 218G      | 44.9               | 67.1                            | 49.3                            | 41.0               | 64.2                            | 44.1                            |
| ViL-Medium          | 60M        | 293G      | 47.6               | 69.8                            | 52.1                            | 43.0               | 66.9                            | 46.6                            |
| **SSMs**            |            |           |                    |                                 |                                 |                    |                                 |                                 |
| PlainMamba-Adpt-L1  | 31M        | 388G      | 44.1               | 64.8                            | 47.9                            | 39.1               | 61.6                            | 41.9                            |
| PlainMamba-Adpt-L2  | 53M        | 542G      | 46.0               | 66.9                            | 50.1                            | 40.6               | 63.8                            | 43.6                            |
| PlainMamba-Adpt-L3  | 79M        | 696G      | 46.8               | 68.0                            | 51.1                            | 41.2               | 64.7                            | 43.9                            |
| VMamba-T            | 50M        | 270G      | 47.4               | 69.5                            | 52.0                            | 42.7               | 66.3                            | 46.0                            |
| VMamba-S            | 64M        | 357G      | 48.7               | 70.0                            | 53.4                            | 43.7               | 67.3                            | 47.0                            |
| VMamba-B            | 108M       | 485G      | 49.2               | 70.9                            | 53.9                            | 43.9               | 67.7                            | 47.6                            |
| EffVMamba-T         | 11M        | 60G       | 35.6               | 57.7                            | 38.0                            | 33.2               | 54.4                            | 35.1                            |
| EffVMamba-S         | 31M        | 197G      | 39.3               | 61.8                            | 42.6                            | 36.7               | 58.9                            | 39.2                            |
| EffVMamba-B         | 53M        | 252G      | 43.7               | 66.2                            | 47.9                            | 40.2               | 63.3                            | 42.9                            |
| LocalVMamba-T       | 45M        | 291G      | 46.7               | 68.7                            | 50.8                            | 42.2               | 65.7                            | 45.5                            |
| LocalVMamba-S       | 69M        | 414G      | 48.4               | 69.9                            | 52.7                            | 43.2               | 66.7                            | 46.5                            |
| SiMBA-S             | 60M        | 382G      | 46.9               | 68.6                            | 51.7                            | 42.6               | 65.9                            | 45.8                            |
| **Mask R-CNN 3× schedule** |     |           |                    |                                 |                                 |                    |                                 |                                 |
| **ConvNets**        |            |           |                    |                                 |                                 |                    |                                 |                                 |
| ConvNeXt-T          | 48M        | 262G      | 46.2               | 67.9                            | 50.8                            | 41.7               | 65.0                            | 44.9                            |
| ConvNeXt-S          | 70M        | 348G      | 47.9               | 70.0                            | 52.7                            | 42.9               | 66.9                            | 46.2                            |
| **Transformers**    |            |           |                    |                                 |                                 |                    |                                 |                                 |
| ViT-Adpt-S          | 48M        | 403G      | 48.2               | 69.7                            | 52.5                            | 42.8               | 66.4                            | 45.9                            |
| Swin-T              | 48M        | 267G      | 46.0               | 68.1                            | 50.3                            | 41.6               | 65.1                            | 44.9                            |
| Swin-S              | 69M        | 354G      | 48.2               | 69.8                            | 52.8                            | 43.2               | 67.0                            | 46.1                            |
| **SSMs**            |            |           |                    |                                 |                                 |                    |                                 |                                 |
| VMamba-T            | 50M        | 270G      | 48.9               | 70.6                            | 53.6                            | 43.7               | 67.7                            | 46.8                            |
| VMamba-S            | 70M        | 384G      | 49.9               | 70.9                            | 54.7                            | 44.2               | 68.2                            | 47.7                            |
| LocalVMamba-T       | 45M        | 291G      | 48.7               | 70.1                            | 53.0                            | 43.4               | 67.0                            | 46.4                            |
| LocalVMamba-S       | 69M        | 414G      | 49.9               | 70.5                            | 54.4                            | 44.1               | 67.8                            | 47.4                            |

### Table 3: Results of semantic segmentation on ADE20K val using UperNet. FLOPs are calculated using input size 512×2048. 'SS' and 'MS' denote single-scale and multi-scale testing, respectively. MLN: multi-level neck.

| Backbone           | Crop Size        | Params | FLOPs | mIoU (SS) | mIoU (MS) |
|------------------|------------------|--------|-------|-----------|-----------|
| **ConvNets**     |                  |        |       |           |           |
| ResNet-50        | 512<sup>2</sup>  | 67M    | 953G  | 42.1      | 42.8      |
| ResNet-101       | 512<sup>2</sup>  | 85M    | 1030G | 42.9      | 44.0      |
| ConvNeXt-T       | 512<sup>2</sup>  | 60M    | 939G  | 46.0      | 46.7      |
| ConvNeXt-S       | 512<sup>2</sup>  | 82M    | 1027G | 48.7      | 49.6      |
| ConvNeXt-B       | 512<sup>2</sup>  | 122M   | 1170G | 49.1      | 49.9      |
| **Transformers** |                  |        |       |           |           |
| DeiT-S + MLN     | 512<sup>2</sup>  | 58M    | 1217G | 43.8      | 45.1      |
| DeiT-B + MLN     | 512<sup>2</sup>  | 144M   | 2007G | 45.5      | 47.2      |
| Swin-T           | 512<sup>2</sup>  | 60M    | 945G  | 44.4      | 45.8      |
| Swin-S           | 512<sup>2</sup>  | 81M    | 1039G | 47.6      | 49.5      |
| Swin-B           | 512<sup>2</sup>  | 121M   | 1188G | 48.1      | 49.7      |
| **SSMs**         |                  |        |       |           |           |
| Vim-Ti           | 512<sup>2</sup>  | 13M    | -     | 41.0      | -         |
| Vim-S            | 512<sup>2</sup>  | 46M    | -     | 44.9      | -         |
| PlainMamba-L1    | 512<sup>2</sup>  | 35M    | 174G  | 44.1      | -         |
| PlainMamba-L2    | 512<sup>2</sup>  | 55M    | 285G  | 46.8      | -         |
| PlainMamba-L3    | 512<sup>2</sup>  | 81M    | 419G  | 49.1      | -         |
| VMamba-T         | 512<sup>2</sup>  | 62M    | 948G  | 48.3      | 48.6      |
| VMamba-S         | 512<sup>2</sup>  | 82M    | 1039G | 50.6      | 51.2      |
| VMamba-B         | 512<sup>2</sup>  | 122M   | 1170G | 51.0      | 51.6      |
| EffVMamba-T      | 512<sup>2</sup>  | 14M    | 230G  | 38.9      | 39.3      |
| EffVMamba-S      | 512<sup>2</sup>  | 29M    | 505G  | 41.5      | 42.1      |
| EffVMamba-B      | 512<sup>2</sup>  | 65M    | 930G  | 46.5      | 47.3      |
| LocalVim-T       | 512<sup>2</sup>  | 36M    | 181G  | 43.4      | 44.4      |
| LocalVim-S       | 512<sup>2</sup>  | 58M    | 297G  | 46.4      | 47.5      |
| LocalVMamba-T    | 512<sup>2</sup>  | 57M    | 970G  | 47.9      | 49.1      |
| LocalVMamba-S    | 512<sup>2</sup>  | 81M    | 1095G | 50.0      | 51.0      |
| SiMBA-S          | 512<sup>2</sup>  | 62M    | 1040G | 49.0      | 49.6      |

