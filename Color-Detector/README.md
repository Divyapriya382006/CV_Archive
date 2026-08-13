# Color Detector

A Python project to detect colors from images or live video feed using the mouse pointer.  
Hover over any pixel to get its color name based on HSV ranges. Perfect for learning OpenCV, NumPy, and color detection.

## Features

- Detect color of any pixel using the mouse pointer
- Convert RGB images to HSV for accurate color detection
- Predefined HSV ranges for multiple colors:
  - Red, Green, Blue
  - Yellow, Pink, Purple
  - Black, White
- Display detected color name on screen using OpenCV's `putText`

## How It Works

1. **Mouse Input:** Track X and Y coordinates of the mouse pointer on the image or video frame.  
2. **Color Conversion:** Capture pixel value in RGB and convert it to HSV using OpenCV.  
3. **Color Detection:** Check which predefined HSV range the pixel falls into.  
4. **Display:** Show the detected color name on the screen near the pointer using OpenCV.

## Technologies Used

- Python
- OpenCV (`cv2`)
- NumPy

## Usage

1. Clone the repository or download the script.  
2. Install dependencies:
   ```bash
   pip install opencv-python numpy
