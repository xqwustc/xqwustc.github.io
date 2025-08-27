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
My name is Xianquan Wang (王宪泉). I am currently a third-year Ph.D. student (since September 2023) majoring in *Intelligence Science and Technology* at University of Science and Technology of China ([USTC](https://ustc.edu.cn/)), advised by Prof. [Qi Liu](http://staff.ustc.edu.cn/~qiliuql/) (刘淇). Prior to this, I obtained my Bachelor's degree in Computer Science and Technology from Qingdao University ([QDU](https://www.qdu.edu.cn/)) in 2023.

My research interests lie in user modeling & personalization, and cognitive science. I am fortunate to collaborate with researchers and have co-authored several papers presented at top-tier conferences, including KDD, EMNLP, AAAI, and IJCAI.



# 🔥 News
TBD


<!-- - *2024.06.08*: &nbsp;🎉🎉 One paper has been accepted by T-PAMI 2024. Congrats to all! -->
<!-- - *2024.05.2*: &nbsp;🎉🎉 Three papers have been accepted by ICML 2024 (One is Spotlight). Congrats to all! -->
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

TBD

<!--
- [One Image is Worth a Thousand Words: A Usability Preservable Text-Image Collaborative Erasing Framework for Diffusion Models](https://arxiv.org/pdf/2505.11131). Feiran Li, Qianqian Xu, **Shilong Bao**, Zhiyong Yang, Xiaochun Cao, Qingming Huang. International Conference on Machine Learning (ICML), 2025. \|[\[Code\]](https://github.com/Ferry-Li/Co-Erasing)\|

- [MixBridge: Heterogeneous Image-to-Image Backdoor Attack through Mixture of Schrödinger Bridges](https://arxiv.org/pdf/2505.08809?). Shixi Qin, Zhiyong Yang, **Shilong Bao**, Shi Wang, Qianqian Xu, Qingming Huang. International Conference on Machine Learning (ICML), 2025. \|[\[Code\]](https://github.com/qsx830/MixBridge)\|

- [OpenworldAUC: Towards Unified Evaluation and Optimization for Open-world Prompt Tuning](https://arxiv.org/pdf/2505.05180). Cong Hua, Qianqian Xu, Zhiyong Yang, Zitai Wang, **Shilong Bao**, Qingming Huang. International Conference on Machine Learning (ICML), 2025. \|[\[Code\]](https://github.com/huacong/OpenworldAUC)\|

- [AUCPro: AUC-Oriented Provable Robustness Learning](https://ieeexplore.ieee.org/document/10904855). **Shilong Bao**, Qianqian Xu, Zhiyong Yang, Yuan He, Xiaochun Cao, and Qingming Huang. IEEE Transactions on Pattern Analysis and Machine Intelligence (**T-PAMI**), 2025. \|[\[Code\]](https://github.com/statusrank/AUCPro)\|

- [Bidirectional Logits Tree: Pursuing Granularity Reconcilement in Fine-Grained Classification](https://arxiv.org/abs/2412.12782). Zhiguang Lu, Qianqian Xu, **Shilong Bao**, and Zhiyong Yang and Qingming Huang. AAAI Conference on Artificial Intelligence (AAAI), 2025. \|[\[Code\]](https://github.com/ZhiguangLuu/BiLT)\|

- [AUCSeg: AUC-oriented Pixel-level Long-tail Semantic Segmentation](https://arxiv.org/abs/2409.20398). Boyu Han, Qianqian Xu, Zhiyong Yang, **Shilong Bao**, Peisong Wen, Yangbangyan Jiang and Qingming Huang. Advances in Neural Information Processing Systems (**NeurIPS**), 2024. \|[\[Code\]](https://github.com/boyuh/AUCSeg)\|

- [Improved Diversity-Promoting Collaborative Metric Learning for Recommendation](https://ieeexplore.ieee.org/abstract/document/10553349). **Shilong Bao**, Qianqian Xu, Zhiyong Yang, Yuan He, Xiaochun Cao, and Qingming Huang. IEEE Transactions on Pattern Analysis and Machine Intelligence (**T-PAMI**), 46(12): 9004-9022, Jun. 2024. \|[\[Code\]](https://)\|

- [ReconBoost: Boosting Can Achieve Modality Reconcilement](https://arxiv.org/abs/2405.09321). Cong Hua, Qianqian Xu, **Shilong Bao**, Zhiyong Yang and Qingming Huang. International Conference on Machine Learning (**ICML**), 2024 \| [\[Code\]](https://github.com/huacong/ReconBoost) \|

- [Harnessing Hierarchical Label Distribution Variations in Test Agnostic Long-tail Recognition](https://arxiv.org/pdf/2405.07780). Zhiyong Yang, Qianqian Xu, Zitai Wang, Sicong Li, Boyu Han, **Shilong Bao**, Xiaochun Cao and Qingming Huang. International Conference on Machine Learning (**ICML**), 2024 \| [\[Code\]](https://github.com/scongl/DirMixE) \|

- [Revisiting AUC-oriented Adversarial Training with Loss-Agnostic Perturbations](https://ieeexplore.ieee.org/abstract/document/10214340). Zhiyong Yang, Qianqian Xu, Wenzheng Hou, **Shilong Bao**, Yuan He, Xiaochun Cao and Qingming Huang. IEEE Transactions on Pattern Analysis and Machine Intelligence (**T-PAMI**), 2023. \| [\[Code\]](https://github.com/statusrank/AUC-Oriented-Adversarial-Training) \|

- [AUC-Oriented Domain Adaptation: From Theory to Algorithm](https://ieeexplore.ieee.org/abstract/document/10214222). Zhiyong Yang, Qianqian Xu, **Shilong Bao**, Peisong Wen, Yuan He, Xiaochun Cao and Qingming Huang. IEEE Transactions on Pattern Analysis and Machine Intelligence (**T-PAMI**), 2023. \| [\[Code\]](https://github.com/statusrank/AUC-Oriented-Domain-Adaptation) \|

- [Asymptotically Unbiased Instance-wise Regularized Partial AUC Optimization: Theory and Algorithm](https://arxiv.org/pdf/2210.03967.pdf). Huiyang Shao, Qianqian Xu, Zhiyong Yang, **Shilong Bao** and Qingming Huang. Advances in Neural Information Processing Systems (NeurIPS), 38667–38679, 2022. \| [\[Code\]](https://github.com/Shaocr/PAUCI) \|

- [Optimizing Two-way Partial AUC with an End-to-end Framework](https://arxiv.org/abs/2206.11655). Zhiyong Yang, Qianqian Xu, **Shilong Bao**, Yuan He, Xiaochun Cao and Qingming Huang. IEEE Transactions on Pattern Analysis and Machine Intelligence (**T-PAMI**), 10228-10246, 2022. \| [\[Code\]](https://github.com/statusrank/XCurve) \|

- [AdAUC: End-to-end Adversarial AUC Optimization Against Long-tail Problems](https://arxiv.org/abs/2206.12169). Wenzheng Hou, Qianqian Xu, Zhiyong Yang, **Shilong Bao**, Yuan He and Qingming Huang. International Conference on Machine Learning (**ICML**), 8903–8925, 2022. \| [\[Code\]](https://github.com/statusrank/AUC-Oriented-Adversarial-Training) \|

- [Rethinking Collaborative Metric Learning: Toward an Efficient Alternative without Negative Sampling](https://arxiv.org/abs/2206.11549). **Shilong Bao**, Qianqian Xu, Zhiyong Yang, Xiaochun Cao and Qingming Huang. IEEE Transactions on Pattern Analysis and Machine Intelligence (**T-PAMI**), 45(1): 1017-1035, Jan. 2023. \|[\[Code\]](https://github.com/statusrank/SFCML)\|

- [Learning with Multiclass AUC: Theory and Algorithms](https://arxiv.org/pdf/2107.13171.pdf). Zhiyong Yang, Qianqian Xu, **Shilong Bao**, Xiaochun Cao and Qingming Huang. IEEE Transactions on Pattern Analysis and Machine Intelligence (**T-PAMI**),  7747–7763, 2021. \| [\[Code\]](https://github.com/joshuaas/Learning-with-Multiclass-AUC-Theory-and-Algorithms) \|

- [Collaborative Preference Embedding against Sparse Labels](http://www.jdl.link/doc/2011/20191229_ACMM-Collaborative%20Preference%20Embedding%20against%20Sparse%20Labels.pdf). **Shilong Bao**, Qianqian Xu, Ke Ma, Zhiyong Yang, Xiaochun Cao and Qingming Huang. ACM International Conference on Multimedia (**ACM-MM**), 2079–2087, 2019. \| [\[Code\]](https://github.com/statusrank/CPE)\|
!-->

# 📚 Academic Services
- **Conference Program Committee / Reviewer**: ICLR 2025 & 2026, AAAI 2026, ICML 2025, NeurIPS 2025, KDD 2025, WWW 2025 (Research & Short Paper), ARR 2025 (Feb), IJCAI 2025, ICME 2025, BIBM 2024 & 2025.
- **Journal Reviewer**: Science China-Information Sciences

# 🎖 Honors and Awards
- *2024* Graduate National Scholarship, Ministry of Education of the People’s Republic of China. (研究生国家奖学金)
- *2021* Undergraduate National Scholarship, Ministry of Education of the People’s Republic of China. (本科生国家奖学金)
- *2022* The 46th ACM-ICPC Asia Regional Contest <font color='red'> Silver Medal</font>. (第46届 ACM-ICPC 亚洲区域赛银奖)
- *2022* The 12th Shandong Provincial ICPC Collegiate Programming Contest <font color='red'> Gold Medal</font>. (第12届山东省ICPC大学生程序设计竞赛金奖)
- *2022* The 7th China College Computer Competition - Team Programming Ladder Contest <font color='red'> First Prize</font>. (第7届中国高校计算机大赛-程序设计天梯赛团体一等奖)
- *2020* The 12th National Undergraduate Mathematics Contest <font color='red'> National First Prize</font>. (第12届全国大学生数学竞赛国家一等奖)

# 🎓 Educations

<div class='school-box'>
<div><img src='images/ustc.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2023.09 - Present, Ph.D. Candidate.

School of Artificial Intelligence and Data Science.
  
University of Science and Technology of China, Hefei, China.
    
</div>
</div>

<div class='school-box'>
<div><img src='images/qdu.png' alt="sym" width="80"></div>
<div class='school-box-text' markdown="1">
2019.09 - 2023.06, Undergraduate.

College of Computer Science and Technology.

Qingdao University, Qingdao, China.
</div>
</div>
