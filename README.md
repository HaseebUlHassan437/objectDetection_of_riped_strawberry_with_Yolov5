**Author:** [Haseeb Ul Hassan]
# Riped Strawberry Detection With Yolov5s
## Dataset
The dataset used in this project consists of images and their corresponding labels in XML format. The XML format is often used to store annotations like bounding boxes and class labels.

## Label Conversion
A Python script is provided to convert the annotations from the XML format to YOLO format. The YOLO format requires the bounding box coordinates to be normalized and centered, which is different from the absolute pixel values typically found in XML annotations.

## XML to YOLO Conversion Script
The conversion script reads each XML file, extracts the object annotations, and saves them in YOLO format:
## License
This project is licensed under the MIT License - see the LICENSE file for details.

