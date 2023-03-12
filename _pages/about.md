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

# About Me

<span class='anchor' id='about-me'></span>

Hi! I'm Shilong Bao(包世龙, E-mail: baoshilong@iie.ac.cn). Now I am a PhD. student of **Institute of Information Engineering, Chinese Academy of Sciences (IIE, CAS)**, supervised by Prof. [Qingming Huang (黄庆明)](https://qmhuang-ucas.github.io/) (IEEE Fellow). I am also lucky to have opportunities to collaborate with [Qianqian Xu (许倩倩)](https://qianqianxu010.github.io/) (Professor at Institute of Computing Technology (ICT), CAS.), [Xiaochun Cao (操晓春)](http://people.ucas.ac.cn/~xiaochun) (Professor at Sun Yat-sen University, Shenzhen Compus, China), [Zhiyong Yang (杨智勇)](https://joshuaas.github.io/) (postdoc at UCAS) and [Ke Ma (马坷)](https://www.researchgate.net/profile/Ke_Ma10) (postdoc at UCAS).

My research interest includes machine learning and data mining. I have authored or co-authored several academic papers in top-tier international conferences and journals, including T-PAMI, ICML, NeurIPS, and ACM Multimedia.


# 🔥 News
- *2022.11*: &nbsp;🎉🎉 I have obtained the National Scholarship (国家奖学金) from the Ministry of Education of the People’s Republic of China.
- *2022.09*: &nbsp;🎉🎉 Two of our papers have been accepted by NeurIPS 2022 (One paper has been selected as an oral presentation and one is a poster). 
- *2022.06*: &nbsp;🎉🎉 Our XCurve-v1.0.0 library has been released! Please Try now and give us feedback!
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022 (Oral)</div><img src='images/dpcml_nips22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Minority Matters: A Diversity-Promoting Collaborative Metric Learning Algorithm](https://arxiv.org/pdf/2209.15292.pdf).

