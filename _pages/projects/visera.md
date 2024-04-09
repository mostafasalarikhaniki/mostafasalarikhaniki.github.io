---
layout: splash
title: ViSERA
permalink: /projects/visera/
author_profile: false
---

# ViSERA: A Python-based Medical Image Analysis Software

---


<html>
<style>
    html,
    body {
        width: 100%;
    }
    img.two {
        height: 80%;
        width: 80%;
    }
    * {
        box-sizing: border-box;
    }
    .column {
        float: left;
        width: 50%;
        padding: 5px;
    }
    .row::after {
        content: "";
        clear: both;
        display: table;
    }
</style>
</html>

## Introduction
ViSERA is a comprehensive and user-friendly medical image analysis software developed as an independent international project. This software is built from scratch using Python and utilizes libraries such as VTK, ITK and machine learning algorithms for various renderings and image manipulations. Additionally, it employs Pyside6 and NodeGraphQt libraries for graphical user interface. The primary goal of ViSERA is to create a powerful medical image processing system that assists physicians in diagnosing brain and glandular diseases with greater accuracy.


<html>
<body>
    <center>
    <video controls autoplay="autoplay" loop="true" controls muted>
    <source src="/files/visera/workflow-video.mp4" type="video/mp4">
    </video>
    </center>
</body>
</html>


## Image Visualization in ViSERA

- One of the key and vital modules in the ViSERA project is the Image Visualization module. This module is designed for displaying medical images and providing features for manipulation and rendering on these images. Utilizing advanced technologies such as VTK (The Visualization Toolkit) and ITK (Insight Segmentation and Registration Toolkit), this module offers powerful capabilities to physicians and medical experts for examining and analyzing medical images.


<html>
<body>
    <center>
    <video controls autoplay="autoplay" loop="true" controls muted width="1024" height="640">
    <source src="/files/visera/open-vis-pan.mp4" type="video/mp4">
    </video>
    </center>
</body>
</html>


## Interactive Tools in Image Visualization
ViSERA offers a range of interactive tools.
 
- Triangulation is one of the important and practical tools in the field of image visualization, through which medical images are transformed into three-dimensional structures while preserving the continuity and relationship between points. In other words, this tool connects various points of the image in the form of triangles to generate a three-dimensional model. These models enable access to deeper information and more precise analysis of the internal structures of patients for anatomical examination and investigation.


<html>
<body>
    <center>
    <video controls autoplay="autoplay" loop="true" controls muted width="1024" height="640">
    <source src="/files/visera/triangulation.mp4" type="video/mp4">
    </video>
    </center>
</body>
</html>

- Using Crop, physicians can select and isolate specific portions of the image that they are particularly interested in, such as regions containing specific points of a disease. This tool enables physicians to focus on analyzing and diagnosing more accurately by precisely selecting the required parts of the image.

<html>
<body>
    <center>
        <img class="two" src='/files/visera/crop.png' width="1024" height="640">
        <br>
        <br>
    </center>
</body>
</html>

- Thresholding allows physicians to select and examine parts of the image whose values fall within a specific range by adjusting threshold values. For instance, physicians can choose regions of the image where the pixel intensities are higher or lower than a particular threshold value. This capability grants users the ability to access desired sections of the image with greater precision and conduct more accurate analyses.

<html>
<body>
    <center>
        <img class="two" src='/files/visera/threshold.png' width="1024" height="640">
        <br>
        <br>
    </center>
</body>
</html>


## Cross-Platform Compatibility
ViSERA has been developed to ensure compatibility across platforms, supporting all three major operating systems: Linux, Windows, and macOS. A standalone executable file is provided for each platform to facilitate ease of use and installation.
