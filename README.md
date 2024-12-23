**Document Scanner**
----
Overview
The Document Scanner application allows users to scan physical documents using a webcam, automatically detecting the document's edges and applying a perspective transformation to create a well-aligned image of the document. This project is built using Python and OpenCV, providing a simple and effective solution for document scanning.

Features
Document Detection: Automatically detects the edges of a document in real-time using OpenCV.
Perspective Transformation: Warps the detected document area to create a rectangular, properly aligned image of the document.
Real-time Camera Feed: Displays the camera feed with real-time detection of documents.
User-friendly Interface: Simple and intuitive interface for easy document scanning.
Requirements
Before running the application, ensure you have the following dependencies installed:

Python
Python 3.6 or higher
Required Libraries
opencv-python
numpy
Install the required libraries using pip:

bash
Copy code
pip install opencv-python numpy
Installation & Setup
Clone or download the project repository to your local machine.
Install the required libraries by running the command:
bash
Copy code
pip install -r requirements.txt
Ensure you have a webcam or camera connected to your system.
Usage
Run the main.py file to start the document scanning application:
bash
Copy code
python main.py
The webcam feed will open, and the application will automatically detect documents within the camera's view.
Once the document is detected, the program will align it, and a scanned image of the document will be displayed.
Key Functions:
find_document(): Detects the largest contour in the camera feed and identifies the document.
apply_perspective(): Applies a perspective transformation to straighten the detected document.
How It Works
Document Detection: The application processes the live camera feed, converts it to grayscale, and detects contours. The largest contour is assumed to be the document.
Perspective Warp: After the document is detected, a perspective transformation is applied to align the document and create a scanned version of it, ensuring it appears as a rectangular image.
Troubleshooting
Camera Not Detected: Ensure your webcam is connected and recognized by your operating system.
Document Not Detected: Make sure the document is clearly visible in the camera frame and the background is not cluttered.
