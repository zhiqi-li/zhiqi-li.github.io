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

I‘m pursuing a Ph.D. in Computer Science at [Nanjing University](https://en.wikipedia.org/wiki/Nanjing_University), advised by Prof. [Limin Wang](http://wanglimin.github.io/) and Prof. [Tong Lu](https://cs.nju.edu.cn/lutong/index.htm). 
<!-- Now I'm working at [Shanghai AI Lab](https://www.shlab.org.cn/). -->

My research interests are General visual perception and human-computer and multimodal interaction system. 
I am focusing on video understanding, egocentric vision perception and user-centric visual computing.


# 🔥 News
- *2023-10-10*: In the first [Perception Test](https://github.com/google-deepmind/perception_test/tree/main) challenge, We obtain the best performance in Temporal Sound Localisation & runner-up in Temporal Action Localisation. The code of solution is [here](https://github.com/OpenGVLab/perception_test_iccv2023).

- *2023-08-16*: Code of [MAT](https://echo0125.github.io/mat/) is released in [here](https://github.com/Echo0125/Memory-and-Anticipation-Transformer).

- *2023-07-14*: Our paper [MAT](https://echo0125.github.io/mat/) is accepted by [ICCV](https://iccv2023.thecvf.com/).

- *2023-05-22*: We present a novel Video Sequence Understanding Framework [VideoLLM](https://arxiv.org/abs/2305.13292).

- *2023-04-03*: [BasicTAD](https://arxiv.org/abs/2205.02717) is accepted by [CVIU](https://www.sciencedirect.com/journal/computer-vision-and-image-understanding).

- *2023-01-17*: Our team wins the champion of [WSDM Cup 2023 Toloka VQA Challenge](https://codalab.lisn.upsaclay.fr/competitions/7434#learn_the_details).

- *2022-11-17*: 🎂 We provide the final Ego4D [report](https://arxiv.org/pdf/2211.09529.pdf) and the [code](https://github.com/OpenGVLab/ego4d-eccv2022-solutions).

- *2022-09-19*: Our team wins <font color="#dd0000"><strong>Top-1</strong></font> rankings in <font color="#dd0000"><strong>7 tracks</strong></font> of [Ego4D ECCV2022 Challenge](https://ego4d-data.org/workshops/eccv22/).

- *2022-09-15*: We have released the [source code](https://github.com/MCG-NJU/BasicTAD) of [BasicTAD](https://arxiv.org/abs/2205.02717).

- *2022-06-21*: Code of [DCAN](https://ojs.aaai.org/index.php/AAAI/article/view/19900) is released in [here](https://github.com/cg1177/DCAN).

- *2022-05-05*: We present the [BasicTAD](https://arxiv.org/abs/2205.02717), an end-to-end TAD baseline method. 

- *2021-12-01*: Our paper [DCAN](https://ojs.aaai.org/index.php/AAAI/article/view/19900) is accepted by [AAAI](https://aaai.org/).

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
- CG-Bench is a benchmark for evaluating multimodal large language models' understanding of long videos through clue-grounded question answering, featuring 1,219 videos and 12,129 QA pairs across perception, reasoning, and hallucination question types. It introduces novel evaluation methods to ensure models retrieve relevant clues, highlighting the challenges in long video comprehension and the performance gap between open-source and commercial models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/internvideo2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Internvideo2: Scaling foundation models for multimodal video understanding](https://arxiv.org/pdf/2403.15377)

Yi Wang, Kunchang Li, Xinhao Li, Jiashuo Yu, Yinan He, **Guo Chen**, Baoqi Pei, Rongkun Zheng, Zun Wang, Yansong Shi, Tianxiang Jiang, Songze Li, Jilan Xu, Hongjie Zhang, Yifei Huang, Yu Qiao, Yali Wang, Limin Wang

[**PDF**](https://arxiv.org/pdf/2403.15377) [**code**](https://github.com/OpenGVLab/InternVideo) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- InternVideo2 introduces a new family of video foundation models that excel in video recognition, video-text tasks, and video-centric dialogue through a progressive training approach, achieving state-of-the-art results with a 6B parameter video encoder. By ensuring spatiotemporal consistency and aligning video with text, it outperforms in over 60 tasks, especially in video-related dialogue and long video understanding.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/egoexolearn.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Egoexolearn: A dataset for bridging asynchronous ego-and exo-centric view of procedural activities in real world](http://openaccess.thecvf.com/content/CVPR2024/papers/Huang_EgoExoLearn_A_Dataset_for_Bridging_Asynchronous_Ego-_and_Exo-centric_View_CVPR_2024_paper.pdf)

**Guo Chen**, Yin-Dong Zheng, Limin Wang, Tong Lu#

[**PDF**](http://openaccess.thecvf.com/content/CVPR2024/papers/Huang_EgoExoLearn_A_Dataset_for_Bridging_Asynchronous_Ego-_and_Exo-centric_View_CVPR_2024_paper.pdf) [**code**](https://github.com/OpenGVLab/EgoExoLearn) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- EgoExoLearn is a comprehensive dataset designed to study human ability to map activities across perspectives, featuring 120 hours of egocentric and demonstration videos with gaze data and multimodal annotations, aimed at advancing AI learning through observation, with benchmarks for cross-view tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/internvl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Internvl: Scaling up vision foundation models and aligning for generic visual-linguistic tasks](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_InternVL_Scaling_up_Vision_Foundation_Models_and_Aligning_for_Generic_CVPR_2024_paper.pdf)

Zhe Chen, Jiannan Wu, Wenhai Wang, Weijie Su, **Guo Chen**, Sen Xing, Muyan Zhong, Qinglong Zhang, Xizhou Zhu, Lewei Lu, Bin Li, Ping Luo, Tong Lu, Yu Qiao, Jifeng Dai#

[**PDF**](https://openaccess.thecvf.com/content/CVPR2024/papers/Chen_InternVL_Scaling_up_Vision_Foundation_Models_and_Aligning_for_Generic_CVPR_2024_paper.pdf) [**code**](https://github.com/OpenGVLab/InternVL) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We designed a large-scale vision-language foundation model (InternVL) with 6 billion parameters, aligning it progressively with large language models using web-scale image-text data, achieving state-of-the-art performance on 32 visual-linguistic benchmarks, and advancing multi-modal AGI development.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/mat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Memory-and-Anticipation Transformer for Online Action Understanding](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659)

Jiahao Wang*, **Guo Chen***, Yifei Huang, Limin Wang, Tong Lu#

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


