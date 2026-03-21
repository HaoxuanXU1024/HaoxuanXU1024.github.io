---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- The following code is used to fetch and display Google Scholar citation stats. 
     It will be rendered correctly by the Jekyll theme and is NOT garbled text. -->
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi! I am **Haoxuan Xu (Harrison, 徐浩轩)**. 

I am an MPhil student in System Hub/ROAS Trust at the Hong Kong University of Science and Technology (Guangzhou), advised by [Prof. Haoang Li](https://sites.google.com/view/haoangli/homepage). Previously, I earned my undergraduate degree from the School of Information Science and Engineering at Shandong University ([Chongxin College](https://baike.baidu.com/item/%E5%B1%B1%E4%B8%9C%E5%A4%A7%E5%AD%A6%E5%B4%87%E6%96%B0%E5%AD%A6%E5%A0%82/20809738?fr=aladdin)), advised by [Prof. Yang Yang](https://faculty.sdu.edu.cn/yangyang/zh_CN/index.htm).

<div style="display: flex; justify-content: space-between; gap: 20px; background: #fff; padding: 20px; border-radius: 12px; box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1); margin-bottom: 25px;">
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 15px; font-size: 1.2em; border-bottom: 2px solid #f3f4f6; padding-bottom: 8px;">🎓 Education</h3>
    <div style="display: flex; align-items: flex-start; margin-bottom: 12px;">
      <img src="https://upload.wikimedia.org/wikipedia/en/thumb/e/e4/HKUST_Logo.svg/1200px-HKUST_Logo.svg.png" style="width: 24px; margin-right: 12px; margin-top: 3px;">
      <div>
        <div style="font-weight: 600;">HKUST(GZ)</div>
        <div style="font-size: 0.9em; color: #666;">MPhil in Robotics</div>
        <div style="font-size: 0.8em; color: #999;">2024.9 - 2026.7 (Expected)</div>
      </div>
    </div>
    <div style="display: flex; align-items: flex-start;">
      <img src="https://upload.wikimedia.org/wikipedia/en/thumb/5/53/Shandong_University_logo.svg/1200px-Shandong_University_logo.svg.png" style="width: 24px; margin-right: 12px; margin-top: 3px;">
      <div>
        <div style="font-weight: 600;">Shandong University</div>
        <div style="font-size: 0.9em; color: #666;">B.Eng. in Information Science</div>
        <div style="font-size: 0.8em; color: #999;">2020.9 - 2024.6</div>
      </div>
    </div>
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 15px; font-size: 1.2em; border-bottom: 2px solid #f3f4f6; padding-bottom: 8px;">💼 Experience</h3>
    <div style="display: flex; align-items: flex-start; margin-bottom: 12px;">
      <img src="https://www.dji.com/favicon.ico" style="width: 24px; margin-right: 12px; margin-top: 3px;">
      <div>
        <div style="font-weight: 600;">DJI</div>
        <div style="font-size: 0.9em; color: #666;">Image Algorithm Intern</div>
        <div style="font-size: 0.8em; color: #999;">2023.11 - 2024.4</div>
      </div>
    </div>
    <div style="display: flex; align-items: flex-start;">
      <img src="https://www.vivo.com/favicon.ico" style="width: 24px; margin-right: 12px; margin-top: 3px;">
      <div>
        <div style="font-weight: 600;">vivo</div>
        <div style="font-size: 0.9em; color: #666;">Research Intern</div>
        <div style="font-size: 0.8em; color: #999;">Current</div>
      </div>
    </div>
  </div>
</div>

# 🚀 Research Interests
- **Mobile Manipulation**
- **Vision and Language Navigation**
- **Computer Vision**

My research interests lie in ​Vision-and-Language Navigation (VLN)​ and Computer Vision, with a focus on ​embodied AI for service robotics. ​Currently, I work on bridging advanced machine learning techniques with real-world applications, particularly in developing ​adaptive navigation systems​ that interpret natural language instructions and dynamic environments.

If you are interested in any aspect of me, I am always open to discussions and collaborations. Feel free to reach out to me at - hxu095 [at] connect.hkust-gz.edu.cn

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='https://HaoxuanXU1024.github.io/images/p3nav.png' alt="P3Nav" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[P<sup>3</sup>Nav: End-to-End Perception, Prediction and Plannning for Vision-and-Language Navigation](http://arxiv.org/abs/2603.17459)

**ArXiv Preprint**

Tianfu Li†, Wenbo Chen†, **Haoxuan Xu†**, et al.

- Unified perception, prediction, and planning in a single VLN network, using intermediate modules to sharpen scene understanding and boost navigation accuracy.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal</div><img src='https://HaoxuanXU1024.github.io/images/CDCDMA.jpg' alt="CDCDMA" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cross-domain Car Detection Model with Integrated Convolutional Block Attention Mechanism](https://www.sciencedirect.com/science/article/pii/S0262885623002081)

**Image and Vision Computing** (JCR Q1, IF:4.7 | CCF-C)

**Haoxuan Xu†**, Songnung Lai†, Yang Yang~  

- Proposed a complete cross-domain detection framework with an integrated CBAM architecture and GIOU loss optimization.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal</div><img src='https://HaoxuanXU1024.github.io/images/emotion.jpg' alt="Earthquake Analysis" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[How did the Chinese Public Discuss the 2023 Türkiye-Syria Earthquake and the Humanitarian Response on Social Media? A Topical and Sentimental Analysis](https://link.springer.com/article/10.1007/s13753-025-00641-6)

**International Journal of Disaster Risk Science** (JCR Q1 (IF: 5.0))

Mengfan Shen, **Haoxuan Xu**, Hongbing Liu and Ziqiang Han~  

- Applied topic modeling and sentiment analysis to Weibo posts, identifying key themes and public emotions during international disaster response.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal</div><img src='https://HaoxuanXU1024.github.io/images/Multimodal_survey.jpg' alt="Multimodal Survey" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multimodal Sentiment Analysis: A Survey](https://www.sciencedirect.com/science/article/pii/S0141938223001968)

**Displays** (JCR Q1 (IF: 4.3))

Songning Lai, Xifeng Hu, **Haoxuan Xu**, Zhaoxia Ren~ and Zhi Liu~  

- Provides a comprehensive overview of multimodal sentiment analysis, covering its history, datasets, advanced models, and future prospects.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Journal</div><img src='https://HaoxuanXU1024.github.io/images/MG_KG.jpg' alt="MG-KG" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MG-KG: Unsupervised video anomaly detection based on motion guidance and knowledge graph](https://www.sciencedirect.com/science/article/pii/S026288562500232X)

**Image and Vision Computing** (JCR Q1, IF:4.7 | CCF-C)

Qiyue Sun, Yang Yang, **Haoxuan Xu**, Zezhou Li, Yunxia Liu and Hongjun Wang~  

- Addresses spatio-temporal linkage and interpretability in VAD by unifying motion-guided prediction with knowledge-graph retrieval.
</div>
</div>

# 🔭 Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">RBM Project</div><img src='https://HaoxuanXU1024.github.io/images/667.gif' alt="Service Robot" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Research and Development of Embodied AI-based Multi-terrain Service Robot**

- Used ConceptGraph for open-vocabulary scene mapping and CLIP/GPT4 for object retrieval.
- Implemented optimized A* and KD-Tree for path planning.
- Deployed on Songling chassis for sim-to-real transition.
</div>
</div>

# 🎖 Honors and Awards
- **Postgraduate Studentship (PGS) Award**, HKUST(GZ)
- **First Prize**, National College Student Mathematical Modeling Competition (Shandong Province)
- **Second Prize**, 14th National College Student Mathematics Competition
- **Outstanding Graduate**, Shandong University

# 💻 Internships
- **Image Algorithm Intern**, [DJI](https://www.dji.com/cn), 2023.11 – 2024.4
- **Research Intern**, KAUST, 2023.12 – 2024.03
- **Outstanding Volunteer**, Shandong University (over 200h)
