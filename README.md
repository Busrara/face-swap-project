# Face Swap 

This project uses [InsightFace](https://github.com/deepinsight/insightface) to perform high-quality face swapping between two images. It supports face detection, face alignment, and identity-aware face replacement using pre-trained models.

## Features

- Face detection and embedding with `buffalo_l`
- Face swapping with `inswapper_128.onnx`
- Smooth mask blending to reduce swap artifacts
- Optional augmentation pipeline and quality filtering for better result
- Visualization and result saving in one click

## Getting Started

1. **Clone the repository:**

```bash
git clone https://github.com/Busrara/face-swap-project.git
cd face-swap-project
