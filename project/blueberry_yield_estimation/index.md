---
layout: default
title: "Blueberry Yield Estimation Through Multi-View Imagery with YOLOv8"
permalink: /project/blueberry_yield_estimation/
author_profile: true
---

# Blueberry Yield Estimation Through Multi-View Imagery with YOLOv8 Object Detection

**Authors:** Zhengkun Li, Changying Li<sup>*</sup>, Rui Xu, Patricio Munoz

**Affiliation:** BSAIL Research Group, University of Florida

---

## 📋 Overview

This project focuses on developing an automated in-field blueberry fruit phenotyping system using a multi-view mobile robotic platform and advanced deep learning techniques. The system enables accurate blueberry yield estimation through multi-view imagery analysis and YOLOv8-based object detection, providing a non-destructive approach for agricultural monitoring.

## 🎯 Key Objectives

- Develop a mobile multi-view imaging platform for in-field blueberry phenotyping
- Implement YOLOv8-based detection algorithm for accurate blueberry fruit detection
- Create a multi-view regression model for blueberry yield estimation
- Validate the system's performance in real-world agricultural settings

## 🔬 Methodology

### Multi-View Mobile Platform

The system utilizes a custom-designed mobile robotic platform equipped with multiple cameras positioned at different angles to capture comprehensive views of blueberry bushes. This multi-view approach significantly improves detection accuracy by:

- Capturing occluded fruits from different perspectives
- Providing redundancy for detection validation
- Enabling 3D spatial understanding of fruit distribution

### YOLOv8 Object Detection

We employed YOLOv8 (You Only Look Once version 8), one of the state-of-the-art object detection models, for blueberry fruit detection. The model was:

- Trained on a large dataset of in-field blueberry images
- Optimized for real-time performance on mobile platforms
- Fine-tuned for varying lighting conditions and fruit maturity stages

### Multi-View Regression for Yield Estimation

A regression model was developed to estimate total yield by:

- Aggregating detection results from multiple viewpoints
- Accounting for fruit visibility from different angles
- Providing uncertainty quantification for yield predictions

## 🚀 Results

The system demonstrated:

- High detection accuracy in diverse field conditions
- Real-time processing capabilities suitable for field deployment
- Accurate yield estimation compared to manual ground truth measurements
- Robust performance across different blueberry varieties and growth stages

## 📚 Publications

- **Journal Article:** [In-field blueberry fruit phenotyping with a MARS-PhenoBot and customized BerryNet](https://www.sciencedirect.com/science/article/pii/S0168169925001632), *Computers and Electronics in Agriculture*, 232, 110057 (2025)

- **Conference Paper:** [Blueberry Yield Estimation Through Multi-View Imagery with YOLOv8 Object Detection](https://elibrary.asabe.org/abstract.asp?aid=54189), *Proceedings of the ASABE Annual International Meeting* (2023)

## 🔗 Resources

- [**Conference Paper**](https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/images/publications/multi-view%20blueberry%20yield%20estimation.pdf)
- [**Poster**](/project/robotic_phenotyping/robotic_blueberry_phenotyping_poster.pdf)
- [**Presentation Video**](https://www.youtube.com/watch?v=QKO6Pqt4tuA)
- [**GitHub Repository**](https://github.com/UGA-BSAIL/BerryNet)

## 🛠️ Technical Highlights

- **Multi-view image acquisition:** Custom mobile platform with synchronized multi-camera system
- **Deep learning:** YOLOv8 for real-time fruit detection
- **Data fusion:** Multi-view regression for yield estimation
- **Field validation:** Extensive testing in commercial blueberry fields

## 📸 Project Gallery

{% include gallery.html 
   folder="project/blueberry_yield_estimation/images" 
   title="Project Images" 
   columns="3" 
   gap="12px" 
   thumb_max_height="250px" 
%}


## 📝 Key Features

- ✅ Multi-view mobile platform for in-field blueberry phenotyping
- ✅ YOLOv8 detector optimized for blueberry detection
- ✅ Real-time processing capabilities
- ✅ Accurate yield evaluation with multi-view regression
- ✅ Field-tested and validated in commercial settings

---

*For more information about this project, please refer to the publications or contact the authors.*

