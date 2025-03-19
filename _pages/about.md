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

I am a final-year Ph.D. student in Computer Science at [Nanjing University](https://en.wikipedia.org/wiki/Nanjing_University), advised by Prof. [Tong Lu](https://cs.nju.edu.cn/lutong/index.htm). Later this year, I will be joining **NVIDIA Research** as a **Research Scientist**.

My research focuses on **Vision-Language Models (VLMs)** and **Autonomous Driving Perception**. I have published 10+ papers <a href='https://scholar.google.com/citations?hl=zh-CN&user=H2fJLqEAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FRayeRen%2Frayeren.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at the top international AI conferences such as CVPR, ICCV and ECCV. 


Currently, I am working on **frontier Vision-Language Models** at NVIDIA, collaborating with [Zhiding Yu](https://research.nvidia.com/person/zhiding-yu), [Guilin Liu](https://liuguilin1225.github.io/), and other outstanding researchers on **Project [Eagle](https://huggingface.co/collections/nvidia/eagle-2-6764ba887fa1ef387f7df067)**. Eagle also contributes to **NVIDIA Cosmos Nemotron** and [**NVIDIA Isaac GR00T N1**](https://github.com/NVIDIA/Isaac-GR00T).

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

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='images/eagle2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Eagle 2: Building Post-Training Data Strategies from Scratch for Frontier Vision-Language Models](https://arxiv.org/pdf/2501.14818)

Zhiqi Li, **Guo Chen**, Shilong Liu, Shihao Wang, Vibashan VS, Yishen Ji, Shiyi Lan, Hao Zhang, Yilin Zhao, Subhashree Radhakrishnan, Nadine Chang, Karan Sapra, Amala Sanjay Deshmukh, Tuomas Rintamaki, Matthieu Le, Ilia Karmanov, Lukas Voegtle, Philipp Fischer, De-An Huang, Timo Roman, Tong Lu, Jose M Alvarez, Bryan Catanzaro, Jan Kautz, Andrew Tao, Guilin Liu, Zhiding Yu

[**PDF**](https://arxiv.org/pdf/2501.14818) [**code**](https://github.com/NVlabs/EAGLE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work focuses on developing open-source vision-language models by emphasizing data strategy in post-training, resulting in the performant Eagle2 models that achieve state-of-the-art results across various multimodal benchmarks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/cg_bench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cg-bench: Clue-grounded question answering benchmark for long video understanding](https://arxiv.org/pdf/2412.12075?)

**Guo Chen**, Yicheng Liu, Yifei Huang, Yuping He, Baoqi Pei, Jilan Xu, Yali Wang, Tong Lu, Limin Wang

[**PDF**](https://arxiv.org/pdf/2412.12075?) [**code**](https://github.com/CG-Bench/CG-Bench) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- CG-Bench tests multimodal models on long videos with clue-based QA, featuring 1,219 videos and 12,129 questions. It highlights challenges in video comprehension and the gap between open-source and commercial models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/internvideo2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Internvideo2: Scaling foundation models for multimodal video understanding](https://arxiv.org/pdf/2403.15377)

Yi Wang, Kunchang Li, Xinhao Li, Jiashuo Yu, Yinan He, **Guo Chen**, Baoqi Pei, Rongkun Zheng, Zun Wang, Yansong Shi, Tianxiang Jiang, Songze Li, Jilan Xu, Hongjie Zhang, Yifei Huang, Yu Qiao, Yali Wang, Limin Wang

[**PDF**](https://arxiv.org/pdf/2403.15377) [**code**](https://github.com/OpenGVLab/InternVideo) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- InternVideo2 offers advanced video models with a 6B encoder, excelling in video recognition, text alignment, and dialogue, achieving top results in over 60 tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/egoexolearn.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Egoexolearn: A dataset for bridging asynchronous ego-and exo-centric view of procedural activities in real world](http://openaccess.thecvf.com/content/CVPR2024/papers/Huang_EgoExoLearn_A_Dataset_for_Bridging_Asynchronous_Ego-_and_Exo-centric_View_CVPR_2024_paper.pdf)

Yifei Huang*, **Guo Chen***, Jilan Xu, Mingfang Zhang, Lijin Yang, Baoqi Pei, Hongjie Zhang, Lu Dong, Yali Wang, Limin Wang, Yu Qiao

[**PDF**](http://openaccess.thecvf.com/content/CVPR2024/papers/Huang_EgoExoLearn_A_Dataset_for_Bridging_Asynchronous_Ego-_and_Exo-centric_View_CVPR_2024_paper.pdf) [**code**](https://github.com/OpenGVLab/EgoExoLearn) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- EgoExoLearn is a dataset with 120 hours of egocentric and demonstration videos, gaze data, and multimodal annotations, designed to advance AI learning through observation and cross-view task benchmarks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/internvl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Internvl: Scaling up vision foundation models and aligning for generic visual-linguistic tasks](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_InternVL_Scaling_up_Vision_Foundation_Models_and_Aligning_for_Generic_CVPR_2024_paper.pdf)

Zhe Chen, Jiannan Wu, Wenhai Wang, Weijie Su, **Guo Chen**, Sen Xing, Muyan Zhong, Qinglong Zhang, Xizhou Zhu, Lewei Lu, Bin Li, Ping Luo, Tong Lu, Yu Qiao, Jifeng Dai#

[**PDF**](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_InternVL_Scaling_up_Vision_Foundation_Models_and_Aligning_for_Generic_CVPR_2024_paper.pdf) [**code**](https://github.com/OpenGVLab/InternVL) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We developed InternVL, a 6 billion parameter vision-language model, aligned with large language models using vast image-text data. It achieves state-of-the-art results on 32 benchmarks, advancing multi-modal AGI.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/mat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Memory-and-Anticipation Transformer for Online Action Understanding](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659)

Jiahao Wang*, **Guo Chen**, Yifei Huang, Limin Wang, Tong Lu#

[**Homepage**](https://echo0125.github.io/mat/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work presents a memory-anticipation-based method for online action understanding.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVIU</div><img src='images/basictad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[BasicTAD: an Astounding RGB-Only Baseline for Temporal Action Detection](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659)

Min Yang*, **Guo Chen***, Yin-Dong Zheng, Tong Lu, Limin Wang#

[**PDF**](https://arxiv.org/abs/2205.02717)  [**code**](https://github.com/MCG-NJU/BasicTAD) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work presents a simple yet effective end-to-end training framework for temporal action detection.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2022</div><img src='images/dcan.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DCAN: Improving Temporal Action Detection via Dual Context Aggregation](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659)

**Guo Chen**, Yin-Dong Zheng, Limin Wang, Tong Lu#

[**PDF**](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659)  [**code**](https://github.com/cg1177/DCAN) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work explored boundary-based methods for temporal action detection and proposed a novel network, termed DCAN, to improve temporal action detection via temporal-level and proposal-level context aggregation.
</div>
</div>


- [Modeling Fine-Grained Hand-Object Dynamics for Egocentric Video Representation Learning](https://arxiv.org/pdf/2503.00986), Baoqi Pei, Yifei Huang, Jilan Xu, **Guo Chen**, etal. **ICLR 2025**
- [X-Gen: Ego-centric Video Prediction by Watching Exo-centric Videos](https://openreview.net/forum?id=8J2DrrWDKE), Jilan Xu, Yifei Huang, Baoqi Pei, Junlin Hou, Qingqiu Li, **Guo Chen**, etal. **ICLR 2025**
- [Avsegformer: Audio-visual segmentation with transformer]([https://github.com](https://ojs.aaai.org/index.php/AAAI/article/view/29104/30087)), Shengyi Gao, Zhe Chen, **Guo Chen**, etal. **AAAI 2024**
- [Mvbench: A comprehensive multi-modal video understanding benchmark](https://openaccess.thecvf.com/content/CVPR2024/papers/Li_MVBench_A_Comprehensive_Multi-modal_Video_Understanding_Benchmark_CVPR_2024_paper.pdf), Kunchang Li, Yali Wang, Yinan He, Yizhuo Li, Yi Wang, Yi Liu, Zun Wang, Jilan Xu, **Guo Chen**, etal. **CVPR 2024**
- [Retrieval-augmented egocentric video captioning](http://openaccess.thecvf.com/content/CVPR2024/papers/Xu_Retrieval-Augmented_Egocentric_Video_Captioning_CVPR_2024_paper.pdf), Jilan Xu, Yifei Huang, Junlin Hou, **Guo Chen**, etal. **CVPR 2024**
- [Internvid: A large-scale video-text dataset for multimodal understanding and generation](https://arxiv.org/pdf/2307.06942), Yi Wang, Yinan He, Yizhuo Li, Kunchang Li, Jiashuo Yu, Xin Ma, Xinhao Li, **Guo Chen**, etal. **ICLR 2023**
- [Elan: Enhancing temporal action detection with location awareness]([https://github.com](https://ieeexplore.ieee.org/abstract/document/10219585/)), **Guo Chen**, Yin-Dong Zheng, etal. **ICME 2023**
- [Mrsn: Multi-relation support network for video action detection]([https://github.com](https://ieeexplore.ieee.org/abstract/document/10219718)), Yin-Dong Zheng, **Guo Chen**, etal. **ICME 2023**
- [Matching compound prototypes for few-shot action recognition](https://link.springer.com/article/10.1007/s11263-024-02017-7), Yifei Huang, Lijin Yang, **Guo Chen**, etal. **IJCV**
- [Videollm: Modeling video sequence with large language models](https://arxiv.org/pdf/2305.13292), **Guo Chen**, Yin-Dong Zheng, Jiahao Wang, etal. **Arxiv**
- [Token-Efficient Long Video Understanding for Multimodal LLMs](https://arxiv.org/pdf/2503.04130), Jindong Jiang, Xiuyu Li, Zhijian Liu, Muyang Li, **Guo Chen**, etal. **Arxiv**
- [Video mamba suite: State space model as a versatile alternative for video understanding]([https://github.com](https://arxiv.org/pdf/2403.09626)), **Guo Chen**, Yifei Huang, Jilan Xu, etal. **Arxiv**
- [An Egocentric Vision-Language Model based Portable Real-time Smart Assistant](https://arxiv.org/pdf/2503.04250), Yifei Huang, Jilan Xu, Baoqi Pei, Yuping He, **Guo Chen**, etal. **Arxiv**
- [FAST: Faster Arbitrarily-Shaped Text Detector with Minimalist Kernel Representation](https://arxiv.org/abs/2111.02394), Zhe Chen, Jiahao Wang, Wenhai Wang, **Guo Chen**, etal. **Arxiv**

# 📝 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV Workspace</div><img src='images/egovideo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Egovideo: Exploring egocentric foundation model and downstream adaptation](https://arxiv.org/pdf/2406.18070)

**Guo Chen**, Baoqi Pei, Jilan Xu, Yuping He, Yicheng Liu, Kanghua Pan, Yifei Huang, Yali Wang, Tong Lu, Limin Wang, Yu Qiao

[**PDF**](https://arxiv.org/pdf/2406.18070) [**code**](https://github.com/OpenGVLab/ego4d-eccv2022-solutions) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work presents our champion solutions to seven tracks at 1st EgoVis challenge.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Generalist Model</div><img src='images/internvideo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InternVideo: General Video Foundation Models via Generative and Discriminative Learning](https://arxiv.org/pdf/2212.03191)

Yi Wang, Kunchang Li, Yizhuo Li, Yinan He, Bingkun Huang, Zhiyu Zhao, Hongjie Zhang, Jilan Xu, Yi Liu, Zun Wang, Sen Xing, **Guo Chen**, Junting Pan, Jiashuo Yu, Yali Wang, Limin Wang, Yu Qiao#

[**PDF**](https://arxiv.org/pdf/2212.03191) [**code**](https://github.com/OpenGVLab/InternVideo) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work presents our champion solutions to seven tracks at Ego4D challenge.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV Workshop</div><img src='images/ego4d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InternVideo-Ego4D: A Pack of Champion Solutions to Ego4D Challenges](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659)

**Guo Chen***, Sen Xing*, Zhe Chen*, Yi Wang*, Kunchang Li, Yizhuo Li, Yi Liu, Jiahao Wang, Yin-Dong Zheng, Bingkun Huang, Zhiyu Zhao, Junting Pan, Yifei Huang, Zun Wang, Jiashuo Yu, Yinan He, Hongjie Zhang, Tong Lu, Yali Wang, Limin Wang, Yu Qiao#

[**PDF**](https://arxiv.org/pdf/2211.09529.pdf) [**code**](https://github.com/OpenGVLab/ego4d-eccv2022-solutions) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work presents our champion solutions to five tracks at Ego4D challenge.
</div>
</div>

# 🎖 Honors and Awards
  - *2024-07-01*: 1st EgoVis Challenge, ECCV2024, **7 Top-1 Rankings**
  - *2023-10-01*: 1st Perception Test Challenge, **Top-1 and Top-2 Rankings**
  - *2023-01-01*: WSDM Cup 2023 Toloka VQA Challenge, WSDM2023, **Top-1 Ranking**
  - *2022-10-01*: 2nd Ego4D Challenge, ECCV2022, **7 Top-1 Rankings**
  - *2017-12-01*: CCPC Final Contest, **Bronze Medal**
  - *2017-10-01*: CCPC Regional Contest, **Bronze Medal**
  - *2017-10-15*: ACM-ICPC Asia Regional Contest, **Silver Medal**

# 📖 Educations
- *20.09 - present*, Nanjing University, Nanjing, China
- *15.09 - 19.06*, University of South China, Hengyang, China


