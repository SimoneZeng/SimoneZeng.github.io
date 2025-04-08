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

I'm currently a PhD student admitted in 2024 at [School of Computer Science and Engineering](https://www.scse.uestc.edu.cn/), [University of Electronic Science and Technology of China](https://www.uestc.edu.cn/), supervised by Prof. [Kai Zheng](https://zheng-kai.com/).
Previously, I received my B.E. degree from Chongqing University of Posts and Telecommunications in 2022. 

My research interests include spatial-temporal data mining, spatial crowdsourcing, and vector approximate nearest neighbor search.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.03*: &nbsp;🎉🎉 Two papers are accepted by ICDE 2025. 
- *2025.01*: &nbsp;🎉🎉 One paper is accepted by WWW 2025. 
- *2024.11*: &nbsp;🎉🎉 One paper is accepted by VLDB 2025. 

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

<!-- [Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

**Selected Conference Papers**

- `ICDE 2025` **Ximu Zeng**, Jianxing Lin, Liwei Deng, Yuchen Fang, Yan Zhao, Kai Zheng. Optimizing Multi-Center Collaboration for Task Assignment in Spatial Crowdsoucing. <span style="color:red">**[CCF A]**</span>
- `ICDE 2025` Liwei Deng, Penghao Chen, **Ximu Zeng**, Yuchen Fang, Jin Chen, Yan Zhao. Towards Accurate Distance Estimation for Distribution-Aware c-ANN Search. <span style="color:red">**[CCF A]**</span> |  [![LSH Stars](https://img.shields.io/github/stars/Ur-Eine/distribution-aware-LSH?label=LSH%20Stars&style=social)](https://github.com/Ur-Eine/distribution-aware-LSH)
- `WWW 2025` **Ximu Zeng**, Liwei Deng, Penghao Chen, Xu Chen, Han Su, Kai Zheng. [LIRA: A Learning-based Query-aware Partition Framework for Large-scale ANN Search](https://arxiv.org/abs/2503.23409). <span style="color:red">**[CCF A]**</span> |  [![Stars](https://img.shields.io/github/stars/SimoneZeng/LIRA-ANN-search?label=LIRA%20Stars&style=social)](https://github.com/SimoneZeng/LIRA-ANN-search)
- `VLDB 2025` Liwei Deng, Penghao Chen, **Ximu Zeng**, Tianfu Wang, Yan Zhao, and Kai Zheng. [Efficient Data-aware Distance Comparison Operations for High-Dimensional Approximate Nearest Neighbor Search](https://arxiv.org/abs/2411.17229). <span style="color:red">**[CCF A]**</span> | [![Stars](https://img.shields.io/github/stars/Ur-Eine/DADE?label=DADE%20Stars&style=social)](https://github.com/Ur-Eine/DADE)
- `DASFAA 2024` Rui Hu, Yuze Wang, **Ximu Zeng**, Shuncheng Liu, Quanlin Yu, Peicong Wu, Han Su, and Kai Zheng. [Imitation Learning Decision with Driving Style Tuning for Personalized Autonomous Driving](https://dl.acm.org/doi/abs/10.1007/978-981-97-5575-2_15). <span style="color:red">**[CCF B]**</span>
- `CIKM 2023` **Ximu Zeng**, Quanlin Yu, Shuncheng Liu, Yuyang Xia, Han Su, and Kai Zheng. [Target-Oriented Maneuver Decision for Autonomous Vehicle: A Rule-Aided Reinforcement Learning Framework](https://dl.acm.org/doi/abs/10.1145/3583780.3615072). <span style="color:red">**[Core A, CCF B]**</span>
- `DASFAA 2023` Weijie Lian, Yuze Wang, **Ximu Zeng**, Shuncheng Liu, Yuyang Xia, Huiyong Tang, and Han Su. [EGL: Efficient Graph Learning with Safety Constrains for Heterogeneous Trajectory Prediction](https://dl.acm.org/doi/abs/10.1007/978-3-031-35415-1_5). <span style="color:red">**[CCF B]**</span>
- `DASFAA 2022` Xu Chen, **Ximu Zeng**, Shuncheng Liu, Zhi Xu, Yuyang Xia, Ruyi Lai, and Han Su. [TSummary: A Traffic Summarization System Using Semantic Words](https://dl.acm.org/doi/abs/10.1007/978-3-031-11217-1_19). <span style="color:red">**[CCF B]**</span>
- `DASFAA 2022` Yupeng Diao, Yiteng Su, **Ximu Zeng**, Xu Chen, Shuncheng Liu, and Han Su. [Astral: An Autoencoder-Based Model for Pedestrian Trajectory Prediction of Variable-Length](https://dl.acm.org/doi/abs/10.1007/978-3-031-11217-1_16). <span style="color:red">**[CCF B]**</span>


# 📖 Educations
- *Sep,2018 - Jun,2022*, Chongqing University of Posts and Telecommunications, Bachelor
  - Data Science and Big Data Technology, School of Computer Science and Technology
- *Sep,2022 - Jun,2024*, University of Electronic Science and Technology of China, Master's candidate
  - Computer Science and Technology, School of Computer Science and Engineering
- *Sep,2024 - present*, University of Electronic Science and Technology of China, Ph.D
  - Computer Science and Technology, School of Computer Science and Engineering


# 🎖 Honors and Awards
- 2024 Academic Seedling Award, 5%, UESTC
- 2022 Outstanding Undergraduate, Chongqing Municipal Education Commission
- 2021 Merit Student, Chongqing Municipal Education Commission
- 2021 National Scholarship


# ⏳ Professional Services
- 2025: WWW