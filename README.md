# Computer Vision Assignments

A collection of computer vision assignments implemented in Google Colab using Python, NumPy, PIL, OpenCV, and Ultralytics YOLO26.

This repository was developed as part of a computer vision training program associated with [SDAIA Academy](https://github.com/SDAIAAcademy).

## Assignments

### Assignment 1: Advanced Pixel-Level Manipulation

This assignment focuses on direct image and pixel manipulation.

The implemented tasks include:

- Loading, inspecting, and displaying two images.
- Manipulating image matrices using NumPy array slicing.
- Extracting a random 30×30 crop from the first image.
- Pasting the cropped region into the second image to create Image3.
- Converting Image1, Image2, and Image3 to grayscale.
- Applying a custom sharpening kernel to Image3.

### Assignment 2: Object Detection and Descriptive Summary

This assignment implements an object detection pipeline using YOLO26.

The implemented tasks include:

- Running object detection on a custom basketball image.
- Extracting class labels, confidence scores, and bounding-box coordinates.
- Applying custom confidence thresholding.
- Drawing bounding boxes and class labels manually using OpenCV.
- Generating a natural-language description of the detected scene.

### Assignment 3: CIFAR-10 Image Classification

This assignment implements multi-class image classification using CIFAR-10 and a YOLO26 classification model.

The implemented tasks include:

- Loading the CIFAR-10 dataset.
- Randomly selecting 10 test images.
- Running baseline classification inference.
- Comparing predicted and ground-truth labels.
- Calculating baseline accuracy.
- Fine-tuning YOLO26 on CIFAR-10.
- Evaluating the trained model on the test set.
- Generating and analyzing a multi-class confusion matrix.

## Repository Structure

```text
computer-vision-assignments/
├── Assignment1/
│   ├── Assignment1_Pixel_Manipulation.ipynb
│   ├── flower.jpg
│   └── cat.jpg
├── Assignment2/
│   ├── Assignment2_Object_Detection.ipynb
│   └── basketball.jpg
└── Assignment3/
    └── Assignment3_CIFAR10_Classification.ipynb
```

## Technologies used

- Python
- Google Colab
- NumPy
- PIL
- OpenCV
- Matplotlib
- PyTorch
- Ultralytics YOLO26
- CIFAR-10

## How to Run

1. Open the required `.ipynb` notebook in Google Colab.
2. Select a GPU runtime when model training is required.
3. Install the required libraries by running the installation cell.
4. Run all notebook cells in order.
5. Upload the input images when requested.
6. Review the generated predictions, accuracy results, and visualizations.

## Technical Documentation

Each notebook contains:
- A clear project structure.
- Step-by-step explanations.
- Documented Python code.
- Input and output visualizations.
- Model evaluation results.
- Analysis of the obtained results.

## Training Program

These assignments were completed as part of a computer vision training program associated with SDAIA Academy.

SDAIA Academy GitHub:  
https://github.com/SDAIAAcademy

## Author

Hala Alhamzah
