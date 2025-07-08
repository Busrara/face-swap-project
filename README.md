# Face Swap Project

## Overview
A simple face swap application that can detect and swap faces between source and target images.

## Features
- **Face Detection**: Automatically detects faces in both source and target images
- **Confidence Scoring**: Measures detection confidence for better results
- **Bounding Box Analysis**: Precise face location mapping
- **Quality Enhancement**: Improved face swap with augmentation

## How It Works
1. **Detection Phase**: Scans images for faces and calculates confidence scores
2. **Mapping Phase**: Identifies face boundaries and positions
3. **Swap Phase**: Performs the face replacement
4. **Enhancement Phase**: Applies improvements and augmentation

## Technical Details
- Minimum confidence threshold for reliable detection
- Bounding box coordinates for precise face mapping
- Multi stage processing for higher quality results

## Usage
Provide source and target images. The tool will:
- Detect faces automatically
- Show confidence scores
- Perform the swap
- Apply enhancements
- Upload final results

## Output
- Face detection statistics
- Confidence scores for each detected face
- Bounding box coordinates
- Processing status updates

### Clone the Repository

```bash
git clone https://github.com/Busraracoban/face-swap-project.git
cd face-swap-project

pip install -r requirements.txt


