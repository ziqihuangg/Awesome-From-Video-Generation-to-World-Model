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
  - [1.1. Stable Diffusion Based Video Generation](#1.1.)
  - [1.2. DiT Based Video Generation](#1.2.)
  - [1.3. Autoregressive Based Video Generation](#1.3.)
  - [1.4. Other Based Video Generation](#1.4.)
- [2. Video Generation for World Model in Robotics](#2.)
  - [2.1. Action Navigation World Model](#2.1.)
  - [2.2. Instruction Navigation World Model](#2.2.)
  - [2.3. Motion Navigation World Model](#2.3.)
  - [2.4. Other Navigation World Model](#2.4.)
- [3. Video Generation for World Model in Autonomous Driving](#3.)
  - [3.1. Instruction Navigation World Model](#3.1.)
  - [3.2. Trajectory Navigation World Model](#3.2.)
  - [3.3. Action Navigation World Model](#3.3.)
  - [3.4. Layout Navigation World Model](#3.4.)
  - [3.5. Hybrid Navigation World Model](#3.5.)
  - [3.6. World Model without Navigation](#3.6.)
- [4. Video Generation for World Model in Gaming](#4.)
  - [4.1. Action Navigation World Model](#4.1.)
  - [4.2. Instruction Navigation World Model](#4.2.)
  - [4.3. Other Navigation World Model](#4.3.)
 
<a name="1."></a>
## 1. Video Generation for World Model in General Scenes
<a name="1.1."></a>
### 1.1. Stable Diffusion Based Video Generation

+ [GEM:AGeneralizable Ego-Vision Multimodal World Model for Fine-Grained
 Ego-Motion, Object Dynamics, and Scene Composition Control](https://arxiv.org/pdf/2412.11198) (2024-12-15) 
[![Code](https://img.shields.io/github/stars/vita-epfl/GEM.svg?style=social&label=Official)](https://github.com/vita-epfl/GEM)
[![Website](https://img.shields.io/badge/Website-9cf)](https://vita-epfl.github.io/GEM.github.io/) 

+ [ReCapture: Generative Video Camera Controls for User-Provided Videos using Masked Video Fine-Tuning](https://arxiv.org/abs/2411.05003) (2024-11-07) 
  ><i>Note: with camera trajectory navigation</i>

+ [SlowFast-VGen: Slow-Fast Learning for Action-driven Long Video Generation](https://arxiv.org/abs/2410.23277) (2024-10-30) 
[![Code (to be released)](https://img.shields.io/github/stars/slowfast-vgen/slowfast-vgen.svg?style=social&label=Official)](https://github.com/slowfast-vgen/slowfast-vgen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://slowfast-vgen.github.io/)

+ [Generative Camera Dolly: Extreme Monocular Dynamic Novel View Synthesis](https://arxiv.org/pdf/2405.14868) (2024-05-23) 

+ [MagicTime: Time-lapse Video Generation Models as Metamorphic Simulators](https://arxiv.org/abs/2404.05014) (2024-04-07) 
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/MagicTime.svg?style=social&label=Official)](https://github.com/PKU-YuanGroup/MagicTime/tree/main)
[![Website](https://img.shields.io/badge/Website-9cf)](https://pku-yuangroup.github.io/MagicTime/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/BestWishYsh/MagicTime)

+ [AnimateLCM: Computation-Efficient Personalized Style Video Generation without Personalized Video Data](https://arxiv.org/abs/2402.00769) (2024-02-01) 
[![Code](https://img.shields.io/github/stars/G-U-N/AnimateLCM.svg?style=social&label=Official)](https://github.com/G-U-N/AnimateLCM)
[![Website](https://img.shields.io/badge/Website-9cf)](https://animatelcm.github.io/) 
[![Hugging Face Demo](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/wangfuyun/AnimateLCM-SVD)

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

+ [Pre-Trained Video Generative Models as World Simulators](https://arxiv.org/abs/2502.07825) (2025-02-10)

+ [IPO: Iterative Preference Optimization for Text-to-Video Generation](https://arxiv.org/abs/2502.02088) (2024-02-04) 
[![Code](https://img.shields.io/github/stars/SAIS-FUXI/IPO.svg?style=social&label=Official)](https://github.com/SAIS-FUXI/IPO) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://yangxlarge.github.io/ipoc//)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/Fudan-FUXI/IPOC-2B-v1.0)


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

+ [STIV: Scalable Text and Image Conditioned Video Generation](https://arxiv.org/abs/2412.07730) (2024-12-10)

+ [Navigation World Models](https://arxiv.org/abs/2412.03572) (2024-12-04)
[![Code](https://img.shields.io/github/stars/facebookresearch/nwm.svg?style=social&label=Official)](https://github.com/facebookresearch/nwm/)
[![Website](https://img.shields.io/badge/Website-9cf)](https://www.amirbar.net/nwm/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/facebook/nwm)


+ [Open-Sora Plan: Open-Source Large Video Generation Model](https://arxiv.org/abs/2412.00131) (2024-11-28) 
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/Open-Sora-Plan.svg?style=social&label=Official)](https://github.com/PKU-YuanGroup/Open-Sora-Plan)

+ [Allegro: Open the black box of commercial-level video generation model](https://arxiv.org/abs/2410.15458) (2024-10-20)
+ [![Code](https://img.shields.io/github/stars/rhymes-ai/Allegro.svg?style=social&label=Official)](https://github.com/rhymes-ai/Allegro)
[![Website](https://img.shields.io/badge/Website-9cf)](https://rhymes.ai/allegro_gallery)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/rhymes-ai/Allegro)

+ [Cogvideox:Text-to-video diffusion models with an expert transformer](https://arxiv.org/abs/2408.06072) (2024-08-12) 
[![Code](https://img.shields.io/github/stars/THUDM/CogVideo.svg?style=social&label=Official)](https://github.com/THUDM/CogVideo) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/THUDM/CogVideoX-5B-Space)

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

+ [Pre-Trained Video Generative Models as World Simulators](https://arxiv.org/abs/2502.07825) (2025-02-10)

+ [Cosmos World Foundation Model Platform for Physical AI](https://arxiv.org/abs/2501.03575) (2025-01-07) 
[![Code](https://img.shields.io/github/stars/nvidia-cosmos/cosmos-predict1.svg?style=social&label=Official)](https://github.com/nvidia-cosmos/cosmos-predict1)
[![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/dir/cosmos-predict1/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/nvidia/cosmos-predict1-67c9d1b97678dbf7669c89a7)

+ [Owl-1: Omni World Model for Consistent Long Video Generation](https://arxiv.org/abs/2412.09600) (2024-12-12) 
[![Code](https://img.shields.io/github/stars/huang-yh/Owl.svg?style=social&label=Official)](https://github.com/huang-yh/Owl)

+ [Pandora: Towards general world model with natural language actions and video states](https://arxiv.org/abs/2406.09455) (2024-06-12) 
[![Code](https://img.shields.io/github/stars/maitrix-org/Pandora.svg?style=social&label=Official)](https://github.com/maitrix-org/Pandora)
[![Website](https://img.shields.io/badge/Website-9cf)](https://world-model.maitrix.org/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/maitrix-org/Pandora)

+ [MAGVIT:Masked Generative Video Transformer](https://arxiv.org/abs/2212.05199) (2022-12-10) 
[![Code](https://img.shields.io/github/stars/google-research/magvit.svg?style=social&label=Official)](https://github.com/google-research/magvit)
[![Website](https://img.shields.io/badge/Website-9cf)](https://magvit.cs.cmu.edu/) 

<a name="1.4."></a>
### 1.4. Other Based Video Generation

+ [From Slow Bidirectional to Fast Autoregressive Video Diffusion Models](https://arxiv.org/abs/2412.07772) (2024-12-10) 
[![Code](https://img.shields.io/github/stars/tianweiy/CausVid.svg?style=social&label=Official)](https://github.com/tianweiy/CausVid)
[![Website](https://img.shields.io/badge/Website-9cf)](https://causvid.github.io/) 

+ [WorldDreamer: Towards General World Models for Video Generation via Predicting Masked Tokens](https://arxiv.org/abs/2401.09985) (2024-01-18) 
[![Code](https://img.shields.io/github/stars/JeffWang987/WorldDreamer.svg?style=social&label=Official)](https://github.com/JeffWang987/WorldDreamer)
[![Website](https://img.shields.io/badge/Website-9cf)](https://world-dreamer.github.io/) 


<a name="2."></a>
## 2. Video Generation for World Model in Robotics
<a name="2.1."></a>
### 2.1. Action Navigation World Model

+ [Pre-Trained Video Generative Models as World Simulators](https://arxiv.org/abs/2502.07825) (2025-02-10)

+ [Navigation World Models](https://arxiv.org/abs/2412.03572) (2024-12-04)
[![Code](https://img.shields.io/github/stars/facebookresearch/nwm.svg?style=social&label=Official)](https://github.com/facebookresearch/nwm/)
[![Website](https://img.shields.io/badge/Website-9cf)](https://www.amirbar.net/nwm/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/facebook/nwm)

+ [IRASim: Learning Interactive Real-Robot Action Simulators](https://arxiv.org/abs/2406.14540) (2024-06-20)
[![Code](https://img.shields.io/github/stars/bytedance/IRASim.svg?style=social&label=Official)](https://github.com/bytedance/IRASim)
[![Website](https://img.shields.io/badge/Website-9cf)](https://gen-irasim.github.io/)

<a name="2.2."></a>
### 2.2. Instruction Navigation World Model

+ [SlowFast-VGen: Slow-Fast Learning for Action-driven Long Video Generation](https://arxiv.org/abs/2410.23277) (2024-10-30) 
[![Code (to be released)](https://img.shields.io/github/stars/slowfast-vgen/slowfast-vgen.svg?style=social&label=Official)](https://github.com/slowfast-vgen/slowfast-vgen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://slowfast-vgen.github.io/) 

+ [EVA: An Embodied World Model for Future Video Anticipation](https://arxiv.org/abs/2410.15461) (2024-10-20) 


+ [Pandora: Towards general world model with natural language actions and video states](https://arxiv.org/abs/2406.09455) (2024-06-12) 
[![Code](https://img.shields.io/github/stars/maitrix-org/Pandora.svg?style=social&label=Official)](https://github.com/maitrix-org/Pandora)
[![Website](https://img.shields.io/badge/Website-9cf)](https://world-model.maitrix.org/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/maitrix-org/Pandora)

<a name="2.3."></a>
### 2.3. Motion Navigation World Model

+ [Learning Real-World Action-Video Dynamics with Heterogeneous Masked Autoregression](https://arxiv.org/abs/2502.04296) (2025-02-06) 
[![Code](https://img.shields.io/github/stars/liruiw/HMA.svg?style=social&label=Official)](https://github.com/liruiw/HMA)
[![Website](https://img.shields.io/badge/Website-9cf)](https://liruiw.github.io/hma/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/liruiw/hma-base-disc)


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

+ [WorldDreamer: Towards General World Models for Video Generation via Predicting Masked Tokens](https://arxiv.org/abs/2401.09985) (2024-01-18) 
[![Code](https://img.shields.io/github/stars/JeffWang987/WorldDreamer.svg?style=social&label=Official)](https://github.com/JeffWang987/WorldDreamer)
[![Website](https://img.shields.io/badge/Website-9cf)](https://world-dreamer.github.io/)

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

<a name="3.4."></a>
### 3.4. Layout Navigation World Model

+ [CoGen: 3D Consistent Video Generation via Adaptive Conditioning for Autonomous Driving](https://arxiv.org/abs/2503.22231) (2025-05-28)
[![Website](https://img.shields.io/badge/Website-9cf)](https://xiaomi-research.github.io/cogen/)

+ [UniScene: Unified Occupancy-centric Driving Scene Generation](https://arxiv.org/abs/2412.05435) (2024-12-06)
[![Code](https://img.shields.io/github/stars/Arlo0o/UniScene-Unified-Occupancy-centric-Driving-Scene-Generation.svg?style=social&label=Official)](https://github.com/Arlo0o/UniScene-Unified-Occupancy-centric-Driving-Scene-Generation)
[![Website](https://img.shields.io/badge/Website-9cf)](https://arlo0o.github.io/uniscene/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/Arlolo0/UniScene/tree/main)

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

+ [DriveDreamer: Towards Real-world-driven World Models for Autonomous Driving](https://arxiv.org/abs/2309.09777) (2023-09-18)
[![Code](https://img.shields.io/github/stars/JeffWang987/DriveDreamer.svg?style=social&label=Official)](https://drivedreamer.github.io/)

<a name="3.6."></a>
### 3.6. World Model without Navigation

+ [Seeing the Future, Perceiving the Future: A Unified Driving World Model for Future Generation and Perception](https://arxiv.org/abs/2503.13587) (2025-03-17)
[![Code](https://img.shields.io/github/stars/dk-liang/UniFuture.svg?style=social&label=Official)](https://github.com/dk-liang/UniFuture)
[![Website](https://img.shields.io/badge/Website-9cf)](https://dk-liang.github.io/UniFuture/)

<a name="4."></a>
## 4. Video Generation for World Model in Gaming
<a name="4.1."></a>
### 4.1. Keyboard Navigation World Model
+ [Playable Video Generation](https://arxiv.org/abs/2101.12195) (2021-01-28)
[![Code](https://img.shields.io/github/stars/willi-menapace/PlayableVideoGeneration.svg?style=social&label=Official)](https://github.com/willi-menapace/PlayableVideoGeneration)
[![Website](https://img.shields.io/badge/Website-9cf)](https://willi-menapace.github.io/playable-video-generation-website/)

### 4.2. Instruction Navigation World Model

### 4.3. Other Navigation World Model







