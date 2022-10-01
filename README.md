# RSVG: Exploring Data and Model for Visual Grounding on Remote Sensing Data
##### Author: Zhan Yang 
The offical PyTorch code for paper "RSVG: Exploring Data and Model for Visual Grounding on Remote Sensing Data", arXiv.

## Introduction
This is Multi-level Cross-modal Fusion Network, the PyTorch source code of the paper "RSVG: Exploring Data and Model for Visual Grounding on Remote Sensing Data". It is built on top of the [TransVG](https://github.com/djiajunustc/TransVG) in PyTorch. Our method is a transformer-based method for visual grounding for remote sensing data (RSVG). It has achieved the SOTA performance in the RSVG task on our constructed RSVGD dataset.
<p align="middle">
    <img src="fig/architecture.jpg">
</p>

## Data preparation
Download and extract RSVGD images with annotations from http://. We expect the directory structure to be the following:

    ```
    git clone https://github.com/
    ```
