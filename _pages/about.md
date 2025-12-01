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


I am currently a master's student in Data Science at New York University.

I am interested in Multimodal Representation Learning, Continual Learning, Embodied AI, Robot Learning (Reinforcement & Imitation Learning).

I like gaming 🎮, badminton 🏸, and rock climbing 🧗‍♂️.

And I have Frosty — the cutest little cat ever :33333333


<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<br>
<br>
<br>


<!-- # 🔥 News
- *2023.10.27*: &nbsp;🎉🎉 The paper *"[Saliency-Guided Hidden Associative Replay for Continual Learning](https://arxiv.org/abs/2310.04334)"* has been accepted by the NeurlPS workshop.
- *2023.10.15*: &nbsp;🎉🎉 The code for *"[Fully Spiking Neural Network for Legged Robots](https://arxiv.org/abs/2310.05022)"* is now open source at <https://github.com/thisisnotahuman/FullySNNforLeggedRobots> ~ -->

# 🚧 Ongoing Projects

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Continual Multimodal Contrastive Learning</div><img src='images/memorystoryboard.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
-->

[CMCL: Continual Multimodal Contrastive Learning](https://docs.google.com/presentation/d/1OWy31tBuEgkkjruwrxHcb1Kc0WNHtBNNOG2g6v8so0E/edit?usp=sharing)

<!--
**Xiaoyang Jiang**, Mengye Ren, Brenden Lake, Manling Li

- Developing an online segmentation framework that incrementally refines temporal coherence and semantic persistence in egocentric 4D reconstructions.  
- Combines CUT3R-based global memory with task-driven affordance prediction, enabling subtask-level temporal grounding for embodied agents.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">UAD–Sonata</div><img src='images/uadsonata.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unsupervised Affordance Distillation on Dynamic 3D Memory](https://github.com/xj2366/uad-sonata)

**Xiaoyang Jiang**, Mengye Ren, Brenden Lake

- Integrates CUT3R’s dynamic reconstruction with UAD-style contrastive learning for multi-granularity affordance reasoning.  
- The project explores language-conditioned completion and progress tracking across subtasks (e.g., “pick up cup → pour water → open fridge”).
</div>
</div>
-->
  
# 📝 Papers 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2025</div><img src='images/mithumanoid.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Fully Spiking Neural Network for Legged Robots](https://ieeexplore.ieee.org/document/10890793)

**Xiaoyang Jiang**, **Qiang Zhang**, Jingkai Sun, Jiahang Cao, Jingtong Ma, Renjing Xu

[**Project**](https://github.com/thisisnotahuman/FullySNNforLeggedRobots) <!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

- In this paper, we successfully apply a lightweight population coded Spiking Neural Network (SNN) to process legged robots, achieving outstanding results across a range of simulated terrains. This study presents a highly efficient SNN for legged robots that can be seamless integrated into other learning models.
- Paper accepted for oral presentation at ICASSP 2025.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICRA 2024</div><img src='images/overview.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Prompt, Plan, Perform: LLM-based Humanoid Control via Quantized Imitation Learning](https://ieeexplore.ieee.org/abstract/document/10610948)

**Jingkai Sun**, **Qiang Zhang**, Yiqun Duan, Xiaoyang Jiang, Chong Cheng, Renjing Xu

<!-- [**Project**](https://github.com/thisisnotahuman/FullySNNforLeggedRobots) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

- We present a novel approach that combines adversarial imitation learning with large language models (LLMs). This innovative method enables the agent to learn reusable skills with a single policy and solve zero-shot tasks under the guidance of LLMs. To the best of our knowledge, this is the first framework that controls humanoid robots using a single learning policy network and LLM as a planner.
- Accepted at ICRA 2024.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023 Workshops</div><img src='images/sharc_overall_00.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Saliency-Guided Hidden Associative Replay for Continual Learning](https://arxiv.org/abs/2310.04334)

**Guangji Bai**, Qilong Zhao, Xiaoyang Jiang, Yifei Zhang, Liang Zhao

<!-- [**Project**](https://github.com/thisisnotahuman/FullySNNforLeggedRobots) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->

- This paper presents the Saliency Guided Hidden Associative Replay for Continual Learning. SHARC primarily archives salient data segments via sparse memory encoding. Importantly, by harnessing associative memory paradigms, it introduces a content focused memory retrieval mechanism, promising swift and near-perfect recall, bringing CL a step closer to authentic human memory processes.
- Accepted at NeurIPS 2023 Workshops.
</div>
</div>


<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2020 - 2024* Excellent Student Scholarship granted by Northeastern University 
- *2022.06* Silver Prize in Liaoning in China College Students' Internet Plus Innovation and Entrepreneurship Competition held by the Ministry of Education
- *2022.04* National Third Prize in the Underwater Operations Program in China Robot Contest co-held by China Association of Automation and Chinese RoboCup Committee
- *2020.08* First Prize in the RoboMaster University Championship and First Prize in the RoboMaster Infantry Racing and Intelligent Shooting programs, funded and organized by DJI
- *2020.11* Third Prize in the National English Competition for College Students held by TEFL China

# 📖 Educations
- *2024.09 - 2026.05 (now)*, M.S. in Data Science, Center for Data Science, New York University.
- *2020.09 - 2024.07*, B.Eng. in Robotics Engineering, Faculty of Robot Science and Engineering, Northeastern University. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Professional Experience
- *2024.09 - now*, CILVR Lab, NYU
- *2022.09 - 2024.07*, Microelectronics Thrust, Function Hub, HKUST
- *2023.04 - 2023.11*, Incremental Learning Group, Emory University
- *2020.08 - 2021.08*, T-DT Innovation Laboratory, Northeastern University
