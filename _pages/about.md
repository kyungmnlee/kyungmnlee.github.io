---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
I am PhD student at KAIST AI working with professor <a href="https://alinlab.kaist.ac.kr/shin.html">Jinwoo Shin</a>.
Previously, I interned at Google DeepMind working with <a href="https://research.google/people/yinxiaoli/?&type=google">Yinxiao Li</a> and <a href="https://sites.google.com/view/feng-yang">Feng Yang</a>. I also closely worked with <a href="https://sites.google.com/site/kihyuksml/">Kihyuk Sohn</a> via Google University Relation program.

My research interests span probabilistic machine learning, generative modeling, representation learning and their applications. Recently, I am interested in visual generative models and their adaptations such as 3D generative modeling, personalization, and preference learning.

Email: *kyungmnlee (at) kaist (dot) ac (dot) kr* \| [Curriculum Vitae](https://drive.google.com/file/d/1XxunqZrXfL9gef-KC_s9N4QRfZP-tFI0/view?usp=sharing)

# 📝 Publications 

- `CVPR 2025` [Calibrated Multi-Preference Optimization for Aligning Diffusion Models](https://arxiv.org/abs/2502.02588), 
**Kyungmin Lee**, Xiaohang Li, Qifei Wang, Junfeng He, Ming-Hsuan Yang, Irfan Essa, Jinwoo Shin, Feng Yang and Yinxiao Li.
<div style="margin-top: 10px;"></div>

- `ICLR 2025` [DiffusionGuard: A Robust Defense Against Malicious Diffusion-based Image Editing](https://arxiv.org/abs/2410.05694), Junesuk Choi, **Kyungmin Lee**, Jongheon Jeong, Saining Xie, Jinwoo Shin and Kimin Lee. 
[![](https://img.shields.io/github/stars/choi403/DiffusionGuard?style=social&label=Stars)](https://github.com/choi403/DiffusionGuard)
<div style="margin-top: 10px;"></div>

- `NeurIPS 2024` [Direct Consistency Optimization for Robust Text-to-Image Personalization](https://arxiv.org/abs/2402.12004), **Kyungmin Lee**, Sangkyung Kwak, Kihyuk Sohn and Jinwoo Shin. 
[Project page](https://kyungmnlee.github.io/dco/) 
| [![](https://img.shields.io/github/stars/kyungmnlee/dco?style=social&label=Stars)](https://github.com/kyungmnlee/dco)
<div style="margin-top: 10px;"></div>

- `ECCV 2024` [Improving Diffusion Models for Authentic Virtual Try-on in the Wild](https://arxiv.org/abs/2403.05139), Yisol Choi, SangKyung Kwak, **Kyungmin Lee**, Hyungwon Choi and Jinwoo Shin. 
[Project page](https://idm-vton.github.io/) 
| [![](https://img.shields.io/github/stars/yisol/IDM-VTON?style=social&label=Stars)](https://github.com/yisol/IDM-VTON)
| [![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-blue?label=Demo)](https://huggingface.co/spaces/yisol/IDM-VTON)

<div style="margin-top: 10px;"></div>

- `CVPR 2024`<span style="color:red">(Highlight)</span> [Discovering and Mitigating Visual Biases through Keyword Explanation](https://arxiv.org/abs/2301.11104), 
Younghyun Kim, Sangwoo Mo, Minkyu Kim, **Kyungmin Lee**, Jaeho Lee and Jinwoo Shin.
[![](https://img.shields.io/github/stars/alinlab/b2t?style=social&label=Stars)](https://github.com/alinlab/b2t)
<div style="margin-top: 10px;"></div>

- `ICLR 2024`<span style="color:red">(Spotlight)</span> [DreamFlow: High-quality Text-to-3D generation by Approximating Probability Flow](https://arxiv.org/abs/2403.14966), 
**Kyungmin Lee**, Kihyuk Sohn and Jinwoo Shin.
[Project page](https://kyungmnlee.github.io/dreamflow.github.io/)
<div style="margin-top: 10px;"></div>

- `NeurIPS 2023 Workshop` [Fine-tuning Protein Language Models by ranking protein fitness](https://openreview.net/forum?id=DUjUJCqqA7), 
Minji Lee, **Kyungmin Lee** and Jinwoo Shin.
[![](https://img.shields.io/github/stars/haewonc/align-plm?style=social&label=Stars)](https://github.com/haewonc/align-plm)
<div style="margin-top: 10px;"></div>

- `NeurIPS 2023`[Collaborative Score Distillation for Consistent Visual Editing](https://arxiv.org/abs/2307.04787), 
Subin Kim*, **Kyungmin Lee\***, Junesuk Choi, Jongheon Jeong, Kihyuk Sohn and Jinwoo Shin.
[Project page](https://subin-kim-cv.github.io/CSD/)
| [![](https://img.shields.io/github/stars/subin-kim-cv/CSD?style=social&label=Stars)](https://github.com/subin-kim-cv/CSD)
<div style="margin-top: 10px;"></div>

- `NeurIPS 2023`[S-CLIP: Semi-supervised Vision-Language Pre-training using Few Specialist Captions](https://arxiv.org/abs/2305.14095), 
Sangwoo Mo, Minkyu Kim, **Kyungmin Lee** and Jinwoo Shin.
[![](https://img.shields.io/github/stars/alinlab/s-clip?style=social&label=Stars)](https://github.com/alinlab/s-clip)
<div style="margin-top: 10px;"></div>

- `NeurIPS 2023`[Slimmed Asymmetrical Contrastive Learning and Cross Distillation for Lightweight Model Training](https://proceedings.neurips.cc/paper_files/paper/2023/file/8393d955a00c463a982cefe77d0404e1-Paper-Conference.pdf), 
Jian Meng, Li Yang, **Kyungmin Lee**, Jinwoo Shin, Deliang Fan and Jae-sun Seo.
<div style="margin-top: 10px;"></div>

- `ICLR 2023`<span style="color:red">(Spotlight)</span> [STUNT: Few-shot Tabular Learning with Self-generated Tasks from Unlabeled Tables](https://arxiv.org/abs/2303.00918), 
Jaehyun Nam, Jihoon Tack, **Kyungmin Lee**, Hankook Lee and Jinwoo Shin.
[![](https://img.shields.io/github/stars/jaehyun513/STUNT?style=social&label=Stars)](https://github.com/jaehyun513/STUNT)
<div style="margin-top: 10px;"></div>

- `NeurIPS 2022` [RényiCL: Contrastive Representation Learning with Skew Rényi divergence](https://arxiv.org/abs/2208.06270),
**Kyungmin Lee** and Jinwoo Shin. 
[![](https://img.shields.io/github/stars/kyungmnlee/RenyiCL?style=social&label=Stars)](https://github.com/kyungmnlee/RenyiCL)
<div style="margin-top: 10px;"></div>

- `ECCV 2022` [GCISG: Guided Causal Invariant Learning for Improved Syn-to-Real Generalization](https://arxiv.org/abs/2208.10024),
Gilhyun Nam, Gyeongjae Choi and **Kyungmin Lee**.
<div style="margin-top: 10px;"></div>

- `ICLR 2022` [Representation Distillation by Prototypical Contrastive Predictive Coding](https://openreview.net/pdf?id=8la28hZOwug),
**Kyungmin Lee**
<div style="margin-top: 10px;"></div>

- `IJCAI 2022` [Pseudo-spherical Knowledge Distillation](https://www.ijcai.org/proceedings/2022/0441.pdf),
**Kyungmin Lee** and Hyeongkeun Lee.
<div style="margin-top: 10px;"></div>

- `ICLR 2021 Workshop` [Provable Defense by Denoised Smoothing with Learned Score function](https://aisecure-workshop.github.io/aml-iclr2021/papers/28.pdf),
**Kyungmin Lee**
<div style="margin-top: 10px;"></div>


# 💻 Work Experience
- *2024.07 - 2024.12*, Google DeepMind, Student Researcher, Mountain View, CA, US.
- *2023.02 - 2024.03*, Google Research, University Relation Program, Remote.
- *2019.04 - 2022.06*, Agency for Defense Development, Researcher, Daejeon, Korea.

# 🤝 Academic Services
- Conference reviewer: `NeurIPS`, `ICML`, `ICLR`, `CVPR`, `ICCV`, `ECCV`, `WACV`, `AISTATS`
- Journal reviewer: `TMLR`

# 📖 Educations
- *2022.09 - 2026.08*, KAIST, Ph.D. in Artificial Intelligence (expected).
- *2015.03 - 2019.02*, KAIST, B.S. in Mathematics, Electrical and Computer Engineering (double major).

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

