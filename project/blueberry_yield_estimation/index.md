---
layout: default
title: "Blueberry Yield Estimation Through Multi-View Imagery with YOLOv8"
permalink: /project/blueberry_yield_estimation/
author_profile: true
---

<div class="project-header" style="margin-bottom: 2.5em; padding-bottom: 1.5em; border-bottom: 2px solid #e0e0e0;">
  <h1 style="margin-bottom: 0.5em; font-size: 1.8em; font-weight: 600; color: #2c3e50;">Blueberry Yield Estimation Through Multi-View Imagery with YOLOv8 Object Detection</h1>
  
  <div style="margin-top: 1em; color: #555; line-height: 1.8;">
    <p style="margin: 0.5em 0;"><strong>Authors:</strong> Zhengkun Li, Changying Li<sup>*</sup>, Rui Xu, Patricio Munoz</p>
    <p style="margin: 0.5em 0;"><strong>Affiliation:</strong> BSAIL Research Group, Department of Agricultural and Biological Engineering, University of Florida</p>
    <p style="margin: 0.5em 0; font-size: 0.9em; color: #777;"><sup>*</sup>Corresponding author</p>
  </div>
</div>

<div class="abstract-box" style="background-color: #f8f9fa; padding: 1.5em; margin: 2em 0; border-left: 4px solid #4a90e2; border-radius: 4px;">
  <h2 style="margin-top: 0; color: #2c3e50; font-size: 1.3em;">Abstract</h2>
  <p style="margin-bottom: 0; line-height: 1.7; text-align: justify;">
    This research presents an automated in-field blueberry fruit phenotyping system that leverages a multi-view mobile robotic platform integrated with advanced deep learning techniques. The system employs YOLOv8-based object detection and multi-view imagery analysis to enable accurate, non-destructive blueberry yield estimation in commercial agricultural settings. Through comprehensive field validation, the proposed approach demonstrates robust performance across varying lighting conditions, fruit maturity stages, and blueberry varieties, offering a scalable solution for precision agriculture applications.
  </p>
</div>

## 1. Introduction

Accurate yield estimation is critical for agricultural planning, resource management, and economic optimization in commercial blueberry production. Traditional manual counting methods are labor-intensive, time-consuming, and subject to human error. Recent advances in computer vision and deep learning offer promising alternatives for automated fruit detection and counting.

This project addresses the challenge of in-field blueberry phenotyping by developing an integrated robotic system that combines:

- **Multi-view image acquisition** using a custom mobile platform with synchronized cameras
- **Deep learning-based detection** with YOLOv8 for robust fruit identification
- **Data fusion algorithms** for accurate yield estimation from multiple viewpoints

## 2. Methodology

### 2.1 System Architecture

The proposed system consists of three main components:

1. **Mobile Robotic Platform**: A custom-designed multi-camera imaging system capable of capturing synchronized views from multiple angles
2. **Detection Module**: YOLOv8-based deep learning model optimized for blueberry fruit detection
3. **Yield Estimation Module**: Multi-view regression algorithm for aggregating detection results and estimating total yield

### 2.2 Multi-View Image Acquisition

The mobile platform employs multiple cameras positioned at strategically selected angles to maximize fruit visibility. This multi-view approach addresses several key challenges:

- **Occlusion handling**: Fruits occluded from one view become visible from alternative perspectives
- **Detection validation**: Redundant views enable cross-validation of detection results
- **Spatial understanding**: Multiple viewpoints facilitate 3D spatial reconstruction of fruit distribution

### 2.3 YOLOv8 Object Detection

YOLOv8 (You Only Look Once version 8) was selected as the core detection algorithm due to its balance between accuracy and real-time performance. The model was:

- **Trained** on an extensive dataset of in-field blueberry images collected across multiple seasons
- **Optimized** for deployment on mobile computing platforms with limited computational resources
- **Fine-tuned** to handle varying:
  - Lighting conditions (morning, midday, evening)
  - Fruit maturity stages (unripe, partially ripe, fully ripe)
  - Environmental conditions (sunny, cloudy, overcast)

