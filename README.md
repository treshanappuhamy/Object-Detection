# Real-time Object Detection using OpenCV

This repository contains Python code for real-time object detection using OpenCV. The script utilizes a pre-trained SSD (Single Shot MultiBox Detector) model with MobileNetV3 architecture on the COCO dataset for detecting objects in a live video stream from the webcam.

## Requirements

- Python 3
- OpenCV (`pip install opencv-python`)
- Pre-trained model weights (`frozen_inference_graph.pb`)
- Model configuration file (`ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt`)
- Class names file (`coco.names`)

## Usage

1. Install the required dependencies.
2. Download the pre-trained model weights and configuration files.
3. Place the downloaded files in the same directory as the script.
4. Run the Python script.

```bash
python object_detection.py
