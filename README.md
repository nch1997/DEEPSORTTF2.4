# Introduction
Forked and modified from https://github.com/LeonLok/Deep-SORT-YOLOv4 to run on tensorflow 2.4 with RTX 3060Ti

# Quick Start (For more instructions check out the original repo from LeonLok)
1. [Download](https://drive.google.com/file/d/1cewMfusmPjYWbrnuJRuKhPMwRe_b9PaT/view) yolov4 weights and place in model_data folder.
2. Convert the Darknet YOLOv4 model to a Keras model using convert.py. Remember to enter the directory of DEEPSORTTF2.4 first.
``` 
python convert.py
```
3. To run the demo video run demo.py
```
python demo.py
```
