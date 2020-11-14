---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.Eng. in Computer Science, Hong Kong University of Science and Technology, 2020

Experience
======
* Research Assistant @ Computer Vision Lab, Academia Sinica
  * Sep 2020 - Present
  * Researched on single image view 3D mesh reconstruction
  * Supervisor: Professor Liu Tyng-Luh

* Undergraduate Researcher @ HKUST
  * Human Atomic Action Recognition (Submitted to CVPR)
    * Supervised by Prof. Chi-Keung Tang and Prof Yu-Wing Tai
    * Proposed a novel fine-grained human-centric atomic action dataset for action recognition
    * Implemented an action detection model that aggregates human-pose estimation and optical flow
    * Demonstrated the effectiveness of fine-grained atomic action labels and noise-free action clips
   
   * Deep HDR Image Processing with HDR
     * Supervised by Prof. Chen Qifeng
     * Established an image processing pipeline with tone-mapping algorithms for High-Dynamic-Range (HDR) sensors
     * Proposed a deep U-Net and designed synthetic data generation methods for demosaicing artifact removal
     * Applied unsupervised style-transfer to generate DSLR quality images

   * Duplicate Question Pair Identification
      * Supervised by Prof. Dit-Yan Yeung
      * Designed a Siamese-GRU based network for duplicate question pair identification
      * Implmented a bi-directional GRU with attention mechanism
      * Achieved an 5\% improvement on the baseline model with various regularization techniques

Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

