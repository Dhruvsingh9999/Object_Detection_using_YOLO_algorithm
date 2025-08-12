# YOLO Object Detection

## Introduction
This project demonstrates the implementation of **YOLO (You Only Look Once)** for real-time object detection on images, videos, and webcam streams. YOLO is a state-of-the-art deep learning model known for its high speed and accuracy in detecting multiple objects in a single frame.

## Features
- **Image Object Detection**: Detect objects in static images.
- **Video Object Detection**: Process video files and detect objects frame-by-frame.
- **Webcam Live Detection**: Perform real-time object detection using your webcam.

## Installation
To get started, ensure you have Python installed along with the required dependencies:

```bash
pip install opencv-python numpy torch torchvision ultralytics
```

## Usage
### 1. Object Detection on Images
Run the following command to detect objects in an image:
```python
python yolo-Basic.ipynb
```

### 2. Object Detection on Videos
Run the following command to process video files:
```python
python yolo-Basic.ipynb --video path/to/video.mp4
```

### 3. Real-time Object Detection with Webcam
Run the following command to use your webcam for real-time detection:
```python
python yolo-webcam.ipynb
```
## Acknowledgments
This project utilizes **YOLOv8** from the Ultralytics library. Special thanks to the open-source community for providing valuable resources.

## Contributing
Feel free to fork this repository, raise issues, or contribute to enhance this project.

## License
This project is open-source and available under the MIT License.

