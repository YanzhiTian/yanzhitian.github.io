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

**Yanzhi Tian (田炎智)**, is currently a master student at [School of Computer Science and Technology, Beijing Institute of Technology](https://cs.bit.edu.cn/)(北京理工大学计算机学院). He received his bachelor's degree from [Elite class of XUTELI, Beijing Institute of Technology](https://xuteli.bit.edu.cn/)(北京理工大学徐特立英才班) in 2023, majoring in computer science.

His research interests include <font color="#2E8B57"><b>Machine Translation</b></font>, <font color="#DAA520"><b>Large Language Models</b></font> and <font color="#1E90FF"><b>Vision Language Models</b></font>.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News

- *2025.05*: &nbsp;🎉🎉 1 paper has been accepted by ACL 2025 Findings!
<!-- - *2023.10*: &nbsp;🎉🎉 1 paper has been accepted by EMNLP 2023 Findings! -->


# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div style="text-align: center;">
      <div class="badge">ACL 2025 Findings</div>
      <img src='images/ACL2025.png' alt="sym" width="75%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

Exploring In-Image Machine Translation with Real-World Background

**Yanzhi Tian**, Zeming Liu, Zhengyang Liu, Yuhang Guo

- We tackle In-Image Machine Translation with real-world backgrounds by introducing a new dataset IIMT30k and the DebackX model for better translation and visual quality.
- Paper [![arXiv](https://img.shields.io/badge/arXiv-2505.15282-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.15282)
- Code [![GitHub](https://img.shields.io/badge/GitHub-grey.svg?style=flat&logo=github)](https://github.com/BITHLP/DebackX)
- Dataset [![HuggingFace](https://img.shields.io/badge/HuggingFace-yellow?style=flat&logo=huggingface)](https://huggingface.co/datasets/yztian/IIMT30k)
</div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div style="text-align: center;">
      <div class="badge">EMNLP 2023 Findings</div>
      <img src='images/IIMT.png' alt="sym" width="85%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023 Findings</div><img src='images/IIMT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

In-Image Neural Machine Translation with Segmented Pixel Sequence-to-Sequence Model

**Yanzhi Tian**, Xiang Li, Zeming Liu, Yuhang Guo, Bin Wang

<!-- [**Project**](https://scholar.google.com.hk/citations?view_op=view_citation&hl=zh-CN&user=WtHJWXIAAAAJ&citation_for_view=WtHJWXIAAAAJ:UeHWp8X0CEIC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We design an end-to-end model for IIMT that outperforms traditional cascade methods for the first time.
- Paper [![ACL](https://img.shields.io/badge/ACL-white.svg?stype=flat)](https://aclanthology.org/2023.findings-emnlp.1004/) [![OpenReview](https://img.shields.io/badge/OpenReview-white.svg?stype=flat)](https://openreview.net/forum?id=3RS2T9EPjI)
- Code [![GitHub](https://img.shields.io/badge/GitHub-grey.svg?style=flat&logo=github)](https://github.com/YanzhiTian/E2E-IIMT)
</div>
</div>


## 2023
- ``IWSLT 2023`` [The Xiaomi AI Lab’s Speech Translation Systems for IWSLT 2023 Offline Task, Simultaneous Task and Speech-to-Speech Task](https://aclanthology.org/2023.iwslt-1.39/), Wuwei Huang, Mengge Liu, Xiang Li, **Yanzhi Tian**, Fengyu Yang, Wen Zhang, Jian Luan, Bin Wang, Yuhang Guo, Jinsong Su

## 2022
- ``LREC 2022 Workshop``[Ancient Chinese Word Segmentation and Part-of-Speech Tagging Using Data Augmentation](https://aclanthology.org/2022.lt4hala-1.21/), **Yanzhi Tian**, Yuhang Guo
- ``NAACL 2022  Workshop``[BIT-Xiaomi’s System for AutoSimTrans](https://aclanthology.org/2022.autosimtrans-1.6/), Mengge Liu, Xiang Li, Bao Chen, **Yanzhi Tian**, Tianwei Lan, Silin Li, Yuhang Guo, Jian Luan, Bin Wang

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2023.09 - now*: Master. Computer Science, **School of Computer Science and Technology, Beijing Institute of Technology**.  
- *2019.09 - 2023.06*: Undergraduate. Computer Science, **Elite class of XUTELI, Beijing Institute of Technology**.

# 🧐 Services
- **Reviewer** of ACL Rolling Review (ARR), 2024

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.01 - 2023.06*, Internship at **Xiaomi AI Lab**. Mentor: Xiang Li.