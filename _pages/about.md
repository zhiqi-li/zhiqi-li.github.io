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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2022</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DCAN: Improving Temporal Action Detection via Dual Context Aggregation](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659)

**Guo Chen**, Yin-Dong Zheng, Limin Wang, Tong Lu#

[**PDF**](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659) [**bibtex**](/bibtex/dcan.txt) [**code**](https://github.com/cg1177/DCAN) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work explored boundary-based methods for temporal action detection and proposed a novel network, termed DCAN, to improve temporal action detection via temporal-level and proposal-level context aggregation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2022</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DCAN: Improving Temporal Action Detection via Dual Context Aggregation](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659)

**Guo Chen**, Yin-Dong Zheng, Limin Wang, Tong Lu#

[**PDF**](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659) [**bibtex**](/bibtex/dcan.txt) [**code**](https://github.com/cg1177/DCAN) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work explored boundary-based methods for temporal action detection and proposed a novel network, termed DCAN, to improve temporal action detection via temporal-level and proposal-level context aggregation.
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

[**PDF**](https://arxiv.org/abs/2205.02717) [**bibtex**](/bibtex/basic.txt) [**code**](https://github.com/MCG-NJU/BasicTAD) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work presents a simple yet effective end-to-end training framework for temporal action detection.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2022</div><img src='images/dcan.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DCAN: Improving Temporal Action Detection via Dual Context Aggregation](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659)

**Guo Chen**, Yin-Dong Zheng, Limin Wang, Tong Lu#

[**PDF**](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659) [**bibtex**](/bibtex/dcan.txt) [**code**](https://github.com/cg1177/DCAN) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work explored boundary-based methods for temporal action detection and proposed a novel network, termed DCAN, to improve temporal action detection via temporal-level and proposal-level context aggregation.
</div>
</div>

# 📝 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV Workspace</div><img src='images/ego4d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Egovideo: Exploring egocentric foundation model and downstream adaptation](https://arxiv.org/pdf/2406.18070)

**Guo Chen**, Baoqi Pei, Jilan Xu, Yuping He, Yicheng Liu, Kanghua Pan, Yifei Huang, Yali Wang, Tong Lu, Limin Wang, Yu Qiao

[**PDF**](https://arxiv.org/pdf/2406.18070) [**bibtex**](/bibtex/internvideo.txt) [**code**](https://github.com/OpenGVLab/ego4d-eccv2022-solutions) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work presents our champion solutions to five tracks at Ego4D challenge.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Generalist Model</div><img src='images/internvideo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InternVideo: General Video Foundation Models via Generative and Discriminative Learning](https://arxiv.org/pdf/2212.03191)

Yi Wang, Kunchang Li, Yizhuo Li, Yinan He, Bingkun Huang, Zhiyu Zhao, Hongjie Zhang, Jilan Xu, Yi Liu, Zun Wang, Sen Xing, **Guo Chen**, Junting Pan, Jiashuo Yu, Yali Wang, Limin Wang, Yu Qiao#

[**PDF**](https://arxiv.org/pdf/2212.03191) [**bibtex**](/bibtex/internvideo.txt) [**code**](https://github.com/OpenGVLab/InternVideo) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work presents our champion solutions to five tracks at Ego4D challenge.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV Workshop</div><img src='images/ego4d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[InternVideo-Ego4D: A Pack of Champion Solutions to Ego4D Challenges](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659)

**Guo Chen***, Sen Xing*, Zhe Chen*, Yi Wang*, Kunchang Li, Yizhuo Li, Yi Liu, Jiahao Wang, Yin-Dong Zheng, Bingkun Huang, Zhiyu Zhao, Junting Pan, Yifei Huang, Zun Wang, Jiashuo Yu, Yinan He, Hongjie Zhang, Tong Lu, Yali Wang, Limin Wang, Yu Qiao#

[**PDF**](https://arxiv.org/pdf/2211.09529.pdf) [**bibtex**](/bibtex/ego4d.txt) [**code**](https://github.com/OpenGVLab/ego4d-eccv2022-solutions) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This work presents our champion solutions to five tracks at Ego4D challenge.
</div>
</div>


- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

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


