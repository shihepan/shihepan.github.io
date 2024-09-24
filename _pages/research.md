---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

*My (current) academic interest lies in the developments of fast, compact, and energy-efficient all-optical/hybrid image processing systems.*

During **undergraduate** studies, my research spanned photonic crystals, granular materials, image processing, and robotics, where I applied advanced methodologies to solve problems in thermal insulation, biological systems, and automation. These experiences have shaped my ability to tackle complex technical challenges across multiple disciplines. Key projects included: 
- [Omnidirectional Reflector for Infrared Radiation Barrier](#omnidirectional-reflector-for-infrared-radiation-barrier)
- [Root Growth Investigation with X‑ray Computed Tomography](#root-growth-investigation-with-xray-computed-tomography)
- [Automated Grasping System Using Object Recognition and Depth Sensing](#automated-grasping-system-using-object-recognition-and-depth-sensing)


In **graduate** school, I found my biggest research interest and focused on computational imaging and free-space optical computing, working on projects aimed at enhancing imaging systems and optimizing algorithms for real-world applications, such as super-resolution and road line detection. Projects included:
- [Super-Resolution Imaging via Co-design of Optical Encoder and Digital Decoder](#super-resolution-imaging-via-co-design-of-optical-encoder-and-digital-decoder)
- [PhyCV-Enabled Lane Line Detection for Autonomous Driving](#phycv-enabled-lane-line-detection-for-autonomous-driving)



<br>

## Super-Resolution Imaging via Co-design of Optical Encoder and Digital Decoder
*In Progress* 

We aim to co-design a [D2NN](https://www.science.org/doi/full/10.1126/science.aat8084)-based optical encoder integrated with digital neural network decoders to achieve image super-resolution for sensors with limited pixel number. We optimize the synergy between optical encoding and digital decoding process through deep optics framework to enhance resolution beyond the native capacity of image sensors.

<br>

## PhyCV-Enabled Lane Line Detection for Autonomous Driving
This was an in-class project for UCLA ECE 279AS - Physics, AI, and Algorithmic Imaging, conducted in collaboration with Ash Aggarwal and supervised by Prof. Bahram Jalali. Building on the idea that the [Phase Stretch Transform (PST)](https://en.wikipedia.org/wiki/Phase_stretch_transform) algorithm from [PhyCV](https://github.com/JalaliLabUCLA/phycv) is highly effective for edge detection, we applied it as a preprocessing step to improve deep neural network performance in road line detection for autonomous vehicles. We retrained several models with this preprocessing step and performed a comparative analysis of benchmark models with and without PST preprocessing, focusing on accuracy, robustness, generalizability, and model efficiency. 

The experiment preliminarily demonstrated that preprocessing with PhyCV algorithms is promising in its ability to enhance lane lines and bring out details in low-light environments: 

<center><img src="/images/PhyCV.png" alt="phycv result" width="800"/></center>

<br>

**Relevent Sources**

[GitHub](https://github.com/JalaliLabUCLA/2024_279AS_Project3_Lane_Detection), [Presentation](https://duke.box.com/v/shihepanphycv). 

<br>


## Omnidirectional Reflector for Infrared Radiation Barrier
This study develops novel optical devices and materials for high-temperature thermal insulation, specifically targeting at small-scale radioisotope thermophotovoltaic (RTPV) systems used in extra-solar space exploration. The thermal insulation component is critical in such systems. When conventional multilayer insulation (MLI) designs proved inadequate, we proposed the use of omnidirectional reflectors (ODRs) as an innovative solution. The ODR developed in this study utilizes the complete photonic bandgap in 1D photonic crystals, offering a remarkably thin material with superior shielding performance across a huge temperature gradient (1000 °C across 21 μm). The design combines insights from photonics and thermodynamics, offering potential advancements in thermal management for NASA spacecraft, nuclear systems, and cryogenics.


<center><img src="/images/TPV.png" alt="poster" width="800"/></center>
<center>Left: Schematics of a typical TPV system (source: Sakakibara et al., Journal of Photonics for Energy, 2019); Right: Complete photonic band in 1D photonic crystals (source: Joannopoulos et al., Photonic Crystals: Molding the Flow of Light, 2008) </center>

<br>

**Relevent Sources**

(1) Zhou, Xiaoqi, Dingning Li, Junjie Zhang, Xin Wang, Peter Fisher, Yixin Sun, Shihe Pan, Shipei Zhang, Lin Qiu, and Xiawa Wang. 2024. [“Modeling and Implementation of Multilayer Insulation for Small-Scale Ultrahigh Temperature Systems.”](https://doi.org/10.1016/j.applthermaleng.2024.122838) Applied Thermal Engineering 245 (May):122838.

(2) Pan, Shihe, Yixin Sun, Xiaoquan Liu, Xiaoqi Zhou, Shipei Zhang, and Xiawa Wang. “Design and Optimization of Infrared Radiation 
Barrier Using Omnidirectional Reflectors.” (*In peer review*)


<br>


## Root Growth Investigation with X‑ray Computed Tomography
Exploring the relationship between root and soil has significance in environmental protection. In this signature work (thesis) project, we grew plants (e.g., Arabidopsis) in a granular medium composed of spherical particles and used X‐ray computed tomography (CT) for visualization without destroying the local environment. Besides identifying the optimal parameters for CT measurement, the first phase of the work involved processing CT tomograms with computer vision algorithms to extract centroids and positions of granular particles, along with constructing 3D surface models of the roots. Next, we generated and analyzed the 3D (Set) Voronoi diagrams of particles near the roots, both graphically and numerically, to decipher the interactions between soil particles and plant roots on a bio-mechanical level. 

<center><img src="/images/rootgrowth.png" alt="poster" width="800"/></center>

<br>
We ultilized a series of image processing algorithms (e.g, erosion, binarization, denoising) to extract particles and roots in 3D X-ray tomograms. We also conducted structural analysis via Voronoi diagrams, packing fractions, and pair correlation functions. 

<div style="display: flex; justify-content: space-around; align-items: center">
    <img src="/images/gif1.gif" alt="GIF 1" style="width: 30%; height: auto;">
    <img src="/images/gif2.gif" alt="GIF 2" style="width: 30%; height: 30%;">
</div>

<br>

**Relevent Sources**

[Thesis](https://duke.box.com/v/shihepanthesis), [Report](https://duke.box.com/v/shihepansummerreport), [Poster](https://duke.box.com/v/shihepanposter), 5-minute [Presentation](https://duke.box.com/v/shihepanpresentation).

[APS March Meeting 2024](https://meetings.aps.org/Meeting/MAR24/Session/N00.155)


<br>

## Automated Grasping System Using Object Recognition and Depth Sensing
Robot arms can be useful in experiments, especially for those that require repetitive operations, such as object placement and retrieval. During the summer of my 1st year of undergraduate studies, I spent two months working on a 7-axis robotic arm system, enabling object recognition, grasping, and placement on a flat platform. We used the Hough transform and particle filter to recognize objects in the video stream from a general camera, and through camera calibration, we 'informed' the robotic arm of the object's relative spatial coordinates to achieve accurate grasping. Though simple, this project opened the door to engineering for me.

<center><img src="/images/robotimage.jpg" alt="robot arm and camera calibration" width="600"/></center>

Our robotic arm system allows for real-time object recognition, grasping, and placement with the assistance of a single camera:
<center>
<video width="600" controls>
  <source src="/images/robotvideo.mp4" type="video/mp4">
</video>
</center>





