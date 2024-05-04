# Object-Tracking-PyTorch-YOLOv5-DeepSort

## Introduction
This project utilizes YOLOv5 for object detection and DeepSORT YOLO for tracking human objects in a video stream. YOLOv5 is a popular deep learning model for real-time object detection, while DeepSORT YOLO adds object tracking capabilities to YOLOv5.

## Installation
1. Create an environment:
   ```
   conda create -n deepvenv python=3.8

   conda activate deepvenv

   ```
2. Install dependencies:

   ```
   pip install -r yolov5/requirements.txt

   pip install -r Yolov5_DeepSort_Pytorch/requirements.txt

   conda install pytorch==1.7.0 torchvision==0.8.0 torchaudio==0.7.0 cpuonly -c pytorch

   pip install easydict
   ```
## Usage

Detect Object using the configured model:
   ```
  python detect_sort.py --weights yolov5m.pt  --img 640  --source data\pedestrian.mp4  --save-txt --class 0
 
   ```

## References
- YOLOv5: [https://github.com/ultralytics/yolov5](https://github.com/ultralytics/yolov5)
- DeepSORT: [https://github.com/gongliyu/Yolov5_DeepSort_Pytorch](https://github.com/gongliyu/Yolov5_DeepSort_Pytorch)

## Acknowledgements
Special thanks to the developers of YOLOv5 and DeepSORT for their contributions to the open-source community.