### 2.4 Multi-View Regression for Yield Estimation

A custom regression model aggregates detection results from multiple viewpoints while accounting for:

- Viewpoint-dependent visibility factors
- Spatial overlap between views
- Confidence scores from individual detections
- Statistical uncertainty quantification

## 3. Results and Validation

The system was extensively validated in commercial blueberry fields with the following outcomes:

<div class="results-box" style="margin: 2em 0; padding: 1.5em; background-color: #f0f7ff; border-radius: 6px;">
  <h3 style="margin-top: 0; color: #1a5490;">Key Performance Metrics</h3>
  <ul style="margin: 1em 0; padding-left: 1.5em;">
    <li><strong>Detection Accuracy:</strong> High precision and recall across diverse field conditions</li>
    <li><strong>Real-time Performance:</strong> Suitable for field deployment with processing times meeting operational requirements</li>
    <li><strong>Yield Estimation Accuracy:</strong> Strong correlation with manual ground truth measurements</li>
    <li><strong>Robustness:</strong> Consistent performance across different blueberry varieties and growth stages</li>
  </ul>
</div>

## 4. Publications

<div class="publication-list" style="margin: 2em 0;">
  <div class="publication-item" style="margin-bottom: 1.5em; padding: 1em; background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 4px;">
    <h3 style="margin-top: 0; font-size: 1.1em; color: #2c3e50;">Journal Article</h3>
    <p style="margin: 0.5em 0; line-height: 1.6;">
      <strong>Li, Z.</strong>, Xu, R., Li, C., Munoz, P., Takeda, F., & Leme, B. (2025). In-field blueberry fruit phenotyping with a MARS-PhenoBot and customized BerryNet. <em>Computers and Electronics in Agriculture</em>, 232, 110057.
    </p>
    <p style="margin: 0.5em 0;">
      <a href="https://www.sciencedirect.com/science/article/pii/S0168169925001632" target="_blank" style="color: #4a90e2; text-decoration: none; border-bottom: 1px solid #4a90e2;">View Article →</a>
      <span style="color: #999; margin: 0 1em;">|</span>
      <a href="https://doi.org/10.1016/j.compag.2025.110057" target="_blank" style="color: #4a90e2; text-decoration: none; border-bottom: 1px solid #4a90e2;">DOI: 10.1016/j.compag.2025.110057</a>
    </p>
  </div>

  <div class="publication-item" style="margin-bottom: 1.5em; padding: 1em; background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 4px;">
    <h3 style="margin-top: 0; font-size: 1.1em; color: #2c3e50;">Conference Paper</h3>
    <p style="margin: 0.5em 0; line-height: 1.6;">
      <strong>Li, Z.</strong>, Li, C., & Munoz, P. (2023). Blueberry Yield Estimation Through Multi-View Imagery with YOLOv8 Object Detection. <em>Proceedings of the ASABE Annual International Meeting</em>, Paper No. 2300129. St. Joseph, MI: ASABE.
    </p>
    <p style="margin: 0.5em 0;">
      <a href="https://elibrary.asabe.org/abstract.asp?aid=54189" target="_blank" style="color: #4a90e2; text-decoration: none; border-bottom: 1px solid #4a90e2;">View Abstract →</a>
    </p>
  </div>
</div>

## 5. Project Resources

