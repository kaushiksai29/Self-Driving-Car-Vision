
# Self-Driving Car Vision - Obstacle Detection
This project demonstrates real-time obstacle detection using a pre-trained YOLO model to identify common objects in a road scene. It simulates a key component of a self-driving car's perception system, showcasing skills in applied AI and computer vision with OpenCV.

# Features
- Object Detection: Uses a pre-trained YOLOv3-tiny model for fast object detection.

- OpenCV Integration: Leverages OpenCV for all image processing, model loading, and annotation tasks.

- Automatic Setup: The script automatically downloads the required YOLO model files and a sample image.

# How to Run
1. Clone the repository and cd into it.

2. Install dependencies: pip install -r requirements.txt

3. Run the detection script: python detector.py

4. Check the output: The script will download model files into a model/ directory, a sample image into images/, and save the final annotated image as output_detection.jpg.
