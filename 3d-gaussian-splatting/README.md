
- [最新工作](#最新工作)
  - [3D Gaussian Splatting](#3d-gaussian-splatting)
  - [Optimization](#optimization)
  - [Autonomous Driving](#autonomous-driving)
  - [Dynamic 3D Gaussian Splatting](#dynamic-3d-gaussian-splatting)
  - [Multimodal 3D Gaussian Splatting](#multimodal-3d-gaussian-splatting)
  - [Neural Rendering](#neural-rendering)
  - [3D Editing](#3d-editing)
- [插件工具](#插件工具)
- [应用服务](#应用服务)
  - [Polycam](#polycam)
  - [gsplat](#gsplat)
  - [UnityGaussianSplatting](#unitygaussiansplatting)

### 最新工作

#### 3D Gaussian Splatting

| Paper                                                        | Project                                                      | Code+Data                                                    | Year & Conference |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------- |
| [3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_low.pdf) | [Project](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) | [Code+Data](https://github.com/graphdeco-inria/gaussian-splatting)<br />[C++&CUDA Implementation](https://github.com/MrNeRF/gaussian-splatting-cuda) | [2023] [SIGGRAPH] |

#### Optimization

| Paper                                                        | Project                                                    | Code+Data                                                    | Year & Conference |
| ------------------------------------------------------------ | ---------------------------------------------------------- | ------------------------------------------------------------ | ----------------- |
| [Mip-Splatting: Alias-free 3D Gaussian Splatting](https://arxiv.org/pdf/2311.16493.pdf) | [Project](https://niujinshuchong.github.io/mip-splatting/) | [Code+Data](https://github.com/autonomousvision/mip-splatting) | [2023] [arXiv]    |

#### Autonomous Driving

| Paper                                                        | Project                                               | Code+Data                 | Year & Conference |
| ------------------------------------------------------------ | ----------------------------------------------------- | ------------------------- | ----------------- |
| [DrivingGaussian: Composite Gaussian Splatting for Surrounding Dynamic Autonomous Driving Scenes](https://arxiv.org/pdf/2312.07920.pdf) | [Project](https://pkuvdig.github.io/DrivingGaussian/) | [Code+Data](Comming soon) | [2023] [arXiv]    |

#### Dynamic 3D Gaussian Splatting

| Paper                                                        | Project                                                     | Code+Data                                                    | Year & Conference |
| ------------------------------------------------------------ | ----------------------------------------------------------- | ------------------------------------------------------------ | ----------------- |
| [Dynamic 3D Gaussians: Tracking by Persistent Dynamic View Synthesis](https://arxiv.org/pdf/2308.09713.pdf) | [Project](https://dynamic3dgaussians.github.io/)            | [Code+Data](https://github.com/JonathonLuiten/Dynamic3DGaussians) | [2023] [arXiv]    |
| [Deformable 3D Gaussians for High-Fidelity Monocular Dynamic Scene Reconstruction](https://arxiv.org/pdf/2309.13101.pdf) | [Project](https://ingra14m.github.io/Deformable-Gaussians/) | [Code+Data](https://github.com/ingra14m/Deformable-3D-Gaussians) | [2023] [arXiv]    |
| [4D Gaussian Splatting for Real-Time Dynamic Scene Rendering](https://arxiv.org/pdf/2310.08528.pdf) | [Project](https://guanjunwu.github.io/4dgs/)                | [Code+Data](https://github.com/hustvl/4DGaussians)           | [2023] [arXiv]    |
| [Real-time Photorealistic Dynamic Scene Representation and Rendering with 4D Gaussian Splatting](https://arxiv.org/pdf/2310.10642.pdf) |                                                             | [Code+Data](https://github.com/fudan-zvg/4d-gaussian-splatting) | [2023] [arXiv]    |
| [PhysGaussian: Physics-Integrated 3D Gaussians for Generative Dynamics](https://arxiv.org/pdf/2311.12198.pdf) | [Project](https://xpandora.github.io/PhysGaussian/)         | [Code+Data](https://github.com/XPandora/PhysGaussian)        | [2023] [arXiv]    |

#### Multimodal 3D Gaussian Splatting

| Paper                                                        | Project                                          | Code+Data                                                   | Year & Conference |
| ------------------------------------------------------------ | ------------------------------------------------ | ----------------------------------------------------------- | ----------------- |
| [DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation](https://arxiv.org/pdf/2309.16653.pdf) | [Project](https://dreamgaussian.github.io/)      | [Code+Data](https://github.com/dreamgaussian/dreamgaussian) | [2023] [arXiv]    |
| [Text-to-3D using Gaussian Splatting](https://arxiv.org/pdf/2309.16585.pdf) | [Project](https://gsgen3d.github.io/)            | [Code+Data](https://github.com/gsgen3d/gsgen)               | [2023] [arXiv]    |
| [GaussianDreamer: Fast Generation from Text to 3D Gaussian Splatting with Point Cloud Priors](https://arxiv.org/pdf/2310.08529.pdf) | [Project](https://taoranyi.com/gaussiandreamer/) | [Code+Data](https://github.com/hustvl/GaussianDreamer)      | [2023] [arXiv]    |

#### Neural Rendering

| Paper                                                        | Project                                                      | Code+Data                                                    | Year & Conference      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------------- |
| [Point-Based Neural Rendering with Per-View Optimization](https://arxiv.org/pdf/2109.02369.pdf) | [Project](https://repo-sam.inria.fr/fungraph/differentiable-multi-view/) | [Code+Data](https://gitlab.inria.fr/sibr/projects/pointbased_neural_rendering) | [2021] [CGF]           |
| [Neural Point Catacaustics for Novel-View Synthesis of Reflections](https://arxiv.org/pdf/2301.01087.pdf) | [Project](https://repo-sam.inria.fr/fungraph/neural_catacaustics/) | [Code+Data](https://gitlab.inria.fr/fungraph/neural-catacaustics) | [2022] [SIGGRAPH Asia] |
| [Pulsar: Efficient Sphere-based Neural Rendering](https://arxiv.org/pdf/2004.07484.pdf) |                                                              |                                                              | [2021] [CVPR]          |
| [ADOP: Approximate Differentiable One-Pixel Point Rendering](https://arxiv.org/pdf/2110.06635.pdf) |                                                              | [Code+Data](https://github.com/darglein/ADOP)                | [2021] [arXiv]         |
| [EWA Splatting](https://www.cs.umd.edu/~zwicker/publications/EWASplatting-TVCG02.pdf) |                                                              |                                                              | [2002] [TVCG]          |
| [Surface Splatting](https://www.cs.umd.edu/~zwicker/publications/SurfaceSplatting-SIG01.pdf) |                                                              |                                                              | [2001] [SIGGRAPH]      |
| [Differentiable Surface Splatting for Point-based Geometry Processing](https://arxiv.org/pdf/1906.04173.pdf) | [Project](https://igl.ethz.ch/projects/differentiable-surface-splatting/) | [Code+Data](https://github.com/yifita/DSS)                   | [2019] [SIGGRAPH Asia] |

#### 3D Editing

| Paper                                                        | Project                                               | Code+Data                                              | Year & Conference |
| ------------------------------------------------------------ | ----------------------------------------------------- | ------------------------------------------------------ | ----------------- |
| [GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting](https://arxiv.org/pdf/2311.14521.pdf) | [Project](https://buaacyw.github.io/gaussian-editor/) | [Code+Data](https://github.com/buaacyw/GaussianEditor) | [2023] [arXiv]    |

### 插件工具

[UnityGaussianSplatting](https://github.com/aras-p/UnityGaussianSplatting)

### 应用服务

#### Polycam

支持3d gaussian splatting重建的网站服务(目前重建是免费的，只需要注册账号)，可以支持
1. 上传图片(最少20张，不同视角的)进行重建并随时可以查看重建进度
2. 上传本地重建后的.plt，可视化重建后的三维场景
3. 查看自己和其他人上传图片的重建三维场景

[服务链接](https://poly.cam/gaussian-splatting)

#### gsplat

基于WebGL的3d gaussian splatting重建结果的可视化服务，目前只能看作者手动上传的三维数据，还不支持用户上传

[服务链接](https://poly.cam/gaussian-splatting)

#### UnityGaussianSplatting

