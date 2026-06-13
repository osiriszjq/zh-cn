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
{% assign gsRepository = site.google_scholar_stats_repository | default: site.repository %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: gsRepository | append: "@" %}
{% else %}
{% assign gsRepository = site.google_scholar_stats_repository | default: site.repository %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: gsRepository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

我现任中国地质大学（北京）人工智能学院讲师。此前博士毕业于澳大利亚阿德莱德大学 Australian Institute for Machine Learning (AIML)。我的研究兴趣包括三维与几何视觉、点云与神经场、视觉 Transformer、注意力机制与位置编码等。<a href='https://scholar.google.com/citations?user=R8d2QOsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>

<span class='anchor' id='-appointments'></span>

# 工作经历

- 2026 - 至今，中国地质大学（北京）人工智能学院，讲师。
- 2025.07 - 2025.12，澳大利亚阿德莱德大学，博士研究员。
- 2019.08 - 2020.05，美国卡耐基梅隆大学 CI2CV Lab，全职研究助理实习。

<span class='anchor' id='-education'></span>

# 教育背景

- 2021.03 - 2025.06，<a href="https://www.adelaide.edu.au/"><img class="png" src="/images/UoA_logo.png" width="23pt" alt="澳大利亚阿德莱德大学"></a> 澳大利亚阿德莱德大学，Australian Institute for Machine Learning (AIML)，博士。导师：Prof. Simon Lucey。
- 2017.09 - 2019.05，<a href="https://www.umich.edu/"><img class="png" src="/images/Umich_logo.png" width="20pt" alt="美国密歇根大学"></a> 美国密歇根大学安娜堡分校，计算机视觉方向，硕士。
- 2013.09 - 2017.05，<a href="https://www.hit.edu.cn/"><img class="png" src="/images/HIT_logo.png" width="20pt" alt="哈尔滨工业大学"></a> 哈尔滨工业大学英才学院，自动化专业，学士。

<span class='anchor' id='-publications'></span>

# 论文

## 发表论文

[1] **Jianqiao Zheng**, Xueqian Li, Hemanth Saratchandran, Simon Lucey.  
**Structured Initialization for Attention in Vision Transformers.**  
NeurIPS 2025. [[论文]](https://arxiv.org/abs/2404.01139)

[2] **Jianqiao Zheng**, Xueqian Li, Sameera Ramasinghe, Simon Lucey.  
**Robust Point Cloud Processing through Positional Embedding.**  
3DV 2024. [[论文]](https://arxiv.org/abs/2309.00339)

[3] Xueqian Li, **Jianqiao Zheng**, Francesco Ferroni, Jhony Kaesemodel Pontes, Simon Lucey.  
**Fast Neural Scene Flow.**  
ICCV 2023. [[论文]](https://arxiv.org/abs/2304.09121)

[4] **Jianqiao Zheng**, Sameera Ramasinghe, Xueqian Li, Simon Lucey.  
**Trading Positional Complexity vs. Deepness in Coordinate Networks.**  
ECCV 2022. [[论文]](https://arxiv.org/abs/2205.08987)

[5] **Jianqiao Zheng**, Sameera Ramasinghe, Simon Lucey.  
**Rethinking Positional Encoding.**  
arXiv 2021. [[论文]](https://arxiv.org/abs/2107.02561)

[6] Yiping Ji, James Martens, **Jianqiao Zheng**, Ziqin Zhou, Peyman Moghadam, Xinyu Zhang, Hemanth Saratchandran, Simon Lucey.  
**Cutting the Skip: Training Residual-Free Transformers.**  
ICLR 2026. [[论文]](https://arxiv.org/abs/2510.00345)

## 预印本

[7] Hemanth Saratchandran, **Jianqiao Zheng**, Yiping Ji, Wenbo Zhang, Simon Lucey.  
**Rethinking Attention: Polynomial Alternatives to Softmax in Transformers.**  
arXiv / 在投. [[论文]](https://arxiv.org/abs/2410.18613)

[8] **Jianqiao Zheng**, Cameron Gordon, Yiping Ji, Hemanth Saratchandran, Simon Lucey.  
**From Tables to Signals: Revealing Spectral Adaptivity in TabPFN.**  
arXiv / 在投. [[论文]](https://arxiv.org/abs/2511.18278)

<span class='anchor' id='-projects'></span>

# 项目

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ViT 初始化</div><img src='images/structured_vit_initialization.png' alt="结构化 ViT 初始化" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**结构化 ViT 初始化**  
NeurIPS 2025 工作，研究如何通过结构化初始化向 Vision Transformer 引入视觉归纳偏置，并保持其可扩展性。  
[[论文]](https://arxiv.org/abs/2404.01139)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">三维视觉</div><img src='images/method.png' alt="鲁棒点云处理" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**鲁棒点云处理**  
3DV 2024 项目，围绕位置嵌入提升点云处理鲁棒性，从带宽控制角度进行理论分析，并在噪声和分布外扰动下进行实验验证。  
[[主页]](https://osiriszjq.github.io/robustPPE) [[代码]](https://github.com/osiriszjq/robustPPE) [[论文]](https://arxiv.org/abs/2309.00339)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">坐标网络</div><img src='images/simple_complex_encoding.png' alt="坐标网络" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**位置复杂度与网络深度的权衡**  
ECCV 2022 项目，研究坐标神经网络中位置编码复杂度与网络深度之间的权衡关系。  
[[主页]](https://osiriszjq.github.io/complex_encoding) [[代码]](https://github.com/osiriszjq/complex_encoding) [[论文]](https://arxiv.org/abs/2205.08987)

</div>
</div>

<span class='anchor' id='-teaching'></span>

# 教学经历

- 2023 - 2025，澳大利亚阿德莱德大学，教学助理，COMP SCI 3315 Computer Vision。
- 2025，澳大利亚阿德莱德大学，教学助理，MATHS 1004 Mathematics for Data Science I。
- 2018，美国密歇根大学，教学助理，SI 670 Applied Machine Learning。

<span class='anchor' id='-honors'></span>

# 荣誉奖励

- 博士毕业论文获得 Dean's Commendation for Doctoral Thesis Excellence。
- 中国国际大学生创新大赛（2024）国际赛道总决赛金奖。
