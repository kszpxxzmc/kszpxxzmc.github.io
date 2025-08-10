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

Hi! I am a second-year Ph.D. student at [College of Computer Science and Technology, Zhejiang University](http://www.cs.zju.edu.cn/), supervised by Prof. [Dahua Lin](http://dahua.site/). 
I also work closely with [Tong Wu](https://wutong16.github.io/) and [Ziwei Liu](https://liuziwei7.github.io/). Prior to this, I earned my Bachelor's degree from [School of Artificial Intelligence, Nanjing University](https://ai.nju.edu.cn/main.htm) in 2023.

My research interest includes 3D/4D generation and pose estimation. I have published papers with total google scholar citations <a href='https://scholar.google.com/citations?user=oWXEaQoAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.


# 🔥 News
- *2025.08*: &nbsp;🎉🎉  One first-author paper accepted to [Siggraph Asia 2025 (Journal)](https://dl.acm.org/journal/tog).
- *2025.06*: &nbsp;🎉🎉  One first-author paper accepted to [ICCV 2025](https://iccv.thecvf.com/).
- *2025.03*: &nbsp;🎉🎉  One paper accepted to [Siggraph 2025](https://s2025.siggraph.org/).
- *2025.01*: &nbsp;🎉🎉  One paper accepted to [ICLR 2025](https://iclr.cc/).
- *2024.09*: &nbsp;🎉🎉  One paper accepted to [NeurIPS 2024 (D&B Track)](https://neurips.cc/).
- *2024.07*: &nbsp;🎉🎉  One first-author paper accepted to [ECCV 2024](https://eccv.ecva.net/).
- *2023.07*: &nbsp;🎉🎉  We are organizing [OmniObject3D Challenge](https://omniobject3d.github.io/challenge.html), hosted by [AI for 3D Content Creation Workshop](https://ai3dcc.github.io/) on [ICCV 2023](https://iccv2023.thecvf.com/).

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/papers/ECCV2024_teaser.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GenDoP: Auto-regressive Camera Trajectory Generation as a Director of Photography](https://arxiv.org/abs/2504.07083) [ICCV 2025]

**Mengchen Zhang**, Tong Wu, Jing Tan, Ziwei Liu, Gordon Wetzstein, Dahua Lin

[**[Project]**](https://kszpxxzmc.github.io/GenDoP/)&nbsp;
[**[Paper]**](https://arxiv.org/abs/2504.07083)&nbsp;
[**[Code]**](https://github.com/3DTopia/GenDoP)&nbsp;
[**[Data]**]()

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2025</div><img src='images/papers/3DGen-Bench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[Omni6D: Large-Vocabulary 3D Object Dataset for Category-Level 6D Object Pose Estimation](https://arxiv.org/abs/2409.18261) [ECCV 2024]

**Mengchen Zhang**, Tong Wu, Tai Wang, Tengfei Wang, Ziwei Liu, Dahua Lin 

[**[Paper]**](https://arxiv.org/abs/2409.18261)&nbsp;
[**[Video]**](https://www.youtube.com/watch?v=BKyw51bUhZs)&nbsp;
[**[Code]**](https://github.com/3DTopia/Omni6D/)&nbsp;
[**[Data]**](https://openxlab.org.cn/datasets/kszpxxzmcwww/Omni6D/)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/papers/GenDoP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">


[3DGen-Bench: Comprehensive Benchmark Suite for 3D Generative Models](https://arxiv.org/abs/2503.21745) [Arxiv 2025]

Yuhan Zhang$^\*$, **Mengchen Zhang**$^\*$, Tong Wu, Tengfei Wang, Gordon Wetzstein, Dahua Lin, Ziwei Liu

[**[Paper]**](https://arxiv.org/abs/2503.21745)&nbsp;
[**[Data]**](https://huggingface.co/datasets/3DGen/3DGen-Bench)

</div>
</div>

[LayerPano3D: Layered 3D Panorama for Hyper-Immersive Scene Generation](https://arxiv.org/abs/2408.13252) [SIGGRAPH 2025]

Shuai Yang, Jing Tan, **Mengchen Zhang**, Tong Wu, Yixuan Li, Gordon Wetzstein, Ziwei Liu, Dahua Lin

[**[Project]**](https://ys-imtech.github.io/projects/LayerPano3D/)&nbsp;
[**[Paper]**](https://arxiv.org/abs/2408.13252)&nbsp;
[**[Code]**](https://github.com/3DTopia/LayerPano3D)&nbsp;

<hr> 

[IDArb: Intrinsic Decomposition for Arbitrary Number of Input Views and Illuminations](https://lizb6626.github.io/IDArb/) [ICLR 2025]

Zhibing Li, Tong Wu, Jing Tan, **Mengchen Zhang**, Jiaqi Wang, Dahua Lin

[**[Project]**](https://lizb6626.github.io/IDArb/)&nbsp;
[**[Paper]**](https://arxiv.org/abs/2412.12083)&nbsp;
[**[Code]**](https://github.com/Lizb6626/IDArb/)&nbsp;
[**[Data]**](https://huggingface.co/datasets/lizb6626/Arb-Objaverse)

<hr>
[FiVA: Fine-grained Visual Attribute Dataset for Text-to-Image Diffusion Models](https://arxiv.org/abs/2412.07674) [NeurIPS 2024 (Datasets and Benchmarks Track)]

Tong Wu, Yinghao Xu, Ryan Po, **Mengchen Zhang**, Guandao Yang, Jiaqi Wang, Ziwei Liu, Dahua Lin, Gordon Wetzstein

[**[Project]**](https://fiva-dataset.github.io/)&nbsp;
[**[Paper]**](https://arxiv.org/abs/2412.07674)&nbsp;
[**[Code]**](https://github.com/wutong16/FiVA)&nbsp;
[**[Data]**](https://huggingface.co/datasets/FiVA/FiVA)


<hr> 
[Tailor3D: Customized 3D Assets Editing and Generation with Dual-Side Images](https://arxiv.org/abs/2407.06191) [Arxiv 2024]

Zhangyang Qi, Yunhan Yang, **Mengchen Zhang**, Long Xing, Xiaoyang Wu, Tong Wu, Dahua Lin, Xihui Liu, Jiaqi Wang, Hengshuang Zhao

[**[Project]**](https://tailor3d-2024.github.io/)&nbsp;
[**[Paper]**](https://arxiv.org/abs/2407.06191)&nbsp;
[**[Code]**](https://github.com/Qi-Zhangyang/Tailor3D)&nbsp;

<hr> 
[Gemini vs GPT-4V: A Preliminary Comparison and Combination of Vision-Language Models Through Qualitative Cases](https://arxiv.org/abs/2312.15011) [Arxiv 2023]

Zhangyang Qi, Ye Fang, **Mengchen Zhang**, Zeyi Sun, Tong Wu, Ziwei Liu, Dahua Lin, Jiaqi Wang, Hengshuang Zhao

[**[Project]**](https://github.com/Qi-Zhangyang/Gemini-vs-GPT4V)&nbsp;
[**[Paper]**](https://arxiv.org/abs/2312.15011)&nbsp;

<hr> 
[Image data augmentation for deep learning: A survey](https://arxiv.org/abs/2204.08610) [Arxiv 2022]

Suorong Yang, Weikang Xiao, **Mengchen Zhang**, Suhan Guo, Jian Zhao, Furao Shen

# 📖 Educations
- *2023.09 - Present*, Ph.D. in College of Computer Science and Technology, Zhejiang University.
- *2019.09 - 2023.06*, B.Sc. in School of Artificial Intelligence, Nanjing University.

# 🎖 Honors and Awards
- *2022.09*, National Scholarship

# 🎉 Misc
- Graduated from Suzhou High School
- [BIng 🧊](https://lizb6626.github.io/) is both my best friend and collaborator. Wish her all the best and good luck!