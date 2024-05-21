# Computer-Vision

![](Dance.gif)

![Python version](https://img.shields.io/badge/python-3.9.5-blue)
![torch version](https://img.shields.io/badge/pytorch-2.1.0%20-orange)
![mediapipe version](https://img.shields.io/badge/mediapipe-0.10.10%20-red)
![numpy version](https://img.shields.io/badge/numpy-1.22.4%20-blue)
![yolo version](https://img.shields.io/badge/Yolov8-0.12.2%20-blueviolet)
![plt version](https://img.shields.io/badge/matplotlib-3.6.2%20-purple)
![opencv version](https://img.shields.io/badge/opencv-4.9.0-red)
![shapely version](https://img.shields.io/badge/shapely-2.1.0%20-green)


## Table of Contents
1. About
2. Requirements
3. Project Status

## 1. About
This repository is a collection of various computer vision projects. Each project is designed to ﬁt real-world scenarios. To achieve this, we make use of the most cutting-edge tools and techniques currently available, as well as apply ﬂexible approaches to develop algorithms that enhance the functionality of these tools and compensate for their inherent limitations.

The projects are separated into individual directories and mostly coded in Python. Each project comprises a series of annotated notebooks detailing the objectives and explanations for each step of the workflow. Notebooks may be supplemented by Python scripts for instances where code automation is necessary. 

Since data is collected from a variety of sources, a specific folder for the data will be created for every project. In recognition of the work done by the community, and to facilitate access to the data for future efforts, all sources will be acknowledged and source links will be provided when possible. Note, however, that some datasets are processed using multiple data sources. In such cases, the sources shall be disclosed, with varying degrees of detail. Additionally, we reserve the right to disclose the processing code when relevant to the project. It will also be clarified if the used data was artificially produced.

## 2. Requirements
For the correct execution and reproducibility of the notebooks, we recommend the use of the [Anaconda](https://www.anaconda.com/download) distribution system.

It is advisable to use systems with hardware capable of supporting the demands of complex algorithms, which may require significant memory and processing power. 
Alternatively, cloud environments can be employed. 

The required libraries are listed at the beginning of each notebook. We also recommend installing [`OpenCV`](https://pypi.org/project/opencv-python/), [`Tensorflow`](https://docs.anaconda.com/free/working-with-conda/applications/tensorflow/), [`Pytorch`](https://pytorch.org/get-started/locally/#windows-installation), [`YOLO`](https://docs.ultralytics.com/quickstart/#install-ultralytics) and [`MediaPipe`](https://pypi.org/project/mediapipe/) libraries.

The creation of animated videos with `matplotlib.animation` will require the installation of the FFMpeg library. To do so, it will be first necessary to install FFMpeg in your OS (follow this tutorial for [Windows](https://phoenixnap.com/kb/ffmpeg-windows) or this other for [Linux](https://phoenixnap.com/kb/install-ffmpeg-ubuntu) installation) and then install the FFMpeg library in your conda environment:

For the `default` channel:
```
conda install ffmpeg 
```
And for the `conda-forge` channel:
```
conda-forge install ffmpeg
```
It is advisable to check for compatibility between certain versions of the libraries used in each project, with particular attention to numpy, matplotlib and tensorflow.

## 3. Project Status
1. Person tracking with `YOLOv8` and `MediaPipe`:
    - The 4 notebooks composing this project are under completion (60% complete).
    - First results can be displayed.


[Ongoing...]

<img 
src="https://i.giphy.com/MT5UUV1d4CXE2A37Dg.webp" 
width="320" height="220">
