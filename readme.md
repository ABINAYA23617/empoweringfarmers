# 🌴 Coconut Disease Detection

A Streamlit web application that detects common coconut tree diseases from images using a YOLOv8 object detection model and explains causes using Google Gemini AI.  
The app also suggests possible solutions and links to relevant agricultural products.

---

##  Features

- Detects coconut tree diseases from uploaded images.
- AI-generated explanations of causes (via Google Gemini).
- Suggests preventive measures and treatments.
- Adjustable confidence threshold.
- Modular code for adding more data sources (webcam, RTSP, YouTube, videos).

---

## Project Structure

Coconut-Disease-Detection/
│
├── app.py # Main Streamlit app
├── helper.py # Helper functions for YOLO model loading and video stream handling
├── settings.py # Configuration for paths, model settings, and sources
├── README.md # Project documentation
├── requirements.txt # List of Python dependencies
│
├── weights/ # Folder for YOLO model weights
│ └── bestcoconutdisease.pt
│
├── images/ # Default and sample images for testing
│ ├── office_4.jpg
│ └── office_4_detected.jpg
|

#### Requirements
streamlit
ultralytics
opencv-python
pillow
google-generativeai