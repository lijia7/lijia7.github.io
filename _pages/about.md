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

I am Jiaqi Li, a current (2023.09-) master student in Artificial Intelligence at Huazhong University of Science and Technology (HUST), supervised by Prof. Zhiguo Cao. Prior to that, I received my B.S. degree from Huazhong University of Science and Technology in 2023. 

My current research interests are 3D vision, autonomous driving and diffusion-based depth estimation.

# 🎓**Education**

- **2023~Present,** **Master student in Artificial Intelligence(Advised by Prof. Zhiguo Cao)**, *School of Artificial intelligence & Automation (AIA) ,
Huazhong University of Science & Technology (HUST), Wuhan, China*
- **2019~2023,** **B.S. in Automation**, *School of Artificial intelligence & Automation (AIA) ,
Huazhong University of Science & Technology (HUST), Wuhan, China*

# 🔥 **News**
- *2024.09*: &nbsp;🎉🎉 <a href='https://neurips.cc/virtual/2024/poster/93704'>SDDR</a> is accepted by **NeurIPS 2024**.
- *2024.09*: &nbsp;🎉🎉 <a href='https://ieeexplore.ieee.org/document/10707178'>NVDS+</a> is accepted by **TPAMI**. 
- *2024.05*: &nbsp;🎉🎉 Winner of two international prizes(**<a href='https://cvlai.net/ntire/2024'>NTIRE 2024</a>** and **<a href='https://sites.google.com/view/eccv24-tricky-workshop/home'>TRICKY 2024</a>**). One paper is accepted by **<a href='https://arxiv.org/abs/2408.06083'>ECCV 2024 Workshop</a>**.
- *2023.07*: &nbsp;🎉🎉 <a href='https://dlnext.acm.org/doi/abs/10.1145/3581783.3611807'>DADP</a> is accepted by **ACM MM 2023**.
- *2023.07*: &nbsp;🎉🎉 <a href='https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Neural_Video_Depth_Stabilizer_ICCV_2023_paper.html'>NVDS</a> is accepted by **ICCV 2023**. 

# 📝 **Publications** 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/neurips2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Self-Distilled Depth Refinement with Noisy Poisson Fusion](https://arxiv.org/pdf/2409.17880v1)

**Jiaqi Li***, Yiran Wang*, Jinghong Zheng, Zihao Huang, Ke Xian, Zhiguo Cao§, Jianming Zhang

[Paper](https://arxiv.org/pdf/2409.17880v1) [Github](https://github.com/lijia7/SDDR) [Poster](https://neurips.cc/virtual/2024/poster/93704)

- We model the depth refinement task through the noisy Poisson fusion problem with local inconsistency noise and edge deformation noise as two types of depth degradation.
- We present the robust and efficient Self-distilled Depth Refinement (SDDR) framework, which can generate accurate depth edge representation by the coarse-to-fine self-distillation paradigm.
- We design the edge-guided gradient loss and edge-based fusion loss, as the edge-based guidance to enforce the model with both consistent depth structures and meticulous depth edges.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCVW 2024</div><img src='images/eccvw2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Robust Monocular Depth Estimation in Non-Lambertian Surfaces](https://arxiv.org/abs/2408.06083)

Junrui Zhang, **Jiaqi Li§**, Yachuan Huang, Yiran Wang, Jinghong Zheng, Liao Shen, Zhiguo Cao

[Paper](https://arxiv.org/abs/2408.06083) [Github](https://github.com/RiverrHuang/Depth-Estimation-for-Transparent-and-Mirror-Surfaces-via-Leveraging-Large-Model-Priors)

We focus on the robustness of depth estimation on mirrors and transparent objects, and based on the existing monocular depth estimation model, we complement its robustness to special reflective surfaces with a core of three designs.
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023&amp;TPAMI</div><img src='images/iccv2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Neural Video Depth Stabilizer(ICCV)](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Neural_Video_Depth_Stabilizer_ICCV_2023_paper.html)

[NVDS+: Towards Efficient and Versatile Neural Stabilizer for Video Depth Estimation(TPAMI)](https://ieeexplore.ieee.org/document/10707178)

Yiran Wang, Min Shi, **Jiaqi Li**, Zihao Huang, Zhiguo Cao, Jianming Zhang, Ke Xian§,  Guosheng Lin

[Paper(ICCV)](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Neural_Video_Depth_Stabilizer_ICCV_2023_paper.html) [Paper(TPAMI)](https://ieeexplore.ieee.org/document/10707178) [Github](https://github.com/RaymondWang987/NVDS/) [Project Page](https://raymondwang987.github.io/NVDS/) [Dataset Page](https://raymondwang987.github.io/VDW/) 

- We propose a plug-and-play and bidirectional learning-based framework termed Neural Video Depth Stabilizer(NVDS), which can be directly adapted to different single-image depth predictors to remove flickers.
- We propose VDW dataset, which is currently the largest video depth dataset in the wild with the most diverse video scenes.
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2023</div><img src='images/acmmm2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Diffusion-Augmented Depth Prediction with Sparse Annotations](https://dlnext.acm.org/doi/abs/10.1145/3581783.3611807)

**Jiaqi Li**, Yiran Wang§, Zihao Huang, Jinghong Zheng, Ke Xian, Zhiguo Cao, Jianming Zhang

The depth annotations collected by LiDAR in autonomous driving scenarios are highly sparse, and it is difficult for the model to reconstruct a dense and complete depth map from this learning. The previous methods have poor robustness in challenging scenarios such as night, rain, and dazzling light, and cannot meet the practical applications. We propose a plug-and-play framework based on diffusion modeling and object-guided integrality loss to enhance global and local structural integrity, respectively.
</div>
</div>

* : Equal Contribution; § : Corresponding Author

# 🏁**Competitions**

1. **[Winner Award] [Team Leader]** TRICKY 2024 Challenge on Monocular Depth from Images of Specular and Transparent Surfaces, ECCVW 2024
2. **[Winner Award] [Team Leader]** NTIRE 2024 Challenge on HR Depth from Images of Specular and Transparent Surfaces, CVPRW 2024
3. **[Fifth Place]** **[Team Leader]** Mobile AI & AIM 2022 Challenge, ECCVW 2022

# 🏆**Awards & Honors**

- First-Class Scholarship for Postgraduates(研究生一等学业奖学金), HUST, 2023
- Honours Degrees(荣誉学士学位), HUST (Top 3%), 2023
- Outstanding graduates(优秀毕业生), HUST (Top 10%), 2023
- National Scholarship(国家奖学金), Ministry of Education of PRC (Highest Honor, Top 0.2%), 2021
- Outstanding Undergraduates Student(本科特优生), HUST (Top 1%), 2021
- Merit Undergraduate(三好学生), HUST (Top 7%), 2021
