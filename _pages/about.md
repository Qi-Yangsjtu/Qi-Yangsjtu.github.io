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

I am a postdoctoral researcher of [Multimedia Computing & Communication (MCC) Lab] at the University of Missouri - Kansas City. Before that, I received my PhD from [Shanghai Jiao Tong University (SJTU)](https://en.sjtu.edu.cn/), and bachelor degree from [Xidian University](https://en.xidian.edu.cn/).

I am currently advised by [Prof. Zhu Li]([https://ziweiwangthu.github.io/](https://l.web.umkc.edu/lizhu/)), and working closely with [Dr. Geert Van Der Auwera](https://rui-ye.github.io/](https://www.linkedin.com/in/geertvanderauwera/) and [Prof. Yiling Xu](https://scholar.google.com/citations?user=638kRwkAAAAJ&hl=en). My research interests include 3D Gaussian Splatting (GS) compact generation and compression, media quality assessment (i.e., 3D GS, 3D point cloud, and 3D mesh), and immersive media streaming.

## 🔥 News

- *2025.09*: TMQA is accepted by **TVCG**!
- *2025.06*: LINR-PCGC and MATE-3D are accepted by **ICCV 2025**!
- *2025.06*: Our survey on point cloud compression and quality assessment is released!
- *2024.05*: HybridGS is accepted by **ICML 2025**!
- *2025.04*: ADC-GS is accepted by **IJCAI 2025**!
- *2024.12*: Our mesh compression paper is selected as the best paper candidate by **VCIP 2024**!
- *2024.12*: AFQ-Net is accepted by **T-CSVT**!
- *2024.11*: GeodesicPSIM is accepted by **TIP**!
- *2024.10*: GGSC&GSQA and MS-GeodesicPSIM are accepted by **ACMM MM Asia 2024**!
- *2024.10*: PHM is accepted by **TIP**!
- *2024.09*: Joined MCC lab @ UMKC, founded by **Qualcomm**!
- *2024.09*: GLQI is accepted by **TOMM**!
- *2024.08*: TDMD is accepted by **TVCG**!
- *2024.03*: PAME is accepted by **ICME2024 (Oral)**! 
- *2024.02*: CoPA is accepted by **CVPR2024**!
- *2023.10*: TCDM is accepted by **TVCG**! 
- *2023.05*: GPA-Net is accepted by **TVCG**!
- *2023.02*: ResSCNN&LS-PCQA is accepted by **TOMM**!
- *2022.10*: MPED is accepted by **TPAMI**!
- *2022.02*: IT-PCQA is accepted by **CVPR2022**!
- *2021.10*: MS-GraphSIM is accepted by **ACM MM 2021 (Oral)**!
- *2020.12*: GraphSIM is accepted by **TPAMI**!
- *2020.10*: SJTU-PCQA is accepted by **TMM**!

## 📝 Selected Publications 

<sup>\*</sup> denotes equal contribution, <sup>†</sup> denotes corresponding author.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arixv</div><img src='images/survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Point Cloud Compression and Objective Quality Assessment: A Survey

Yiling Xu<sup>†</sup>, Yujie Zhang, Shuting Xia, Kaifa Yang, He Huang, **Ziyu Shan**, Wenjie Huang, Qi Yang, Le Yang

- [**\[pdf\]**](https://arxiv.org/abs/2506.22902)
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS</div><img src='images/dispa.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Learning Disentangled Representations for Perceptual Point Cloud Quality Assessment via Mutual Information Minimization

- **Ziyu Shan**<sup>\*</sup>, Yujie Zhang<sup>\*</sup>, Yipeng Liu, Yiling Xu<sup>†</sup>

- [**\[pdf\]**](https://arxiv.org/abs/2411.07936) [**\[code\]**](https://github.com/zyshan0929/PAME)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR</div><img src='images/CoPA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


Contrastive Pre-Training with Multi-View Fusion for No-Reference Point Cloud Quality Assessment

- **Ziyu Shan**, Yujie Zhang, Qi Yang, Haichen Yang, Yiling Xu<sup>†</sup>, Jenq-Neng Hwang, Xiaozhong Xu, Shan Liu

- [**\[pdf\]**](https://arxiv.org/abs/2403.10066) [**\[code\]**](https://github.com/zyshan0929/GPA-Net)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME</div><img src='images/PAME.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

PAME: Self-Supervised Masked Autoencoder for No-Reference Point Cloud Quality Assessment <font color='red'> (Oral) </font>

- **Ziyu Shan**, Yujie Zhang, Qi Yang, Haichen Yang, Yiling Xu<sup>†</sup>, Shan Liu

- [**\[pdf\]**](https://arxiv.org/abs/2403.10061) [**\[code\]**](https://github.com/zyshan0929/PAME)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP</div><img src='images/MFT-PCQA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

MFT-PCQA: Multi-Modal Fusion Transformer for No-Reference Point Cloud Quality Assessment
- Yating Liu<sup>\*</sup>, **Ziyu Shan<sup>\*</sup>**, Yujie Zhang, Yiling Xu<sup>†</sup>

- [**\[pdf\]**](https://arxiv.org/abs/2210.16478)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TVCG</div><img src='images/GPA-Net.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

GPA-Net:No-Reference Point Cloud Quality Assessment with Multi-task Graph Convolutional Network

- **Ziyu Shan**<sup>\*</sup>, Qi Yang<sup>\*</sup>, Rui Ye, Yujie Zhang, Yiling Xu<sup>†</sup>, Xiaozhong Xu, Shan Liu

- [**\[pdf\]**](https://arxiv.org/abs/2210.16478)
</div>
</div>

## 🎖 Honors and Awards

- *2023* Outstanding Staff, Tencent Media Lab
- *2022* Outstanding Staff, Tencent Media Lab
- *2021.10* China National Scholarship for PhD students, Shanghai Jiao Tong University.
- *2020.06* Scholarship for Outstanding Graduate Students, CMIC of Shanghai Jiao Tong University
- *2019.06* Scholarship for Outstanding Graduate Students, CMIC of Shanghai Jiao Tong University
- *2019.02* Scholarship for Outstanding Graduate Students, CMIC of Shanghai Jiao Tong University
- *2020.6* Excellent Graduate Student, Xi'dian University.

## 💻 Services
- Reviewers for:
  - Journal
    - IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)
    - IEEE Transactions on Image Processing (TIP)
    - IEEE Transactions on Visualization and Computer Graphics (TVCG)
    - IEEE Transactions on MultiMedia (TMM)
    - IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)
    - ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM)
    - Elsevier Neurocomputing
  - Conference
    - International Conference on Learning Representation (ICLR)
    - International Conference on Machine Learning (ICML)
    - Annual Conference on Neural Information Processing Systems (NeurIPS)
    - IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
    - IEEE/CVF International Conference on Computer Vision (ICCV)
    - European Conference on Computer Vision (ECCV)
    - International Joint Conference on Artificial Intelligence (IJCAI)
    - Association for the Advancement of Artificial Intelligence (AAAI)
    - ACM International Conference on Multimedia (ACM MM)
    - IEEE International Conference on Multimedia and Expo (ICME)
    - IEEE International Conference on Image Processing (ICIP)
    - IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)
    - IEEE International Conference on Visual Communications and Image Processing (VCIP)

