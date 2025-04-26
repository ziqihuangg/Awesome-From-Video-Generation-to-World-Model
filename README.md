# Awesome From Video Generation to World Model

*This repository collects world model methods based on video generation task.*


### Table of Contents
- [1. Video Generation for World Model in General Scenes](#1.)
  - [1.1. Stable Diffusion Based Video Generation](#1.1.)
  - [1.2. DiT Based Video Generation](#1.2.)
  - [1.3. Autoregressive Based Video Generation](#1.3.)
  - [1.4. Other Based Video Generation](#1.4.)
- [2.  Video Generation for World Model in Robotics](#2.)
  - [2.1. Action Navigation World Model](#2.1.)
  - [2.2. Instruction Navigation World Model](#2.2.)
  - [2.3. Motion Navigation World Model](#2.3.)
  - [2.4. Other Navigation World Model](#2.4.)
- [3.  Video Generation for World Model in Autonomous Driving](#3.)
  - [3.1. Instruction Navigation World Model](#3.1.)
  - [3.2. Trajectory Navigation World Model](#3.2.)
  - [3.3. Action Navigation World Model](#3.3.)
  - [3.4. Layout Navigation World Model](#3.4.)
  - [3.5. Hybrid Navigation World Model](#3.5.)
  - [3.6.World Model without Navigation](#3.6.)
- [4.  Video Generation for World Model in Gaming](#4.)
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

+ [SlowFast-VGen: Slow-Fast Learning for Action-driven Long Video Generation](https://arxiv.org/abs/2410.23277) (2024-10-30) 
[![Code (to be released)](https://img.shields.io/github/stars/slowfast-vgen/slowfast-vgen.svg?style=social&label=Official)](https://github.com/slowfast-vgen/slowfast-vgen)
[![Website](https://img.shields.io/badge/Website-9cf)](https://slowfast-vgen.github.io/) 

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

+ [ModelScope Text-to-Video Technical Report](https://arxiv.org/abs/2308.06571) (2023-8-12) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://modelscope.cn/models/iic/text-to-video-synthesis/summary)

+ [AnimateDiff: Animate Your Personalized Text-to-Image Diffusion Models without Specific Tuning](https://arxiv.org/abs/2307.04725) (2023-07-10) 
[![Code](https://img.shields.io/github/stars/guoyww/AnimateDiff.svg?style=social&label=Official)](https://github.com/guoyww/AnimateDiff)
[![Website](https://img.shields.io/badge/Website-9cf)](https://animatediff.github.io/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/guoyww/AnimateDiff)

+ [Diffusion Models for Video Prediction and Infilling](https://arxiv.org/abs/2206.07696) (2022-06-15) 
[![Code](https://img.shields.io/github/stars/Tobi-r9/RaMViD.svg?style=social&label=Official)](https://github.com/Tobi-r9/RaMViD)
[![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/video-diffusion-prediction)

<a name="1.2."></a>
### 1.2. DiT Based Video Generation

+ [AETHER: Geometric-Aware Unified World Modeling](https://arxiv.org/abs/2503.18945) (2025-03-24)
+ [![Code](https://img.shields.io/github/stars/OpenRobotLab/Aether.svg?style=social&label=Official)](https://github.com/OpenRobotLab/Aether)
[![Website](https://aether-world.github.io/)]

+ [Cosmos-Transfer1: Conditional World Generation with Adaptive Multimodal Control](https://arxiv.org/abs/2503.14492) (2025-03-18)
+ [![Code](https://img.shields.io/github/stars/nvidia-cosmos/cosmos-transfer1.svg?style=social&label=Official)](https://github.com/nvidia-cosmos/cosmos-transfer1)
[![Website](https://research.nvidia.com/labs/dir/cosmos-transfer1/)]
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/nvidia/cosmos-transfer1-67c9d328196453be6e568d3e)

+ [WISA: World Simulator Assistant for Physics-Aware Text-to-Video Generation](https://arxiv.org/abs/2503.08153) (2025-03-11)
+ [![Code](https://img.shields.io/github/stars/360CVGroup/WISA.svg?style=social&label=Official)](https://github.com/360CVGroup/WISA)
[![Website](https://360cvgroup.github.io/WISA/)]

+ [Pre-Trained Video Generative Models as World Simulators](https://arxiv.org/abs/2502.07825) (2025-02-10)

+ [Vchitect-2.0: Parallel trans former for scaling up video diffusion models](https://arxiv.org/abs/2501.08453) (2025-01-14) 

+ [Cosmos World Foundation Model Platform for Physical AI](https://arxiv.org/abs/2501.03575) (2025-01-07) 
[![Code](https://img.shields.io/github/stars/nvidia-cosmos/cosmos-predict1.svg?style=social&label=Official)](https://github.com/nvidia-cosmos/cosmos-predict1)
[![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/dir/cosmos-predict1/) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/collections/nvidia/cosmos-predict1-67c9d1b97678dbf7669c89a7)

+ [Open-sora: Democratizing efficient video production for all](https://arxiv.org/abs/2412.20404) (2024-12-29) 
[![Code](https://img.shields.io/github/stars/hpcaitech/Open-Sora.svg?style=social&label=Official)](https://github.com/hpcaitech/Open-Sora) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://hpcaitech.github.io/Open-Sora/) 

+ [Navigation World Models](https://arxiv.org/abs/2412.03572) (2024-12-04)
+ [![Code](https://img.shields.io/github/stars/facebookresearch/nwm.svg?style=social&label=Official)](https://github.com/facebookresearch/nwm/)
[![Website](https://www.amirbar.net/nwm/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/facebook/nwm)


+ [Open-Sora Plan: Open-Source Large Video Generation Model](https://arxiv.org/abs/2412.00131) (2024-11-28) 
[![Code](https://img.shields.io/github/stars/PKU-YuanGroup/Open-Sora-Plan.svg?style=social&label=Official)](https://github.com/PKU-YuanGroup/Open-Sora-Plan)

+ [Allegro: Open the black box of commercial-level video generation model](https://arxiv.org/abs/2410.15458) (2024-10-20)
+ [![Code](https://img.shields.io/github/stars/rhymes-ai/Allegro.svg?style=social&label=Official)](https://github.com/rhymes-ai/Allegro)
[![Website](https://rhymes.ai/allegro_gallery)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/rhymes-ai/Allegro)

+ [Cogvideox:Text-to-video diffusion models with an expert transformer](https://arxiv.org/abs/2408.06072) (2024-08-12) 
[![Code](https://img.shields.io/github/stars/THUDM/CogVideo.svg?style=social&label=Official)](https://github.com/THUDM/CogVideo) 
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/THUDM/CogVideoX-5B-Space)

+ [T2v-turbo: Breaking the quality bottleneck of video consistency model with mixed reward feedback](https://arxiv.org/abs/2405.18750) (2024-05-29)
+ [![Code](https://img.shields.io/github/stars/Ji4chenLi/t2v-turbo.svg?style=social&label=Official)](https://github.com/Ji4chenLi/t2v-turbo)
[![Website](https://t2v-turbo.github.io/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/TIGER-Lab/T2V-Turbo)

+ [Easyanimate: A  high-performance long video generation method based on  transformer architecture](https://arxiv.org/abs/2405.18991) (2024-05-29)
+ [![Code](https://img.shields.io/github/stars/aigc-apps/EasyAnimate.svg?style=social&label=Official)](https://github.com/aigc-apps/EasyAnimate)
[![Website](https://easyanimate.github.io/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue)](https://huggingface.co/spaces/alibaba-pai/EasyAnimate)

+ [Videocrafter2:Overcoming data limitations for high-quality video diffusion models](https://arxiv.org/abs/2401.09047) (2024-01-17) 
[![Code](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Official)](https://github.com/AILab-CVC/VideoCrafter)
[![Website](https://img.shields.io/badge/Website-9cf)](https://ailab-cvc.github.io/videocrafter2/)

+ [Latte: Latent Diffusion Transformer for Video Generation](https://arxiv.org/abs/2401.03048) (2024-01-05) 
[![Code](https://img.shields.io/github/stars/hpcaitech/Open-Sora.svg?style=social&label=Official)](https://github.com/hpcaitech/Open-Sora) 
[![Website](https://img.shields.io/badge/Website-9cf)](https://hpcaitech.github.io/Open-Sora/) 

+ [Videocrafter1: Open diffusion models for high-quality video generation](https://arxiv.org/abs/2310.19512) (2023-10-30) 
[![Code](https://img.shields.io/github/stars/AILab-CVC/VideoCrafter.svg?style=social&label=Official)](https://github.com/AILab-CVC/VideoCrafter)




