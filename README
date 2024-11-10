# Computer Vision Assignment

This repository contains three Jupyter notebooks that demonstrate fundamental computer vision techniques: Lucas-Kanade Optical Flow, Anisotropic Diffusion, and Harris Corner Detection. Each notebook provides a detailed explanation of the algorithms, their implementation, and example usage.

## Table of Contents

1. [Lucas-Kanade Optical Flow](#lucas-kanade-optical-flow)
2. [Anisotropic Diffusion](#anisotropic-diffusion)
3. [Harris Corner Detector](#harris-corner-detector)

---

## Lucas-Kanade Optical Flow

### Overview
The Lucas-Kanade method estimates the motion between two consecutive frames in a video. It assumes that the motion is small and constant within a neighborhood of each pixel. The optical flow constraint equation is used to calculate the optical flow vectors.

### Key Steps
- Import necessary libraries (NumPy, OpenCV).
- Set up argument parser for video input.
- Define functions for initializing video capture, setting parameters, and processing frames.
- Visualize the optical flow results.

### Example Usage
To run the optical flow calculation, specify the path to your video file in the `main` function.

---

## Anisotropic Diffusion

### Overview
Anisotropic diffusion is a technique used to smooth images while preserving edges. The diffusion equation is applied iteratively to achieve this effect, using a diffusion coefficient that depends on the image gradient.

### Key Steps
- Import necessary libraries (NumPy, OpenCV, Matplotlib).
- Define functions for computing gradients, conduction coefficients, and updating the image.
- Perform anisotropic diffusion on an input image and visualize the results.

### Example Usage
Load an image and specify the number of iterations and kappa values for diffusion in the `plot_images` function.

---

## Harris Corner Detector

### Overview
The Harris corner detector identifies points in an image where there are significant changes in intensity. It uses the second moment matrix to compute a corner response function, which helps in detecting corners.

### Key Steps
- Import necessary libraries (SciPy, Matplotlib, scikit-image).
- Define functions for loading images, computing gradients, and calculating the Harris response.
- Perform non-maximum suppression to refine corner detection and visualize the results.

### Example Usage
Load an image and call the `main` function to execute the corner detection process.

---

## Requirements
- Python 3.x
- Jupyter Notebook
- OpenCV
- NumPy
- Matplotlib
- SciPy
- scikit-image

## Installation
Clone the repository and install the required libraries using pip:
```bash
git clone https://github.com/ranjanchoubey/cv-assignment.git
cd cv-assignment
pip install -r requirements.txt
```


---
## Acknowledgments
- We would like to express our gratitude to [Professor Pradipta Majhi](https://scholar.google.co.in/citations?user=RtOqKr0AAAAJ&hl=en) from the Indian Statistical Institute for providing this assignment and teaching all these concepts in class.

