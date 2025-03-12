---
permalink: /
title: 
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am Zhendong. This homepage introduces myself and my previous research projects. 

Biography
======
I am a rising third-year master's student in Electronic Information Engineering at the University of Electronic Sci. and Tech. of China, advised by Professor Le Zhang. My research focuses on ubiquitous computing, wireless sensing and human action analysis. I had developed a model for untrimmed, long-term signal's temporal action detection. Additionally, I am actively exploring advancements in indoor localization. 

---
我是CS PhD。在此之前，我在电子科技大学AVC2 Lab完成了硕士学位，掌握着时间序列分析和计算机视觉的知识。我的研究兴趣在AIoT领域，具体来说它聚焦于两个方面：（1）开发高可用性的环境感知算法。（2）开发高效、长期人类行为理解算法。我的研究可以实现普适的人机交互，智能健康等应用。
---

Research Projects
======
Temporal Action Detection in WiFi CSI & IMU

![TAD model outputs](/images/tad.jpg)


| Model    | mAP_0.3 | mAP_0.4 | mAP_0.5 | mAP_0.6 | mAP_0.7 | **mAP_avg** | GFlops | Time/ms |
|----------|---------|---------|---------|---------|---------|-------------|--------|---------|
| SOTA_Baseline | 66.8    | 64.2    | 62.4    | 56.4    | 40.1    | 58.0        | 304.0  | 106.0   |
| **Ours** | **85.5**| **83.0**| **77.3**| **72.1**| **54.5**| **74.5**    | **44.1**| **61.8**    |

*Comparison of the model mAPs, GFLOPs, and inference time(ms) of different methods.*

![Error Analysis](/images/error.jpg)

Future Work
======

The application of Temporal Action Detection (TAD) is currently limited. I am interested in combining TAD with other practical researches to create a multi-modal model for ambient intelligence that can be integrated into human–computer interaction devices.
