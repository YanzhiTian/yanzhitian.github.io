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

**Yanzhi Tian (田炎智)**, is currently a PhD student at [School of Computer Science and Technology, Beijing Institute of Technology](https://cs.bit.edu.cn/)(北京理工大学计算机学院). He received his bachelor's degree from [XUTELI School, Beijing Institute of Technology](https://xuteli.bit.edu.cn/)(北京理工大学徐特立英才班) in 2023, majoring in computer science.

His research interests include <font color="#2E8B57"><b>Machine Translation</b></font> and <font color="#DAA520"><b>Large Language Models</b></font>.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News

- *2025.08*: &nbsp;🎉🎉 1 paper has been accepted by EMNLP 2025 Main!
- *2025.05*: &nbsp;🎉🎉 1 paper has been accepted by ACL 2025 Findings!
<!-- - *2023.10*: &nbsp;🎉🎉 1 paper has been accepted by EMNLP 2023 Findings! -->


# 📝 Publications

`Preprint` *Beyond Literal Mapping: Benchmarking and Improving Non-Literal Translation Evaluation*
- **Yanzhi Tian**, Cunxiang Wang, Zeming Liu, Heyan Huang, Wenbo Yu, Dawei Song, Jie Tang, Yuhang Guo
- [![arXiv](https://img.shields.io/badge/arXiv-2601.07338-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2601.07338) [![GitHub](https://img.shields.io/badge/GitHub-RATE-white?style=flat&logo=github&labelColor=grey&color=white)](https://github.com/BITHLP/RATE)

`EMNLP 2025 Main` *PRIM: Towards Practical In-Image Multilingual Machine Translation*
- **Yanzhi Tian**, Zeming Liu, Zhengyang Liu, Chong Feng, Xin Li, Heyan Huang, Yuhang Guo
- [![ACL Anthology](https://img.shields.io/badge/ACL%20Anthology-EMNLP%202025%20Main-b31b1b?logo=book&logoColor=white)](https://aclanthology.org/2025.emnlp-main.691/) [![GitHub](https://img.shields.io/badge/GitHub-PRIM-white?style=flat&logo=github&labelColor=grey&color=white)](https://github.com/BITHLP/PRIM)

`ACL 2025 Findings` *Exploring In-Image Machine Translation with Real-World Background*
- **Yanzhi Tian**, Zeming Liu, Zhengyang Liu, Yuhang Guo
- [![ACL Anthology](https://img.shields.io/badge/ACL%20Anthology-ACL%202025%20Findings-b31b1b?logo=book&logoColor=white)](https://aclanthology.org/2025.findings-acl.6) [![GitHub](https://img.shields.io/badge/GitHub-DebackX-white?style=flat&logo=github&labelColor=grey&color=white)](https://github.com/BITHLP/DebackX)

`EMNLP 2023 Findings` *In-Image Neural Machine Translation with Segmented Pixel Sequence-to-Sequence Model*
- **Yanzhi Tian**, Xiang Li, Zeming Liu, Yuhang Guo, Bin Wang
- [![ACL Anthology](https://img.shields.io/badge/ACL%20Anthology-EMNLP%202023%20Findings-b31b1b?logo=book&logoColor=white)](https://aclanthology.org/2023.findings-emnlp.1004/) [![GitHub](https://img.shields.io/badge/GitHub-grey.svg?style=flat&logo=github)](https://github.com/YanzhiTian/E2E-IIMT)


<!-- <div class='paper-box'>
  <div class='paper-box-image'>
    <div style="text-align: center;">
      <div class="badge">EMNLP 2025 Main</div>
      <img src='images/EMNLP2025.png' alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

PRIM: Towards Practical In-Image Multilingual Machine Translation

**Yanzhi Tian**, Zeming Liu, Zhengyang Liu, Chong Feng, Xin Li, Heyan Huang, Yuhang Guo

- We propose PRIM, the first real-world multilingual In-Image Machine Translation benchmark, and develop VisTrans, an end-to-end model that achieves superior translation quality and visual effect.

- [![ACL Anthology](https://img.shields.io/badge/ACL%20Anthology-EMNLP%202025%20Main-b31b1b?logo=book&logoColor=white)](https://aclanthology.org/2025.emnlp-main.691/) [![GitHub](https://img.shields.io/badge/GitHub-PRIM-white?style=flat&logo=github&labelColor=grey&color=white)](https://github.com/BITHLP/PRIM)
</div>
</div> -->


<!-- <div class='paper-box'>
  <div class='paper-box-image'>
    <div style="text-align: center;">
      <div class="badge">ACL 2025 Findings</div>
      <img src='images/ACL2025.png' alt="sym" width="65%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

Exploring In-Image Machine Translation with Real-World Background

**Yanzhi Tian**, Zeming Liu, Zhengyang Liu, Yuhang Guo

- We tackle In-Image Machine Translation with real-world backgrounds by introducing a new dataset IIMT30k and the DebackX model for better translation and visual quality.
- [![ACL Anthology](https://img.shields.io/badge/ACL%20Anthology-ACL%202025%20Findings-b31b1b?logo=book&logoColor=white)](https://aclanthology.org/2025.findings-acl.6) [![GitHub](https://img.shields.io/badge/GitHub-DebackX-white?style=flat&logo=github&labelColor=grey&color=white)](https://github.com/BITHLP/DebackX)
</div>
</div> -->


<!-- <div class='paper-box'>
  <div class='paper-box-image'>
    <div style="text-align: center;">
      <div class="badge">EMNLP 2023 Findings</div>
      <img src='images/EMNLP2023.png' alt="sym" width="85%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

In-Image Neural Machine Translation with Segmented Pixel Sequence-to-Sequence Model

**Yanzhi Tian**, Xiang Li, Zeming Liu, Yuhang Guo, Bin Wang -->

<!-- [**Project**](https://scholar.google.com.hk/citations?view_op=view_citation&hl=zh-CN&user=WtHJWXIAAAAJ&citation_for_view=WtHJWXIAAAAJ:UeHWp8X0CEIC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<!-- - We design an end-to-end model for IIMT that outperforms traditional cascade methods for the first time.
- [![ACL Anthology](https://img.shields.io/badge/ACL%20Anthology-EMNLP%202023%20Findings-b31b1b?logo=book&logoColor=white)](https://aclanthology.org/2023.findings-emnlp.1004/) [![GitHub](https://img.shields.io/badge/GitHub-grey.svg?style=flat&logo=github)](https://github.com/YanzhiTian/E2E-IIMT)
</div>
</div> -->


<!-- ## 2023
- ``IWSLT 2023`` [The Xiaomi AI Lab’s Speech Translation Systems for IWSLT 2023 Offline Task, Simultaneous Task and Speech-to-Speech Task](https://aclanthology.org/2023.iwslt-1.39/), Wuwei Huang, Mengge Liu, Xiang Li, **Yanzhi Tian**, Fengyu Yang, Wen Zhang, Jian Luan, Bin Wang, Yuhang Guo, Jinsong Su

## 2022
- ``LREC 2022 Workshop``[Ancient Chinese Word Segmentation and Part-of-Speech Tagging Using Data Augmentation](https://aclanthology.org/2022.lt4hala-1.21/), **Yanzhi Tian**, Yuhang Guo -->

<!-- # 🎖 Honors and Awards -->

# 📖 Educations
- *2023.09 - now*: PhD Student. Computer Science, **School of Computer Science and Technology, Beijing Institute of Technology**.  
- *2019.09 - 2023.06*: Undergraduate. Computer Science, **XUTELI School, Beijing Institute of Technology**.

<!-- # 🧐 Services -->

<!-- # 💬 Invited Talks -->

# 💻 Internships
- *2025.06 - now*, Internship at **Zhipu AI**. Mentor: [Cunxiang Wang](https://wangcunxiang.github.io/).
- *2023.01 - 2023.06*, Internship at **Xiaomi AI Lab**. Mentor: [Xiang Li](https://scholar.google.com.hk/citations?user=DMfYmIEAAAAJ&hl=zh-CN).
