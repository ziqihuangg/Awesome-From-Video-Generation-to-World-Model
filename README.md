# Awesome From Video Generation to World Model

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/ziqihuangg/Awesome-From-Video-Generation-to-World-Model)
![visitors](https://visitor-badge.laobi.icu/badge?page_id=ziqihuangg.Awesome-From-Video-Generation-to-World-Model)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](https://github.com/ziqihuangg/Awesome-From-Video-Generation-to-World-Model/pulls)


## Overview

This repository currently contains a temporary version of the paper list. We will release the final handout notes within one week.

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
- [1. Generation-1: Hyperrealism](#1.)
    - [1.1 U-Net Based Video Generation](#1.1.1)
    - [1.2 DiT Based Video Generation](#1.1.2.)
    - [1.3 Autoregressive Based Video Generation](#1.1.3.)
    - [1.4 Other Based Video Generation](#1.1.4.)

- [2. Generation-2: Lawful Interaction](#2.)
  - [2.1 Video Generation as World Model in General Scene](#2.1)
    - [2.1.1 Geometry Condition Prior World Model](#2.1.1)
    - [2.1.2 3D Prior World Model](#2.1.2.)
    - [2.1.3 Physical Prior World Model](#2.1.3.)
    - [2.1.4 Geometry Navigation World Model](#2.1.4.)
    - [2.1.5Trajectory Navigation World Model](#2.1.5.)
    - [2.1.6 Camera Motion Navigation World Model](#2.1.6.)

  - [2.2 Video Generation as World Model in Robotics](#2.2.)
    - [2.2.1 Action Navigation World Model](#2.2.1.)
    - [2.2.2 Instruction Navigation World Model](#2.2.2.)
    - [2.2.3 Goal Navigation World Model](#2.2.3.)
    - [2.2.4 Other Navigation World Model](#2.2.4.)
  
  - [2.3 Video Generation as World Model in Autonomous Driving](#2.3.)
    - [2.3.1 Layout Prior World Model](#2.3.1.)
    - [2.3.1 Instruction Navigation World Model](#2.3.2.)
    - [2.3.2 Trajectory Navigation World Model](#2.3.3.)
    - [2.3.3 Action Navigation World Model](#2.3.4.)
    - [2.3.5 Hybrid Navigation World Model](#2.3.5.)
    - [2.3.6 Other Navigation World Model](#2.3.6.)

      
  - [2.4 Video Generation as World Model in Gaming](#2.4.)
    - [2.4.1 Game Controller Navigation World Model](#2.4.1.)
    - [2.4.2 Keyboard Navigation World Model](#2.4.2.)
    - [2.4.3 Keyboard & Mouse Navigation World Model](#2.4.3.)
    - [2.4.4 Action Trajectory Navigation World Model](#2.4.4.)
    - [2.4.5 Signal Command Navigation World Model](#2.4.5.)
    - [2.4.6 Multiple Navigation World Model](#2.4.6.)
    - [2.4.7 Other Navigation World Model](#2.4.7.)
    
- [3. Generation-3: Intrinsic Planning](#3.)
  - [3.1. Macroscopic Planning World Model](#3.1.)
  - [3.2. Physical-Aligned Planning World Model](#3.2.)
  - [3.3. Microscopic Planning World Model](#3.3.)

- [4. Generation-4: Black Swan Modeling](#4.)
 
<a name="1."></a>
# 1. Generation-1: Hyperrealism
<a name="1.1."></a>
## 1.1 U-Net Based Video Generation

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

+ [MagicVideo-V2: Multi-Stage High-Aesthetic Video Generation](https://arxiv.org/abs/2401.04468) (2024-01-09) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://magicvideov2.github.io/) 

+ [Moonshot: Towards Controllable Video Generation and Editing with Multimodal Conditions](https://arxiv.org/abs/2401.01827) (2024-01-03) 
[![Code](https://img.shields.io/github/stars/salesforce/LAVIS.svg?style=social&label=Official)](https://github.com/salesforce/LAVIS)


+ [InstructVideo: Instructing Video Diffusion Models with Human Feedback](https://arxiv.org/abs/2312.12490) (2023-12-19) 
[![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Official)](https://github.com/ali-vilab/VGen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://instructvideo.github.io/)

+ [Hierarchical Spatio-temporal Decoupling for Text-to-Video Generation](https://arxiv.org/abs/2312.04483) (2023-12-07)
+ [![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Official)](https://github.com/ali-vilab/VGen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://higen-t2v.github.io/)

+ [DreamVideo: Composing Your Dream Videos with Customized Subject and Motion](https://arxiv.org/abs/2312.04433) (2023-12-07) 
[![Code](https://img.shields.io/github/stars/ali-vilab/VGen.svg?style=social&label=Official)](https://github.com/ali-vilab/VGen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://dreamvideo-t2v.github.io/)

+ [Stable Video Diffusion: Scaling Latent Video Diffusion Models to Large Datasets](https://arxiv.org/abs/2311.15127) (2023-11-25) 
[![Code](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social&label=Official)](https://github.com/Stability-AI/generative-models)

 + [Make Pixels Dance: High-Dynamic Video Generation](https://arxiv.org/abs/2311.10982) (2023-11-18) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://makepixelsdance.github.io/) 


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

+ [Any-to-Any Generation via Composable Diffusion](https://arxiv.org/abs/2305.11846) (2023-05-19)
+ [![Code](https://img.shields.io/github/stars/microsoft/i-Code.svg?style=social&label=Official)](https://github.com/microsoft/i-Code)
[![Website](https://img.shields.io/badge/Website-9cf)](https://codi-gen.github.io/)


+ [Align your Latents: High-Resolution Video Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2304.08818) (2023-04-18) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/VideoLDM/)

+ [Text2Video-Zero: Text-to-Image Diffusion Models are Zero-Shot Video Generators](https://arxiv.org/abs/2303.13439) (2023-03-23)
[![Code](https://img.shields.io/github/stars/Picsart-AI-Research/Text2Video-Zero.svg?style=social&label=Official)](https://github.com/Picsart-AI-Research/Text2Video-Zero)
[![Website](https://img.shields.io/badge/Website-9cf)](https://text2video-zero.github.io/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/PAIR/Text2Video-Zero)

+ [Structure and Content-Guided Video Synthesis with Diffusion Models
](https://arxiv.org/abs/2302.03011) (2023-02-06) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://runwayml.com/research/gen-1)

+ [Imagen Video: High Definition Video Generation with Diffusion Models](https://arxiv.org/abs/2210.02303) (2022-10-05) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://imagen.research.google/video/)

+ [Make-A-Video: Text-to-Video Generation without Text-Video Data](https://arxiv.org/abs/2209.14792) (2022-09-29) 
[![Code](https://img.shields.io/github/stars/lucidrains/make-a-video-pytorch.svg?style=social&label=Official)](https://github.com/lucidrains/make-a-video-pytorch)

+ [Flexible Diffusion Modeling of Long Videos](https://arxiv.org/abs/2205.11495) (2022-05-23)

+ [MCVD: Masked Conditional Video Diffusion for Prediction, Generation, and Interpolation](https://arxiv.org/abs/2205.09853) (2022-05-19)
[![Code](https://img.shields.io/github/stars/voletiv/mcvd-pytorch.svg?style=social&label=Official)](https://github.com/voletiv/mcvd-pytorch)
[![Website](https://img.shields.io/badge/Website-9cf)](https://mask-cond-video-diffusion.github.io/)

<a name="1.2."></a>
## 1.2 DiT Based Video Generation

+ [AccVideo: Accelerating Video Diffusion Model with Synthetic Dataset](https://arxiv.org/abs/2503.19462) (2025-03-25)
[![Code](https://img.shields.io/github/stars/aejion/AccVideo.svg?style=social&label=Official)](https://github.com/aejion/AccVideo)
[![Website](https://img.shields.io/badge/Website-9cf)](https://aejion.github.io/accvideo/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/aejion/AccVideo)

+ [AETHER: Geometric-Aware Unified World Modeling](https://arxiv.org/abs/2503.18945) (2025-03-24)
[![Code](https://img.shields.io/github/stars/OpenRobotLab/Aether.svg?style=social&label=Official)](https://github.com/OpenRobotLab/Aether)
[![Website](https://img.shields.io/badge/Website-9cf)](https://aether-world.github.io/) 

+ [Cosmos-Transfer1: Conditional World Generation with Adaptive Multimodal Control](https://arxiv.org/abs/2503.14492) (2025-03-18)
[![Code](https://img.shields.io/github/stars/nvidia-cosmos/cosmos-transfer1.svg?style=social&label=Official)](https://github.com/nvidia-cosmos/cosmos-transfer1)
[![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/dir/cosmos-transfer1/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/nvidia/cosmos-transfer1-67c9d328196453be6e568d3e)

+ [WISA: World Simulator Assistant for Physics-Aware Text-to-Video Generation](https://arxiv.org/abs/2503.08153) (2025-03-11)
[![Code](https://img.shields.io/github/stars/360CVGroup/WISA.svg?style=social&label=Official)](https://github.com/360CVGroup/WISA)
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

+ [Movie Gen: A Cast of Media Foundation Models](https://arxiv.org/abs/2410.13720) (2024-10-17)
[![Website](https://img.shields.io/badge/Website-9cf)](https://ai.meta.com/blog/movie-gen-media-foundation-models-generative-ai-video/)


+ [Pyramidal Flow Matching for Efficient Video Generative Modeling](https://arxiv.org/abs/2410.05954) (2024-10-08)
+ [![Code](https://img.shields.io/github/stars/jy0205/Pyramid-Flow.svg?style=social&label=Official)](https://github.com/jy0205/Pyramid-Flow)
[![Website](https://img.shields.io/badge/Website-9cf)](https://pyramid-flow.github.io/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/rain1011/pyramid-flow-sd3)

+ [T2V-Turbo-v2: Enhancing Video Generation Model Post-Training through Data, Reward, and Conditional Guidance Design](https://arxiv.org/abs/2410.05677) (2024-10-08)
+ [![Code](https://img.shields.io/github/stars/Ji4chenLi/t2v-turbo.svg?style=social&label=Official)](https://github.com/Ji4chenLi/t2v-turbo)
[![Website](https://img.shields.io/badge/Website-9cf)](https://t2v-turbo-v2.github.io/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/TIGER-Lab/T2V-Turbo)

+ [Emu3: Next-Token Prediction is All You Need](https://arxiv.org/abs/2409.18869) (2024-09-27) 
[![Code](https://img.shields.io/github/stars/baaivision/Emu3.svg?style=social&label=Official)](https://github.com/baaivision/Emu3) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://emu.baai.ac.cn/about)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/BAAI/emu3-66f4e64f70850ff358a2e60f)

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

+ [Photorealistic Video Generation with Diffusion Models](https://arxiv.org/abs/2312.06662) (2023-12-11) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://walt-video-diffusion.github.io/)

+ [Videocrafter1: Open diffusion models for high-quality video generation](https://arxiv.org/abs/2310.19512) (2023-10-30) 
[![Code](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Official)](https://github.com/AILab-CVC/VideoCrafter)

<a name="1.3."></a>
## 1.3 Autoregressive Based Video Generation

+ [Cosmos World Foundation Model Platform for Physical AI](https://arxiv.org/abs/2501.03575) (2025-01-07) 
[![Code](https://img.shields.io/github/stars/nvidia-cosmos/cosmos-predict1.svg?style=social&label=Official)](https://github.com/nvidia-cosmos/cosmos-predict1)
[![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/dir/cosmos-predict1/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/nvidia/cosmos-predict1-67c9d1b97678dbf7669c89a7)

+ [Owl-1: Omni World Model for Consistent Long Video Generation](https://arxiv.org/abs/2412.09600) (2024-12-12) 
[![Code](https://img.shields.io/github/stars/huang-yh/Owl.svg?style=social&label=Official)](https://github.com/huang-yh/Owl)

+ [DimensionX: Create Any 3D and 4D Scenes from a Single Image with Controllable Video Diffusion](https://arxiv.org/abs/2411.04928) (2024-11-07)
+ [![Code](https://img.shields.io/github/stars/wenqsun/DimensionX.svg?style=social&label=Official)](https://github.com/wenqsun/DimensionX)
[![Website](https://img.shields.io/badge/Website-9cf)](https://chenshuo20.github.io/DimensionX/) 

+ [StreamingT2V: Consistent, Dynamic, and Extendable Long Video Generation from Text](https://arxiv.org/abs/2403.14773) (2024-03-21) 
[![Code](https://img.shields.io/github/stars/Picsart-AI-Research/StreamingT2V.svg?style=social&label=Official)](https://github.com/Picsart-AI-Research/StreamingT2V)
[![Website](https://img.shields.io/badge/Website-9cf)](https://streamingt2v.github.io/) 


+ [Pandora: Towards general world model with natural language actions and video states](https://arxiv.org/abs/2406.09455) (2024-06-12) 
[![Code](https://img.shields.io/github/stars/maitrix-org/Pandora.svg?style=social&label=Official)](https://github.com/maitrix-org/Pandora)
[![Website](https://img.shields.io/badge/Website-9cf)](https://world-model.maitrix.org/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/maitrix-org/Pandora)

+ [VideoPoet: A Large Language Model for Zero-Shot Video Generation](https://arxiv.org/abs/2312.14125) (2023-12-21) 
[![Website](https://img.shields.io/badge/Website-9cf)](http://sites.research.google/videopoet/)

+ [Generative Multimodal Models are In-Context Learners](https://arxiv.org/abs/2312.13286) (2023-12-20)
[![Code](https://img.shields.io/github/stars/baaivision/Emu.svg?style=social&label=Official)](https://github.com/baaivision/Emu)
[![Website](https://img.shields.io/badge/Website-9cf)](https://baaivision.github.io/emu2/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/BAAI/Emu2)

+ [MAGVIT:Masked Generative Video Transformer](https://arxiv.org/abs/2212.05199) (2022-12-10) 
[![Code](https://img.shields.io/github/stars/google-research/magvit.svg?style=social&label=Official)](https://github.com/google-research/magvit)
[![Website](https://img.shields.io/badge/Website-9cf)](https://magvit.cs.cmu.edu/)

+ [CogVideo: Large-scale Pretraining for Text-to-Video Generation via Transformers](https://arxiv.org/abs/2408.06072) (2022-05-29) 
[![Code](https://img.shields.io/github/stars/THUDM/CogVideo.svg?style=social&label=Official)](https://github.com/THUDM/CogVideo) 

<a name="1.4."></a>
## 1.4 Other Based Video Generation

+ [From Slow Bidirectional to Fast Autoregressive Video Diffusion Models](https://arxiv.org/abs/2412.07772) (2024-12-10) 
[![Code](https://img.shields.io/github/stars/tianweiy/CausVid.svg?style=social&label=Official)](https://github.com/tianweiy/CausVid)
[![Website](https://img.shields.io/badge/Website-9cf)](https://causvid.github.io/)

+ [ViD-GPT: Introducing GPT-style Autoregressive Generation in Video Diffusion Models](https://arxiv.org/abs/2406.10981) (2024-06-16) 
[![Code](https://img.shields.io/github/stars/Dawn-LX/CausalCache-VDM.svg?style=social&label=Official)](https://github.com/Dawn-LX/CausalCache-VDM)

+ [Vidu: a Highly Consistent, Dynamic and Skilled Text-to-Video Generator with Diffusion Models](https://arxiv.org/abs/2405.04233) (2024-05-07) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://www.vidu.com/zh)

+ [InteractiveVideo: User-Centric Controllable Video Generation with Synergistic Multimodal Instructions](https://arxiv.org/abs/2402.03040) (2024-02-05) 
[![Code](https://img.shields.io/github/stars/invictus717/InteractiveVideo.svg?style=social&label=Official)](https://github.com/invictus717/InteractiveVideo)
[![Website](https://img.shields.io/badge/Website-9cf)](https://invictus717.github.io/InteractiveVideo/)


+ [WorldDreamer: Towards General World Models for Video Generation via Predicting Masked Tokens](https://arxiv.org/abs/2401.09985) (2024-01-18) 
[![Code](https://img.shields.io/github/stars/JeffWang987/WorldDreamer.svg?style=social&label=Official)](https://github.com/JeffWang987/WorldDreamer)
[![Website](https://img.shields.io/badge/Website-9cf)](https://world-dreamer.github.io/) 


<a name="2."></a>
# 2. Generation-2: Lawful Interaction
<a name="2.1."></a>
## 2.1 Video Generation as World Model in General Scenes
<a name="2.1.1."></a>
### 2.1.1 Geometry Condition Prior World Model
+ [Control-A-Video: Controllable Text-to-Video Diffusion Models with Motion Prior and Reward Feedback Learning](https://arxiv.org/abs/2305.13840) (2023-05-23)
[![Code](https://img.shields.io/github/stars/Weifeng-Chen/control-a-video.svg?style=social&label=Official)](https://github.com/Weifeng-Chen/control-a-video)
[![Website](https://img.shields.io/badge/Website-9cf)](https://controlavideo.github.io/)

+ [Adding Conditional Control to Text-to-Image Diffusion Models](https://arxiv.org/abs/2302.05543) (2023-02-10)
[![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/lllyasviel/ControlNet)

<a name="2.1.2."></a>
### 2.1.2 3D Condition Prior World Model

+ [Diffusion as Shader: 3D-aware Video Diffusion for Versatile Video Generation Control](https://arxiv.org/abs/2501.03847) (2025-01-07)
[![Code](https://img.shields.io/github/stars/IGL-HKUST/DiffusionAsShader.svg?style=social&label=Official)](https://github.com/IGL-HKUST/DiffusionAsShader)
[![Website](https://img.shields.io/badge/Website-9cf)](https://igl-hkust.github.io/das/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/EXCAI/Diffusion-As-Shader)

+ [GS-DiT: Advancing Video Generation with Pseudo 4D Gaussian Fields through Efficient Dense 3D Point Tracking](https://arxiv.org/abs/2501.02690) (2025-01-05)
[![Code (to be released)](https://img.shields.io/github/stars/wkbian/GS-DiT.svg?style=social&label=Official)](https://github.com/wkbian/GS-DiT)
[![Website](https://img.shields.io/badge/Website-9cf)](https://wkbian.github.io/Projects/GS-DiT/)


<a name="2.1.3."></a>
### 2.1.3 Physical Prior World Model

<a name="2.1.4."></a>
### 2.1.4 Geometry Navigation World Model
+ [ConditionVideo: Training-Free Condition-Guided Text-to-Video Generation](https://arxiv.org/abs/2310.07697) (2023-10-11)

+ [ControlVideo: Training-free Controllable Text-to-Video Generation](https://arxiv.org/abs/2305.13077) (2023-05-22)
[![Code](https://img.shields.io/github/stars/YBYBZhang/ControlVideo.svg?style=social&label=Official)](https://github.com/YBYBZhang/ControlVideo)
[![Website](https://img.shields.io/badge/Website-9cf)](https://controlvideov1.github.io/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/Yabo/ControlVideo)

<a name="2.1.5."></a>
### 2.1.5 Trajectory Navigation World Model
+ [Go-with-the-Flow: Motion-Controllable Video Diffusion Models Using Real-Time Warped Noise](https://arxiv.org/abs/2501.08331) (2025-01-14)
+ [![Code](https://img.shields.io/github/stars/Eyeline-Research/Go-with-the-Flow.svg?style=social&label=Official)](https://github.com/Eyeline-Research/Go-with-the-Flow)
[![Website](https://img.shields.io/badge/Website-9cf)](https://eyeline-research.github.io/Go-with-the-Flow/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/Eyeline-Research/Go-with-the-Flow/tree/main)

+ [Motion Prompting: Controlling Video Generation with Motion Trajectories](https://arxiv.org/abs/2412.02700) (2024-12-03)
[![Website](https://img.shields.io/badge/Website-9cf)](https://motion-prompting.github.io/)

+ [SG-I2V: Self-Guided Trajectory Control in Image-to-Video Generation](https://arxiv.org/abs/2411.04989) (2024-11-07)
[![Code](https://img.shields.io/github/stars/Kmcode1/SG-I2V.svg?style=social&label=Official)](https://github.com/Kmcode1/SG-I2V)
[![Website](https://img.shields.io/badge/Website-9cf)](https://kmcode1.github.io/Projects/SG-I2V/)

+ [FreeTraj: Tuning-Free Trajectory Control in Video Diffusion Models](https://arxiv.org/abs/2406.16863) (2024-06-24)
[![Code](https://img.shields.io/github/stars/arthur-qiu/FreeTraj.svg?style=social&label=Official)](https://github.com/arthur-qiu/FreeTraj)
[![Website](https://img.shields.io/badge/Website-9cf)](http://haonanqiu.com/projects/FreeTraj.html)

+ [Image Conductor: Precision Control for Interactive Video Synthesis](https://arxiv.org/abs/2406.15339) (2024-06-21)
[![Code](https://img.shields.io/github/stars/liyaowei-stu/ImageConductor.svg?style=social&label=Official)](https://github.com/liyaowei-stu/ImageConductor)
[![Website](https://img.shields.io/badge/Website-9cf)](https://liyaowei-stu.github.io/project/ImageConductor/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/TencentARC/ImageConductor)

+ [TrailBlazer: Trajectory Control for Diffusion-Based Video Generation](https://arxiv.org/abs/2401.00896) (2023-12-21)
[![Code](https://img.shields.io/github/stars/hohonu-vicml/Trailblazer.svg?style=social&label=Official)](https://github.com/hohonu-vicml/Trailblazer)
[![Website](https://img.shields.io/badge/Website-9cf)](https://hohonu-vicml.github.io/Trailblazer.Page/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/hohonu-vicml/Trailblazer)

+ [PEEKABOO: Interactive Video Generation via Masked-Diffusion](https://arxiv.org/abs/2312.07509) (2023-12-12)
[![Code](https://img.shields.io/github/stars/microsoft/Peekaboo.svg?style=social&label=Official)](https://github.com/microsoft/Peekaboo)
[![Website](https://img.shields.io/badge/Website-9cf)](https://yash-jain.com/projects/Peekaboo/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/anshuln/peekaboo-demo)

+ [MotionCtrl: A Unified and Flexible Motion Controller for Video Generation](https://arxiv.org/abs/2312.03641) (2023-12-06)
[![Code](https://img.shields.io/github/stars/TencentARC/MotionCtrl.svg?style=social&label=Official)](https://github.com/TencentARC/MotionCtrl)
[![Website](https://img.shields.io/badge/Website-9cf)](https://wzhouxiff.github.io/projects/MotionCtrl/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/TencentARC/MotionCtrl)

+ [Fine-grained Controllable Video Generation via Object Appearance and Context](https://arxiv.org/abs/2312.02919) (2023-12-05)
[![Website](https://img.shields.io/badge/Website-9cf)](https://hhsinping.github.io/factor/)

<a name="2.1.6."></a>
### 2.1.6 Camera Motion Navigation World Model
+ [CameraCtrl II: Dynamic Scene Exploration via Camera-controlled Video Diffusion Models](https://arxiv.org/abs/2503.10592) (2025-03-13)
[![Website](https://img.shields.io/badge/Website-9cf)](https://hehao13.github.io/Projects-CameraCtrl-II/)


+ [Go-with-the-Flow: Motion-Controllable Video Diffusion Models Using Real-Time Warped Noise](https://arxiv.org/abs/2501.08331) (2025-01-14)
+ [![Code](https://img.shields.io/github/stars/Eyeline-Research/Go-with-the-Flow.svg?style=social&label=Official)](https://github.com/Eyeline-Research/Go-with-the-Flow)
[![Website](https://img.shields.io/badge/Website-9cf)](https://eyeline-research.github.io/Go-with-the-Flow/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/Eyeline-Research/Go-with-the-Flow/tree/main)

+ [GS-DiT: Advancing Video Generation with Pseudo 4D Gaussian Fields through Efficient Dense 3D Point Tracking](https://arxiv.org/abs/2501.02690) (2025-01-05)
[![Code (to be released)](https://img.shields.io/github/stars/wkbian/GS-DiT.svg?style=social&label=Official)](https://github.com/wkbian/GS-DiT)
[![Website](https://img.shields.io/badge/Website-9cf)](https://wkbian.github.io/Projects/GS-DiT/)

+ [AKiRa: Augmentation Kit on Rays for optical video generation](https://arxiv.org/abs/2412.14158) (2024-12-18)
[![Code (to be released)](https://img.shields.io/github/stars/Triocrossing/AKiRa.svg?style=social&label=Official)](https://github.com/Triocrossing/AKiRa)
[![Website](https://img.shields.io/badge/Website-9cf)](https://www.lix.polytechnique.fr/vista/projects/2024_akira_wang/)


+ [Image Conductor: Precision Control for Interactive Video Synthesis](https://arxiv.org/abs/2406.15339) (2024-06-21)
[![Code](https://img.shields.io/github/stars/liyaowei-stu/ImageConductor.svg?style=social&label=Official)](https://github.com/liyaowei-stu/ImageConductor)
[![Website](https://img.shields.io/badge/Website-9cf)](https://liyaowei-stu.github.io/project/ImageConductor/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/TencentARC/ImageConductor)

+ [MotionCtrl: A Unified and Flexible Motion Controller for Video Generation](https://arxiv.org/abs/2312.03641) (2023-12-06)
[![Code](https://img.shields.io/github/stars/TencentARC/MotionCtrl.svg?style=social&label=Official)](https://github.com/TencentARC/MotionCtrl)
[![Website](https://img.shields.io/badge/Website-9cf)](https://wzhouxiff.github.io/projects/MotionCtrl/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/TencentARC/MotionCtrl)


<a name="2.2."></a>
## 2.2 Video Generation as World Model in Robotics
<a name="2.2.1."></a>
### 2.2.1 Action Navigation World Model

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

+ [iVideoGPT: Interactive VideoGPTs are Scalable World Models](https://arxiv.org/abs/2405.15223) (2024-05-24)
[![Code](https://img.shields.io/github/stars/thuml/iVideoGPT.svg?style=social&label=Official)](https://github.com/thuml/iVideoGPT)
[![Website](https://img.shields.io/badge/Website-9cf)](https://thuml.github.io/iVideoGPT/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/thuml/ivideogpt-674c59cae32231024d82d6c5)

+ [Model-Based Reinforcement Learning for Atari](https://arxiv.org/abs/1903.00374) (2019-03-01)


<a name="2.2.2."></a>
### 2.2.2 Instruction Navigation World Model

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


+ [Learning an Actionable Discrete Diffusion Policy via Large-Scale Actionless Video Pre-Training](https://arxiv.org/abs/2402.14407) (2024-02-22) 
[![Code](https://img.shields.io/github/stars/tinnerhrhe/VPDD.svg?style=social&label=Official)](https://github.com/tinnerhrhe/VPDD)
[![Website](https://img.shields.io/badge/Website-9cf)](https://video-diff.github.io/) 

+ [Video Language Planning](https://arxiv.org/abs/2310.10625) (2023-10-16) 
[![Code](https://img.shields.io/github/stars/video-language-planning/vlp_code.svg?style=social&label=Official)](https://github.com/video-language-planning/vlp_code)
[![Website](https://img.shields.io/badge/Website-9cf)](https://video-language-planning.github.io/)

+ [Learning Interactive Real-World Simulators](https://arxiv.org/abs/2310.06114) (2023-10-09) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://universal-simulator.github.io/unisim/)

+ [Compositional Foundation Models for Hierarchical Planning](https://arxiv.org/abs/2309.08587) (2023-09-15) 
[![Code](https://img.shields.io/github/stars/anuragajay/hip.svg?style=social&label=Official)](https://github.com/anuragajay/hip/)
[![Website](https://img.shields.io/badge/Website-9cf)](https://hierarchical-planning-foundation-model.github.io/)


<a name="2.2.3."></a>
### 2.2.3 Goal Navigation World Model

+ [Grounding Video Models to Actions through Goal Conditioned Exploration](https://arxiv.org/abs/2411.07223) (2024-11-11) 
[![Code](https://img.shields.io/github/stars/video-to-action/v2a-video-model-release.svg?style=social&label=Official)](https://github.com/video-to-action/v2a-video-model-release)
[![Website](https://img.shields.io/badge/Website-9cf)](https://video-to-action.github.io/)

+ [Learning to Act from Actionless Videos through Dense Correspondences](https://arxiv.org/abs/2310.08576) (2023-10-12) 
[![Code](https://img.shields.io/github/stars/flow-diffusion/AVDC.svg?style=social&label=Official)](https://github.com/flow-diffusion/AVDC)
[![Website](https://img.shields.io/badge/Website-9cf)](https://flow-diffusion.github.io/)

+ [Learning Universal Policies via Text-Guided Video Generation](https://arxiv.org/abs/2302.00111) (2023-01-31) 
[![Code](https://img.shields.io/github/stars/flow-diffusion/AVDC.svg?style=social&label=Official)](https://github.com/flow-diffusion/AVDC)
[![Website](https://img.shields.io/badge/Website-9cf)](https://universal-policy.github.io/unipi/)

<a name="2.2.4."></a>
### 2.2.4 Other Navigation World Model

+ [TASTE-Rob: Advancing Video Generation of Task-Oriented Hand-Object Interaction for Generalizable Robotic Manipulation](https://arxiv.org/abs/2503.11423) (2025-03-14) 
[![Code](https://img.shields.io/github/stars/GAP-LAB-CUHK-SZ/TASTE-Rob.svg?style=social&label=Official)](https://github.com/GAP-LAB-CUHK-SZ/TASTE-Rob)
[![Website](https://img.shields.io/badge/Website-9cf)](https://taste-rob.github.io/)

+ [This&That: Language-Gesture Controlled Video Generation for Robot Planning](https://arxiv.org/abs/2407.05530) (2024-07-08) 
[![Code](https://img.shields.io/github/stars/Kiteretsu77/This_and_That_VDM.svg?style=social&label=Official)](https://github.com/Kiteretsu77/This_and_That_VDM)
[![Website](https://img.shields.io/badge/Website-9cf)](https://cfeng16.github.io/this-and-that/) 

+ [RoboDreamer: Learning Compositional World Models for Robot Imagination](https://arxiv.org/abs/2404.12377) (2024-04-18) 
[![Code](https://img.shields.io/github/stars/rainbow979/robodreamer.svg?style=social&label=Official)](https://github.com/rainbow979/robodreamer)
[![Website](https://img.shields.io/badge/Website-9cf)](https://robovideo.github.io/) 

<a name="2.3."></a>
## 2.3. Video Generation as World Model in Autonomous Driving

<a name="2.3.1."></a>
### 2.3.1 Layout Prior World Model

+ [CoGen: 3D Consistent Video Generation via Adaptive Conditioning for Autonomous Driving](https://arxiv.org/abs/2503.22231) (2025-03-28)
[![Website](https://img.shields.io/badge/Website-9cf)](https://xiaomi-research.github.io/cogen/)

+ [UniScene: Unified Occupancy-centric Driving Scene Generation](https://arxiv.org/abs/2412.05435) (2024-12-06)
[![Code](https://img.shields.io/github/stars/Arlo0o/UniScene-Unified-Occupancy-centric-Driving-Scene-Generation.svg?style=social&label=Official)](https://github.com/Arlo0o/UniScene-Unified-Occupancy-centric-Driving-Scene-Generation)
[![Website](https://img.shields.io/badge/Website-9cf)](https://arlo0o.github.io/uniscene/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/Arlolo0/UniScene/tree/main)

+ [Seeing Beyond Views: Multi-View Driving Scene Video Generation with Holistic Attention](https://arxiv.org/abs/2412.03520) (2024-12-04)
[![Website](https://img.shields.io/badge/Website-9cf)](https://luhannan.github.io/CogDrivingPage/)

+ [MyGo: Consistent and Controllable Multi-View Driving Video Generation with Camera Control](https://arxiv.org/abs/2409.06189) (2024-09-10) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://metadrivescape.github.io/papers_project/MyGo/page.html)

+ [DreamForge: Motion-Aware Autoregressive Video Generation for Multi-View Driving Scenes](https://arxiv.org/abs/2409.04003) (2024-09-06) 
[![Code](https://img.shields.io/github/stars/PJLab-ADG/DriveArena.svg?style=social&label=Official)](https://github.com/PJLab-ADG/DriveArena)
[![Website](https://img.shields.io/badge/Website-9cf)](https://pjlab-adg.github.io/DriveArena/dreamforge/)

+ [DiVE: DiT-based Video Generation with Enhanced Control](https://arxiv.org/abs/2409.01595) (2024-09-03) 
[![Code (to be released)](https://img.shields.io/github/stars/LiAutoAD/DIVE.svg?style=social&label=Official)](https://github.com/LiAutoAD/DIVE)
[![Website](https://img.shields.io/badge/Website-9cf)](https://liautoad.github.io/DIVE/)

+ [Unleashing Generalization of End-to-End Autonomous Driving with Controllable Long Video Generation](https://arxiv.org/abs/2406.01349) (2024-06-03)
[![Code (to be released)](https://img.shields.io/github/stars/westlake-autolab/Delphi.svg?style=social&label=Official)](https://github.com/westlake-autolab/Delphi)
[![Website](https://img.shields.io/badge/Website-9cf)](https://westlake-autolab.github.io/delphi.github.io/)

+ [SubjectDrive: Scaling Generative Data in Autonomous Driving via Subject Control](https://arxiv.org/abs/2403.19438) (2024-03-28) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://subjectdrive.github.io/)

+ [Panacea: Panoramic and Controllable Video Generation for Autonomous Driving](https://arxiv.org/abs/2311.16813) (2023-11-28) 
[![Code](https://img.shields.io/github/stars/wenyuqing/panacea.svg?style=social&label=Official)](https://github.com/wenyuqing/panacea)
[![Website](https://img.shields.io/badge/Website-9cf)](https://panacea-ad.github.io/)

+ [DrivingDiffusion: Layout-Guided multi-view driving scene video generation with latent diffusion model](https://arxiv.org/abs/2310.07771) (2023-10-11) 
[![Code](https://img.shields.io/github/stars/shalfun/DrivingDiffusion.svg?style=social&label=Official)](https://github.com/shalfun/DrivingDiffusion)
[![Website](https://img.shields.io/badge/Website-9cf)](https://drivingdiffusion.github.io/)

+ [MagicDrive: Street View Generation with Diverse 3D Geometry Control](https://arxiv.org/abs/2310.02601) (2023-10-04) 
[![Code](https://img.shields.io/github/stars/cure-lab/MagicDrive.svg?style=social&label=Official)](https://github.com/cure-lab/MagicDrive)
[![Website](https://img.shields.io/badge/Website-9cf)](https://gaoruiyuan.com/magicdrive/)
<a name="2.3.2."></a>
### 2.3.2 Instruction Navigation World Model

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

<a name="2.3.3."></a>
### 2.3.3 Trajectory Navigation World Model

+ [Other Vehicle Trajectories Are Also Needed: A Driving World Model Unifies  Ego-Other Vehicle Trajectories in Video Latent Space](https://arxiv.org/abs/2503.09215) (2025-03-12)

+ [DrivingWorld: Constructing World Model for Autonomous Driving via Video GPT](https://arxiv.org/abs/2412.19505) (2024-12-27)
[![Code](https://img.shields.io/github/stars/YvanYin/DrivingWorld.svg?style=social&label=Official)](https://github.com/YvanYin/DrivingWorld)
[![Website](https://img.shields.io/badge/Website-9cf)](https://huxiaotaostasy.github.io/DrivingWorld/index.html)

+ [Doe-1: Closed-Loop Autonomous Driving with Large World Model](https://arxiv.org/abs/2412.09627) (2024-12-12)
[![Code](https://img.shields.io/github/stars/wzzheng/Doe.svg?style=social&label=Official)](https://github.com/wzzheng/Doe)
[![Website](https://img.shields.io/badge/Website-9cf)](https://wzzheng.net/Doe/)

+ [ACT-BENCH:Towards Action Controllable World Models for Autonomous Driving](https://arxiv.org/abs/2412.05337) (2024-12-06)

<a name="2.3.4."></a>
### 2.3.4 Action Navigation World Model

+ [DrivingGPT: Unifying Driving World Modeling and Planning with Multi-modal Autoregressive Transformers](https://arxiv.org/abs/2412.18607) (2024-12-24)

+ [InfinityDrive: Breaking Time Limits in Driving World Models](https://arxiv.org/abs/2412.01522) (2024-12-02)
[![Website](https://img.shields.io/badge/Website-9cf)](https://metadrivescape.github.io/papers_project/InfinityDrive/page.html)

+ [WoVoGen: World Volume-aware Diffusion for Controllable Multi-camera Driving Scene Generation](https://arxiv.org/abs/2312.02934) (2023-12-05)
[![Code](https://img.shields.io/github/stars/fudan-zvg/WoVoGen.svg?style=social&label=Official)](https://github.com/fudan-zvg/WoVoGen)

+ [Driving into the Future: Multiview Visual Forecasting and Planning with World Model for Autonomous Driving](https://arxiv.org/abs/2311.17918) (2023-11-29)
[![Code](https://img.shields.io/github/stars/BraveGroup/Drive-WM.svg?style=social&label=Official)](https://github.com/BraveGroup/Drive-WM)
[![Website](https://img.shields.io/badge/Website-9cf)](https://drive-wm.github.io/)

+ [GAIA-1: A Generative World Model for Autonomous Driving](https://arxiv.org/abs/2309.17080) (2023-09-29)

+ [DriveDreamer: Towards Real-world-driven World Models for Autonomous Driving](https://arxiv.org/abs/2309.09777) (2023-09-18)
[![Code](https://img.shields.io/github/stars/JeffWang987/DriveDreamer.svg?style=social&label=Official)](https://drivedreamer.github.io/)

+ [Model-Based Imitation Learning for Urban Driving](https://arxiv.org/abs/2210.07729) (2022-10-14)
[![Code](https://img.shields.io/github/stars/wayveai/mile.svg?style=social&label=Official)](https://github.com/wayveai/mile)
[![Website](https://img.shields.io/badge/Website-9cf)](https://wayve.ai/thinking/learning-a-world-model-and-a-driving-policy/)

+ [Enhance Sample Efficiency and Robustness of End-to-end Urban Autonomous Driving via Semantic Masked World Model](https://arxiv.org/abs/2210.04017) (2022-10-08)

+ [Iso-Dream: Isolating and Leveraging Noncontrollable Visual Dynamics in World Models](https://arxiv.org/abs/2205.13817) (2022-05-27)

+ [DriveGAN: Towards a Controllable High-Quality Neural Simulation](https://arxiv.org/abs/2104.15060) (2021-04-30)

+ [Learning a Driving Simulator](https://arxiv.org/abs/1608.01230) (2016-08-03)




<a name="2.3.5."></a>
### 2.3.5 Hybrid Navigation World Model

+ [GAIA-2: A Controllable Multi-View Generative World Model for Autonomous Driving](https://arxiv.org/abs/2503.20523) (2025-03-26)
[![Website](https://img.shields.io/badge/Website-9cf)](https://wayve.ai/thinking/gaia-2/)

+ [MiLA: Multi-view Intensive-fidelity Long-term Video Generation World Model for Autonomous Driving](https://arxiv.org/abs/2503.15875) (2025-03-20)
[![Website](https://img.shields.io/badge/Website-9cf)](https://xiaomi-mlab.github.io/mila.github.io/) 

+ [MaskGWM: a Generalizable driving World Model embodied with Video Mask reconstruction](https://arxiv.org/abs/2502.11663) (2025-02-17)
[![Code](https://img.shields.io/github/stars/SenseTime-FVG/OpenDWM.svg?style=social&label=Official)](https://github.com/SenseTime-FVG/OpenDWM)

+ [GEM:AGeneralizable Ego-Vision Multimodal World Model for Fine-Grained Ego-Motion, Object Dynamics, and Scene Composition Control](https://arxiv.org/abs/2412.11198) (2024-12-15)
[![Code](https://img.shields.io/github/stars/vita-epfl/GEM.svg?style=social&label=Official)](https://github.com/vita-epfl/GEM)
[![Website](https://img.shields.io/badge/Website-9cf)](https://vita-epfl.github.io/GEM.github.io/)

+ [MagicDriveDiT: High-Resolution Long Video Generation for Autonomous Driving with Adaptive Control](https://arxiv.org/abs/2411.13807v1) (2024-11-21)
[![Website](https://img.shields.io/badge/Website-9cf)](https://gaoruiyuan.com/magicdrive-v2/)

+ [DriveScape: Towards High-Resolution Controllable Multi-View Driving Video Generation](https://arxiv.org/abs/2409.05463) (2024-09-09)
[![Website](https://img.shields.io/badge/Website-9cf)](https://metadrivescape.github.io/papers_project/drivescapev1/index.html)

+ [Vista: A Generalizable Driving World Model with High Fidelity and Versatile Controllability](https://arxiv.org/abs/2405.17398) (2024-05-27)
[![Code](https://img.shields.io/github/stars/OpenDriveLab/DriveAGI.svg?style=social&label=Official)](https://github.com/OpenDriveLab/DriveAGI)
[![Website](https://img.shields.io/badge/Website-9cf)](https://opendrivelab.com/Vista/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/OpenDriveLab/Vista)

+ [MagicDrive3D: Controllable 3D Generation for Any-View Rendering in Street Scenes](https://arxiv.org/abs/2405.14475) (2024-05-23)
[![Code](https://img.shields.io/github/stars/flymin/MagicDrive3D.svg?style=social&label=Official)](https://github.com/flymin/MagicDrive3D)
[![Website](https://img.shields.io/badge/Website-9cf)](https://gaoruiyuan.com/magicdrive3d/)



+ [GenAD: Generalized Predictive Model for Autonomous Driving](https://arxiv.org/abs/2403.09630) (2024-03-14)
[![Code](https://img.shields.io/github/stars/OpenDriveLab/DriveAGI.svg?style=social&label=Official)](https://github.com/OpenDriveLab/DriveAGI)



<a name="2.3.6."></a>
### 2.3.6 Other Navigation World Model

+ [Seeing the Future, Perceiving the Future: A Unified Driving World Model for Future Generation and Perception](https://arxiv.org/abs/2503.13587) (2025-03-17)
[![Code](https://img.shields.io/github/stars/dk-liang/UniFuture.svg?style=social&label=Official)](https://github.com/dk-liang/UniFuture)
[![Website](https://img.shields.io/badge/Website-9cf)](https://dk-liang.github.io/UniFuture/)

+ [Physical Informed Driving World Model](https://arxiv.org/abs/2412.08410) (2024-12-11)
[![Website](https://img.shields.io/badge/Website-9cf)](https://metadrivescape.github.io/papers_project/DrivePhysica/page.html)

+ [Generative Camera Dolly: Extreme Monocular Dynamic Novel View Synthesis](https://arxiv.org/abs/2405.14868) (2024-05-23)
   ><i>Note: with relative camera  extrinsics navigation</i>


<a name="2.4."></a>
## 2.4 Video Generation as World Model in Gaming
<a name="2.4.1."></a>
### 2.4.1 Game Controller Navigation World Model

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

<a name="2.4.2."></a>
### 2.4.2 Keyboard Navigation World Model

+ [The Matrix: Infinite-Horizon World Generation with Real-Time Moving Control](https://arxiv.org/abs/2412.03568) (2024-12-04)
[![Website](https://img.shields.io/badge/Website-9cf)](https://thematrix1999.github.io/)

+ [GameGen-X: Interactive Open-world Game Video Generation](https://arxiv.org/abs/2411.00769) (2024-11-01)
[![Code](https://img.shields.io/github/stars/GameGen-X/GameGen-X.svg?style=social&label=Official)](https://github.com/GameGen-X/GameGen-X)
[![Website](https://img.shields.io/badge/Website-9cf)](https://gamegen-x.github.io/)

+ [Diffusion Models Are Real-Time Game Engines](https://arxiv.org/abs/2408.14837) (2024-08-27)
[![Website](https://img.shields.io/badge/Website-9cf)](https://gamengen.github.io/)

+ [Learning to Simulate Dynamic Environments with GameGAN](https://arxiv.org/abs/2005.12126) (2020-05-25)
[![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/gameGAN/)

<a name="2.4.3."></a>
### 2.4.3 Keyboard & Mouse Navigation World Model

+ [MineWorld: a Real-Time and Open-Source Interactive World Model on Minecraft](https://arxiv.org/abs/2504.08388) (2025-04-11)
[![Code](https://img.shields.io/github/stars/microsoft/MineWorld.svg?style=social&label=Official)](https://github.com/microsoft/MineWorld)


+ [GameFactory: Creating New Games with Generative Interactive Videos](https://arxiv.org/abs/2501.08325) (2025-01-14)
[![Code](https://img.shields.io/github/stars/KwaiVGI/GameFactory.svg?style=social&label=Official)](https://github.com/KwaiVGI/GameFactory)
[![Website](https://img.shields.io/badge/Website-9cf)](https://yujiwen.github.io/gamefactory/)

+ [3DTrajMaster: Mastering 3D Trajectory for Multi-Entity Motion in Video Generation](https://arxiv.org/abs/2412.07759) (2024-12-10)
[![Code](https://img.shields.io/github/stars/KwaiVGI/3DTrajMaster.svg?style=social&label=Official)](https://github.com/KwaiVGI/3DTrajMaster)
[![Website](https://img.shields.io/badge/Website-9cf)](https://fuxiao0719.github.io/projects/3dtrajmaster/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/datasets/KwaiVGI/360Motion-Dataset)

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

<a name="2.4.4."></a>
### 2.4.4 Action Trajectory Navigation World Model

+ [Pre-Trained Video Generative Models as World Simulators](https://arxiv.org/abs/2502.07825) (2025-02-10)

<a name="2.4.5."></a>
### 2.4.5 Signal Command Navigation World Model

+ [WORLDMEM: Long-term Consistent World Simulation with Memory](https://arxiv.org/abs/2504.12369) (2025-04-16)
[![Code](https://img.shields.io/github/stars/xizaoqu/WorldMem.svg?style=social&label=Official)](https://github.com/xizaoqu/WorldMem)
[![Website](https://img.shields.io/badge/Website-9cf)](https://xizaoqu.github.io/worldmem/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/yslan/worldmem)

+ [Transformer-based World Models Are Happy With 100k Interactions](https://arxiv.org/abs/2303.07109) (2023-03-13)
[![Code](https://img.shields.io/github/stars/jrobine/twm.svg?style=social&label=Official)](https://github.com/jrobine/twm)

+ [Mastering Diverse Domains through World Models](https://arxiv.org/abs/2301.04104) (2023-01-10)
[![Code](https://img.shields.io/github/stars/danijar/dreamerv3.svg?style=social&label=Official)](https://github.com/danijar/dreamerv3)
[![Website](https://img.shields.io/badge/Website-9cf)](https://danijar.com/project/dreamerv3/)

+ [Transformers are Sample-Efficient World Models](https://arxiv.org/abs/2209.00588) (2022-09-05)
[![Code](https://img.shields.io/github/stars/eloialonso/iris.svg?style=social&label=Official)](https://github.com/eloialonso/iris)


+ [Mastering Atari with Discrete World Models](https://arxiv.org/abs/2010.02193) (2020-10-05)
[![Code](https://img.shields.io/github/stars/danijar/dreamerv2.svg?style=social&label=Official)](https://github.com/danijar/dreamerv2)
[![Website](https://img.shields.io/badge/Website-9cf)](https://danijar.com/project/dreamerv2/)

+ [Dream to Control: Learning Behaviors by Latent Imagination](https://arxiv.org/abs/1912.01603) (2019-12-03)
[![Code](https://img.shields.io/github/stars/danijar/dreamer.svg?style=social&label=Official)](https://github.com/danijar/dreamer)
[![Website](https://img.shields.io/badge/Website-9cf)](https://danijar.com/project/dreamer/)


+ [Recurrent Environment Simulators](https://arxiv.org/abs/1704.02254) (2017-04-07)


<a name="2.4.6."></a>
### 2.4.6 Multiple Navigation World Model

+ [Promptable Game Models: Text-Guided Game Simulation via Masked Diffusion Models](https://arxiv.org/abs/2303.13472) (2023-03-23)
[![Website](https://img.shields.io/badge/Website-9cf)](https://snap-research.github.io/promptable-game-models/)


+ [Playable Environments: Video Manipulation in Space and Time](https://arxiv.org/abs/2203.01914) (2022-03-03)
[![Code](https://img.shields.io/github/stars/willi-menapace/PlayableEnvironments.svg?style=social&label=Official)](https://github.com/willi-menapace/PlayableEnvironments)
[![Website](https://img.shields.io/badge/Website-9cf)](https://willi-menapace.github.io/playable-environments-website/)


<a name="2.4.7."></a>
### 2.4.7 Other Navigation World Model

+ [AdaWorld: Learning Adaptable World Models with Latent Actions](https://arxiv.org/abs/2503.18938) (2025-03-24)
[![Code](https://img.shields.io/github/stars/Little-Podi/AdaWorld.svg?style=social&label=Official)](https://github.com/Little-Podi/AdaWorld)
[![Website](https://img.shields.io/badge/Website-9cf)](https://adaptable-world-model.github.io/)


<a name="3."></a>
# 3. Generation-3: Intrinsic Planning
<a name="3.1."></a>
## 3.1 Macroscopic planning World Model
<a name="3.2."></a>
## 3.2 Physical-Aligned planning World Model
<a name="3.3."></a>
## 3.3 Microscopic planning World Model

<a name="4."></a>
# 4. Generation-4: Black Swan Modeling
