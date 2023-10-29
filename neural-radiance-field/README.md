
- [最新工作](#最新工作)
  - [NeRF](#nerf)
  - [NeRF Speedup](#nerf-speedup)
  - [Dynamic NeRF](#dynamic-nerf)
  - [Multimodal NeRF](#multimodal-nerf)
  - [3D Editing](#3d-editing)
- [](#)
- [应用服务](#应用服务)
  - [nerfstudio](#nerfstudio)

### 最新工作

#### NeRF

| Paper                                                        | Project                                               | Code+Data                                                    | Year & Conference |
| ------------------------------------------------------------ | ----------------------------------------------------- | ------------------------------------------------------------ | ----------------- |
| [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/pdf/2003.08934.pdf) | [Project](https://www.matthewtancik.com/nerf)         | [Code+Data](https://github.com/bmild/nerf)<br />[PyTorch Version](https://github.com/yenchenlin/nerf-pytorch) | [2020] [ECCV]     |
| [Neural Sparse Voxel Fields](https://arxiv.org/pdf/2007.11571.pdf) | [Project](https://lingjie0206.github.io/papers/NSVF/) | [Code+Data](https://github.com/facebookresearch/NSVF)        | [2020] [NIPS]     |
| [NeRF in the Wild: Neural Radiance Fields for Unconstrained Photo Collections](https://arxiv.org/pdf/2008.02268.pdf) | [Project](https://nerf-w.github.io/)                  |                                                              | [2021] [CVPR]     |
| [NeRF++: Analyzing and Improving Neural Radiance Fields](https://arxiv.org/pdf/2010.07492.pdf) |                                                       | [Code+Data](https://github.com/Kai-46/nerfplusplus)          | [2020] [arXiv]    |
| [Nerfies: Deformable Neural Radiance Fields](https://arxiv.org/pdf/2011.12948.pdf) | [Project](https://nerfies.github.io/)                 | [Code+Data](https://github.com/google/nerfies)               | [2021] [ICCV]     |
| [MVSNeRF: Fast Generalizable Radiance Field Reconstruction from Multi-View Stereo](https://arxiv.org/pdf/2103.15595.pdf) | [Project](https://apchenstu.github.io/mvsnerf/)       | [Code+Data](https://github.com/apchenstu/mvsnerf)            | [2021] [ICCV]     |
| [IBRNet: Learning Multi-View Image-Based Rendering](https://arxiv.org/pdf/2102.13090.pdf) | [Project](https://ibrnet.github.io/)                  | [Code+Data](https://github.com/googleinterns/IBRNet)         | [2021] [CVPR]     |
| [pixelNeRF: Neural Radiance Fields from One or Few Images](https://arxiv.org/pdf/2012.02190.pdf) |                                                       | [Code+Data](https://github.com/sxyu/pixel-nerf)              | [2021] [CVPR]     |
| [Ref-NeRF: Structured View-Dependent Appearance for Neural Radiance Fields](https://arxiv.org/pdf/2112.03907.pdf) | [Project](https://dorverbin.github.io/refnerf/)       | [Code+Data](https://github.com/google-research/multinerf)    | [2022] [CVPR]     |
| [Mip-NeRF 360: Unbounded Anti-Aliased Neural Radiance Fields](https://arxiv.org/pdf/2111.12077.pdf) | [Project](https://jonbarron.info/mipnerf360/)         | [Code+Data](https://github.com/google-research/multinerf)    | [2022] [CVPR]     |
| [NeRF in the Dark: High Dynamic Range View Synthesis from Noisy Raw Images](https://arxiv.org/pdf/2111.13679.pdf) | [Project](https://bmild.github.io/rawnerf/)           | [Code+Data](https://github.com/google-research/multinerf)    | [2022] [CVPR]     |

#### NeRF Speedup

| Paper                                                        | Project                                                      | Code+Data                                          | Year & Conference | Type       |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------------------- | ----------------- | ---------- |
| [Plenoxels: Radiance Fields without Neural Networks](https://arxiv.org/pdf/2112.05131.pdf) | [Project](https://alexyu.net/plenoxels/)                     | [Code+Data](https://github.com/sxyu/svox2)         | [2022] [CVPR]     | Voxel      |
| [Point-NeRF: Point-based Neural Radiance Fields](https://arxiv.org/pdf/2201.08845.pdf) | [Project](https://xharlie.github.io/projects/project_sites/pointnerf/index.html) | [Code+Data](https://github.com/Xharlie/pointnerf)  | [2022] [CVPR]     | Points     |
| [Instant Neural Graphics Primitives with a Multiresolution Hash Encoding](https://arxiv.org/pdf/2201.05989.pdf) | [Project](https://nvlabs.github.io/instant-ngp/)             | [Code+Data](https://github.com/NVlabs/instant-ngp) | [2022] [SIGGRAPH] | Hash Grids |

#### Dynamic NeRF

| Paper                                                        | Project                                            | Code+Data                                                    | Year & Conference       |
| ------------------------------------------------------------ | -------------------------------------------------- | ------------------------------------------------------------ | ----------------------- |
| [Neural Scene Flow Fields for Space-Time View Synthesis of Dynamic Scenes](https://arxiv.org/pdf/2011.13084.pdf) | [Project](https://www.cs.cornell.edu/~zl548/NSFF/) | [Code+Data](https://github.com/zhengqili/Neural-Scene-Flow-Fields) | [2021] [CVPR]           |
| [Efficient Neural Radiance Fields for Interactive Free-viewpoint Video](https://arxiv.org/pdf/2112.01517.pdf) | [Project](https://zju3dv.github.io/enerf/)         | [Code+Data](https://github.com/zju3dv/ENeRF)                 | [2022] [SIGGRAPH Asia ] |
| [4K4D: Real-Time 4D View Synthesis at 4K Resolution](https://arxiv.org/pdf/2310.11448.pdf) | [Project](https://zju3dv.github.io/4k4d/)          | [Code+Data](https://github.com/zju3dv/4K4D)                  | [2023] [arXiv]          |

#### Multimodal NeRF

| Paper                                                        | Project                                             | Code+Data                                                    | Year & Conference |
| ------------------------------------------------------------ | --------------------------------------------------- | ------------------------------------------------------------ | ----------------- |
| [CLIP-NeRF: Text-and-Image Driven Manipulation of Neural Radiance Fields](https://arxiv.org/pdf/2112.05139.pdf) | [Project](https://cassiepython.github.io/clipnerf/) | [Code+Data](https://github.com/cassiePython/CLIPNeRF)        | [2022] [CVPR]     |
| [Zero-Shot Text-Guided Object Generation with Dream Fields](https://arxiv.org/pdf/2112.01455.pdf) | [Project](https://ajayj.com/dreamfields)            | [Code+Data](https://github.com/google-research/google-research/tree/master/dreamfields) | [2022] [CVPR]     |

#### 3D Editing

| Paper                                                        | Project                                                      | Code+Data                                                    | Year & Conference      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- |
| [Clip-nerf: Text-and-image driven manipulation of neural radiance fields](https://arxiv.org/pdf/2112.05139.pdf) | [Project](https://cassiepython.github.io/clipnerf/)          | [Code+Data](https://github.com/cassiePython/CLIPNeRF)        | [2022] [CVPR]          |
| [Nerf-art: Text-driven neural radiance fields stylization](https://arxiv.org/pdf/2212.08070.pdf) | [Project](https://cassiepython.github.io/nerfart/index.html) | [Code+Data](https://github.com/cassiePython/NeRF-Art)        | [2023] [TVCG]          |
| [Instruct-nerf2nerf: Editing 3d scenes with instructions](https://arxiv.org/pdf/2303.12789.pdf) | [Project](https://instruct-nerf2nerf.github.io/)             | [Code+Data](https://github.com/ayaanzhaque/instruct-nerf2nerf) | [2023] [ICCV]          |
| [Efficient text-guided editing of 3d scene using latent space nerf] |                                                              |                                                              | [2023] [arXiv]         |
| [Dreameditor: Text-driven 3d scene editing with neural fields](https://arxiv.org/pdf/2306.13455.pdf) | [Project](https://www.sysu-hcp.net/projects/cv/111.html)     | [Code+Data](https://github.com/zjy526223908/dreameditor)     | [2023] [SIGGRAPH Asia] |

### 

### 应用服务

#### nerfstudio

nerfstudio是为了简化NeRF研究的开发和部署而开发的基于PyTorch的框架包。支持

1. 实时可视化
2. 多种输入输入pipeline
3. 可以导出视频、点云和网格格式的结果

[Paper](https://arxiv.org/pdf/2302.04264.pdf) | [Code+Data](https://github.com/nerfstudio-project/nerfstudio) | [Docs](https://docs.nerf.studio/) | [Viewer](https://viewer.nerf.studio/) | [Colab](https://colab.research.google.com/github/nerfstudio-project/nerfstudio/blob/main/colab/demo.ipynb)

