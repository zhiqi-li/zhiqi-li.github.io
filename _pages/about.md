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

I am a Research Scientist at **NVIDIA Research**, based in Singapore. Previously, I earned my Ph.D. in Computer Science from [Nanjing University](https://www.nju.edu.cn/).

My research focuses on **Vision-Language Models (VLMs)** and **Autonomous Driving Perception**. I have published 10+ papers（[Google Scholar](https://scholar.google.com/citations?hl=zh-CN&user=H2fJLqEAAAAJ)） at the top international AI conferences such as CVPR, ICCV, ECCV and etc. 

Currently, I am working on **frontier Vision-Language Models** at NVIDIA, collaborating with [Zhiding Yu](https://research.nvidia.com/person/zhiding-yu), [Guilin Liu](https://liuguilin1225.github.io/), and other outstanding researchers on **Project [Eagle](https://huggingface.co/collections/nvidia/eagle-2-6764ba887fa1ef387f7df067)**. Eagle is contributing to **NVIDIA Commercial VLMs** and [**NVIDIA Isaac GR00T N1**](https://github.com/NVIDIA/Isaac-GR00T).

Previously, I focused on **autonomous driving**, where I developed [**BEVFormer**](https://github.com/fundamentalvision/BEVFormer), a widely recognized method in the field. I have also won **three consecutive championships** in autonomous driving challenges at **CVPR 2022, 2023, and 2024**. 

I am also the first Ph.D. student from a Chinese institution awarded the [NVIDIA PhD Fellowship](https://research.nvidia.com/graduate-fellowships/2024).


# 🔥 News

- *2025-03*: [Eagle2](https://arxiv.org/pdf/2501.14818) has been adopted by NVIDIA GEAR Team to develop robotic foundation model [GR00T N1](https://research.nvidia.com/publication/2025-03_nvidia-isaac-gr00t-n1-open-foundation-model-humanoid-robots).

- *2025-01*: We present the frontier VLM, [Eagle2](https://arxiv.org/pdf/2501.14818) and the model weight has been released at [huggingface](https://huggingface.co/nvidia/Eagle2-9B).

- *2024-11*: [BEVFormer](https://www.computer.org/csdl/journal/tp/2025/03/10791908/22ABgP6PlUQ) was accepted at T-PAMI.

- *2024-06*: On CVPR 2024, our Team-NVIDIA won the outstanding champion and Innovation Award of [End-to-End Driving at Scale Challenge](https://opendrivelab.com/challenge2024/#end_to_end_driving_at_scale). Our Team at NJU-ImagineLab won the **True** outstanding champion of [Driving with Language](https://opendrivelab.com/challenge2024/#driving_with_language).

- *2024-02*: [BEV-Planner](https://arxiv.org/pdf/2312.03031.pdf) and [DCNv4](https://arxiv.org/pdf/2401.06197v1.pdf) were accpeted at CVPR 2024.

- *2023-11*: [VCD](https://arxiv.org/pdf/2310.15670.pdf) was accepted at NeurIPS 2023 and one [BEV Survey](https://arxiv.org/pdf/2209.05324) was accepted to TPAMI


- *2023-10*: [InternImage](https://arxiv.org/pdf/2211.05778.pdf) was selected as one of [CVPR 2023 Top-10 Influential Papers](https://www.paperdigest.org/2023/09/most-influential-cvpr-papers-2023-09/).


- *2023-07*: [FB-BEV](https://arxiv.org/pdf/2308.02236.pdf) was acceped at ICCV 2023

- *2023-06*: Our team wins both the outstanding champion and Innovation Award of [Occupancy Prediction Challenge](https://opendrivelab.com/AD23Challenge.html#Track3) (15,000+5,000 UDS Bonus) on CVPR2023.

- *2023-01*: [BEVFormer](https://arxiv.org/pdf/2203.17270.pdf) is selected as one of [ECCV 2022 Top-10
                        Influential Papers](https://www.paperdigest.org/2023/01/most-influential-eccv-papers-2023-01/) and [the 100 most cited AI papers in 2022](https://www.zeta-alpha.com/post/must-read-the-100-most-cited-ai-papers-in-2022)
- *2022-11*: We release [InternImage](https://arxiv.org/abs/2211.05778.pdf), setting a new record **65.4 box mAP** on COCO test-dev

- *2022-06*:  Our team wins the
                    champion of [Waymo 2022 3D Camera-Only Detection Task](https://waymo.com/open/challenges/2022/3d-camera-only-detection/) (15,000 USD Bonus)

# 📝 Publications and Reports

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/eagle2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Eagle 2: Building Post-Training Data Strategies from Scratch for Frontier Vision-Language Models](https://arxiv.org/pdf/2501.14818)

**Zhiqi Li**, Guo Chen, Shilong Liu, Shihao Wang, Vibashan VS, Yishen Ji, Shiyi Lan, Hao Zhang, Yilin Zhao, Subhashree Radhakrishnan, Nadine Chang, Karan Sapra, Amala Sanjay Deshmukh, Tuomas Rintamaki, Matthieu Le, Ilia Karmanov, Lukas Voegtle, Philipp Fischer, De-An Huang, Timo Roman, Tong Lu, Jose M Alvarez, Bryan Catanzaro, Jan Kautz, Andrew Tao, Guilin Liu, Zhiding Yu

[**PDF**](https://arxiv.org/pdf/2501.14818) [**code**](https://github.com/NVlabs/EAGLE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work focuses on developing open-source vision-language models by emphasizing data strategy in post-training, resulting in the performant Eagle2 models that achieve state-of-the-art results across various multimodal benchmarks.
</div>
</div>



# 🎖 Honors and Awards
  - *2024-06*: **True** outstanding champion of [Driving with Language](https://opendrivelab.com/challenge2024/#driving_with_language)
  - *2024-06*: Outstanding champion and Innovation Award of [End-to-End Driving at Scale Challenge](https://opendrivelab.com/challenge2024/#end_to_end_driving_at_scale)
  - *2023-12*: NVIDIA Graduate Fellowship (Top-10 globally, First awarded student from Chinese institution)
  - *2023-12*: Distinguished Student of Nanjing University (南京大学学生年度人物, Top-10)
  - *2023-11*: National Scholarship
  - *2023-06*: Occupancy Prediction Challenge, <a href="https://opendrivelab.com/AD23Challenge.html#Track3">1st Place and Innovation Award (15,000+5000 USD Bonus)</a>
  - *2022-06*: Waymo 2022 3D Camera-Only Detection Task, <a href="https://waymo.com/open/challenges/2022/3d-camera-only-detection/">1st Place (15,000 USD Bonus)</a>
# 📖 Educations
- *20.09 - present*, Nanjing University, China
- *16.09 - 20.06*, Nanjing University, China


