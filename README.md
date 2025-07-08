# Face Swap 

This project performs face swapping using [InsightFace](https://github.com/deepinsight/insightface)'s pretrained models. It includes **augmentation techniques** for improving source image adaptability and swap realism.

## Features
- Pretrained face detection, landmarking, and swapping models
- Smart quality filtering for face selection
- Image augmentation to simulate realistic lighting and color variations

## Why Augmentation?
We apply augmentation on the source image before swapping to:
- Better match the lighting and tone of the target image
- Reduce sharp boundaries in the swapped face
- Make the model robust to real-world variations like brightness, blur, and shadows

## Techniques include:
- Random Brightness and Contrast adjustment
- Hue, Saturation, and Value shifts
- Gaussian Noise addition
- Motion Blur

## Installation

Make sure you have Python 3.7 or higher installed.

Clone the repository:

```bash
git clone https://github.com/Busrara/face-swap-project.git
cd face-swap-project

Install the dependencies:
```bash
pip install -r requirements.txt






