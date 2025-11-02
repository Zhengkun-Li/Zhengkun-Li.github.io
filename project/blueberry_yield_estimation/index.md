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

<div class="resources-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.5em; margin: 2em 0;">
  <!-- Conference Paper -->
  <div style="background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.1); transition: transform 0.3s, box-shadow 0.3s;" onmouseover="this.style.transform='translateY(-5px)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'" onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 2px 8px rgba(0,0,0,0.1)'">
    <a href="https://github.com/Zhengkun-Li/Zhengkun-Li.github.io/blob/main/images/publications/multi-view%20blueberry%20yield%20estimation.pdf" target="_blank" style="text-decoration: none; color: inherit;">
      <div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); padding: 1.5em; text-align: center; color: white;">
        <div style="font-size: 3em; margin-bottom: 0.5em;">📄</div>
        <h4 style="margin: 0; color: white; font-size: 1.1em;">Conference Paper</h4>
      </div>
      <div style="padding: 1em; text-align: center;">
        <div style="margin: 0.8em 0; color: #666; font-size: 0.9em;">ASABE 2023</div>
        <div style="color: #4a90e2; font-weight: 500; margin-top: 1em;">Download PDF →</div>
      </div>
    </a>
  </div>
  
  <!-- Conference Poster -->
  <div style="background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.1); transition: transform 0.3s, box-shadow 0.3s;" onmouseover="this.style.transform='translateY(-5px)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'" onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 2px 8px rgba(0,0,0,0.1)'">
    <a href="/project/blueberry_yield_estimation/documents/robotic_blueberry_phenotyping_poster.pdf" target="_blank" style="text-decoration: none; color: inherit;">
      <div style="position: relative; background: #f5f5f5; padding: 1em; text-align: center; min-height: 180px; display: flex; align-items: center; justify-content: center;">
        <div style="font-size: 4em; opacity: 0.3;">🖼️</div>
        <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); font-size: 0.85em; color: #999;">Poster Preview</div>
      </div>
      <div style="padding: 1em; text-align: center; background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);">
        <h4 style="margin: 0; color: white; font-size: 1.1em;">Conference Poster</h4>
        <div style="color: rgba(255,255,255,0.9); font-weight: 500; margin-top: 0.5em;">View PDF →</div>
      </div>
    </a>
  </div>
  
  <!-- Presentation Video -->
  <div style="background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.1); transition: transform 0.3s, box-shadow 0.3s;" onmouseover="this.style.transform='translateY(-5px)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'" onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 2px 8px rgba(0,0,0,0.1)'">
    <a href="https://www.youtube.com/watch?v=QKO6Pqt4tuA" target="_blank" style="text-decoration: none; color: inherit;">
      <div style="position: relative; background: #000; padding: 0; min-height: 180px; overflow: hidden;">
        <img src="https://img.youtube.com/vi/QKO6Pqt4tuA/maxresdefault.jpg" alt="Video thumbnail" style="width: 100%; height: 100%; object-fit: cover; opacity: 0.9;" onerror="this.style.display='none'; this.parentElement.innerHTML='<div style=\'color: white; text-align: center; padding: 2em; font-size: 3em;\'>🎥</div>'">
        <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); width: 60px; height: 60px; background: rgba(255,0,0,0.8); border-radius: 50%; display: flex; align-items: center; justify-content: center; cursor: pointer;">
          <div style="width: 0; height: 0; border-left: 20px solid white; border-top: 12px solid transparent; border-bottom: 12px solid transparent; margin-left: 5px;"></div>
        </div>
      </div>
      <div style="padding: 1em; text-align: center; background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);">
        <h4 style="margin: 0; color: white; font-size: 1.1em;">Presentation Video</h4>
        <div style="color: rgba(255,255,255,0.9); font-weight: 500; margin-top: 0.5em;">Watch on YouTube →</div>
      </div>
    </a>
  </div>
  
  <!-- GitHub Repository -->
  <div style="background-color: #ffffff; border: 1px solid #e0e0e0; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.1); transition: transform 0.3s, box-shadow 0.3s;" onmouseover="this.style.transform='translateY(-5px)'; this.style.boxShadow='0 4px 12px rgba(0,0,0,0.15)'" onmouseout="this.style.transform='translateY(0)'; this.style.boxShadow='0 2px 8px rgba(0,0,0,0.1)'">
    <a href="https://github.com/UGA-BSAIL/BerryNet" target="_blank" style="text-decoration: none; color: inherit;">
      <div style="background: linear-gradient(135deg, #2d3748 0%, #1a202c 100%); padding: 1.5em; text-align: center; color: white; min-height: 140px; display: flex; flex-direction: column; justify-content: center;">
        <svg style="width: 48px; height: 48px; margin: 0 auto 0.5em; fill: white;" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
        <h4 style="margin: 0.5em 0 0 0; color: white; font-size: 1.1em;">GitHub Repository</h4>
        <div style="color: rgba(255,255,255,0.8); font-size: 0.85em; margin-top: 0.3em;">UGA-BSAIL/BerryNet</div>
      </div>
      <div style="padding: 1em; text-align: center; background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);">
        <div style="color: white; font-weight: 500;">View Source Code →</div>
      </div>
    </a>
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
