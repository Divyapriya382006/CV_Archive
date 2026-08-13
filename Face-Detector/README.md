# Face Detector

A simple Python project to detect faces in images or live video using OpenCV and a pre-trained Haar Cascade model.

## Features

- Detect faces in real-time or from images
- Converts BGR images to grayscale for faster and more accurate detection
- Draws rectangles around detected faces with optional text

## How It Works

1. Convert the input image or video frame to grayscale.  
2. Load the pre-trained Haar Cascade face detection model.  
3. Detect faces in the grayscale image.  
4. Draw rectangles around detected faces and add any desired text.

## Technologies Used

- Python
- OpenCV (`cv2`)

## Usage

1. Clone or download the project.  
2. Install dependencies:
   ```bash
   pip install opencv-python
