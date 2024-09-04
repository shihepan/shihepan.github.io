---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

*This page is under construction.*

As an **undergraduate**, my research spanned photonic crystals, granular materials, image processing, and robotics, where I applied advanced methodologies to solve problems in thermal isolation, biological systems, and automation. These experiences have shaped my ability to tackle complex technical challenges across multiple disciplines. Key projects included: 
- [Omnidirectional Reflector for Infrared Radiation Barrier](#omnidirectional-reflector-for-infrared-radiation-barrier)
- [Root Growth Investigation with X‑ray Computed Tomography](#root-growth-investigation-with-xray-computed-tomography)
- [Automated Grasping System Using Object Recognition and Depth Sensing](#automated-grasping-system-using-object-recognition-and-depth-sensing)


In **graduate** school, I found my biggest research interest and focused on computational imaging and free-space optical computing, working on projects aimed at enhancing imaging systems and optimizing algorithms for real-world applications, such as super-resolution and road line detection. Projects included:
- [Super-Resolution Imaging via Co-design of Optical Encoder and Digital Decoder](#super-resolution-imaging-via-co-design-of-optical-encoder-and-digital-decoder)
- [PhyCV-Enabled Lane Line Detection for Autonomous Driving](#phycv-enabled-lane-line-detection-for-autonomous-driving)



## Omnidirectional Reflector for Infrared Radiation Barrier

## Root Growth Investigation with X‑ray Computed Tomography

## Automated Grasping System Using Object Recognition and Depth Sensing



## Super-Resolution Imaging via Co-design of Optical Encoder and Digital Decoder

## PhyCV-Enabled Lane Line Detection for Autonomous Driving



## High-throughput computational 3D imaging with camera arrays
We present 3D-RAPID (<ins>3D</ins> <ins>R</ins>econstruction with an <ins>A</ins>rray-based <ins>P</ins>arallelized <ins>I</ins>maging <ins>D</ins>evice), a computational 3D imaging technique based on an array of 12-megapixel cameras capable of imaging at extremely high spatiotemporal throughts (>5 gigapixels/sec). 3D-RAPID features a spatiotemporally scalable, physics/self-supervised algorithm that enables simultaneous 3D reconstruction and stitching of arbitrarily many cameras across arbitrarily many temporal frames.
<center><img src="/images/3d-rapid.jpg" alt="3D-RAPID" width="900"/></center>

Our high spatiotemporal throughputs (>5 GP/sec) enable high-resolution 3D imaging of freely behaving organisms over wide FOVs (>130 cm<sup>2</sup>) at high speed (up to 230 fps):
<center>
<video width="700" controls>
  <source src="/images/zebrafish_60fps_tracked.mp4" type="video/mp4">
</video>
</center>
The left panel shows the zoomed-out view of the entire arena of freely swimming zebrafish; the right panels show the zoomed-in individually tracked zebrafish. The video alternates between photometric (RGB) and 3D height information.
<center>
<video width="700" controls>
  <source src="/images/S12_ants_230fps_compressed.mp4" type="video/mp4">
</video>
</center>
Freely moving harvester ants (left: photometric frame, right: 3D height map).

For more videos, see the supplementary materials of the accompanying publication below. See also [https://gigazoom.rc.duke.edu/](https://gigazoom.rc.duke.edu/) for interactive views of full video frames.

**Relevant publications**
- KC Zhou et al., [Parallelized computational 3D video microscopy of freely moving organisms at multiple gigapixels per second](https://www.nature.com/articles/s41566-023-01171-7), *Nature Photonics* (2023)

**Code**  
- [https://github.com/kevinczhou/3D-RAPID](https://github.com/kevinczhou/3D-RAPID)  



