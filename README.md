# Car Detection with YOLO

This repository contains a Python-based car detection solution using the YOLO (You Only Look Once) object detection algorithm with OpenCV. The model is designed to detect cars in a given video, count them, and output the video with the detected cars marked with bounding boxes.

## Features
- Detect cars in a video using YOLOv3.
- Outputs processed video with bounding boxes around detected cars.
- Provides a count of detected cars.
- Filters out trucks and other vehicles.

## Requirements

- Python 3.x
- OpenCV
- Numpy
- Pretrained YOLO model (YOLOv3)
- COCO names file

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/car-detection-yolo.git
    ```

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the YOLOv3 weights from [YOLO official website](https://pjreddie.com/darknet/yolo/).

4. Run the detection:
    ```bash
    python car_detection_yolo.py
    ```

### How to Use
1. Ensure the video file is available in the `video/` directory.
2. Modify the paths in `car_detection_yolo.py` to point to your specific paths for `cfg`, `weights`, and `video`.
3. Run the script and check the output in the `output/` folder.

### Example

An example of car detection in action can be found in the `output/` folder.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