**Shilong Bao**, Qianqian Xu, Zhiyong Yang , Yuan He, Xiaochun Cao, Qingming Huang. Advances in Neural Information Processing Systems (**NeurIPS**), 2022. **<font color='red'> (Oral, 1.9%) </font>** \| [\[Code\]](https://github.com/statusrank/DPCML)\| [\[Video\]](https://nips.cc/virtual/2022/poster/55412) \| [\[Poster\]](https://nips.cc/media/PosterPDFs/NeurIPS%202022/55412.png?t=1668477709.8846257) \| [\[Slides\]](https://nips.cc/virtual/2022/poster/55412)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2021 (Long Talk)</div><img src='images/tpauc_icml21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[When All We Need is a Piece of the Pie: A Generic Framework for Optimizing Two-way Partial AUC](https://github.com/statusrank/A-Generic-Framework-for-Optimizing-Two-way-Partial-AUC/blob/main/TPAUC.pdf).

Zhiyong Yang, Qianqian Xu, **Shilong Bao**, Yuan He, Xiaochun Cao and Qingming Huang. International Conference on Machine Learning (**ICML**), 2021. **<font color='red'> (Long Talk, 3%) </font>** \| [\[Code\]](https://github.com/statusrank/A-Generic-Framework-for-Optimizing-Two-way-Partial-AUC)\| [\[Video\]](https://slideslive.com/38958537/when-all-we-need-is-a-piece-of-the-pie-a-generic-framework-for-optimizing-twoway-partial-auc?ref=speaker-22247) \| [\[Poster\]](https://github.com/statusrank/A-Generic-Framework-for-Optimizing-Two-way-Partial-AUC/blob/main/TPAUC_poster.png) \| [\[Slides\]](https://github.com/statusrank/A-Generic-Framework-for-Optimizing-Two-way-Partial-AUC/blob/main/oral_pdf.pdf)
</div>
</div>

- [Asymptotically Unbiased Instance-wise Regularized Partial AUC Optimization: Theory and Algorithm](https://arxiv.org/pdf/2210.03967.pdf). Huiyang Shao, Qianqian Xu, Zhiyong Yang, **Shilong Bao** and Qingming Huang. Advances in Neural Information Processing Systems (NeurIPS), 2022. \| [\[Code\]](https://github.com/Shaocr/PAUCI) \|

- [Optimizing Two-way Partial AUC with an End-to-end Framework](https://arxiv.org/abs/2206.11655). Zhiyong Yang, Qianqian Xu, **Shilong Bao**, Yuan He, Xiaochun Cao and Qingming Huang. IEEE Transactions on Pattern Analysis and Machine Intelligence (**T-PAMI**), 2022. \| [\[Code\]](https://github.com/statusrank/XCurve) \|

- [AdAUC: End-to-end Adversarial AUC Optimization Against Long-tail Problems](https://arxiv.org/abs/2206.12169). Wenzheng Hou, Qianqian Xu, Zhiyong Yang, **Shilong Bao**, Yuan He and Qingming Huang. International Conference on Machine Learning (**ICML**), 2022. \| [\[Code\]](https://github.com/hhh0hwz/Adauc) \|

- [Rethinking Collaborative Metric Learning: Toward an Efficient Alternative without Negative Sampling](https://arxiv.org/abs/2206.11549). **Shilong Bao**, Qianqian Xu, Zhiyong Yang, Xiaochun Cao and Qingming Huang. IEEE Transactions on Pattern Analysis and Machine Intelligence (**T-PAMI**),  2022. \| [\[Code\]](https://github.com/statusrank/SFCML) \|

- [Learning with Multiclass AUC: Theory and Algorithms](https://arxiv.org/pdf/2107.13171.pdf). Zhiyong Yang, Qianqian Xu, **Shilong Bao**, Xiaochun Cao and Qingming Huang. IEEE Transactions on Pattern Analysis and Machine Intelligence (**T-PAMI**),  2021. \| [\[Code\]](https://github.com/joshuaas/Learning-with-Multiclass-AUC-Theory-and-Algorithms) \|

- [Collaborative Preference Embedding against Sparse Labels](http://www.jdl.link/doc/2011/20191229_ACMM-Collaborative%20Preference%20Embedding%20against%20Sparse%20Labels.pdf). **Shilong Bao**, Qianqian Xu, Ke Ma, Zhiyong Yang, Xiaochun Cao and Qingming Huang. ACM International Conference on Multimedia (**ACM-MM**), 2019. \| [\[Code\]](https://github.com/statusrank/CPE)\|

# 🎖 Honors and Awards
- *2022* National Scholarship, Ministry of Education of the People’s Republic of China. (国家奖学金)
- *2021* Director Special Scholarship Award, IIE, CAS. (中科院信息工程研究所所长特别奖)

# 📖 Educations

<div class='school-box'>
<div><img src='images/ucas.jpg' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2019.09 - now, Ph.D. Student.

Institute of Information Engineering, Chinese Academy of Sciences (IIE, CAS).

University of Chinese Academy of Sciences, Beijing.
</div>
</div>

<div class='school-box'>
<div><img src='images/qdu.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2015.09 - 2019.06, Undergraduate.

College of Computer Science and Technology.

Qingdao University (QDU), Qingdao.
</div>
</div>

# 💬 Invited Talks
- *2023.02*: &nbsp; AI TIME Youth PhD Talk of NeurIPS2022. [\[Video\]](https://www.bilibili.com/video/BV1624y1G7un/?spm_id_from=333.999.0.0&vd_source=356f7336a633368638ff41a90a11197b).

# 💻 Project

<!-- <div class='school-box'>
<div><img src='images/Xcurve.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1"> -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">XCurve</div><img src='images/Xcurve.png' alt="sym" width="120%"></div></div>
<div class='paper-box-text' markdown="1">

*2020.02 - now*: &nbsp; **<font color='red'> As a core member, </font>** I participated in the development of [XCurve: Machine Learning with X-Curve Metrics](https://github.com/statusrank/XCurve). 

- XCurve focuses on **the design criteria of the objective function for ML tasks**, which can be formulated as a series of X-metric (say AUROC, AUPRC, AUTKC) optimization problems considering the **average performance of all decision thresholds** during the training phase. Welcome to try now and give us feedback!
</div>
</div>

<!-- - *2020.02 - 至今*: &nbsp; As core member, I participated in the developments of X as [XCurve: Machine Learning with X-Curve Metrics](https://github.com/statusrank/XCurve). 

XCurve focuses on **the design criteria of the objective function for ML tasks**, which can be formulated as a series of X-metric (say AUROC, AUPRC, AUTKC) optimization problems considering the **average performance of all decision thresholds** during the training phase. Welcome to try now and give us feedback! -->