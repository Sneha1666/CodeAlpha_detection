# README.md

# AI Object Detection Using TensorFlow.js

## Project Overview

This project is a real-time AI Object Detection System built using HTML, CSS, JavaScript, TensorFlow.js, and the COCO-SSD pre-trained model. The application accesses the user's webcam, detects objects in real time, and displays bounding boxes with object labels and confidence scores directly in the browser.

The project does not require Python or any backend server and runs entirely on the client side.

---

## Features

* Real-time webcam access
* AI-powered object detection
* Bounding box visualization
* Object labels and confidence scores
* Browser-based execution
* No Python required
* Responsive and user-friendly interface

---

## Technologies Used

* HTML5
* CSS3
* JavaScript
* TensorFlow.js
* COCO-SSD Model

---

## Project Structure

```text
Object-Detection/
│
├── index.html
├── README.md
└── assets/
```

---

## How It Works

1. The application accesses the webcam using the MediaDevices API.
2. TensorFlow.js loads the pre-trained COCO-SSD model.
3. Video frames are continuously processed.
4. Detected objects are identified.
5. Bounding boxes and labels are drawn on the canvas.
6. Detection results are updated in real time.

---

## Installation and Execution

### Method 1: Using VS Code

1. Install Visual Studio Code.
2. Install the Live Server extension.
3. Open the project folder.
4. Right-click on `index.html`.
5. Select **Open with Live Server**.
6. Allow camera permission when prompted.

---

## Supported Object Classes

The COCO-SSD model can detect common objects such as:

* Person
* Cell Phone
* Bottle
* Chair
* Laptop
* Book
* Backpack
* Car
* Bus
* Bicycle
* Dog
* Cat

and many more.

---

## Output

The system displays:

* Live webcam feed
* Object name
* Confidence percentage
* Bounding box around detected objects

Example:

```text
Person 92.4%
Bottle 81.6%
Cell Phone 87.3%
```

---

## Future Enhancements

* Object Tracking IDs
* Object Counting
* FPS Counter
* Dark/Light Theme
* Detection History Panel
* Export Detection Logs
* Deep Learning Model Optimization

---

## Applications

* Smart Surveillance Systems
* Security Monitoring
* Automated Attendance Systems
* Traffic Monitoring
* Retail Analytics
* Smart City Solutions

---

## Conclusion

This project demonstrates the implementation of real-time object detection using TensorFlow.js and the COCO-SSD model. It provides a lightweight, browser-based AI solution capable of detecting and displaying objects without requiring any backend processing.

