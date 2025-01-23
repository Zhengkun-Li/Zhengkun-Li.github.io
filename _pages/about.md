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
I am a robotics engineer and researcher working with <a href='https://www.tricrobotics.com/'>TRIC Robotics </a>, and focusing on agricultural robotics, automation, and deep learning-based perception techniques. I am proud of working with our teams to take cutting-edge AI technologies to our robotic system and data management system, enhancing automation’s robustness and smarter farming applications! 

Before that, I studied Electrical and Biological Engineering at University of Georgia from Aug 2021 to Dec 2022. Then, I graduated from Agricultural and Biological Engineering at University of Folorida in December 2024. During the past years, I was a graduate research assistant in <a href='https://uflbsail.net/'>BSAIL Research Group</a>, working with <a href='https://scholar.google.com/citations?user=3A9RLWwAAAAJ&hl=en'> Dr.Changying Li </a>.

# 💻 Research Interests
- *Agricultural Robotics*
- *Computer vision and deep learning*
- *High-Throughput Phenotyping*

# 📖 Educations
- *2023.01 - 2024.12*, Master degree, Agricultural and Biological Engineering, University of Folorida, Gainesville, Folorida, USA
- *2021.01 - 2022.12*, Graduate research Assistant, Electrical and Computer Engineering, University of Georgia, Athens, Georgia, USA.
- *2016.09 - 2020.06*, Undergraduate student, Mechanical Engineering, Northwest Agriculture and Forestry University, Yangling, Shaanxi, China.

# 🔥 News
- *2025.01*: &nbsp;🎉🎉 Excited to join <a href='https://www.tricrobotics.com/'>TRIC Robotics </a> as robotic enngineer for robotic pest and disease control!
- *2024.12*: &nbsp;🎉🎉 Graduated and received the Master degree from Agricultral and Boilogical Enfinnering, University of Frorida (<a href='https://www.linkedin.com/feed/update/urn:li:activity:7274230553447452672/'>"Post" </a>)!
- *2024.12*: &nbsp;🎉🎉 The paper <a href='https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.22473'>"Digital Twin/MARS‐CycleGAN" </a> has published on Journal of Field Robotics!
- *2024.07*: &nbsp;🎉🎉 Presented Plot-scale Peanut Yield estimation project in <a href='https://asabemeetings.org/'>ASABE 2024 </a>!
- *2024.07*: &nbsp;🎉🎉 won the first prize in <a href='https://www.aocabfe.org/'>AOCABFE </a> student paper competition!
- *2024.07*: &nbsp;🎉🎉 won the service and leadership award in <a href='https://www.aocabfe.org/'>AOCABFE </a> (Student chair during Aguest 2023 - Auguest 2024)!
- *2023.10*: &nbsp;🎉🎉 Presented Pheno-SAM project in <a href='https://sites.google.com/illinois.edu/iros2023-agrobotics'> IROS 2023 Agrobotic Workshop </a>!
- *2023.07*: &nbsp;🎉🎉 won the second prize in <a href='https://www.aocabfe.org/'>AOCABFE </a> student oral presentation competition!
- *2023.07*: &nbsp;🎉🎉 Presented robotic Blueberry phenotyping project in  <a href='https://www.asabe.org/Events/2023-Annual-International-Meeting'>ASABE 2023 </a>!!
- *2023.04*: &nbsp;🎉🎉 Presented PhenoBot with visual navigation in AGAI conference 2023!
- *2023.01*: &nbsp;🎉🎉 Joined <a href='https://uflbsail.net/'>BSAIL Research Group</a> ， Agricultural and Biological Engineering department, University of Florida!

# 💻 Projects

## Robotic Crop Phenotyping 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASABE 2024</div><a href="https://zhengkun-li.github.io/project/robotic_phenotyping"><img src='/images/publications/Plot-scale_peanut_yield_estimation.jpg' alt="sym" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Robotic Plot-scale Peanut Counting and Yield Estimation using Transformer-based Image Stitching and Detection](https://elibrary.asabe.org/abstract.asp?aid=54774)

**Zhengkun Li**, Rui Xu, Changying Li<sup>*</sup>, Barry Tillman, Nino Brown

