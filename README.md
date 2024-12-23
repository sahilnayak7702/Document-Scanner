# Document Scanner

## Overview
The **Document Scanner** application is designed to scan physical documents using a webcam. The app automatically detects the edges of the document and applies a perspective transformation to generate a well-aligned image of the document. This project is built using Python and OpenCV.

## Features
- **Real-time Camera Feed**: Displays live feed from your webcam.
- **Document Detection**: Automatically detects the edges of a document in real-time.
- **Perspective Transformation**: Warps the detected document area to generate a well-aligned image.
- **Simple and User-friendly**: Easy-to-use interface to scan documents.

## Requirements
Before you begin, ensure you have the following installed:

### Software
- Python 3.6 or higher

### Libraries
The application requires the following Python libraries:

- `opencv-python`
- `numpy`

### Install Dependencies
To install the required libraries, run the following command:

```bash
pip install opencv-python numpy
