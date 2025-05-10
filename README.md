# Awesome From Video Generation to World Model

## Overview

### What You'll Find Here

We hope to support the research and industrial communities by systematically collecting and organizing influential works that drive progress in video generation for world modeling.

![overall_structure](./fig_teaser.png)

The field of video generation is undergoing a paradigm shift - from generating realistic and appealing visuals to constructing world models that can simulate interactive and navigable environments. These models are not just visual tools; they serve as testbeds for training and evaluating intelligent agents, such as robots, autonomous vehicles, or virtual avatars. A central goal is to enable agents to perceive, act, and plan within generated video scenarios as if they were interacting with the real world. We compile key works that push video generation toward actionable world modeling, focusing physical plausibility, and the capacity for agents to navigate, manipulate, and learn from these synthetic environments.


### Updates

This repository is updated periodically. If you have suggestions for additional resources, updates on methodologies, or fixes for expiring links, please feel free to do any of the following:
- raise an [Issue](https://github.com/ziqihuangg/Awesome-From-Video-Generation-to-World-Model/issues),
- nominate awesome related works with [Pull Requests](https://github.com/ziqihuangg/Awesome-From-Video-Generation-to-World-Model/pulls),
- For other queries: email both `yuejingtong137 at gmail dot com` and `ZIQI002 at e dot ntu dot edu dot sg`.


### Table of Contents
- [1. Video Generation for World Model in General Scenes](#1.)
  - [1.1. U-Net Based Video Generation](#1.1.)
  - [1.2. DiT Based Video Generation](#1.2.)
  - [1.3. Autoregressive Based Video Generation](#1.3.)
  - [1.4. Other Based Video Generation](#1.4.)
- [2. Video Generation for World Model in Robotics](#2.)
  - [2.1. Action Navigation World Model](#2.1.)
  - [2.2. Instruction Navigation World Model](#2.2.)
  - [2.3. Goal Navigation World Model](#2.3.)
  - [2.4. Other Navigation World Model](#2.4.)
- [3. Video Generation for World Model in Autonomous Driving](#3.)
  - [3.1. Instruction Navigation World Model](#3.1.)
  - [3.2. Trajectory Navigation World Model](#3.2.)
  - [3.3. Action Navigation World Model](#3.3.)
  - [3.4. Layout Navigation World Model](#3.4.)
  - [3.5. Hybrid Navigation World Model](#3.5.)
  - [3.6. World Model without Navigation](#3.6.)
  - [3.7. Other Navigation World Model](#3.7.)
- [4. Video Generation for World Model in Gaming](#4.)
  - [4.1. Game Controller Navigation World Model](#4.1.)
  - [4.2. Keyboard Navigation World Model](#4.2.)
  - [4.3. Keyboard & Mouse Navigation World Model](#4.3.)
  - [4.4. Action Trajectory Navigation World Model](#4.4.)
  - [4.5. Multiple Navigation World Model](#4.5.)
  - [4.6. Other Navigation World Model](#4.6.)
 
<a name="1."></a>
## 1. Video Generation for World Model in General Scenes
<a name="1.1."></a>
### 1.1. U-Net Based Video Generation

+ [GEM:AGeneralizable Ego-Vision Multimodal World Model for Fine-Grained
 Ego-Motion, Object Dynamics, and Scene Composition Control](https://arxiv.org/pdf/2412.11198) (2024-12-15) 
[![Code](https://img.shields.io/github/stars/vita-epfl/GEM.svg?style=social&label=Official)](https://github.com/vita-epfl/GEM)
[![Website](https://img.shields.io/badge/Website-9cf)](https://vita-epfl.github.io/GEM.github.io/) 


+ [SlowFast-VGen: Slow-Fast Learning for Action-driven Long Video Generation](https://arxiv.org/abs/2410.23277) (2024-10-30) 
[![Code (to be released)](https://img.shields.io/github/stars/slowfast-vgen/slowfast-vgen.svg?style=social&label=Official)](https://github.com/slowfast-vgen/slowfast-vgen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://slowfast-vgen.github.io/)

+ [T2v-turbo: Breaking the quality bottleneck of video consistency model with mixed reward feedback](https://arxiv.org/abs/2405.18750) (2024-05-29)
+ [![Code](https://img.shields.io/github/stars/Ji4chenLi/t2v-turbo.svg?style=social&label=Official)](https://github.com/Ji4chenLi/t2v-turbo)
[![Website](https://img.shields.io/badge/Website-9cf)](https://t2v-turbo.github.io/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/TIGER-Lab/T2V-Turbo)

+ [MagicTime: Time-lapse Video Generation Models as Metamorphic Simulators](https://arxiv.org/abs/2404.05014) (2024-04-07) 
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/MagicTime.svg?style=social&label=Official)](https://github.com/PKU-YuanGroup/MagicTime/tree/main)
[![Website](https://img.shields.io/badge/Website-9cf)](https://pku-yuangroup.github.io/MagicTime/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/BestWishYsh/MagicTime)

+ [AnimateLCM: Computation-Efficient Personalized Style Video Generation without Personalized Video Data](https://arxiv.org/abs/2402.00769) (2024-02-01) 
[![Code](https://img.shields.io/github/stars/G-U-N/AnimateLCM.svg?style=social&label=Official)](https://github.com/G-U-N/AnimateLCM)
[![Website](https://img.shields.io/badge/Website-9cf)](https://animatelcm.github.io/) 
[![Hugging Face Demo](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/wangfuyun/AnimateLCM-SVD)

+ [InstructVideo: Instructing Video Diffusion Models with Human Feedback](https://arxiv.org/abs/2312.12490) (2023-12-19) 
[![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Official)](https://github.com/ali-vilab/VGen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://instructvideo.github.io/)

+ [Hierarchical Spatio-temporal Decoupling for Text-to-Video Generation](https://arxiv.org/abs/2312.04483) (2023-12-07)
+ [![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Official)](https://github.com/ali-vilab/VGen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://higen-t2v.github.io/)

+ [DreamVideo: Composing Your Dream Videos with Customized Subject and Motion](https://arxiv.org/abs/2312.04433) (2023-12-07) 
[![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Official)](https://github.com/ali-vilab/VGen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://dreamvideo-t2v.github.io/)

 + [Emu Video: Factorizing Text-to-Video Generation by Explicit Image Conditioning](https://arxiv.org/abs/2311.10709) (2023-11-17) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://emu-video.metademolab.com/) 

 + [I2VGen-XL: High-Quality Image-to-Video Synthesis via Cascaded Diffusion Models](https://arxiv.org/abs/2311.04145) (2023-11-07) 
[![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Official)](https://github.com/ali-vilab/VGen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://i2vgen-xl.github.io/) 

+ [DynamiCrafter: Animating Open-domain Images with Video Diffusion Priors](https://arxiv.org/abs/2310.12190) (2023-10-18) 
[![Code](https://img.shields.io/github/stars/Doubiiu/DynamiCrafter.svg?style=social&label=Official)](https://github.com/Doubiiu/DynamiCrafter)
[![Website](https://img.shields.io/badge/Website-9cf)](https://doubiiu.github.io/projects/DynamiCrafter) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/papers/2310.12190)

+ [Show-1: Marrying Pixel and Latent Diffusion Models for Text-to-Video ](https://arxiv.org/abs/2309.15818) (2023-09-27) 
[![Code](https://img.shields.io/github/stars/showlab/Show-1.svg?style=social&label=Official)](https://github.com/showlab/Show-1)
[![Website](https://img.shields.io/badge/Website-9cf)](https://showlab.github.io/Show-1/) 

+ [LaVie: High-Quality Video Generation with Cascaded Latent Diffusion Models](https://arxiv.org/abs/2309.15103) (2023-09-26) 
[![Code](https://img.shields.io/github/stars/Vchitect/LaVie.svg?style=social&label=Official)](https://github.com/Vchitect/LaVie)
[![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/LaVie-project/) 


+ [ModelScope Text-to-Video Technical Report](https://arxiv.org/abs/2308.06571) (2023-08-12) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://modelscope.cn/models/iic/text-to-video-synthesis/summary)

+ [AnimateDiff: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning](https://arxiv.org/abs/2307.04725) (2023-07-10) 
[![Code](https://img.shields.io/github/stars/guoyww/AnimateDiff.svg?style=social&label=Official)](https://github.com/guoyww/AnimateDiff)
[![Website](https://img.shields.io/badge/Website-9cf)](https://animatediff.github.io/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/guoyww/AnimateDiff)

+ [Align your Latents: High-Resolution Video Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2304.08818) (2023-04-18) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/VideoLDM/)

<a name="1.2."></a>
### 1.2. DiT Based Video Generation

+ [AccVideo: Accelerating Video Diffusion Model with Synthetic Dataset](https://arxiv.org/abs/2503.19462) (2025-03-25)
+ [![Code](https://img.shields.io/github/stars/aejion/AccVideo.svg?style=social&label=Official)](https://github.com/aejion/AccVideo)
[![Website](https://img.shields.io/badge/Website-9cf)](https://aejion.github.io/accvideo/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/aejion/AccVideo)

+ [AETHER: Geometric-Aware Unified World Modeling](https://arxiv.org/abs/2503.18945) (2025-03-24)
+ [![Code](https://img.shields.io/github/stars/OpenRobotLab/Aether.svg?style=social&label=Official)](https://github.com/OpenRobotLab/Aether)
[![Website](https://img.shields.io/badge/Website-9cf)](https://aether-world.github.io/) 

+ [Cosmos-Transfer1: Conditional World Generation with Adaptive Multimodal Control](https://arxiv.org/abs/2503.14492) (2025-03-18)
+ [![Code](https://img.shields.io/github/stars/nvidia-cosmos/cosmos-transfer1.svg?style=social&label=Official)](https://github.com/nvidia-cosmos/cosmos-transfer1)
[![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/dir/cosmos-transfer1/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/nvidia/cosmos-transfer1-67c9d328196453be6e568d3e)

+ [WISA: World Simulator Assistant for Physics-Aware Text-to-Video Generation](https://arxiv.org/abs/2503.08153) (2025-03-11)
+ [![Code](https://img.shields.io/github/stars/360CVGroup/WISA.svg?style=social&label=Official)](https://github.com/360CVGroup/WISA)
[![Website](https://img.shields.io/badge/Website-9cf)](https://360cvgroup.github.io/WISA/)]

+ [IPO: Iterative Preference Optimization for Text-to-Video Generation](https://arxiv.org/abs/2502.02088) (2025-02-04) 
[![Code](https://img.shields.io/github/stars/SAIS-FUXI/IPO.svg?style=social&label=Official)](https://github.com/SAIS-FUXI/IPO) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://yangxlarge.github.io/ipoc//)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/Fudan-FUXI/IPOC-2B-v1.0)

+ [RepVideo: Rethinking Cross-Layer Representation for Video Generation](https://arxiv.org/abs/2501.08994) (2025-01-15) 
[![Code](https://img.shields.io/github/stars/Vchitect/RepVideo.svg?style=social&label=Official)](https://github.com/Vchitect/RepVideo)
[![Website](https://img.shields.io/badge/Website-9cf)](https://vchitect.github.io/RepVid-Webpage/)


+ [Vchitect-2.0: Parallel trans former for scaling up video diffusion models](https://arxiv.org/abs/2501.08453) (2025-01-14) 

+ [Cosmos World Foundation Model Platform for Physical AI](https://arxiv.org/abs/2501.03575) (2025-01-07) 
[![Code](https://img.shields.io/github/stars/nvidia-cosmos/cosmos-predict1.svg?style=social&label=Official)](https://github.com/nvidia-cosmos/cosmos-predict1)
[![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/dir/cosmos-predict1/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/nvidia/cosmos-predict1-67c9d1b97678dbf7669c89a7)

+ [LTX-Video: Realtime Video Latent Diffusion](https://arxiv.org/abs/2501.00103) (2024-12-30) 
[![Code](https://img.shields.io/github/stars/Lightricks/LTX-Video.svg?style=social&label=Official)](https://github.com/Lightricks/LTX-Video) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://www.lightricks.com/)

+ [Open-sora: Democratizing efficient video production for all](https://arxiv.org/abs/2412.20404) (2024-12-29) 
[![Code](https://img.shields.io/github/stars/hpcaitech/Open-Sora.svg?style=social&label=Official)](https://github.com/hpcaitech/Open-Sora) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://hpcaitech.github.io/Open-Sora/)

+ [VAST 1.0: A Unified Framework for Controllable and Consistent Video Generation](https://arxiv.org/abs/2412.16677) (2024-12-21)

+ [STIV: Scalable Text and Image Conditioned Video Generation](https://arxiv.org/abs/2412.07730) (2024-12-10)

+ [Navigation World Models](https://arxiv.org/abs/2412.03572) (2024-12-04)
[![Code](https://img.shields.io/github/stars/facebookresearch/nwm.svg?style=social&label=Official)](https://github.com/facebookresearch/nwm/)
[![Website](https://img.shields.io/badge/Website-9cf)](https://www.amirbar.net/nwm/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/facebook/nwm)

+ [HunyuanVideo: A Systematic Framework For Large Video Generative Models](https://arxiv.org/abs/2412.03603) (2024-12-03)
+ [![Code](https://img.shields.io/github/stars/Tencent/HunyuanVideo.svg?style=social&label=Official)](https://github.com/Tencent/HunyuanVideo)
[![Website](https://img.shields.io/badge/Website-9cf)](https://aivideo.hunyuan.tencent.com/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/tencent/HunyuanVideo)

+ [Open-Sora Plan: Open-Source Large Video Generation Model](https://arxiv.org/abs/2412.00131) (2024-11-28) 
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/Open-Sora-Plan.svg?style=social&label=Official)](https://github.com/PKU-YuanGroup/Open-Sora-Plan)


+ [Allegro: Open the black box of commercial-level video generation model](https://arxiv.org/abs/2410.15458) (2024-10-20)
+ [![Code](https://img.shields.io/github/stars/rhymes-ai/Allegro.svg?style=social&label=Official)](https://github.com/rhymes-ai/Allegro)
[![Website](https://img.shields.io/badge/Website-9cf)](https://rhymes.ai/allegro_gallery)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/rhymes-ai/Allegro)

+ [Pyramidal Flow Matching for Efficient Video Generative Modeling](https://arxiv.org/abs/2410.05954) (2024-10-08)
+ [![Code](https://img.shields.io/github/stars/jy0205/Pyramid-Flow.svg?style=social&label=Official)](https://github.com/jy0205/Pyramid-Flow)
[![Website](https://img.shields.io/badge/Website-9cf)](https://pyramid-flow.github.io/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/rain1011/pyramid-flow-sd3)

+ [T2V-Turbo-v2: Enhancing Video Generation Model Post-Training through Data, Reward, and Conditional Guidance Design](https://arxiv.org/abs/2410.05677) (2024-10-08)
+ [![Code](https://img.shields.io/github/stars/Ji4chenLi/t2v-turbo.svg?style=social&label=Official)](https://github.com/Ji4chenLi/t2v-turbo)
[![Website](https://img.shields.io/badge/Website-9cf)](https://t2v-turbo-v2.github.io/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/TIGER-Lab/T2V-Turbo)

+ [xGen-VideoSyn-1: High-fidelity Text-to-Video Synthesis with Compressed Representations](https://arxiv.org/abs/2408.12590) (2024-08-22) 

+ [Cogvideox:Text-to-video diffusion models with an expert transformer](https://arxiv.org/abs/2408.06072) (2024-08-12) 
[![Code](https://img.shields.io/github/stars/THUDM/CogVideo.svg?style=social&label=Official)](https://github.com/THUDM/CogVideo) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/TIGER-Lab/T2V-Turbo-V2)

+ [MiraData: A Large-Scale Video Dataset with Long Durations and Structured Captions](https://arxiv.org/abs/2407.06358v1) (2024-07-08)
+ [![Code](https://img.shields.io/github/stars/mira-space/MiraData.svg?style=social&label=Official)](https://github.com/mira-space/MiraData)
[![Website](https://img.shields.io/badge/Website-9cf)](https://mira-space.github.io/)]
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/datasets/TencentARC/MiraData)

+ [T2v-turbo: Breaking the quality bottleneck of video consistency model with mixed reward feedback](https://arxiv.org/abs/2405.18750) (2024-05-29)
+ [![Code](https://img.shields.io/github/stars/Ji4chenLi/t2v-turbo.svg?style=social&label=Official)](https://github.com/Ji4chenLi/t2v-turbo)
[![Website](https://img.shields.io/badge/Website-9cf)](https://t2v-turbo.github.io/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/TIGER-Lab/T2V-Turbo)

+ [Easyanimate: A high-performance long video generation method based on  transformer architecture](https://arxiv.org/abs/2405.18991) (2024-05-29)
+ [![Code](https://img.shields.io/github/stars/aigc-apps/EasyAnimate.svg?style=social&label=Official)](https://github.com/aigc-apps/EasyAnimate)
[![Website](https://img.shields.io/badge/Website-9cf)](https://easyanimate.github.io/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/alibaba-pai/EasyAnimate)

+ [Videocrafter2:Overcoming data limitations for high-quality video diffusion models](https://arxiv.org/abs/2401.09047) (2024-01-17) 
[![Code](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Official)](https://github.com/AILab-CVC/VideoCrafter)
[![Website](https://img.shields.io/badge/Website-9cf)](https://ailab-cvc.github.io/videocrafter2/)

+ [Latte: Latent Diffusion Transformer for Video Generation](https://arxiv.org/abs/2401.03048) (2024-01-05) 
[![Code](https://img.shields.io/github/stars/hpcaitech/Open-Sora.svg?style=social&label=Official)](https://github.com/hpcaitech/Open-Sora) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://hpcaitech.github.io/Open-Sora/) 

+ [Videocrafter1: Open diffusion models for high-quality video generation](https://arxiv.org/abs/2310.19512) (2023-10-30) 
[![Code](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Official)](https://github.com/AILab-CVC/VideoCrafter)

<a name="1.3."></a>
### 1.3. Autoregressive Based Video Generation

+ [Cosmos World Foundation Model Platform for Physical AI](https://arxiv.org/abs/2501.03575) (2025-01-07) 
[![Code](https://img.shields.io/github/stars/nvidia-cosmos/cosmos-predict1.svg?style=social&label=Official)](https://github.com/nvidia-cosmos/cosmos-predict1)
[![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/dir/cosmos-predict1/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/nvidia/cosmos-predict1-67c9d1b97678dbf7669c89a7)

+ [Owl-1: Omni World Model for Consistent Long Video Generation](https://arxiv.org/abs/2412.09600) (2024-12-12) 
[![Code](https://img.shields.io/github/stars/huang-yh/Owl.svg?style=social&label=Official)](https://github.com/huang-yh/Owl)

+ [DimensionX: Create Any 3D and 4D Scenes from a Single Image with Controllable Video Diffusion](https://arxiv.org/abs/2411.04928) (2024-11-07)
+ [![Code](https://img.shields.io/github/stars/wenqsun/DimensionX.svg?style=social&label=Official)](https://github.com/wenqsun/DimensionX)
[![Website](https://img.shields.io/badge/Website-9cf)](https://chenshuo20.github.io/DimensionX/) 

+ [Pandora: Towards general world model with natural language actions and video states](https://arxiv.org/abs/2406.09455) (2024-06-12) 
[![Code](https://img.shields.io/github/stars/maitrix-org/Pandora.svg?style=social&label=Official)](https://github.com/maitrix-org/Pandora)
[![Website](https://img.shields.io/badge/Website-9cf)](https://world-model.maitrix.org/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/maitrix-org/Pandora)

+ [VideoPoet: A Large Language Model for Zero-Shot Video Generation](https://arxiv.org/abs/2312.14125) (2023-12-21) 
[![Website](https://img.shields.io/badge/Website-9cf)](http://sites.research.google/videopoet/) 

+ [MAGVIT:Masked Generative Video Transformer](https://arxiv.org/abs/2212.05199) (2022-12-10) 
[![Code](https://img.shields.io/github/stars/google-research/magvit.svg?style=social&label=Official)](https://github.com/google-research/magvit)
[![Website](https://img.shields.io/badge/Website-9cf)](https://magvit.cs.cmu.edu/)

+ [CogVideo: Large-scale Pretraining for Text-to-Video Generation via Transformers](https://arxiv.org/abs/2408.06072) (2022-05-29) 
[![Code](https://img.shields.io/github/stars/THUDM/CogVideo.svg?style=social&label=Official)](https://github.com/THUDM/CogVideo) 

<a name="1.4."></a>
### 1.4. Other Based Video Generation

+ [From Slow Bidirectional to Fast Autoregressive Video Diffusion Models](https://arxiv.org/abs/2412.07772) (2024-12-10) 
[![Code](https://img.shields.io/github/stars/tianweiy/CausVid.svg?style=social&label=Official)](https://github.com/tianweiy/CausVid)
[![Website](https://img.shields.io/badge/Website-9cf)](https://causvid.github.io/)

+ [ViD-GPT: Introducing GPT-style Autoregressive Generation in Video Diffusion Models](https://arxiv.org/abs/2406.10981) (2024-06-16) 
[![Code](https://img.shields.io/github/stars/Dawn-LX/CausalCache-VDM.svg?style=social&label=Official)](https://github.com/Dawn-LX/CausalCache-VDM)

+ [WorldDreamer: Towards General World Models for Video Generation via Predicting Masked Tokens](https://arxiv.org/abs/2401.09985) (2024-01-18) 
[![Code](https://img.shields.io/github/stars/JeffWang987/WorldDreamer.svg?style=social&label=Official)](https://github.com/JeffWang987/WorldDreamer)
[![Website](https://img.shields.io/badge/Website-9cf)](https://world-dreamer.github.io/) 


<a name="2."></a>
## 2. Video Generation for World Model in Robotics
<a name="2.1."></a>
### 2.1. Action Navigation World Model

+ [Unified Video Action Model](https://arxiv.org/abs/2503.00200) (2025-02-28)
[![Code](https://img.shields.io/github/stars/ShuangLI59/unified_video_action.svg?style=social&label=Official)](https://github.com/ShuangLI59/unified_video_action)
[![Website](https://img.shields.io/badge/Website-9cf)](https://unified-video-action-model.github.io/)

+ [Pre-Trained Video Generative Models as World Simulators](https://arxiv.org/abs/2502.07825) (2025-02-10)

+ [Learning Real-World Action-Video Dynamics with Heterogeneous Masked Autoregression](https://arxiv.org/abs/2502.04296) (2025-02-06) 
[![Code](https://img.shields.io/github/stars/liruiw/HMA.svg?style=social&label=Official)](https://github.com/liruiw/HMA)
[![Website](https://img.shields.io/badge/Website-9cf)](https://liruiw.github.io/hma/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/liruiw/hma-base-disc)

+ [Navigation World Models](https://arxiv.org/abs/2412.03572) (2024-12-04)
[![Code](https://img.shields.io/github/stars/facebookresearch/nwm.svg?style=social&label=Official)](https://github.com/facebookresearch/nwm/)
[![Website](https://img.shields.io/badge/Website-9cf)](https://www.amirbar.net/nwm/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/facebook/nwm)

+ [IRASim: Learning Interactive Real-Robot Action Simulators](https://arxiv.org/abs/2406.14540) (2024-06-20)
[![Code](https://img.shields.io/github/stars/bytedance/IRASim.svg?style=social&label=Official)](https://github.com/bytedance/IRASim)
[![Website](https://img.shields.io/badge/Website-9cf)](https://gen-irasim.github.io/)


<a name="2.2."></a>
### 2.2. Instruction Navigation World Model

+ [NavigateDiff: Visual Predictors are Zero-Shot Navigation Assistants](https://arxiv.org/abs/2502.13894) (2025-02-19) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://21styouth.github.io/NavigateDiff/) 

+ [SlowFast-VGen: Slow-Fast Learning for Action-driven Long Video Generation](https://arxiv.org/abs/2410.23277) (2024-10-30) 
[![Code (to be released)](https://img.shields.io/github/stars/slowfast-vgen/slowfast-vgen.svg?style=social&label=Official)](https://github.com/slowfast-vgen/slowfast-vgen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://slowfast-vgen.github.io/) 

+ [EVA: An Embodied World Model for Future Video Anticipation](https://arxiv.org/abs/2410.15461) (2024-10-20) 


+ [Pandora: Towards general world model with natural language actions and video states](https://arxiv.org/abs/2406.09455) (2024-06-12) 
[![Code](https://img.shields.io/github/stars/maitrix-org/Pandora.svg?style=social&label=Official)](https://github.com/maitrix-org/Pandora)
[![Website](https://img.shields.io/badge/Website-9cf)](https://world-model.maitrix.org/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/maitrix-org/Pandora)


+ [COMBO: Compositional World Models for Embodied Multi-Agent Cooperation](https://arxiv.org/abs/2404.10775) (2024-04-16) 
[![Code](https://img.shields.io/github/stars/UMass-Embodied-AGI/COMBO.svg?style=social&label=Official)](https://github.com/UMass-Embodied-AGI/COMBO)
[![Website](https://img.shields.io/badge/Website-9cf)](https://umass-embodied-agi.github.io/COMBO/) 


+ [Video Language Planning](https://arxiv.org/abs/2310.10625) (2023-10-16) 
[![Code](https://img.shields.io/github/stars/video-language-planning/vlp_code.svg?style=social&label=Official)](https://github.com/video-language-planning/vlp_code)
[![Website](https://img.shields.io/badge/Website-9cf)](https://video-language-planning.github.io/)

+ [Learning Interactive Real-World Simulators](https://arxiv.org/abs/2310.06114) (2023-10-09) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://universal-simulator.github.io/unisim/)

+ [Compositional Foundation Models for Hierarchical Planning](https://arxiv.org/abs/2309.08587) (2023-09-15) 
[![Code](https://img.shields.io/github/stars/anuragajay/hip.svg?style=social&label=Official)](https://github.com/anuragajay/hip/)
[![Website](https://img.shields.io/badge/Website-9cf)](https://hierarchical-planning-foundation-model.github.io/)


<a name="2.3."></a>
### 2.3.  Goal Navigation World Model

+ [Grounding Video Models to Actions through Goal Conditioned Exploration](https://arxiv.org/abs/2411.07223) (2024-11-11) 
[![Code](https://img.shields.io/github/stars/video-to-action/v2a-video-model-release.svg?style=social&label=Official)](https://github.com/video-to-action/v2a-video-model-release)
[![Website](https://img.shields.io/badge/Website-9cf)](https://video-to-action.github.io/)

+ [Learning Universal Policies via Text-Guided Video Generation](https://arxiv.org/abs/2302.00111) (2023-01-31) 
[![Code](https://img.shields.io/github/stars/flow-diffusion/AVDC.svg?style=social&label=Official)](https://github.com/flow-diffusion/AVDC)
[![Website](https://img.shields.io/badge/Website-9cf)](https://universal-policy.github.io/unipi/)

<a name="2.4."></a>
### 2.4.  Other Navigation World Model

+ [TASTE-Rob: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation](https://arxiv.org/abs/2503.11423) (2025-03-14) 
[![Code](https://img.shields.io/github/stars/GAP-LAB-CUHK-SZ/TASTE-Rob.svg?style=social&label=Official)](https://github.com/GAP-LAB-CUHK-SZ/TASTE-Rob)
[![Website](https://img.shields.io/badge/Website-9cf)](https://taste-rob.github.io/) 

+ [RoboDreamer: Learning Compositional World Models for Robot Imagination](https://arxiv.org/abs/2404.12377) (2024-04-18) 
[![Code](https://img.shields.io/github/stars/rainbow979/robodreamer.svg?style=social&label=Official)](https://github.com/rainbow979/robodreamer)
[![Website](https://img.shields.io/badge/Website-9cf)](https://robovideo.github.io/) 

<a name="3."></a>
## 3. Video Generation for World Model in Autonomous Driving
<a name="3.1."></a>
### 3.1. Instruction Navigation World Model

+ [SlowFast-VGen: Slow-Fast Learning for Action-driven Long Video Generation](https://arxiv.org/abs/2410.23277) (2024-10-30) 
[![Code (to be released)](https://img.shields.io/github/stars/slowfast-vgen/slowfast-vgen.svg?style=social&label=Official)](https://github.com/slowfast-vgen/slowfast-vgen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://slowfast-vgen.github.io/) 

+ [Pandora: Towards general world model with natural language actions and video states](https://arxiv.org/abs/2406.09455) (2024-06-12) 
[![Code](https://img.shields.io/github/stars/maitrix-org/Pandora.svg?style=social&label=Official)](https://github.com/maitrix-org/Pandora)
[![Website](https://img.shields.io/badge/Website-9cf)](https://world-model.maitrix.org/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/maitrix-org/Pandora)

+ [DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video Generation](https://arxiv.org/abs/2403.06845) (2024-03-11)
[![Code](https://img.shields.io/github/stars/f1yfisher/DriveDreamer2.svg?style=social&label=Official)](https://github.com/f1yfisher/DriveDreamer2)
[![Website](https://img.shields.io/badge/Website-9cf)](https://drivedreamer2.github.io/)

+ [WorldDreamer: Towards General World Models for Video Generation via Predicting Masked Tokens](https://arxiv.org/abs/2401.09985) (2024-01-18) 
[![Code](https://img.shields.io/github/stars/JeffWang987/WorldDreamer.svg?style=social&label=Official)](https://github.com/JeffWang987/WorldDreamer)
[![Website](https://img.shields.io/badge/Website-9cf)](https://world-dreamer.github.io/)

+ [ADriver-I: A General World Model for Autonomous Driving](https://arxiv.org/abs/2311.13549) (2023-11-22) 

+ [Align your Latents: High-Resolution Video Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2304.08818) (2023-04-18) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/VideoLDM/)

<a name="3.2."></a>
### 3.2. Trajectory Navigation World Model

+ [Other Vehicle Trajectories Are Also Needed: A Driving World Model Unifies  Ego-Other Vehicle Trajectories in Video Latent Space](https://arxiv.org/abs/2503.09215) (2025-03-12) 

+ [Doe-1: Closed-Loop Autonomous Driving with Large World Model](https://arxiv.org/abs/2412.09627) (2024-12-12)
[![Code](https://img.shields.io/github/stars/wzzheng/Doe.svg?style=social&label=Official)](https://github.com/wzzheng/Doe)
[![Website](https://img.shields.io/badge/Website-9cf)](https://wzzheng.net/Doe/)

+ [ACT-BENCH:Towards Action Controllable World Models for Autonomous Driving](https://arxiv.org/abs/2412.05337) (2024-12-06)

<a name="3.3."></a>
### 3.3. Action Navigation World Model

+ [DrivingGPT: Unifying Driving World Modeling and Planning with Multi-modal Autoregressive Transformers](https://arxiv.org/abs/2412.18607) (2024-12-24)

+ [WoVoGen: World Volume-aware Diffusion for Controllable Multi-camera Driving Scene Generation](https://arxiv.org/abs/2312.02934) (2023-12-05)
[![Code](https://img.shields.io/github/stars/fudan-zvg/WoVoGen.svg?style=social&label=Official)](https://github.com/fudan-zvg/WoVoGen)

+ [Driving into the Future: Multiview Visual Forecasting and Planning with World Model for Autonomous Driving](https://arxiv.org/abs/2311.17918) (2023-11-29)
[![Code](https://img.shields.io/github/stars/BraveGroup/Drive-WM.svg?style=social&label=Official)](https://github.com/BraveGroup/Drive-WM)
[![Website](https://img.shields.io/badge/Website-9cf)](https://drive-wm.github.io/)

+ [GAIA-1: A Generative World Model for Autonomous Driving](https://arxiv.org/abs/2309.17080) (2023-09-29)


+ [DriveDreamer: Towards Real-world-driven World Models for Autonomous Driving](https://arxiv.org/abs/2309.09777) (2023-09-18)
[![Code](https://img.shields.io/github/stars/JeffWang987/DriveDreamer.svg?style=social&label=Official)](https://drivedreamer.github.io/)

+ [DriveGAN: Towards a Controllable High-Quality Neural Simulation](https://arxiv.org/abs/2104.15060) (2021-04-30)

+ [Learning a Driving Simulator](https://arxiv.org/abs/1608.01230) (2016-08-03)

<a name="3.4."></a>
### 3.4. Layout Navigation World Model

+ [CoGen: 3D Consistent Video Generation via Adaptive Conditioning for Autonomous Driving](https://arxiv.org/abs/2503.22231) (2025-03-28)
[![Website](https://img.shields.io/badge/Website-9cf)](https://xiaomi-research.github.io/cogen/)

+ [UniScene: Unified Occupancy-centric Driving Scene Generation](https://arxiv.org/abs/2412.05435) (2024-12-06)
[![Code](https://img.shields.io/github/stars/Arlo0o/UniScene-Unified-Occupancy-centric-Driving-Scene-Generation.svg?style=social&label=Official)](https://github.com/Arlo0o/UniScene-Unified-Occupancy-centric-Driving-Scene-Generation)
[![Website](https://img.shields.io/badge/Website-9cf)](https://arlo0o.github.io/uniscene/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/Arlolo0/UniScene/tree/main)

+ [DiVE: DiT-based Video Generation with Enhanced Control](https://arxiv.org/abs/2409.01595) (2024-09-03) 
[![Code (to be released)](https://img.shields.io/github/stars/LiAutoAD/DIVE.svg?style=social&label=Official)](https://github.com/LiAutoAD/DIVE)
[![Website](https://img.shields.io/badge/Website-9cf)](https://liautoad.github.io/DIVE/)

+ [Panacea: Panoramic and Controllable Video Generation for Autonomous Driving](https://arxiv.org/abs/2311.16813) (2023-11-28) 
[![Code](https://img.shields.io/github/stars/wenyuqing/panacea.svg?style=social&label=Official)](https://github.com/wenyuqing/panacea)
[![Website](https://img.shields.io/badge/Website-9cf)](https://panacea-ad.github.io/)

+ [DrivingDiffusion: Layout-Guided multi-view driving scene video generation with latent diffusion model](https://arxiv.org/abs/2310.07771) (2023-10-11) 
[![Code](https://img.shields.io/github/stars/shalfun/DrivingDiffusion.svg?style=social&label=Official)](https://github.com/shalfun/DrivingDiffusion)
[![Website](https://img.shields.io/badge/Website-9cf)](https://drivingdiffusion.github.io/)

<a name="3.5."></a>
### 3.5. Hybrid Navigation World Model

+ [GAIA-2: A Controllable Multi-View Generative World Model for Autonomous Driving](https://arxiv.org/abs/2503.20523) (2025-03-26)
[![Website](https://img.shields.io/badge/Website-9cf)](https://wayve.ai/thinking/gaia-2/)

+ [MiLA: Multi-view Intensive-fidelity Long-term Video Generation World Model for Autonomous Driving](https://arxiv.org/abs/2503.15875) (2025-03-20)
[![Website](https://img.shields.io/badge/Website-9cf)](https://xiaomi-mlab.github.io/mila.github.io/) 

+ [MaskGWM: a Generalizable driving World Model embodied with Video Mask reconstruction](https://arxiv.org/abs/2502.11663) (2025-02-17)
[![Code](https://img.shields.io/github/stars/SenseTime-FVG/OpenDWM.svg?style=social&label=Official)](https://github.com/SenseTime-FVG/OpenDWM)

+ [GEM:AGeneralizable Ego-Vision Multimodal World Model for Fine-Grained Ego-Motion, Object Dynamics, and Scene Composition Control](https://arxiv.org/abs/2412.11198) (2024-12-15)
[![Code](https://img.shields.io/github/stars/vita-epfl/GEM.svg?style=social&label=Official)](https://github.com/vita-epfl/GEM)
[![Website](https://img.shields.io/badge/Website-9cf)](https://vita-epfl.github.io/GEM.github.io/)

+ [Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability](https://arxiv.org/abs/2405.17398) (2024-05-27)
[![Code](https://img.shields.io/github/stars/OpenDriveLab/DriveAGI.svg?style=social&label=Official)](https://github.com/OpenDriveLab/DriveAGI)
[![Website](https://img.shields.io/badge/Website-9cf)](https://opendrivelab.com/Vista/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/OpenDriveLab/Vista)

+ [GenAD: Generalized Predictive Model for Autonomous Driving](https://arxiv.org/abs/2403.09630) (2024-03-14)
[![Code](https://img.shields.io/github/stars/OpenDriveLab/DriveAGI.svg?style=social&label=Official)](https://github.com/OpenDriveLab/DriveAGI)


<a name="3.6."></a>
### 3.6. World Model without Navigation

+ [Seeing the Future, Perceiving the Future: A Unified Driving World Model for Future Generation and Perception](https://arxiv.org/abs/2503.13587) (2025-03-17)
[![Code](https://img.shields.io/github/stars/dk-liang/UniFuture.svg?style=social&label=Official)](https://github.com/dk-liang/UniFuture)
[![Website](https://img.shields.io/badge/Website-9cf)](https://dk-liang.github.io/UniFuture/)

<a name="3.7."></a>
### 3.7. Other Navigation World Model

+ [Generative Camera Dolly: Extreme Monocular Dynamic Novel View Synthesis](https://arxiv.org/abs/2405.14868) (2024-05-23)
+   ><i>Note: with relative camera  extrinsics navigation</i>

<a name="4."></a>
## 4. Video Generation for World Model in Gaming
<a name="4.1."></a>
### 4.1. Game Controller Navigation World Model

+ [Model as a Game: On Numerical and Spatial Consistency for Generative Games](https://arxiv.org/abs/2503.21172) (2025-03-27)

+ [World and Human Action Models towards gameplay ideation](https://www.nature.com/articles/s41586-025-08600-3) (2025-02-19)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/microsoft/wham)

+ [Genie: Generative Interactive Environmentsl](https://arxiv.org/abs/2402.15391) (2024-02-23)
[![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/genie-2024/?pli=1)

+ [Video2 Game Generation: A Practical Study using Mario](https://virtual-protocol.github.io/mario-videogamegen/static/pdfs/VideoGameGen.pdf) (2024)
[![Website](https://img.shields.io/badge/Website-9cf)](https://virtual-protocol.github.io/mario-videogamegen/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/virtuals-protocol/mario-videogamegen)

+ [Playable Video Generation](https://arxiv.org/abs/2101.12195) (2021-01-28)
[![Code](https://img.shields.io/github/stars/willi-menapace/PlayableVideoGeneration.svg?style=social&label=Official)](https://github.com/willi-menapace/PlayableVideoGeneration)
[![Website](https://img.shields.io/badge/Website-9cf)](https://willi-menapace.github.io/playable-video-generation-website/)

<a name="4.2."></a>
### 4.2. Keyboard Navigation World Model

+ [The Matrix: Infinite-Horizon World Generation with Real-Time Moving Control](https://arxiv.org/abs/2412.03568) (2024-12-04)
[![Website](https://img.shields.io/badge/Website-9cf)](https://thematrix1999.github.io/)

+ [GameGen-X: Interactive Open-world Game Video Generation](https://arxiv.org/abs/2411.00769) (2024-11-01)
[![Code](https://img.shields.io/github/stars/GameGen-X/GameGen-X.svg?style=social&label=Official)](https://github.com/GameGen-X/GameGen-X)
[![Website](https://img.shields.io/badge/Website-9cf)](https://gamegen-x.github.io/)

+ [Diffusion Models Are Real-Time Game Engines](https://arxiv.org/abs/2408.14837) (2024-08-27)
[![Website](https://img.shields.io/badge/Website-9cf)](https://gamengen.github.io/)

+ [Learning to Simulate Dynamic Environments with GameGAN](https://arxiv.org/abs/2005.12126) (2020-05-25)
[![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/gameGAN/)

<a name="4.3."></a>
### 4.3. Keyboard & Mouse Navigation World Model

+ [MineWorld: a Real-Time and Open-Source Interactive World Model on Minecraft](https://arxiv.org/abs/2504.08388) (2025-04-11)
[![Code](https://img.shields.io/github/stars/microsoft/MineWorld.svg?style=social&label=Official)](https://github.com/microsoft/MineWorld)


+ [GameFactory: Creating New Games with Generative Interactive Videos](https://arxiv.org/abs/2501.08325) (2025-01-14)
[![Code](https://img.shields.io/github/stars/KwaiVGI/GameFactory.svg?style=social&label=Official)](https://github.com/KwaiVGI/GameFactory)
[![Website](https://img.shields.io/badge/Website-9cf)](https://yujiwen.github.io/gamefactory/)

+ [Genie 2: A large-scale foundation world model](https://deepmind.google/discover/blog/genie-2-a-large-scale-foundation-world-model/) (2024-12-04)

+ [Playable Game Generation](https://arxiv.org/abs/2412.00887) (2024-12-01)
[![Code](https://img.shields.io/github/stars/GreatX3/Playable-Game-Generation.svg?style=social&label=Official)](https://github.com/GreatX3/Playable-Game-Generation)

+ [Oasis: A Universe in a Transformer](https://oasis-model.github.io/) (2024-10-31)
[![Code](https://img.shields.io/github/stars/etched-ai/open-oasis.svg?style=social&label=Official)](https://github.com/etched-ai/open-oasis)
[![Website](https://img.shields.io/badge/Website-9cf)](https://oasis-model.github.io/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/Etched/oasis-500m)

+ [Diffusion for World Modeling: Visual Details Matter in Atari](https://arxiv.org/abs/2405.12399) (2024-05-20)
[![Code](https://img.shields.io/github/stars/eloialonso/diamond.svg?style=social&label=Official)](https://github.com/eloialonso/diamond)
[![Website](https://img.shields.io/badge/Website-9cf)](https://diamond-wm.github.io/)

<a name="4.4."></a>
### 4.4. Action Trajectory Navigation World Model

+ [Pre-Trained Video Generative Models as World Simulators](https://arxiv.org/abs/2502.07825) (2025-02-10)


<a name="4.5."></a>
### 4.5. Multiple Navigation World Model

+ [Promptable Game Models: Text-Guided Game Simulation via Masked Diffusion Models](https://arxiv.org/abs/2303.13472) (2023-03-23)
[![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/promptable-game-models/)


+ [Playable Environments: Video Manipulation in Space and Time](https://arxiv.org/abs/2203.01914) (2022-03-03)
[![Code](https://img.shields.io/github/stars/willi-menapace/PlayableEnvironments.svg?style=social&label=Official)](https://github.com/willi-menapace/PlayableEnvironments)
[![Website](https://img.shields.io/badge/Website-9cf)](https://willi-menapace.github.io/playable-environments-website/)


<a name="4.6."></a>
### 4.6. Other Navigation World Model

+ [AdaWorld: Learning Adaptable World Models with Latent Actions](https://arxiv.org/abs/2503.18938) (2025-03-24)
[![Code](https://img.shields.io/github/stars/Little-Podi/AdaWorld.svg?style=social&label=Official)](https://github.com/Little-Podi/AdaWorld)
[![Website](https://img.shields.io/badge/Website-9cf)](https://adaptable-world-model.github.io/)