[**Paper**](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/images/publications/Plot-scale_peanut_yield_estimation.pdf)     [**Presentation**](https://youtu.be/6KUX528KqG8)

- Robotic plot-scale image stitching based on LoFTR
- Improved real-time RTDETR for peanut pod detection
- SHAI inference for large-resolution Image
- Peanut Yield comparison based on plot-scale counting
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASABE 2023</div><a href="https://zhengkun-li.github.io/project/robotic_phenotyping"><img src='/images/publications/blueberry_project_1.png' alt="sym" width="100%"></a></div></div>
<div class='paper-box-text' markdown="1">

[Blueberry Yield Estimation Through Multi-View Imagery with YOLOv8 Object Detection](https://elibrary.asabe.org/abstract.asp?aid=54189)

**Zhengkun Li**, Changying Li<sup>*</sup>, Rui Xu, Patricio Munoz

[**Paper**](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/images/publications/multi-view%20blueberry%20yield%20estimation.pdf)   [**Poster**](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/project/robotic_phenotyping/robotic_blueberry_phenotyping_poster.pdf)      [**Presentation**](https://www.youtube.com/watch?v=QKO6Pqt4tuA) [**Github**](https://github.com/UGA-BSAIL/BerryNet) 

- Multi-view mobile platform for in-field blueberry phenotyping
- YOLOv8 dedtector for blueberry detection
- Blueberry yield evaluation with multi-view regression
</div>
</div>


## Sim2Real Robotic Transfer: from simulation to reality

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2023</div><img src='project/DT-cycle_GAN/figures/DTcycleGANfig1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dt/mars-cyclegan: Improved object detection for mars phenotyping robot](https://arxiv.org/pdf/2310.12787)

Liu, David, **Zhengkun Li**, Zihao Wu, Changying Li<sup>*</sup>

[**Project**](https://github.com/UGA-BSAIL/DT-MARS-CycleGAN)  [**Paper**](https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.22473) [**Dataset**](https://www.kaggle.com/datasets/zhengkunli3969/dtmars-cyclegan)

- Digital twins for PhenoBot and agricultural field
- DT-CycleGAN: generative agricultural field images
- Zero-shot transfer to the real world dataset
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASABE 2022</div><img src='/images/publications/Phenobot Simulation.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Simulation of an In-field Phenotyping Robot: System Design, Vision-based Navigation and Field Mapping](https://elibrary.asabe.org/abstract.asp?aid=53452)

**Zhengkun Li**, Rui Xu, Changying Li<sup>*</sup>, and Longsheng Fu

[**Paper**](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/images/publications/Phenobot%20Simulation.pdf)   [**Poster**](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/project/robotic_phenotyping/Phenobot_simulation_poster.pdf)      [**Presentation**](https://www.youtube.com/watch?v=2MkA4huXI_0) 

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

[**Report**](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/project/robotic_grasping/Robotic_grasping.pdf)  [**Video**](https://youtu.be/03xThMf7Ot8)

- ROS-based Kinova manipulator control
- YOLO detector for fruit detectin
- RGB-D camera for fruit localization
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> Innovation trainning 2018-2020</div><img src='/project/tomato_classifier/figures/tomato classifier.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Tomato grading system](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0219803)

**Zhengkun Li**, Qunming Liu, Jianxing Li, Yufei Lan, Gangying Shi<sup>*</sup> and Li Liu<sup>*</sup>

[**Paper1**](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/project/tomato_classifier/Tomato%20classifier.pdf)  [**Paper2**](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/project/tomato_classifier/Delta_robot.pdf)  [**Poster**](/project/tomato_classifier/figures/1.jpg)      [**Video1**](https://youtu.be/T6siZ7ZAzVU) [**test**](project/tomato_classifier/tomato_classifier_video.mp4)

- Tomato grading platform with Delta manipulator and vacuum suction cup
- Vision-based non-contact classification algorithm: maturity, size, shape.
- QT-based Software interface
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> Agrobot competition 2017-2018</div><img src='project/robotic_competition/figures/robotic_competition.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Agriclture Harvesting Robot Competition]()

Xing Liang, **Zhengkun Li**, Yingchao Peng, Gangying Shi<sup>*</sup> and Yan Long<sup>*</sup>

[**Video**](https://youtu.be/0XGGfXks-k4) 

- Wheeled base control with STM32 controller: line following control 
- Mechanical design for 5 DoF manipulator
- OpenMV Board for fruit detection
</div>
</div>


# 📝 Publications & Conferences
- **Zhengkun Li**, Rui Xu, Changying Li, Barry Tillman, and Nino Brown. "Robotic Plot-scale Peanut Counting and Yield Estimation using LoFTR-based Image Stitching and Improved RT-DETR." In 2024 ASABE Annual International Meeting, p. 1. American Society of Agricultural and Biological Engineers, 2024.
- Liu, David, **Zhengkun Li**, Zihao Wu, and Changying Li. "Dt/mars-cyclegan: Improved object detection for mars phenotyping robot." arXiv preprint arXiv:2310.12787 (2023).
- **Zhengkun Li**, and Changying Li. "Robotic Vegetable Production." In Encyclopedia of Smart Agriculture Technologies, pp. 1-12. Cham: Springer International Publishing, 2023.
- **Zhengkun Li**, Changying Li, and Patricio Munoz. "Blueberry Yield Estimation Through Multi-View Imagery with YOLOv8 Object Detection." In 2023 ASABE Annual International Meeting, p. 1. American Society of Agricultural and Biological Engineers, 2023.
- **Zhengkun Li**, Rui Xu, Changying Li, and Longsheng Fu. "Simulation of an In-field Phenotyping Robot: System Design, Vision-based Navigation and Field Mapping." In 2022 ASABE Annual International Meeting, p. 1. American Society of Agricultural and Biological Engineers, 2022.
- Liu, Li, **Zhengkun Li**, Yufei Lan, Yinggang Shi, and Yongjie Cui. "Design of a tomato classifier based on machine vision." PloS one 14, no. 7 (2019): e0219803.
- Liu, Li, Xinyu Li, **Zhengkun Li**, and Yinggang Shi. "Application of electronic nose in detection of fresh vegetables freezing time considering odor identification technology." Chemical engineering transactions 68 (2018): 265-270.
## Patents
- **Zhengkun Li**, Li Jianxing, Liu Qunming, etc. A fruit sorting and grabbing mechanism: China, 201821703500.1 [P]. May 14, 2019 
- **Zhengkun Li**, Liu Qunming, LAN Yufei, etc. An automatic fruit grading system: China, 201821703511.X [P]. July 5, 2019 


# 🎖 Honors and Awards
- *2024.07*, won the Service and Leadership Award from the AOCABFE
- *2024.07*, won the first prize in the AOCABFE Student Paper competition 
- *2023.07*, won the second prize in the AOCABFE Student Paper Presentation competition 
- *2023.01-present*, Research Assistantship, University of Florida
- *2022.07*, won the first prize in the AOCABFE student Paper writing competition 
- *2021.01-2022.12*, Research Assistantship, University of Georgia
- *2018.12*, won the first prize at Intelligent Agricultural Equipment Innovation (National level)
- *2018.08*, won the first prize at China Robot Competition (National level) - Harvesting robot Competition
- *2016.09-2020.6*, China National Inspiration Scholarship, Northwest Agriculture and Forestry University (Top 5%)
- *2016.09-2020.6*, First-order Major scholarship, Northwest Agriculture and Forestry University (Top 10%)

# 💬 Leaderships
- *2023.08-2024.08*, Chair of Student Activities Committee in Assiciation of OVerseas Chinese Agricultural, Biological and Food Engineering（<a href='https://www.aocabfe.org/'>AOCABFE </a>）
- *2018.06-2019.12*, Chair of Intelligent Agricultural Equipment Student Club.

# 💻 Professional Memberships
- Institute of Electrical and Electronics Engineering (IEEE)  
- American Society of Agricultural and Biological Engineers (ASABE) 
- Association of Overseas Chinese Agricultural, Biological, and Food Engineers (<a href='https://www.aocabfe.org/'>AOCABFE </a>) 
