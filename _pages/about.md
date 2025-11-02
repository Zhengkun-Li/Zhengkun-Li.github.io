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

# About Me
I am a robotics engineer and researcher at <a href='https://www.tricrobotics.com/'>TRIC Robotics</a>, specializing in agricultural robotics, automation, and deep learning-based perception. My work focuses on integrating advanced AI technologies into robotic and data systems to improve automation robustness and enable smarter farming solutions.

My academic journey began at the University of Georgia, where I started my Ph.D. in Electrical and Computer Engineering in August 2021 under the supervision of <a href='https://scholar.google.com/citations?user=3A9RLWwAAAAJ&hl=en'>Dr. Changying Li</a>. In January 2023, I transferred with Dr. Li to the University of Florida to continue doctoral studies in Agricultural and Biological Engineering. During this academic time, I served as a graduate research assistant in the <a href='https://uflbsail.net/'>BSAIL Research Group</a>, conducting research on agricultural robotics and automation until December 2024.

In late 2024, I transitioned from academia to industry by joining agtech startup as core robotic engineer in TRIC Robotics, where I contribute to advancing chemical-free farming through robotics and supporting the company's mission to drive sustainable agriculture.

# 💻 Research Interests
- *Agricultural Robotics*
- *Computer vision and deep learning*
- *High-Throughput Phenotyping*

# 📖 Educations
- *2024.12* — M.S., Agricultural and Biological Engineering, University of Florida, Gainesville, USA
- *2023.01 – 2024.12* — Ph.D. Student, Agricultural and Biological Engineering, University of Florida, Gainesville, USA
- *2021.08 – 2022.12* — Ph.D. Student, Electrical and Computer Engineering, University of Georgia, Athens, USA
- *2016.09 – 2020.06* — B.Eng., Mechanical Engineering, Northwest A&F University, Yangling, China

# 🔥 News
- *2025.07* 🎉 New publication <a href='https://www.sciencedirect.com/science/article/pii/S2772375525003867'>"Plot-scale peanut yield estimation using a phenotyping robot and transformer-based image analysis"</a> published in *Smart Agricultural Technology*.
- *2025.03* 🎉 New publication <a href='https://www.sciencedirect.com/science/article/pii/S2772375525001431'>"Visual navigation and crop mapping of a phenotyping robot MARS-PhenoBot in simulation"</a> published in *Smart Agricultural Technology*.
- *2025.02* 🎉 New publication <a href='https://www.sciencedirect.com/science/article/pii/S0168169925001632'>"Robotic blueberry phenotyping using customized BerryNet"</a> published in *Computers and Electronics in Agriculture*.
- *2025.01* 👨‍💻 Joined <a href='https://www.tricrobotics.com/'>TRIC Robotics</a> as robotic engineer for robotic pest and disease control.
- *2024.12* 🎓 Graduated with Master’s degree in Agricultural and Biological Engineering, University of Florida (<a href='https://www.linkedin.com/feed/update/urn:li:activity:7274230553447452672/'>Post</a>).
- *2024.12* 🎉 Publication <a href='https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.22473'>"Digital Twin/MARS‐CycleGAN"</a> published in *Journal of Field Robotics*.
- *2024.07* 📢 Presented plot-scale peanut yield estimation project at <a href='https://asabemeetings.org/'>ASABE 2024</a>.
- *2024.07* 🏆 Won **first prize** in <a href='https://www.aocabfe.org/'>AOCABFE</a> student paper competition.
- *2024.07* 🏆 Won **Service and Leadership Award** in ASABE <a href='https://www.aocabfe.org/'>AOCABFE</a> (served as Student Chair, 2023.08 – 2024.08).
- *2023.10* 📢 Presented Pheno-SAM project at <a href='https://sites.google.com/illinois.edu/iros2023-agrobotics'>IROS 2023 Agrobotics Workshop</a>.
- *2023.07* 🏆 Won **second prize** in <a href='https://www.aocabfe.org/'>AOCABFE</a> student oral presentation competition.
- *2023.07* 📢 Presented robotic blueberry phenotyping project at <a href='https://www.asabe.org/Events/2023-Annual-International-Meeting'>ASABE 2023</a>.
- *2023.04* 📢 Presented PhenoBot with visual navigation at AGAI Conference 2023.
- *2023.01* 👨‍💻 Joined <a href='https://uflbsail.net/'>BSAIL Research Group</a>, Agricultural and Biological Engineering, University of Florida.