<div class="resources-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1em; margin: 2em 0;">
  <div style="padding: 1.2em; background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 6px; text-align: center;">
    <div style="font-size: 2em; margin-bottom: 0.5em;">📄</div>
    <h4 style="margin: 0.5em 0; color: #2c3e50;">Conference Paper</h4>
    <a href="https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/images/publications/multi-view%20blueberry%20yield%20estimation.pdf" target="_blank" style="color: #4a90e2; text-decoration: none;">Download PDF →</a>
  </div>
  
  <div style="padding: 1.2em; background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 6px; text-align: center;">
    <div style="font-size: 2em; margin-bottom: 0.5em;">🖼️</div>
    <h4 style="margin: 0.5em 0; color: #2c3e50;">Conference Poster</h4>
    <a href="/project/blueberry_yield_estimation/documents/robotic_blueberry_phenotyping_poster.pdf" target="_blank" style="color: #4a90e2; text-decoration: none;">View Poster →</a>
  </div>
  
  <div style="padding: 1.2em; background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 6px; text-align: center;">
    <div style="font-size: 2em; margin-bottom: 0.5em;">🎥</div>
    <h4 style="margin: 0.5em 0; color: #2c3e50;">Presentation Video</h4>
    <a href="https://www.youtube.com/watch?v=QKO6Pqt4tuA" target="_blank" style="color: #4a90e2; text-decoration: none;">Watch Video →</a>
  </div>
  
  <div style="padding: 1.2em; background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 6px; text-align: center;">
    <div style="font-size: 2em; margin-bottom: 0.5em;">💻</div>
    <h4 style="margin: 0.5em 0; color: #2c3e50;">GitHub Repository</h4>
    <a href="https://github.com/UGA-BSAIL/BerryNet" target="_blank" style="color: #4a90e2; text-decoration: none;">View Code →</a>
  </div>
</div>

## 6. Technical Implementation

<div class="technical-highlights" style="margin: 2em 0;">
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.5em;">
    <div style="padding: 1.5em; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; border-radius: 8px;">
      <h3 style="margin-top: 0; color: white;">Multi-View Acquisition</h3>
      <p style="margin-bottom: 0; opacity: 0.95;">Custom mobile platform with synchronized multi-camera system for comprehensive fruit coverage</p>
    </div>
    
    <div style="padding: 1.5em; background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%); color: white; border-radius: 8px;">
      <h3 style="margin-top: 0; color: white;">Deep Learning</h3>
      <p style="margin-bottom: 0; opacity: 0.95;">YOLOv8 optimized for real-time fruit detection with high accuracy in field conditions</p>
    </div>
    
    <div style="padding: 1.5em; background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%); color: white; border-radius: 8px;">
      <h3 style="margin-top: 0; color: white;">Data Fusion</h3>
      <p style="margin-bottom: 0; opacity: 0.95;">Multi-view regression model for accurate yield estimation with uncertainty quantification</p>
    </div>
    
    <div style="padding: 1.5em; background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%); color: white; border-radius: 8px;">
      <h3 style="margin-top: 0; color: white;">Field Validation</h3>
      <p style="margin-bottom: 0; opacity: 0.95;">Extensive testing in commercial blueberry fields across multiple seasons and varieties</p>
    </div>
  </div>
</div>

## 7. Visual Documentation

{% include gallery.html 
   folder="project/blueberry_yield_estimation/images" 
   title="Project Images" 
   columns="3" 
   gap="15px" 
   thumb_max_height="280px" 
%}

## 8. Key Contributions

This research makes several important contributions to the field of agricultural robotics and computer vision:

- ✅ **Novel Multi-View Framework**: First application of synchronized multi-view imaging for in-field blueberry phenotyping
- ✅ **Real-Time Performance**: Optimized deep learning pipeline suitable for mobile field deployment
- ✅ **Robust Detection**: High accuracy across varying environmental conditions and fruit maturity stages
- ✅ **Scalable Solution**: Framework adaptable to other fruit crops and agricultural applications
- ✅ **Validated System**: Extensive field validation demonstrating practical applicability

---

<div class="contact-info" style="margin-top: 3em; padding-top: 2em; border-top: 2px solid #e0e0e0; text-align: center; color: #666;">
  <p style="margin: 0.5em 0;"><strong>For more information about this project, please refer to the publications or contact:</strong></p>
  <p style="margin: 0.5em 0;">
    <a href="mailto:zhengkun.li3969@gmail.com" style="color: #4a90e2; text-decoration: none;">zhengkun.li3969@gmail.com</a>
  </p>
</div>
