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

His research interests include <font color=green>Machine Translation</font> and <font color=blue>Vision Language Models</font>.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2023.10*: &nbsp;🎉🎉 1 paper has been accepted by EMNLP 2023 Findings!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2023 Findings</div><img src='images/IIMT.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[In-Image Neural Machine Translation with Segmented Pixel Sequence-to-Sequence Model](https://aclanthology.org/2023.findings-emnlp.1004/)

**Yanzhi Tian**, Xiang Li, Zeming Liu, Yuhang Guo, Bin Wang

<!-- [**Project**](https://scholar.google.com.hk/citations?view_op=view_citation&hl=zh-CN&user=WtHJWXIAAAAJ&citation_for_view=WtHJWXIAAAAJ:UeHWp8X0CEIC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We design an end-to-end model for IIMT that outperforms traditional cascade methods for the first time.
- Paper [![ACL](https://img.shields.io/badge/ACL-white.svg?stype=plastic&logo=data:image/png;base64,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)](https://aclanthology.org/2023.findings-emnlp.1004/) [![OpenReview](https://img.shields.io/badge/OpenReview-white.svg?stype=plastic)](https://openreview.net/forum?id=3RS2T9EPjI)
- Code [![GitHub](https://img.shields.io/badge/GitHub-grey.svg?style=plastic&logo=github)](https://github.com/YanzhiTian/E2E-IIMT)
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