# 💻 Projects

## Robotic Crop Phenotyping 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASABE 2024</div><a href="/project/peanut_yield_estimation/"><img src='/images/publications/Plot-scale_peanut_yield_estimation.jpg' alt="sym" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Robotic Plot-scale Peanut Counting and Yield Estimation using Transformer-based Image Stitching and Detection](https://elibrary.asabe.org/abstract.asp?aid=54774)

**Zhengkun Li**, Rui Xu, Changying Li<sup>*</sup>, Barry Tillman, Nino Brown

[**Journal**](https://www.sciencedirect.com/science/article/pii/S2772375525003867)  [**Conference**](/project/peanut_yield_estimation/documents/Plot-scale_peanut_yield_estimation.pdf)     [**Presentation**](https://youtu.be/6KUX528KqG8)

- Robotic plot-scale image stitching based on LoFTR
- Improved real-time RTDETR for peanut pod detection
- SHAI inference for large-resolution Image
- Peanut Yield comparison based on plot-scale counting
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASABE 2023</div><a href="/project/blueberry_yield_estimation/"><img src='/images/publications/blueberry_project_1.png' alt="sym" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Blueberry Yield Estimation Through Multi-View Imagery with YOLOv8 Object Detection](https://elibrary.asabe.org/abstract.asp?aid=54189)

**Zhengkun Li**, Changying Li<sup>*</sup>, Rui Xu, Patricio Munoz

[**Journal**](https://www.sciencedirect.com/science/article/pii/S0168169925001632)  [**Conference**](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/images/publications/multi-view%20blueberry%20yield%20estimation.pdf)   [**Poster**](/project/blueberry_yield_estimation/documents/robotic_blueberry_phenotyping_poster.pdf)      [**Presentation**](https://www.youtube.com/watch?v=QKO6Pqt4tuA) [**Github**](https://github.com/UGA-BSAIL/BerryNet) 

- Multi-view mobile platform for in-field blueberry phenotyping
- YOLOv8 detector for blueberry detection
- Blueberry yield evaluation with multi-view regression
</div>
</div>


## Sim2Real Robotic Transfer: from simulation to reality

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><a href="/project/dt_cyclegan/"><img src='project/dt_cyclegan/images/DTcycleGANfig1.png' alt="sym" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Dt/mars-cyclegan: Improved object detection for mars phenotyping robot](https://arxiv.org/pdf/2310.12787)

Liu, David, **Zhengkun Li**, Zihao Wu, Changying Li<sup>*</sup>

[**Project**](https://github.com/UGA-BSAIL/DT-MARS-CycleGAN)  [**Paper**](https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.22473) [**Dataset**](https://www.kaggle.com/datasets/zhengkunli3969/dtmars-cyclegan)  [**PDF**](/project/dt_cyclegan/documents/DT-cycleGAN.pdf)

- Digital twins for PhenoBot and agricultural field
- DT-CycleGAN: generative agricultural field images
- Zero-shot transfer to the real world dataset
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASABE 2022</div><a href="/project/phenobot_simulation/"><img src='project/phenobot_simulation/images/Phenobot Simulation.png' alt="sym" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Simulation of an In-field Phenotyping Robot: System Design, Vision-based Navigation and Field Mapping](https://elibrary.asabe.org/abstract.asp?aid=53452)

**Zhengkun Li**, Rui Xu, Changying Li<sup>*</sup>, and Longsheng Fu

[**Journal**](https://www.sciencedirect.com/science/article/pii/S2772375525001431)  [**Conference**](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/images/publications/Phenobot%20Simulation.pdf)  [**Poster**](/project/phenobot_simulation/documents/Phenobot_simulation_poster.pdf)      [**Presentation**](https://www.youtube.com/watch?v=2MkA4huXI_0) 

- develop a phenotyping robot to perform field phenotyping tasks
- design a vision-based navigation algorithm and evaluate its efficacy
- explore the field mapping pipeline for 3D crop mapping in the field
</div>
</div>

# Previous Projects

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> Course Project 2022</div><img src='project/robotic_grasping/figures/grasp1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Robotic Arm for fruit sensing]

**Zhengkun Li**, Changying Li<sup>*</sup>

[**Report**](/project/robotic_grasping/documents/Robotic_grasping.pdf)  [**Video**](https://youtu.be/03xThMf7Ot8)

- ROS-based Kinova manipulator control
- YOLO detector for fruit detection
- RGB-D camera for fruit localization
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> Innovation training 2018-2020</div><img src='/project/tomato_classifier/figures/tomato classifier.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Tomato grading system](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0219803)

**Zhengkun Li**, Qunming Liu, Jianxing Li, Yufei Lan, Gangying Shi<sup>*</sup> and Li Liu<sup>*</sup>

[**Paper1**](/project/tomato_classifier/documents/Tomato%20classifier.pdf)  [**Paper2**](/project/tomato_classifier/documents/Delta_robot.pdf)  [**Poster**](/project/tomato_classifier/figures/1.jpg)      [**Video1**](https://youtu.be/T6siZ7ZAzVU) [**Video2**](/project/tomato_classifier/tomato_classifier_video.mp4)

- Tomato grading platform with Delta manipulator and vacuum suction cup
- Vision-based non-contact classification algorithm: maturity, size, shape.
- QT-based Software interface
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> Agrobot competition 2017-2018</div><img src='project/robotic_competition/figures/robotic_competition.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Agriculture Harvesting Robot Competition]()

Xing Liang, **Zhengkun Li**, Yingchao Peng, Gangying Shi<sup>*</sup> and Yan Long<sup>*</sup>

[**Video**](https://youtu.be/0XGGfXks-k4) 

- Wheeled base control with STM32 controller: line following control 
- Mechanical design for 5 DoF manipulator
- OpenMV Board for fruit detection
</div>
</div>


<span class='anchor' id='publications-conferences'></span>

# 📝 Publications & Conferences
- **Li, Z.**, Xu, R., Brown, N., Tillman, B. L., & Li, C. (2025). Plot-scale peanut yield estimation using a phenotyping robot and transformer-based image analysis. *Smart Agricultural Technology*, 101154. https://doi.org/10.1016/j.satech.2025.101154
- **Li, Z.**, Xu, R., Li, C., & Fu, L. (2025). Visual navigation and crop mapping of a phenotyping robot MARS-PhenoBot in simulation. *Smart Agricultural Technology*, 100910. https://doi.org/10.1016/j.satech.2025.100910
- **Li, Z.**, Xu, R., Li, C., Munoz, P., Takeda, F., & Leme, B. (2025). In-field blueberry fruit phenotyping with a MARS-PhenoBot and customized BerryNet. *Computers and Electronics in Agriculture*, 232, 110057. https://doi.org/10.1016/j.compag.2025.110057
- Liu, D., **Li, Z.**, Wu, Z., & Li, C. (2024). Digital Twin/MARS‐CycleGAN: Enhancing Sim‐to‐Real crop/row detection for MARS phenotyping robot using synthetic images. *Journal of Field Robotics*. https://doi.org/10.1002/rob.22473
- **Li, Z.**, Xu, R., Li, C., Tillman, B., & Brown, N. (2024). Robotic plot-scale peanut counting and yield estimation using LoFTR-based image stitching and improved RT-DETR. In *Proceedings of the ASABE Annual International Meeting* (pp. 1–7). St. Joseph, MI: ASABE. https://elibrary.asabe.org/abstract.asp?aid=54774
- Liu, D., **Li, Z.**, Wu, Z., & Li, C. (2023). Dt/MARS-CycleGAN: Improved object detection for MARS phenotyping robot. *arXiv preprint* arXiv:2310.12787.
- **Li, Z.**, & Li, C. (2023). Robotic vegetable production. In *Encyclopedia of Smart Agriculture Technologies* (pp. 1–12). Cham: Springer International Publishing. https://doi.org/10.1007/978-3-031-37766-4_104-1
- **Li, Z.**, Li, C., & Munoz, P. (2023). Blueberry yield estimation through multi-view imagery with YOLOv8 object detection. In *Proceedings of the ASABE Annual International Meeting* (pp. 1–6). St. Joseph, MI: ASABE. https://elibrary.asabe.org/abstract.asp?aid=54189
- **Li, Z.**, Xu, R., Li, C., & Fu, L. (2022). Simulation of an in-field phenotyping robot: System design, vision-based navigation, and field mapping. In *Proceedings of the ASABE Annual International Meeting* (pp. 1–7). St. Joseph, MI: ASABE. https://elibrary.asabe.org/abstract.asp?aid=53452
- Liu, L., **Li, Z.**, Lan, Y., Shi, Y., & Cui, Y. (2019). Design of a tomato classifier based on machine vision. *PLoS ONE*, 14(7), e0219803. https://doi.org/10.1371/journal.pone.0219803
- Liu, L., Li, X., **Li, Z.**, & Shi, Y. (2018). Application of electronic nose in detection of fresh vegetables freezing time considering odor identification technology. *Chemical Engineering Transactions*, 68, 265–270. https://doi.org/10.3303/CET1868045

## 📑 Patents
- **Li, Z.**, Jianxing, L., Qunming, L., et al. (2019). A fruit sorting and grabbing mechanism. China Patent No. 201821703500.1. Filed May 14, 2019.
- **Li, Z.**, Qunming, L., Yufei, L., et al. (2019). An automatic fruit grading system. China Patent No. 201821703511.X. Filed July 5, 2019.

# 🎖 Honors and Awards
- *2024.07* 🏆 **Li, Z.** — Service and Leadership Award, AOCABFE  
- *2024.07* 🏆 **Li, Z.** — First Prize, AOCABFE Student Paper Competition  
- *2023.07* 🏆 **Li, Z.** — Second Prize, AOCABFE Student Oral Presentation Competition  
- *2023.01 – 2024.12* 🎓 **Li, Z.** — Research Assistantship, University of Florida  
- *2022.07* 🏆 **Li, Z.** — First Prize, AOCABFE Student Paper Writing Competition  
- *2021.01 – 2022.12* 🎓 **Li, Z.** — Research Assistantship, University of Georgia  
- *2018.12* 🏆 **Li, Z.** — First Prize, Intelligent Agricultural Equipment Innovation (National level)  
- *2018.08* 🏆 **Li, Z.** — First Prize, China Robot Competition (National level, Harvesting Robot)  
- *2016.09 – 2020.06* 🎓 **Li, Z.** — China National Inspiration Scholarship, Northwest A&F University (Top 5%)  
- *2016.09 – 2020.06* 🎓 **Li, Z.** — First-order Major Scholarship, Northwest A&F University (Top 10%)

# 💬 Leaderships
- *2023.08-2024.08*, Chair of Student Activities Committee in Association of Overseas Chinese Agricultural, Biological and Food Engineering（<a href='https://www.aocabfe.org/'>AOCABFE </a>）
- *2018.06-2019.12*, Chair of Intelligent Agricultural Equipment Student Club.

# 💻 Professional Memberships
- Institute of Electrical and Electronics Engineering (IEEE)  
- American Society of Agricultural and Biological Engineers (ASABE) 
- Association of Overseas Chinese Agricultural, Biological, and Food Engineers (<a href='https://www.aocabfe.org/'>AOCABFE </a>) 
